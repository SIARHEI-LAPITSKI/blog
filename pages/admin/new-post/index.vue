<template>
  <NewPostForm @submit="onSubmit" />
</template>

<script>
  import NewPostForm from '~/components/Admin/NewPostForm'
    export default {
        components: {NewPostForm},
        layout: 'admin',
        methods: {
          onSubmit(post){
            console.log('Post Added')
            console.log(post)
          }
        }
    }
</script>

<style scoped>

</style>
