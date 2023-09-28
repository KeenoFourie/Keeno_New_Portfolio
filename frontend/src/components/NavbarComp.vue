<template>
  <div>
    <!-- navbar -->
    <nav class="navbar navbar-expand-lg bg-transparent">
  <div class="container-fluid" id="navbar_links_and_image">
    <div>
      <a class="navbar-brand" href="#">
        <img id="logo_image" src="https://i.postimg.cc/15nNCHtn/Untitled-design-removebg-preview.png" alt="logo-of-keeno-fourie-with-laptop">Keeno Fourie
    </a>
    </div>
    <div>
    <div id="navbarSupportedContent">

        <div class="nav-item dropdown">
          <a class="nav-link" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">Menu</a>
          <ul class="dropdown-menu">
            <li class="nav-item">
              <a class="dropdown-item" href="#Home">Home</a>
            </li>
            <li class="nav-item">
              <a class="dropdown-item" href="#About">About</a>
            </li>
            <li class="nav-item">
              <a class="dropdown-item" href="#Resume">Resume</a>
            </li>
            <li class="nav-item">
              <a class="dropdown-item" href="#Projects">Projects</a>
            </li>
            <li class="nav-item">
              <a class="dropdown-item" href="#Testimonials">Testimonials</a>
            </li>
            <li class="nav-item">
              <a class="dropdown-item" href="#Contact">Contact</a>
            </li>
          </ul>
        </div>
    </div>

      
    </div>
  </div>
</nav>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
nav {
  position: fixed;
  width: 100%;
}
#logo_image {
  height: 5rem;
}
#navbar_links_and_image {
  width: 80%;
  display: flex;
  justify-content: space-between;
}
.navbar-brand {
  display: flex;
  align-items: center;
}
.dropdown-item {
  opacity: 70%;
}
.dropdown-item:hover {
  opacity: 100%;
  background-color: white;
  color: black;
  font-weight: bold;
}
.nav-link {
  color: black;
  border: 1.8px solid black;
  border-radius: 0.4rem;
  padding: 0.2rem;
  padding-inline: 1rem;
}
.nav-link:hover {
  color: white;
  background-color: black;
}
.dropdown-menu {
  border: 1.8px solid black;
}
</style>