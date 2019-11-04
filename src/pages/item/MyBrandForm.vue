<template>
  <v-form v-model="valid">

  </v-form>
</template>

<script>
  export default {
    name: "my-brand-form",
    data() {
      return {
        valid:false, // 表单校验结果标记
        brand:{
          name:'', // 品牌名称
          letter:'', // 品牌首字母
          image:'',// 品牌logo
          categories:[], // 品牌所属的商品分类数组
        }
      }
    }
  }
</script>

<style scoped>

</style>
