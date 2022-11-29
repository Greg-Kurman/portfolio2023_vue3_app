<template>
  <div class="main">
    <div class="header">
      <div class="logo">
        <img src="../assets/logo.png" alt="">
      </div>
      <nav class="head_nav">
        <div class="icons"><img src="../assets/git.png" alt=""> <img src="../assets/vk.png" alt=""></div>
        <div class="btn"><img src="../assets/btn.png" alt="">
          <p>button</p> <img class="btn_el1" src="../assets/btn_el1.png" alt=""> <img class="btn_el2"
            src="../assets/btn_el1.png" alt="">
        </div>
      </nav>
    </div>
    <div class="main_body">
      <div class="body_nav">
        <nav class="nav_text">
          <a href="">Home</a> <img src="../assets/star.png" alt=""> <a href="">Factions</a><img src="../assets/star.png"
            alt=""> <a href="">Roadmap</a>
        </nav>
        <div >
          <h1 class="main_text">FROM DUSK TO DOWN </h1>
          <div class="btn"><img  src="../assets/btn.png" alt="">
          <p>button</p> <img class="btn_el1" src="../assets/btn_el1.png" alt=""> <img class="btn_el2"
            src="../assets/btn_el1.png" alt="">
        </div> 
        </div>
         
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutMe',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style >
a {
  text-decoration: none;
  color: rgb(255, 255, 255);
}

a:hover{
  border-radius: 5%;
  background-color: rgba(194, 117, 218, 0.5)
  
}

.head_nav{
  cursor: pointer;
}

.body_nav {
  display: flex;
  justify-content: space-between;
  text-decoration: none;
  color: white;
  font-size: 20px;
  font-family: 'Orbitron', sans-serif;
  font-style: normal;
}

.nav_text {
  writing-mode: vertical-rl;
  display: flex;
  justify-content: space-around;
  margin: 0 0 0 50px;
  height: 500px;
}

.btn {
  cursor: pointer;
  position: relative;
  width: 190px;
  height: 50px;
}

.btn:hover {
  transform: rotate(1deg);
  background-color: rgba(194, 117, 218, 0.5)
}

.btn p {
  color: white;
  font-size: 20px;
  font-family: 'Orbitron', sans-serif;
  font-style: normal;
  position: absolute;
  top: 15px;
  left: 50px;
}

.btn_el1 {
  position: absolute;
  top: 12px;
  left: 7px;
}

.btn_el2 {
  position: absolute;
  right: 7px;
  bottom: 0px;
  transition: all;
  transform: rotate(180deg);
}

.icons {
  display: flex;
  width: 50px;
  height: 50px;

}

.icons img {
  margin-right: 15px;
}

.head_nav {
  min-width: 20%;
  display: flex;
  justify-content: space-between;
  max-height: 100px;
  margin: 35px 50px 0 0;
}

.header {
  display: flex;
  justify-content: space-between;
}

.main_text {
  margin: 250px auto 0px;
  color: white;
  font-family: 'Orbitron', sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 40px;
  letter-spacing: 0.365em;
}

.main {
  min-height: 98vh;
  background: url(../assets/bg_1.jpg) no-repeat;
  background-size: 100%;
}
</style>
