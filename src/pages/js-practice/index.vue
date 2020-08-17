<template>
  <div>
    <h4>三种创建对象的方式</h4>
    <div>1.字面量的方式创建对象</div>
    <div>2.调用系统的构造函数</div>
    <div>3.自定义构造函数</div>
  </div>
</template>
<script>
var obj = {
  name: 'claven jiang',
  age: '29',
  sex: '男',
  eat: function() {
    console.log('eat everyday')
  },
  play: function() {
    console.log('he likes palying games!')
  }
}

export default {
  // 1.字面量的方式创建对象
  methods: {
    printObj() {
      console.log(obj.name)
    }
  },
  created() {
    this.printObj()
  }
}
</script>