<template >
    <section id="about" class="container bg-gradient">
    <h2 class="pt-">
      <svg xmlns="http://www.w3.org/2000/svg" width="19" height="16" fill="currentColor" class="bi bi-info-circle" viewBox="0 0 16 16">
        <path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"/>
        <path d="m8.93 6.588-2.29.287-.082.38.45.083c.294.07.352.176.288.469l-.738 3.468c-.194.897.105 1.319.808 1.319.545 0 1.178-.252 1.465-.598l.088-.416c-.2.176-.492.246-.686.246-.275 0-.375-.193-.304-.533L8.93 6.588zM9 4.5a1 1 0 1 1-2 0 1 1 0 0 1 2 0z"/>
      </svg>About
    </h2>
    <div class="container-fluid">
      <div class="row">
        <div class="col-6 p-4 d-flex d-md-flex text-center">
              <div id="carouselExampleDark" class="carousel carousel-dark slide w-50 mx-auto" data-bs-ride="carousel">
                  <div class="carousel-indicators">
                    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
                    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
                  </div>
                  <div class="carousel-inner rounded-3">
                    <div class="carousel-item active" data-bs-interval="10000">
                      <img src="https://i.postimg.cc/FRjK4Q2Q/IMG-20210822-WA0208.jpg" class="d-flex w-100 mx-auto img" alt="image1" loading="lazy">
                    </div>
                    <div class="carousel-item" data-bs-interval="2000">
                      <img src="https://i.postimg.cc/kMbQ26dn/IMG-20210822-WA0212.jpg" class="d-block w-100 mx-auto img" alt="image2" loading="lazy">
                    </div>
                    <div class="carousel-item">
                      <img src="https://i.postimg.cc/q7SBW1hQ/IMG-20210822-WA0192-1.jpg" class="d-block w-100 mx-auto " alt="image3" loading="lazy">
                    </div>
                  </div>
                  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                  </button>
                  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
    
                  </button>
                
                </div>
              </div>
                  <div class="col-6 p-3 mx-auto my-auto">
                  <p>Hi My name is Brandon Swinton ,I am an aspiring developer .I was born in Cape Town ,South Africa ,I was raised in Mitchells Plain and this is where Im currently located in .I am a bachelor pass Matriculant from Portland high school.I am a very disciplined young man.I believe in hard work and commitment to be successful in anything .I love solving problems and i love using my creativity in my work.I can work alone and i can corporate well within a team.I believe i can push any company to success with my talents</p>
                </div>
        </div>
    </div>
</section>
</template>
<script>
export default {
    
}
</script>
<style>
.container{
    border-radius: 20px;   
}

h2{
    color: lightslategray;
}
@media screen and (max-width:720px){
    .container-fluid{
        width: 100%;
    }
    #about .col-6{
        width: 100%;
        height: 100%;
        
    }
  }   
</style>