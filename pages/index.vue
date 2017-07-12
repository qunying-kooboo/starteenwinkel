<template>
  <section class="container">
    <ul class="page-list nostyle">
      <li><a href="home">home</a></li>
    </ul>
    <div>
      <logo/>
      <h1 class="title">
         NUXTNUXTNUXT纯纯粹粹次
      </h1>
      <h2 class="subtitle">
        Universal Vue.js Application
      </h2>
      <div class="links">
        <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation</a>
        <a href="https://github.com/nuxt/nuxt.js" target="_blank" class="button--grey">GitHub</a>
      </div>
    </div>
    <Foot/>
  </section>
</template>

<script>
import Logo from '~components/Logo.vue'
import Foot from '~components/footer.vue'

export default {
  components: {
    Logo,
    Foot
  }
}
</script>
<style scoped lang="scss">
.page-list{
  display: inline-block;
  padding: 20px;
  border: solid #ccc 1px;
  border-radius: 5px;
  font-size: 16px;
  a{
    color: #393939;
    text-decoration: none;
  }
}
/*.container
{
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title
{
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; 
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle
{
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links
{
  padding-top: 15px;
}*/
</style>
