<template>
  <header>
    <div class="container d-flex align-items-center justify-content-between">
      <input type="checkbox" id="menu-toggle" />
      <label for="menu-toggle" class="hamburger">
        <img src="../assets/image/hamburger@2x.png" alt="" />
      </label>
      <div class="nav-bar">
        <ul class="nav">
          <li> <p>
          <router-link to="/aboutus">關於我們</router-link>
        </p></li>
          <li><p>
          <router-link to="/productlist">產品列表</router-link>
        </p></li>
          <li><p>
          <router-link to="/talktous">聯絡我們</router-link>
        </p></li>
        </ul>
      </div>

      <div class="logo">
    <router-link to="/aboutus">
        <img src="../assets/image/glintlogo.png" alt="brand logo" /></router-link>
      </div>
      <div class="icon-link d-flex">
        <router-link to="/shoppinghome">
          <img src="../assets/image/cart@2x.png" alt="" class="shopping-cart"
        /></router-link>
        <router-link to="/signin">
        <button
        type="button"
        class="btn btn-sm btn-outline-success my-2 my-sm-0"
      >
        登入
      </button>
      </router-link>
      </div>
    </div>
  </header>
</template>
<style scoped>
.logo {
  width: 48px;
  height: 48px;
}

</style>
