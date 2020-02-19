<template>
  <NewPostForm
    :postEdit="post"
    @submit="onSubmit" />
</template>

<script>
  import NewPostForm from '~/components/Admin/NewPostForm'
  export default {
    components: {NewPostForm},
    layout: 'admin',
    data() {
      return {
        post: {
          id: 1,
          title: '1 post',
          descr: ' Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem, sapiente!',
          content: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam animi consectetur corporis culpa distinctio dolor dolores eos error eum exercitationem explicabo facere facilis fugiat inventore ipsam laudantium mollitia natus nisi, nobis, nostrum porro provident quae sapiente, sed totam vel velit. Alias consequuntur, cumque doloremque explicabo facere nesciunt quam ratione reiciendis velit? Ab aliquam architecto asperiores consectetur consequatur cum ea eius enim error ex explicabo fugit id impedit ipsa ipsum iste itaque, iusto maiores maxime minima minus necessitatibus numquam odit omnis quaerat quam quia repudiandae sed similique sunt tempore tenetur ullam voluptatem. Culpa eligendi excepturi labore laudantium mollitia nihil perspiciatis ratione.',
          img: 'https://static.kulturologia.ru/files/u18476/belayaporoda-0.jpg'
        },
      }
    },
    methods: {
      onSubmit(post){
        console.log('Post Editing')
        console.log(post)
      }
    }
  }
</script>

<style scoped>

</style>
