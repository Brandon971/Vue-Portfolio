<template >
    <section id="resume">
        <div class="container">
            <h2 class="title pb-5">Work and Education</h2>
            <div class="row d-flex flex-column flex-md-row g-2 pt-2 pb-5">
                <div v-for="exp in resume" :key="exp" class="col-12">
                    <h3 class="pb-3">{{exp.work }}</h3>
                    <img :src="exp.image" alt="...">
            <p>{{ exp.etc }}</p>
        </div>
            </div>
        </div>
    </section>
</template>
<script>

export default {
    name:"exp",
    data(){
        return{
            resume: [
                {
                    id: 1 ,
                    work:'Portland High School',
                    etc:'Ive studied at portland high ,I was a very discipline student ,I have excelled at all my subjects during the years.Ive gotten an certificate for business studies which I am very proud of ,reason being i have worked hard for this achievement .School has taught me many lessons ,Ive learned how to be discipline ,I learned how to work hard to achieve success.Achievements made me enjoy school.',
                    image: 'https://i.postimg.cc/5NLZfNbW/My-project-2.png'

                },
                {
                    id:2,
                    work:'Night Owl(Chauffeur)',
                    etc:'Ive done long distance chauffeuring for 1 year and 6 months for an company Night Owls ,It helped me gain social experience.Meeting and conversating with new people.Ive gain experience in traveling long distances at late time slots,Chauffeuring has taught me patience and how to endure,I stopped working for night owls when life choices gave me an amazing opportunity to learn a skill that improve my career and my self' ,
                    image:'https://i.postimg.cc/qRkRMb5c/My-project-1.png'
                },
                {
                    id:3,
                    work:'Life Choices Academy',
                    etc:'Ive Started studying at Life Choice Academy in September 2022,For an coding course, I chose life choices academy reason being I have always aspired to be an creator and coding will explore my creativity and passion.Life choices has taught new skills in coding as well as life skills,Personal development and work ethics,Ive learned Javascript,HTML,Bootstrap,CSS,Vue awell as how behave in a work space and how to be mindful and a more kinder and gentler human being.',
                    image:'https://i.postimg.cc/qMhCY768/Screenshot-20230113-095956.png'
                }
            ]
        }
    }

}
</script>
<style>
img{
    display: flex;
    justify-content: center;
    margin: auto;
}

.title ,h3{
    color: lightslategray;
}
@media screen and (max-width:720px){
    p{
        align-items: center;
    }
}
    
</style>