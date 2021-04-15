<template>
<div>
    <header>
         <div class="container">
            <div class="row top">
            <div class="left">
               <span class="logo"><a href="#"><img src="/images/logo.svg" alt="Atomars"></a></span>
               <span class="line"></span>
               <span class="icon-app">
                  <a href="#">
                     <img src="/images/app_icon.png" alt="App">
                  </a>
               </span>
            </div>
        
            <div class="right">
               
               <div class="buttons">
                  <button class="btn btn1">Login</button>
                  <button class="btn btn2 active">Register</button>
               </div>
               <div class="burger">
                  <img src="/images/burger-menu.png" alt="burger">
               </div>
            </div>  
            
            </div>
           
           
               
               <nav class=header-menu>
                  <ul>
                     <li><a href=""><span class="wallet"><img src="/images/wallet.svg" alt="overview"></span> Overview</a></li>
                     <li><a href="">Fiat and Spot</a></li>
                     <li><a href="">Margin</a></li>
                     <li><a href="">Futures</a></li>
                     <li><a href="">P2P</a></li>
                     <li><a href="">Earn</a></li>
                     <li><a href="">Settings</a></li>
                  </ul>
               </nav>
            
            
         </div>
         
      </header>
</div>
  
</template>

<script>
export default {

}
</script>

<style>
header {
  background: #243040;
}

.container {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.row.top {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}

.left {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}

.logo {
  width: 150px;
  height: 50px;
  margin-right: 10px;
}

.line {
  display: block;
  width: 1px;
  height: 25px;
  background-color: white;
  margin-right: 25px;
}

.icon-app {
  width: 25px;
  height: 25px;
}

.icon-app img {
  width: 100%;
  font-size: 0;
}

.right {
  display: flex;
  flex-direction: row;
}

.buttons {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-right: 10px;
  cursor: pointer;
}

.btn {
  width: 80px;
  height: 30px;
  background-color: transparent;
  font-size: 14px;
  color: #f8f8f8;
  border: none;
  border-radius: 5px;
  border: 1px solid rgba(0, 87, 255, 1);
  cursor: pointer;
}

.btn:hover {
  background-color: rgba(0, 87, 255, 1);
  border: 1px solid transparent;
  transition: all 0.3s ease;
}

.btn.active {
  background-color: rgba(0, 87, 255, 1);
  border: 1px solid transparent;
}

.btn2 {
  margin-left: 20px;
}

.burger {
  width: 30px;
  height: 30px;
  margin: 0 10px;
  }

.burger img {
  display: block;
  width: 100%;
}

.overview {
  
}

.header-menu {
  border-top: 0.2px solid rgba(146, 154, 165, 0.8);
}

ul {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 20px;
}

li {
  list-style-type: none;
  
}

a {
  text-decoration: none;
  margin-right: 5px;
  font-size: 12px;
  color: #929aa5;
}

a:hover {
  color: #f8f8f8;
}
</style>
