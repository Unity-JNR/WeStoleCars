<template>
  <navigation/>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<script>
import navigation from '@/components/navigation.vue'

export default {
  name:'AboutView',
  components :{
navigation
  }
}

</script>


<style>
body.about {
  background-image: url('https://i.imgur.com/i74n3G3.jpg');
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 100vh;

}

</style>