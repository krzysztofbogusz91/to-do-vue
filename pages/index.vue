<template>
  <div id="id">
    <header class="header">Header</header>
    <nav class="nav">
      <ul class="nav-list">
        <li class="nav-list-elem">Opcja 1</li>
        <li class="nav-list-elem">Opcja 2</li>
        <li class="nav-list-elem">Opcja 3</li>
        <li class="nav-list-elem">Opcja 4</li>
      </ul>
    </nav>
    <main class="main">Główna treść</main>
    <aside class="aside">Treść dodatkowa</aside>
    <footer class="footer">Footer</footer>
  </div>
</template>

<script>
export default {
  components: {}
}
</script>

<style>
/* 
  Lista menu columna
  flex-wrap
  
 */
ul {
  margin: 0;
  padding: 0;
}
.header {
  border: 1px solid red;
}
.nav {
  border: 1px solid green;
}
.nav-list {
  list-style: none;
  border: 1px solid orange;
}
.nav-list-elem {
  border: 1px solid yellowgreen;
  background-color: red;
}
.main {
  border: 1px solid grey;
}
.aside {
  border: 1px solid blue;
}
.footer {
  border: 1px solid violet;
}
</style>
