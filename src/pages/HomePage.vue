<template>
  <div class="container-fluid">
    <section class="row">
      <div class="col-12 main-image ">
        <div class="">

          <!-- <p class="fs-1 text-dark  ">Welcome to my Landing Page.</p> -->
        </div>
      </div>

    </section>
    <section class="row d-flex justify-content-center">
      <div class="col-12">
        <p class="text-center p-3 main-text">The Approach</p>
      </div>
      <div class="col-6 ">
        <p class="text-center fs-5 pb-5">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eius doloribus debitis
          iusto
          corporis quod facilis,
          corrupti delectus! Beatae enim neque maxime commodi distinctio saepe ipsa magni! Error doloribus repellat a.</p>

      </div>
    </section>
    <section class="row">
      <div class=" column">
        <img class="project-image"
          src="https://images.unsplash.com/photo-1502945015378-0e284ca1a5be?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTF8fHdlYnNpdGVzfGVufDB8fDB8fHww"
          alt="" style="width: 100%;">
      </div>
      <div class="column">
        <img class="project-image"
          src="https://images.unsplash.com/photo-1502945015378-0e284ca1a5be?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTF8fHdlYnNpdGVzfGVufDB8fDB8fHww"
          alt="" style="width: 100%;">
      </div>
      <div class="column">
        <img class="project-image"
          src="https://images.unsplash.com/photo-1502945015378-0e284ca1a5be?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTF8fHdlYnNpdGVzfGVufDB8fDB8fHww"
          alt="" style="width: 100%;">
      </div>
    </section>
    <section class="row d-flex justify-content-center align-items-center">
      <div class="col-4 m-4 p-5">
        <img class="img-fluid bio-image"
          src="https://images.unsplash.com/photo-1554151228-14d9def656e4?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OHx8cG9ydHJhaXQlMjBnaXJsfGVufDB8fDB8fHww"
          alt="">
      </div>
      <div class="col-3">
        <p class="fs-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga ea molestias quidem, nihil maxime
          quia distinctio
          at, ratione, voluptates autem sit consectetur eum pariatur magnam eveniet laudantium molestiae explicabo.
          Maxime, tenetur, totam quos sit pariatur ab illo incidunt mollitia repudiandae, eligendi sint vitae quo! Error
          quas quo sit praesentium illum?</p>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  setup() {
    return {

    }
  }
}
</script>

<style scoped lang="scss">
.main-image {
  background-image: url("https://images.unsplash.com/photo-1563419837758-e48ef1b731dd?q=80&w=2787&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  height: 100vh;

}

.main-text {
  font-family: 'Pinyon Script', cursive;
  font-size: 60px;
}

.bio-image {
  width: 500px;
  height: 700px;
  object-fit: cover;
  position: center;
  border-radius: 7px;
  border: 3px solid black;
}



.column {
  float: left;
  width: 33.33%;
  padding: 7px;
}

.project-image {
  border-radius: 7px;
  border: solid black 3px;

}
</style>
