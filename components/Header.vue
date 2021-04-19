<template>
  <header>
    <h1 class="title">Acrovision</h1>
    <nav class="nav">
      <ul class="menu-group">
        <li class="menu-item"><a href="#">HOME</a></li>
        <li class="menu-item"><a href="#">COMPANY</a></li>
        <li class="menu-item"><a href="#">SEVICE</a></li>
        <li class="menu-item"><a href="#">WORKS</a></li>
        <li class="menu-item"><a href="#">CONTACT</a></li>
      </ul>
    </nav>
  </header>
</template>


<style lang="scss" scoped>
// 使用するカラー
$mainColor:white; 

header {
  display: flex;
  width: 100%;
  height: 100px;
  background-color:$mainColor;
  align-items: center;
}

.title {
  margin-right: auto;
}

.menu-item {
  list-style: none;
  display: inline-block;
  padding: 10px;
}
</style>