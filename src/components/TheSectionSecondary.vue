<template>
<section class="banner-secundario">
        <div >
            <h2>Invista em viver.</h2>
            <h2>Investir toma tempo, mas não precisa ser o seu.</h2>            
            <button class="btn">Saiba mais</button>                
        </div>
    </section>    
</template>

<script>
export default {
    name:"TheSectionSecondary",
    
}
</script>

<style scoped>

section.banner-secundario{
        width: 100%;
        height: 350px;
        display: flex;
        padding: 140px 140px;
        background-position: -50 -1000px;  
        justify-content: space-evenly;        
        background-image: url("../assets/banner-secundario.jpg");
        margin-left: auto;
        margin-right: auto;
        list-style: none;
        position: relative;
        left: 0;
        top: 90px;
        
        
    }
    

    h2 {
        color: #fff;
        font-size: 30px;
    }

    .btn { 
   display: block;
   padding: 10px 30px;
   background:  rgb(199, 19, 73);;
   border-radius: 4px;
   color: #fff;
   text-align: center;
   font-size: 1rem;
   box-shadow: 0 4px 8px rgba(30, 60, 90, 0.2);
   transition: all 0.3s;
   border:none;
   font-family: "Avenir", Helvetica, Arial, sans-serif;
   cursor: pointer;
}

    

    button:hover{
    background-color: rgb(199, 19, 73);
    color: #FFF;
    }

</style>