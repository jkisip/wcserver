<template>
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <!--<a class="navbar-brand" href="#">ABC NEWS</a>-->
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link">
        <router-link to="/">
         Home
        </router-link>
        </a>
      </li>
      <li class="nav-item active">
        <a class="nav-link">
        <router-link to="/Members">
         Members
        </router-link>
          </a>
      </li>
      <li class="nav-item active">
        <a class="nav-link">
        <router-link to="/News">
         News
        </router-link>
          </a>
      </li>
    </ul>
    <form class="search">
      <input class="aaa" type="text" placeholder="Search" aria-label="Search">
      <button class="aaa" type="submit">Search</button>
    </form>
  </div>
</nav>
</template>
<style>
.nav-link{
  float:left;
  margin-left: 390px;
  font-size: 30px;
}
.router-link{
  color: #35530a;
}
.aaa{
  background-color:lightgray;
}
</style>
