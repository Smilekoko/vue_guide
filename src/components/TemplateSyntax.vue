<template>
  <div class="TemplateSyntax模板语法">

    <p>模板语法引用值：QQ {{ num }}</p>
    <p>{{ uname }}</p>
    <p v-once>{{ uname }}</p>
    <button @click="changeUname">改变uNname值</button>
    <p>使用v-html插入网页内容: </p>
    <span v-html="htmlMsg"/>


  </div>
</template>

<script>
export default {
  name: "TemplateSyntax",
  data() {
    return {
      num: 179621228,
      uname: "该数据修改,插值出内容不会更新",
      htmlMsg: "<h2>从后台放回的html内容</h2>",
    }
  },
  methods: {//给Vue定义方法
    changeUname: function () {
      this.uname = "改变该值";
    }
  }
}
</script>

<style scoped>

</style>