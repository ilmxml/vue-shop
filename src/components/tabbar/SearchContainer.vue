<template>
  <div>
    <mt-search v-model="value" cancel-text="取消" placeholder="搜索"></mt-search>
  </div>
</template>

<script>
import { Search } from "mint-ui";
import Vue from 'vue';

Vue.component(Search.name, Search);
export default {
  data() {
    return {
      value: ""
    }
  }
};
</script>

<style lang="scss" scoped>
</style>
