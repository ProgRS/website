<template>
    <div class="descrition">
        <div id="bloc">
            <img  class="right images" src="/img/principal.jpg" />
            <div class="main-texts">
                <h2>O que é Lorem Ipsum?</h2>
                <h3>Lorem Ipsum é simplesmente uma simulação de texto .</h3>
                <h3>Lorem Ipsum sobreviveu não só a cinco séculos, como também ao 
                    salto para a editoração eletrônica, permanecendo essencialmente inalterado.</h3>
                <h3>Se popularizou na década de 60, quando a Letraset lançou decalques contendo 
                    passagens de Lorem Ipsum, e mais recentemente quando passou a ser integrado a softwares</h3>
                <button class="btn">Comece agora</button>
            </div>
        </div>
        <div id="bloc">
            <div class="secondary-texts">
                <h2>O que é Lorem Ipsum?</h2>
                <h3>Lorem Ipsum é simplesmente uma simulação de texto .</h3>
                <hr class="solid" />
                <h3>Lorem Ipsum sobreviveu não só a cinco séculos, como também ao 
                    salto para a editoração eletrônica, permanecendo essencialmente inalterado.</h3>
                <button class="btn">Comece agora</button>
            </div>
            <img class="right images" src="/img/secundario.jpg"/>
        </div>
    </div>
</template>

<script>
export default {
    name: "TheSectionMain",
}
</script>

<style scoped>


    .descrition {
        padding: 0 2%;
        width: 100%;
    }

    #bloc {
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-between;
        padding: 50px 0px;
    }

    .images {
        width: 100%;
        max-width: 300px;
        background-size: contain;
    }   
    
    .right {
        float: right;
        
        
    }
    
    .main-texts {
        color: #222;
        text-align: justify;
        margin-left: 80px;
    }

    .secondary-texts {
        color: #222;
        text-align: justify;
        margin-right: 80px;
    }
    
    h2 {
        margin-bottom: 35px;
        width: 50%;
        font-size: 28px;
    }

    h3 {
        margin-top: 25px;
        width: 50%;
        font-size: 18px;
        margin-top: 10px;
        color: #444;
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
   width: 130px;
   border:none;  
   font-family: "Avenir", Helvetica, Arial, sans-serif;
   cursor: pointer;
    }


    button:hover{
        background-color: #222;
    }

    hr.solid {
        border-top: 1.5px solid rgb(199, 19, 73);
        margin-top: 20px;
    }

</style>