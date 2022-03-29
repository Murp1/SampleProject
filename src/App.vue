<template>
  <div class="head">
    <div class="left">
  <p>SAMPLE</p>
    </div>
    <div class="right">
        <ul>
          <li> Home </li>  
          <li>About Us</li>
          <li>Services<i class="fas fa-plus"></i></li>
          <li>Contact Us</li>
        </ul>
    </div>
  </div>
  <HelloWorld/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>

i.fas.fa-plus {
    font-size: 13px;
    margin-left: 5px;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
  background: #fff;
  font-family: poppins
}


.head {
    display: grid;
    grid-template-columns: 50% 50%;
    max-width: 1140px;
    margin: auto;
}

.head .left p {
    font-weight: 700;
    font-size: 35px;
    font-family: poppins;
    text-align: left;
}

.head .right {
    display: flex;
    justify-content: end;
    align-items: center;
}

.head .right ul {
  display: flex;
}

.head .right li {
    list-style: none;
    padding: 0 25px;
}

</style>
