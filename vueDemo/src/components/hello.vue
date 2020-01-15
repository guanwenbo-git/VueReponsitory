<template>
  <div>
      <h1>{{msg}}</h1>
      <h1>{{obj.name}}</h1>
      <h1>{{obj.age}}</h1>
  </div>
</template>

<script>
    export default {
      data(){
          return{
              msg:'东那两个哈桑落后于好',
              obj:{"name":"张三","age":"23"}
          }
      }
    }
</script>
