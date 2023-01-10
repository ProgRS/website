<template>
  <header>
    
    <nav>
      <router-link to="/" class="logo">
        <img src="/img/logo-black.svg" alt="Warren" />
      </router-link>
      <router-link to="/" class="menuitem1">Sobre</router-link>
       <div id="div-submenu">
                    <select id="submenu " class="menuitem4">
                        <option hidden selected >Investir</option>
                        <option>Carteiras</option>
                        <option>Bolsa</option>
                        <option>Home Broker</option>
                    </select>
                </div>
      <router-link class="menuitem2" to="/">Aprender</router-link>
      <router-link class="menuitem3" to="/">Magazine</router-link>
      <router-link class="btn" to="/login">Login</router-link>
    </nav>
    
  </header>
</template>

<script>
export default {
  name: "TheHeader",
};
</script>

<style scoped>

.menuitem1 {
    color: black;
    text-decoration: none;
    text-transform: uppercase;
    font-weight: bold;
}
.menuitem2 {
    color: black;
    text-decoration: none;
    text-transform: uppercase;
    font-weight: bold;
}

.menuitem3 {
    color: black;
    text-decoration: none;
    text-transform: uppercase;
    font-weight: bold;
}
.menuitem4 {
    color: black;
    text-decoration: none;
    text-transform: uppercase;
    font-weight: bold;
}
nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 15px 20px;
  margin: 5px;
  margin-left: 100px;
  box-shadow: 0 2px 4px rgba(30, 60, 90, 0.1);
}

.logo {
  padding: 12px 2px;
}

.logo img {
  width: 100px;
}

select {
    border: none;
    cursor: pointer;
    font-size: 15px;
    padding: 5px;
    width: 130px;    
    background: transparent;
    
  }

  select:hover {
    color: rgb(199, 19, 73);
  }
</style>
