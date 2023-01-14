<template >
  <h2>
      <svg xmlns="http://www.w3.org/2000/svg" width="19" height="16" fill="currentColor" class="bi bi-info-circle" viewBox="0 0 16 16">
        <path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"/>
        <path d="m8.93 6.588-2.29.287-.082.38.45.083c.294.07.352.176.288.469l-.738 3.468c-.194.897.105 1.319.808 1.319.545 0 1.178-.252 1.465-.598l.088-.416c-.2.176-.492.246-.686.246-.275 0-.375-.193-.304-.533L8.93 6.588zM9 4.5a1 1 0 1 1-2 0 1 1 0 0 1 2 0z"/>
      </svg>Testimonials
    </h2>
  <div id="container" class="container mx-auto d-flex align-items-center justify-content-center flex-wrap">
  <div v-for="comments in Testimonials" keys="nice" class="box ">
            <div class="body">
                <div class="imgContainer">
                    <img :src="comments.image" alt="...">
                </div>
                <div class="content d-flex flex-column align-items-center justify-content-center">
                    <div>
                        <h3 class="text-white fs-5">{{ comments.name }}</h3>
                        <p class="fs-6 text-white">{{ comments.reference }}</p>
                    </div>
                </div>
            </div>
        </div>
</div>
</template>
<script>
import { reference } from '@popperjs/core';

export default {
    name: 'nice',
    data(){
        return{
            Testimonials : [
                {
                    id: 1,
                    name:'Timothy Jennike',
                    image:'https://i.postimg.cc/FsJGLZym/C11-1.jpg',
                    title:'Developer',
                    reference:'Brandon is hard working guy who completes every project and reaches every goal that he sets for himself.  He is a selfless peer who go out of his way to assist others if they are having trouble with something. He is friendly and respectful which makes him perfect for the work-environment.'
                },
                {
                    id: 2,
                    name:'Maxwill Isaacs', 
                    image:'https://i.postimg.cc/SNq6m0Nw/Me-Profile.jpg',
                    title:'Developer',
                    reference:'Brandon is a very dependable and passion driven person .He is a great team player and is very passionate in his work which he represents .He is very confident,consistent and gives his all and not afraid to listen to advice from peers .'
                },
                {
                    id: 3,
                    name:'Lindokuhle Mgoqi',
                    image:'https://i.postimg.cc/d3mwvZtZ/DSC-3517.jpg',
                    title:'Developer',
                    reference:'Brandon is dedicated to his craft and always looking for ways to improve it and has a tremendous amount of productivity. He is always showing love to those around him'
                },
                {
                    id: 4,
                    name:'Sive Shabane',
                    image:'https://i.postimg.cc/rpqXNy8n/Screenshot-20221103-143935-1.jpg',
                    title:'Developer',
                    reference:' A wonderful colleague to work beside. Always there to lend a helping hand when called upon or even offers to help when he can see that a certain task is a handful. Slow to act on emotions and impulses in order to maintain a healthy work environment for everyone around him. Thoughtful and considerate in his actions and words'
                },
                {
                  id: 5,
                  name:'Joel Mukanya',
                  image:'https://i.postimg.cc/5NPZK37D/1.jpg',
                  title:'Lecturer',
                  reference:'Brandon is a very creative, go-getter, and well-behaved student. He does enjoy working with his classmates and works well on his project.He has gained knowledge of web development, including Bootstrap 5. I will be very delighted to see him get hired.'
                },
                {
                  id: 6,
                  name:'Candice Amon',
                  image:'https://i.postimg.cc/9MxgMX7y/candice-2022.jpg',
                  title:'Facilitator',
                  reference:'Very disciplined and only focus on the task at hand. His presence demands attention without having to say a word. He is very selective with who he surrounds himself with and loves having meaningful conversations.'
                }
              ]
            }
          }
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap');

/* Reseting */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body{
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
}

#container{
  margin-bottom: 5%;
  transform-style: preserve-3d;
}

#container .box{
    position: relative;
    width: 300px;
    height: 300px;
    margin: 20px;
    transform-style: preserve-3d;
    perspective: 1000px;
    cursor: pointer;
}

#container .box .body{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    transform-style: preserve-3d;
    transition: 0.9s ease;
}



#container .box .body .imgContainer{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    transform-style: preserve-3d;
}

#container .box .body .imgContainer img{
  border-radius: 10px;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    backface-visibility: hidden;
    object-fit: cover;
}

#container .box .body .content{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: transparent;
    backface-visibility: hidden;
    transform-style: preserve-3d;
    transform: rotateY(180deg);
}

#container .box:hover .body{
    transform: rotateY(180deg);
}

#container .box .body .content div{
    transform-style: preserve-3d;
    padding: 20px;
    background: transparent;
    transform: translateZ(100px);
}

#container .box .body .content div h3{
    letter-spacing: 1px;
}
body{
  margin-bottom: 5%;
}

.card-text{
  margin-left: 25%;
}
.card{
  border: none;
}
h2{
  color: lightslategray;
  padding-bottom: 3%;
}


    
</style>