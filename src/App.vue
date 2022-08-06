<template>
  <NavBar/>
  <FirstIntro/>
</template>

<script>
import NavBar from './components/NavBar.vue'
import FirstIntro from './components/FirstIntro.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    FirstIntro,
}
}
</script>

<style>
#app {
  /* font-family: 'Dancing Script', cursive;
  font-family: 'Permanent Marker', cursive; */
  font-family: 'Poppins', sans-serif;
  /* font-family: 'Satisfy', cursive; */
  background-color: #212121;
  min-height: 100vh;
  color: white;
}
.mainBackground{
  color: #212121;
}
.textBackground{
  color:#212121
}
.onContainBackground{
  color:#8B432D
}
.projectBackGround{
  color: #FF764D
}
</style>
