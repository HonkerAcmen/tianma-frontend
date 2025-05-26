<template>
  <div class="content">
    <div class="left">
      <div class="title">天马求职</div>
      <div class="nav">
        <ul>
          <li>首页</li>
          <li>职位</li>
          <li>公司</li>
          <li>校园</li>
          <li>海外</li>
        </ul>
      </div>
    </div>
    <div class="right">
      <div class="nav">
        <ul>
          <li>我要招聘</li>
          <li>我要找工作</li>
        </ul>
      </div>
      <div class="btn">
        <el-button type="primary">登陆/注册</el-button>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.content {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  height: 60px;
  // background-color: #f4f4f4;
  padding: 5px 0;
  border-bottom: 1px solid #dddddd;
  box-shadow: 0px 1px 2px #dddddd;

  .left {
    display: flex;
    flex-direction: row;
    margin-left: 20px;
    .nav {
      margin-left: 20px;
    }
    .title {
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 24px;
      cursor: pointer;
    }
  }
  .right {
    display: flex;
    flex-direction: row;
    margin-right: 20px;

    .btn {
      display: flex;
      justify-content: center;
      align-items: center;
      margin-left: 5px;
    }
  }
}

.nav ul {
  display: flex;
  flex-direction: row;
  li {
    padding: 10px 20px;
    cursor: pointer;
    border-radius: 4px;
    transition: background-color ease-in 0.1s;
    &:hover {
      background-color: var(--el-color-info);
    }

    &:active {
      background-color: #dddddd;
    }
  }
}
</style>
