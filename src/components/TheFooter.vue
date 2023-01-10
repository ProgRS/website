<template>
    <footer>
        <div class="w33">
            <ul>
                <h2>Sobre</h2>
                <li >Sobre a Warren</li>
                <li >Quanto custa</li>
                <li >Warren Edu</li>                
            </ul>
        </div>
         <div class="w33">
            <ul>
                <h2>Produtos</h2>
                <li >Bolsa</li>
                <li >Carteiras</li>
                <li >Home Broker</li>                 
            </ul>
        </div>
        
        <div class="w33">
            <ul>
                <h2>Escritórios</h2>
                <li >Blumenau</li>
                <li >Curitiba</li>
                <li >Florianópolis</li> 
                
                
            </ul>
        </div>
        <div class="w33">
            <ul>
                <h2>Fale Conosco</h2>  
                <li >Dúvidas</li>
                <li >Precisa de ajuda?</li>
                <li >Acesse o WhatsApp</li>               
            </ul>
        </div>
    </footer>
</template>

<script>
export default {
    name: "TheFooter"
};
</script>

<style>

footer {
    background: rgb(188, 187, 197);  
    padding: 25px 0;  
    text-align: center;
    font-size: 1.2rem;
    color: #fff;
    display: flex;
    position: relative;
    top:75px

}

.nav.desktop {
    
    max-width: 960px;
    margin: 0 auto;
    padding: 15px 0;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
}

.nav.desktop ul {
    padding:0  35px;
    list-style-type: none;
    font-weight: 300;
    font-size: 15px;
    text-transform: uppercase;
    display: inline-block;
}

.nav.desktop li {
       font-size: 15px;
       padding: 0 30px;
       text-transform: uppercase;
       display: inline-block; 
}

ul {
    list-style-type: none;
}

h2{
    text-transform: uppercase;
}
h3 {
    
    margin-top: 20px;
    }

.right{
    float: right;
}
.left{
    float: left;
}
.w33{
    width: 44.4%;
}


</style>
