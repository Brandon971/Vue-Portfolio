<template >
       <div id="home" class="container-fluid">
            <div class="land">
                <p><h1 id="h1">My Name is Brandon Swinton</h1></p>
                <p><h2 id="h2">This is my Portfolio</h2></p>
                <a href="../assets/Brandon Swinton's CV.docx.pdf"><button  type="button" class="btn btn-outline-secondary d-md-flex m-auto">Download CV</button></a>
            </div>
        </div>
</template>
<script>
export default {
     
}
</script>
<style>
*,
*::after,
::before{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

h1, h2, h3, h4, h5, h6 {
    text-align: center;
    margin-bottom: 15px;
}  

body{
    background-image: url(https://i.postimg.cc/BvfdYCD9/1477387.png);
    font-family: sans-serif;
    background-size: cover;
    overflow-x: hidden;
}

.land{
    padding-top: 250px;
    color:antiquewhite;
    align-content: center;
}

.land img {
    border-radius: 30px;
    display: block;
    margin: 15px auto;
    width: 300px;
}

.land a{
    text-decoration: none;
}
h2,h4{
    color: lightslategray;
    text-align: center;
}
p{
    color: antiquewhite;
    font-family: monospace;
}

#h1{
    position: relative;
    animation: moveright 3s infinite;
    animation-direction: alternate;
}

#h2{
    color: lightslategray;
    position: relative;
    animation: moveleft 3s infinite;
    animation-direction: alternate; 
}

@keyframes moveright {
    from{ left: 0%;}
    to { left: 10%;}  
}
@keyframes moveleft {
    from{right: 0%;}
    to{right: 10%;}   
}
    
</style>