<template>
  <section class="container">
    <div>
      <img src="~/assets/logo.svg">
      <h1 class="title">nuxt-feathers-boilerplate</h1>
      <h2 class="subtitle">A full-stack boilerplate leveraging Nuxt 2.x and Feathers 3.x</h2>
      <div class="links">
        <a href="https://nuxtjs.org/" target="_blank" class="button--green">Nuxt docs</a>
        <a href="https://feathersjs.com" target="_blank" class="button--grey">Feathers docs</a>
      </div>
    </div>
  </section>
</template>

<style>

.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 60px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 30px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
