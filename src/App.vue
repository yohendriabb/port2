<template>
  <div id="main-container">
    <header>
      <nav>
        <ul class="fixed">
          <router-link class="none link" to="/"><img class="logo" src="/img/logo1.png" alt=""></router-link>
          <router-link class="none" to="/about"><li><a  class="link"><strong>Acerca de</strong></a></li></router-link>
          <router-link class="none link" to="/contact"><li><a  class="link"><strong>Contact</strong></a></li></router-link>
        </ul>
        <ul class="hide">
         <li><a href="#" class="link">Search</a></li>
         <li><a href="#" class="link">Cart</a></li>
         <li><a href="#" class="link">Sing In</a></li>
       </ul>
     </nav>
   </header>

 </div>
 <router-view/>

 <footer>

  <div class="footer">
    <div class="copyright">
      <h5 class="copy-text">&copy; 2022  | Yohendri Becerra</h5>
    </div>
  </div>
</footer>


</template>

<style>
.logo {
  margin-left: 4px;
  width: 80px;
  height: 60px;
}
</style>
