<template>
  <div class="wrapper-content wrapper-content--fixed">
    <section class="about">
      <div class="container">
        <h1 class="title">About my blog: </h1>
        <p>
          Lorem ipsum dolor sit amet,
          consectetur adipisicing elit.
          Dolor eligendi nesciunt odio.
          Itaque maxime provident ratione.
          Aliquam aliquid culpa cumque debitis
          est exercitationem facere impedit,
          inventore laborum nulla odit possimus
          praesentium quidem quod ratione, reiciendis
          rem repudiandae vero voluptas voluptatibus!
        </p>
        <client-only>
          <Intro title="Lorem ipsum dolor sit amet" />
          <p>
            Lorem ipsum dolor sit amet,
            consectetur adipisicing elit.
            Dolor eligendi nesciunt odio.
            Itaque maxime provident ratione.
            Aliquam aliquid culpa cumque debitis
            est exercitationem facere impedit,
            inventore laborum nulla odit possimus
            praesentium quidem quod ratione, reiciendis
            rem repudiandae vero voluptas voluptatibus!
          </p>
        </client-only>
        <img src="~/assets/img/design-web.jpg" alt=""/>
        <p>
          Lorem ipsum dolor sit amet,
          consectetur adipisicing elit.
          Dolor eligendi nesciunt odio.
          Itaque maxime provident ratione.
          Aliquam aliquid culpa cumque debitis
          est exercitationem facere impedit,
          inventore laborum nulla odit possimus
          praesentium quidem quod ratione, reiciendis
          rem repudiandae vero voluptas voluptatibus!
        </p>
      </div>
    </section>

  </div>
</template>

<script>
  export default {

  }
</script>

<style>
  .about{
    text-align: center;
  p{
    margin-bottom: 10px;
  }
  }
</style>
