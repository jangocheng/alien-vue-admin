<!--
 * @Description: 账号绑定
 * @Author: Cary
 * @Date: 2019-12-13 17:44:43
 * @FilePath: f:\vue-project\alien-vue-admin\src\views\profile\components\security.vue
 -->
<template>
  <div class="c-security-content">
    <div class="item">
      <div>
        <div class="title">
          <svg-icon icon-class="qq_1" class="c-title-icon cc-f-s30" />
          <span class="cc-mar-l-6">绑定QQ</span>
        </div>
        <div class="c-text-subheading cc-f-s14">
          当前未绑定微信账号
        </div>
      </div>
      <div class="control">
        <el-link :underline="false" type="primary">绑定</el-link>
      </div>
    </div>
    <el-divider class="cc-mar-t-20 cc-mar-b-20" />
    <div class="item">
      <div>
        <div class="title">
          <svg-icon icon-class="邮箱" class="c-title-icon cc-f-s26" />
          <span class="cc-mar-l-6">绑定邮箱</span>
        </div>
        <div class="c-text-subheading cc-f-s14">
          当前已绑定邮箱账号
        </div>
      </div>
      <div class="control">
        <el-link :underline="false" type="primary">解绑</el-link>
      </div>
    </div>
    <el-divider class="cc-mar-t-20 cc-mar-b-20" />
    <div class="item">
      <div>
        <div class="title">
          <svg-icon icon-class="wx" class="c-title-icon cc-f-s26" />
          <span class="cc-mar-l-6">绑定微信</span>
        </div>
        <div class="c-text-subheading cc-f-s14">
          当前未绑定微信账号
        </div>
      </div>
      <div class="control">
        <el-link :underline="false" type="primary">绑定</el-link>
      </div>
    </div>
    <el-divider class="cc-mar-t-20 cc-mar-b-20" />
    <div class="item">
      <div>
        <div class="title">
          <svg-icon icon-class="手机" class="c-title-icon cc-f-s26" />
          <span class="cc-mar-l-6">绑定手机</span>
        </div>
        <div class="c-text-subheading cc-f-s14">
          当前未绑定手机账号
        </div>
      </div>
      <div class="control">
        <el-link :underline="false" type="primary">绑定</el-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {
    }
  },
  computed: {},
  mounted() {},
  methods: {}
}

</script>
<style lang='scss' scoped>
.c-security-content {
  padding: 10px 10px;
  .c-title-icon {
    vertical-align: middle;
  }
  .item {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-self: center;
    justify-content: space-between;
    margin: 10px 0;
    .title {
      color: #000000;
      margin-bottom: 10px;
    }
    .control {
      align-self: center;
    }
  }
}
</style>
