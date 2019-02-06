<template>
<div >
    <div class="title">
    <h1>About the event</h1>
    </div>
    <div  class="content">
        
    
    <p >
        DevHost:19 is an annual Student Developers meet organised by Sahyadri Open-Source Community (SOSC) to bring together young and talented developers from in and around Mangalore. DevHost:19 is aimed to create a platform to join together clubs and organizations to spread the information on latest techologies and trends in the IT industry and train the students to be part of it.
        </p>
        <p >
            DevHost:19 is a two day event which will take place on 24th and 25th March 2019 and will have speakers from various organizations and also will have a 24hrs Hackathon. DevHost:19 is focused on bringing more student developers to foreground. The event is open-to-all and free of cost for anyone who is interested.
        </p>

    </div>
    
<div class="card-holder">
    <div class="card-container" data-aos="fade-up" data-aos-duration="500">
    <div class="card">
        <img src="../assets/cal2.png" style="width:50px">
       <h2>Exciting Workshops</h2>
       
       <p>
           Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat, nemo, sit ipsa incidunt ea necessitatibus at optio aspernatur nisi officia voluptates rem quam, dicta mollitia! Excepturi error quis quidem voluptas!
       </p>
   
    </div>
    </div>



    <div class="card-container" data-aos="fade-up" data-aos-duration="500">
    <div class="card">
         <img src="../assets/live2.png" style="width:50px">
       <h2>handson-sessions</h2>
       <p>
           Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat, nemo, sit ipsa incidunt ea necessitatibus at optio aspernatur nisi officia voluptates rem quam, dicta mollitia! Excepturi error quis quidem voluptas!
       </p>
   
    </div>
    </div>



    <div class="card-container" data-aos="fade-up" data-aos-duration="500">
    <div class="card">
        <img src="../assets/qa2.png" style="width:50px ">
       <h2>Q & A sessions</h2>
       <p>
           Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat, nemo, sit ipsa incidunt ea necessitatibus at optio aspernatur nisi officia voluptates rem quam, dicta mollitia! Excepturi error quis quidem voluptas!
       </p>
   
    </div>
    </div>


   
</div>
</div>
</template>
<script>
import AOS from 'aos';
import 'aos/dist/aos.css';
export default {
    name:'about',
    created(){
        AOS.init()
    
    },
}
</script>


<style scoped>
@import url('https://fonts.googleapis.com/css?family=Open+Sans:400');
body{
    margin: auto;
}
img{
    padding-top: 10px;
    
}
.title{
    margin: 0;
    
    background-color: #292d53;
    color: white;
    font-size: 25px;
    padding-top:50px; 
    text-align: center;
    
    font-family: 'Open Sans',sans-serif;
}
.content{
    margin: auto;

    height: 150px;
    background-color:  #292d53;
    color: grey;
    font-size: 15px;
  
  
    display: flex;
    justify-content: space-evenly;
    overflow-x: hidden;
    font-family: 'Open Sans',sans-serif;
}
h1{
    margin: auto;
    border-bottom: 10px;
    border-bottom-color: #fe2a77;
}
.content p{
    
    text-align: center;
    width: 500px;
    
    
}
.cards{
    
   overflow: hidden;
    white-space: nowrap;
}

.card-holder{
    margin: auto;
    padding-top: 40px; 
    height: 250px;
    background-color:  #2c305e;
    color: white;
    font-size: 10px;
    
    text-align: center;
    display: flex;
    justify-content: space-evenly;
    overflow: hidden    ;
    font-family: 'Open Sans',sans-serif;
}

.card-container{
    width: 200px;
    height: 220px;
  
    box-shadow: 0 10px 10px 0px rgba(0, 0, 0, 0.2);
    background-image: -webkit-linear-gradient(276deg, #f9643d, #fe2a77);
    background-image: linear-gradient(174deg, #f9643d, #fe2a77);
}
.card{
    
}

@media(max-width:900px){
  
.content p{width:auto}
  .content{padding-left: 0;flex-direction: column;height: 350px; }
  .card-holder{flex-direction: column; height: 1000px;align-items: center;padding-top: 10px;} 
  
  
}
@media(min-width:568px){
}
    
</style>
