<template>
  <div class="wrapper-content wrapper-content--fixed">
    <Post :post="post" />
    <Comments :comments="comments" />
    <NewComment />
  </div>
</template>

<script>
  import Post from "~/components/Blog/Post";
  import NewComment from "~/components/Comments/NewComment";
  import Comments from "~/components/Comments/Comments";

    export default {
      components: {
        Post,
        NewComment,
        Comments
      },
      data(){
        return{
          post: {
            id: 1,
            title: '1 post',
            descr: ' Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem, sapiente!',
            content: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam animi consectetur corporis culpa distinctio dolor dolores eos error eum exercitationem explicabo facere facilis fugiat inventore ipsam laudantium mollitia natus nisi, nobis, nostrum porro provident quae sapiente, sed totam vel velit. Alias consequuntur, cumque doloremque explicabo facere nesciunt quam ratione reiciendis velit? Ab aliquam architecto asperiores consectetur consequatur cum ea eius enim error ex explicabo fugit id impedit ipsa ipsum iste itaque, iusto maiores maxime minima minus necessitatibus numquam odit omnis quaerat quam quia repudiandae sed similique sunt tempore tenetur ullam voluptatem. Culpa eligendi excepturi labore laudantium mollitia nihil perspiciatis ratione.',
            img: 'https://static.kulturologia.ru/files/u18476/belayaporoda-0.jpg'
          },
          comments: [
            { name: 'Alex', text: ' Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem, sapiente!'},
            { name: 'Serega', text: ' Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem, sapiente!'},
            { name: 'Yuri', text: ' Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem, sapiente!'}
          ]
        }
      }
    }
</script>

<style lang="scss">
  .post {
    max-width: 900px;
    margin: 0 auto;
  }

  .post-header{
    text-align: center;
    margin-bottom: 30px;
    img{
      max-width: 400px;
      margin-bottom: 16px;
    }
    p{
      color: #999999;
    }
  }
  .post-body{
    text-align: left;
  }
</style>
