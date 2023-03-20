<template>
  <header class="container">
    <NuxtLink class="logo" to="/">Nuxt Content Demo</NuxtLink>
    <nav class="menu-navbar">
      <ul class="menu">
        <li><NuxtLink to="/">Home</NuxtLink></li>
        <li><NuxtLink to="/blog">Blog</NuxtLink></li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 20px 30px;
}

.logo {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  font-size: 2.5em;
  font-weight: bold;
}

.menu {
  display: flex;
  flex-direction: row;
  gap: 20px;
}
</style>
