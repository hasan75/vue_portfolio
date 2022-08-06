<template>
  <nav class="navbar navbar-expand-lg navBarColor">
  <div class="container">
    <a class="navbar-brand navbarTextColor navbarTextFirst" href="#">Hasan Ahmed</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <a class="nav-link navigations" aria-current="page" href="#">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link navigations" href="#">Skills</a>
        </li>
        <li class="nav-item">
          <a class="nav-link navigations" href="#">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link navigations" href="#">Project</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbarTextFirst{
  font-family: 'Dancing Script', cursive;
  font-weight: 900;
  font-size: 2.5rem;
}
.navbarTextColor{
  color: #FF764D;
}
.navigations{
  border: 2px solid #FF764D;
  color: white;
  border-radius: 20px;
  margin: 0px 10px;
  padding: 5px 20px !important;
}
.navigations:hover{
  border: 2px solid #FF764D;
  color: white;
  border-radius: 20px;
  margin: 0px 10px;
  padding: 5px 20px !important;
  background-color: #FF764D;
}

@media only screen and (max-width: 600px){
    .navBarColor{
      background-color: #F56539;
    }

    .navbarTextFirst{
      font-family: 'Dancing Script', cursive;
      font-weight: 900;
      font-size: 2.5rem;
    }
    .navbarTextColor{
      color: #212121;;
    }
    .navigations{
      border: 2px solid #333131;
      color: white;
      border-radius: 20px;
      padding: 5px 20px !important;
      margin: 5px 10px;
      text-align: center;
    } 
    .navigations:hover{
      border: 2px solid #333131;
      color: white;
      border-radius: 20px;
     margin: 5px 10px;
      padding: 5px 20px !important;
      background-color: #FF764D;
      text-align: center;
    }
}
</style>
