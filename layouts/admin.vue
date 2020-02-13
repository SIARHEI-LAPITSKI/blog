<template>
  <div class="wrapper">
    <Header />
    <div class="wrapper-content wrapper-content--fixed">
      <Intro title="Admin Page">
        <nuxt-link class="link linkWhite" to="/admin">Admin</nuxt-link>
        <nuxt-link class="link linkWhite" to="/admin/new-post">New Post</nuxt-link>
      </Intro>
      <nuxt />
    </div>
  </div>
</template>

<script>
  import Header from "@/components/system/Header";

  export default {
    components: {Header}
  }
</script>
