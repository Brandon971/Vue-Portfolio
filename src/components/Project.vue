<template >
      <h2>
        <i class="bi-k bi-person-workspace"></i>Projects
    </h2>
    <div class="row w-75 gap-5 mx-auto pt-3 justify-content-center flex-wrap ">
    <div v-for="work in Projects" keys="work" class="card bg-transparent px-0" style="width: 18rem;">
  <img :src="work.image" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title text-light">{{work.title}}</h5>
    <a :href="work.github" target="_blank
    " class="link"><i class="bi bi-github"></i></a>
<a :href="work.netlify" target="_blank" class="link"><i class="bi bi-globe2"></i></a>
  </div>
    </div>
  </div>

</template>
<script>
import { reference } from '@popperjs/core';

export default {
    name: 'work',
    data(){
        return{
            Projects : [
                {
                    id: 1,
                    title:'Crud ecomerce',
                    image:'https://i.postimg.cc/cJmpBwbJ/Screenshot-20230111-145803.png',
                    github:'https://github.com/Brandon971/End-of-module--JS.git',
                    netlify:'https://brandons-pos.netlify.app/html/products.html'
                },
                {
                    id: 2,
                    title:'Calculator', 
                    image:'https://i.postimg.cc/CM7Lvn99/Screenshot-20230111-145037.png',
                    github:'https://github.com/Brandon971/Calculator.git',
                    netlify:'https://brandons-basic-calculator.netlify.app/'
                },
                {
                    id: 3,
                    title:'First Ecomerce', 
                    image:'https://i.postimg.cc/BbjfWG01/Screenshot-20230112-090230.png',
                    github:'https://github.com/Brandon971/Ecommerce',
                    netlify:'https://symphonious-strudel-5a3cbd.netlify.app'
                },
                {
                    id: 4,
                    title:'Bookcover back-front', 
                    image:'https://i.postimg.cc/FssXX39Q/Screenshot-20230112-091623.png',
                    github:'https://github.com/Brandon971/Flipcard',
                    netlify:'https://dazzling-bombolone-15756f.netlify.app'
                    
                },
                {
                    id: 5,
                    title:'First navbar', 
                    image:'https://i.postimg.cc/659cHhBC/Screenshot-20230112-092102.png',
                    github:'https://github.com/Brandon971/Week1Project.git',
                    netlify:'https://charming-longma-18df01.netlify.app/'

                    
                },
                {
                    id: 6,
                    title:'Vue-ecomerce', 
                    image:'https://i.postimg.cc/wM17jvJq/Screenshot-20230112-093807.png',
                    github:'https://github.com/Brandon971/Vue-ecommerce.git',
                    netlify:'https://gleaming-axolotl-f3a6e8.netlify.app'

                }
                

            ]
        }
    }
}
</script>
<style>
.link{
    margin-left: 30%;
}
i{
    color: red;
}
.bi-k{
    color: lightslategray;
}
h2{
    color: lightslategray;
}


</style>