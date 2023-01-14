<template >
  <section id="skills" class="container bg-gradient p-lg-5 p-0">
    <h2>
      <svg xmlns="http://www.w3.org/2000/svg" width="19" height="16" fill="currentColor" class="bi bi-tools"
        viewBox="0 0 16 16">
        <path
          d="M1 0 0 1l2.2 3.081a1 1 0 0 0 .815.419h.07a1 1 0 0 1 .708.293l2.675 2.675-2.617 2.654A3.003 3.003 0 0 0 0 13a3 3 0 1 0 5.878-.851l2.654-2.617.968.968-.305.914a1 1 0 0 0 .242 1.023l3.27 3.27a.997.997 0 0 0 1.414 0l1.586-1.586a.997.997 0 0 0 0-1.414l-3.27-3.27a1 1 0 0 0-1.023-.242L10.5 9.5l-.96-.96 2.68-2.643A3.005 3.005 0 0 0 16 3c0-.269-.035-.53-.102-.777l-2.14 2.141L12 4l-.364-1.757L13.777.102a3 3 0 0 0-3.675 3.68L7.462 6.46 4.793 3.793a1 1 0 0 1-.293-.707v-.071a1 1 0 0 0-.419-.814L1 0Zm9.646 10.646a.5.5 0 0 1 .708 0l2.914 2.915a.5.5 0 0 1-.707.707l-2.915-2.914a.5.5 0 0 1 0-.708ZM3 11l.471.242.529.026.287.445.445.287.026.529L5 13l-.242.471-.026.529-.445.287-.287.445-.529.026L3 15l-.471-.242L2 14.732l-.287-.445L1.268 14l-.026-.529L1 13l.242-.471.026-.529.445-.287.287-.445.529-.026L3 11Z" />
      </svg>Skills
    </h2>
    <p class="text-center col-12">Why you should choose me ?</p>
    <div class="container mx-auto d-flex align-items-center justify-content-center">
      <img class="logo " src="https://i.postimg.cc/YSrVNJZ4/html.png" alt="HTML">
      <img class="logo " src="https://i.postimg.cc/gj4FPmCP/css-3.png" alt="CSS">
      <img class="logo " src="https://i.postimg.cc/7YCm4x8M/bootstrap.png" alt="bootstrap">
      <img class="logo" src="https://i.postimg.cc/8P5PP0tb/js.png" alt="JavaScript">
    </div>
    <img class="logo pt-3" id="vue" src="https://i.postimg.cc/j2KN1Mjw/pngegg-4.png" alt="Vue">
    <div class="col-12 col-lg-6 mx-auto p-3">
      <h2 class="p-3">Soft Skills</h2>
      <h7 class="text-light">Creativity</h7>
      <div class="progress">
        <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar"
          aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"
          style="width: 95%"></div>
      </div>
      <h7 class="text-light">Ambition</h7>
      <div class="progress">
        <div class="progress-bar progress-bar-striped progress-bar-animated bg-success" role="progressbar"
          aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"
          style="width: 85%"></div>
      </div>
      <h7 class="text-light">Discipline</h7>
      <div class="progress">
        <div class="progress-bar progress-bar-striped progress-bar-animated bg-dark" role="progressbar"
          aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"
          style="width: 100%"></div>
      </div>


    </div>
  </section>
</template>
<script>
export default {



}
</script>
<style>
#skills {
  border-radius: 10%;
}

.logo {
  width: 10vw;
  padding-left: 5%;
}

#vue {
  margin-left: 42%;
  height: 13vh;
}

@media screen and (max-width:720px) {
  .container {
    width: 100%;
  }

  #vue {
    width: 10vw;
    height: 7vh;
    margin-left: 42%;
  }
}
</style>