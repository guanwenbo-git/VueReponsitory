<template>
  <el-tabs v-model="activeName" type="card" @tab-click="handleClick">
    <el-tab-pane label="用户管理" name="first">
        <tab1 :optionMsg="option"></tab1>
    </el-tab-pane>
    <el-tab-pane label="配置管理" name="second">
        <tab2 :optionMsg="option"></tab2>
    </el-tab-pane>
  </el-tabs>
</template>
<script>
import tab1 from "../../components/tabs/tab1";
import tab2 from "../../components/tabs/tab2";
export default {
  components: {
    tab1,
    tab2
  },
  data() {
    return {
      activeName: "first",
      option:""
    };
  },
  methods: {
    handleClick(tab, event) {
    //   console.log(tab, event);
        //   if(tab.index='0'){
        //       this.
        //   }
    }
  }
};
</script>