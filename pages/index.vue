<template>
  <header>
    <h1 class="title">タイトル</h1>
    <nav class="nav">
      <ul class="menu-group">
        <li class="menu-item"><a href="#">項目1</a></li>
        <li class="menu-item"><a href="#">項目2</a></li>
        <li class="menu-item"><a href="#">項目3</a></li>
        <li class="menu-item"><a href="#">項目4</a></li>
        <li class="menu-item"><a href="#">項目5</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {}
</script>

<style lang="scss">
// メディアクエリ
$pc: 'only screen and (min-width:769px) ';
$sp: 'only screen and (max-width:769px) ';

// 使用するカラー
$mainColor:#002e73; 

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
