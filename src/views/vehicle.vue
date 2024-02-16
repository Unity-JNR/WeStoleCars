<template lang="">
    <navigation/>

    <div>
        <video autoplay muted loop id="background-video">
    <source src="../assets/car_-_88481 (Original).mp4" type="video/mp4">
  
  </video>
    </div>

    <div class="header">
        <h1 class="brand">Supercars </h1>
        <div class="buttons">
            <button class="know-us">Know Us</button>
            <button class="our-vehicle">Our Vehicle</button>
        </div>
    </div>
    <div class="lets-go-popup" id="letsGoPopup">
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit..</p>
    </div>
    
       
    
</template>
<script>
import navigation from '@/components/navigation.vue'

export default {
  name:'vehicle',
  components :{
navigation
  }
}
</script>
<style>
body{
    background-color: black;
}
#background-video {
  position: fixed;
  right: 0;
  bottom: 0;
  min-width: 100%;
  min-height: 100%;
  width: auto;
  height: 500px;
  z-index: -1;
} 

/* Home screen btns */
.header {
    background-color: transparent;
    color: white;
    padding: 20px;
    text-align: center;
    position: relative;
    margin-top: 150px;
}

.brand {
    margin: 0;
}

.buttons {
    margin-top: 20px;
}

.know-us {
    padding: 10px 20px;
    margin: 0 10px;
    font-size: 16px;
    background-color: magenta;
    color: white;
    border: none;
    cursor: pointer;
    transition: transform 0.3s;
}

 .know-us:hover {
    transform: skewX(20deg);
   
}


.know-us::before {
    transform: skewX(-20deg);
    content: 'know us';
    display: none;
}

.our-vehicle{
    padding: 10px 20px;
    margin: 0 10px;
    font-size: 16px;
    background-color: magenta;
    color: white;
    border: none;
    cursor: pointer;
    transition: transform 0.3s;
}


.our-vehicle:hover {
    transform: skewX(-20deg);
   
}

.our-vehicle::before {
    transform: skewX(-20deg);
    content: 'know us';
    display: none;
}






</style>