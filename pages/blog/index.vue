<template>
  <div class="wrapper-content wrapper-content--fixed">
    <Intro title="My posts: " />
    <PostList :posts="posts" />
  </div>
</template>

<script>

  export default {

    data(){
      return{
        posts: [
          {
            id: 1,
            title: '1 post',
            descr: ' Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem, sapiente!',
            img: 'https://static.kulturologia.ru/files/u18476/belayaporoda-0.jpg'
          },
          {
            id: 2,
            title: '2 post',
            descr: ' Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem, sapiente!',
            img: 'https://static.kulturologia.ru/files/u18476/belayaporoda-0.jpg'
          },
          {
            id: 3,
            title: '3 post',
            descr: ' Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem, sapiente!',
            img: 'https://static.kulturologia.ru/files/u18476/belayaporoda-0.jpg'
          },

        ]
      }
    }
  }
</script>

<style lang="scss">

</style>
