<template>
  <div>
    <h1>Artigos</h1>
    <section>
      <div v-for="article in articles" :key="article._path">
        <NuxtLink :to="article._path">{{ article.title }}</NuxtLink>
      </div>
    </section>
  </div>
</template>

<script setup>
const articles = await queryContent('blog').find();
</script>
