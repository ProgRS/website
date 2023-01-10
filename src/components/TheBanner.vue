<template>
    <section class="banner-principal">
        <div class="center">
            <h2>Invista em viver.</h2>
            <h2>Investir toma tempo, mas não precisa ser o seu.</h2>
            <h3>Consulte nossos especialistas.</h3>
            <button class="btn">Saiba mais</button>
                 
        </div>

    </section>
</template>

<script>
export default {
    name:"TheBanner",
    
}
</script>

<style scoped>

    ul {
    list-style-type: none;
    }

    section.banner-principal{
        width: 100%;
        height: 400px;
        background-image: url("../assets/banner-primario.jpeg");
    }

    h2 {
        font-size: 50px;
        color: #fff;
        margin-left: 200px;
        margin-right: 250px;
        text-align: left;
        display: block;
         justify-content: flex-start;
    }

    h3 {
        font-size: 20px;
        margin-top: 35px;
        margin-bottom: 35px;
        justify-content: flex-start;
        margin-left: 200px;
        margin-right: 250px;
    }

     .btn {    
   display: block;
   padding: 10px 0px;
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
   margin-left: 200px;
  margin-right: 250px;
}

    

    button {
    background-color: white;
    color: black;
    border: none;
    border-radius: 15px;
    font-size: 14px;
    width: 130px;
    height: 40px;    
    font-weight: bold;
    }

    button:hover{
    background-color: white;
    color: rgb(199, 19, 73)
    }
</style>