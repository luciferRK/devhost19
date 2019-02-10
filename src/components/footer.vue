<template>
<div class="footer">
    <div class="social">
        <a href="https://sosc.org.in/"class="sosc-logo" ><img src="../assets/sosc_logo.png" class="sosc-logo-img"></a>
        <a href="https://github.com/so-sc" class="fa fa-github"></a>
        <a href="https://instagram.com/sosc.sahyadri"class="fa fa-instagram"></a>
        <a href="https://linkedin.com/company/sosc-sahyadri" class="fa fa-linkedin"></a>
    </div>
    <div class="address">
        <p>
        <strong>Sahyadri Open-Source Community</strong>
        <br>
        Sahyadri College of Engineering and Management, Adyar, Mangalore - 575007 IN
        <br>
        sosc@sahyadri.edu.in
        </p>
    
    </div>
    <div class="Copyright">SOSC &copy 2019</div>
</div>
</template>

<style scoped>
     @import url('https://fonts.googleapis.com/css?family=Open+Sans:400');
     @import url('https://maxcdn.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css');
    .fa {   
        padding: 2px;
        font-size: 30px;
        width: 40px;
        text-align: center;
        text-decoration: none;
        margin: 3px 2px;
    }
    .fa:focus{
        outline: none;
    }
    .sosc-logo,.sosc_logo:focus{
        outline:none;
    }
    .fa:hover {
        opacity: 0.7;
        font-size:32px;
        transition:font-size 0.4s;
        margin:1px 2px;
    }
    .sosc-logo-img{
        padding: 2px;
        width: 44px;
        margin: 3px 1px;
        height:auto;

    }
    .sosc-logo-img:hover{
        opacity: 0.5;
    }
    .fa-instagram {
    color: white;
    }   
    .fa-github{
        color: white;
    }
    .fa-linkedin{
        color:white;
    }
    .social{
        display:flex;
        color: white;
        font-size: 15px;
        font-family: 'Open Sans',sans-serif;
        
    }
    .address{
         display: flex;
         padding:10px;
         color: white;
        font-size: 15px;
        font-family: 'Open Sans',sans-serif;
        margin:5px 2px;
    }
    .Copyright{
         
        text-align:center;     
        color: white;
        font-size: 15px;
        padding:5px;
        font-family: 'Open Sans',sans-serif;
    }
    a{
        text-decoration: none;
        padding: 10px;
        color: white
    }
    .footer{
           background-color:  #2e3261;
    }
</style>

<script>
export default {
    name:'footer'
}
</script>

