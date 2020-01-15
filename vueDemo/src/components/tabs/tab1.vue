<template>
  <div>
    <h1>{{msg}}</h1>
  </div>
</template>

<script>
export default {
  props: ["optionMsg"], //注意这里要父组件的名字一致
  data() {
    return {
      msg: "tab1"
    };
  },
  watch: {
    optionMsg: function(newValue) {
      console.log(newValue); //可以看到数据已经拿到
    }
  }
};
</script>
