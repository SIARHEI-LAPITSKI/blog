<template>
  <div class="wrapper-content wrapper-content--fixed">
    <promo />
    <Intro title="My lasts posts: " />
    <PostList :posts="posts" />
    <Contact />
  </div>


</template>

<script>
  import promo from '~/components/Promo'
  import Contact from "~/components/Contact";



  export default {
    components: {
      promo,
      Contact
    },
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
