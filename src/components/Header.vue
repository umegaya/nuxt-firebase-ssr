<template>
  <header class="wrapper">
    <nav>
      <ul>
        <li><nuxt-link to="/">HOME</nuxt-link></li>
        <li><nuxt-link to="/content">CONTENT</nuxt-link></li>
        <li><nuxt-link to="/about">ABOUT</nuxt-link></li>
      </ul>
    </nav>
  </header>
</template>


<style scoped>
ul {
  display: flex;
  list-style: none;
  padding: 0;
}

li {
  margin-right: 10px;
}
</style>
