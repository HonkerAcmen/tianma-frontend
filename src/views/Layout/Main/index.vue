<template>
  <div class="content">
    <!-- <div class="search"></div> -->
    <input type="text" placeholder="请输入职位信息" class="search" />
    <div class="hot">
      <span>热门职位: </span>
      <ul>
        <li>Java</li>
        <li>.NET</li>
        <li>硬件测试</li>
        <li>IT技术支持</li>
        <li>实施工程师</li>
        <li>嵌入式工程师</li>
        <li>前端开发工程师</li>
      </ul>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  // background-color: green;
  width: 90%;
}
.search {
  width: 40%;
  height: 48px;
  margin-top: 40px;
  border: 2px solid #2359d8;
  border-radius: 10px;
  font-family: inherit;
  font-size: 100%;
}

.hot {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  margin-top: 10px;
}
.hot ul {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.hot span,
li {
  margin-right: 10px;
}
.hot li {
  padding: 4px 8px;
  cursor: pointer;
  background-color: #d4def0;
  color: #216bea;
  border-radius: 5px;
  transition: background-color ease-in 0.2s;
  &:hover {
    background-color: #216bea;
    color: #fff;
  }
}
</style>
