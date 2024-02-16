<template>
  <navigation/>
  <div class="container mt-4">
    <div class="row">
      <div class="col-md-8">
        <h2 class="heading">About WestoleCars</h2>
        <p class="para">Welcome to WestoleCars, your trusted destination for buying high-quality, pre-owned vehicles. With years of experience in the automotive industry, we pride ourselves on offering a wide selection of cars at competitive prices. Whether you're in the market for a reliable sedan, a spacious SUV, or a sporty coupe, we have the perfect vehicle to suit your needs and budget.</p>
        <p class="para">At WestoleCars, customer satisfaction is our top priority. Our team of knowledgeable and friendly sales professionals is dedicated to providing exceptional service and assisting you every step of the way, from browsing our inventory to securing financing. We believe in transparency and integrity, and we strive to make your car-buying experience as seamless and stress-free as possible.</p>
        <p class="para">Explore our website to view our current inventory, schedule a test drive, or learn more about our financing options. If you have any questions or would like to speak with a member of our team, don't hesitate to contact us. We look forward to helping you find the perfect car!</p>
      </div>
      <div class="col-md-4">
        <img src="https://via.placeholder.com/300" class="img-fluid" alt="WestoleCars">
      </div>
    </div>
  </div>

  <footer class="footer mt-auto py-3 bg-dark text-white">
    <div class="container text-center">
      <span class="text-muted">Copyright &copy; 2024 WestoleCars. All rights reserved.</span>
    </div>
  </footer>
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
@import url('https://fonts.googleapis.com/css2?family=Merriweather:ital,wght@0,300;0,400;0,700;0,900;1,300;1,400;1,700;1,900&display=swap');
body.about {
  background-image: url('https://cdn-images.imagevenue.com/44/a8/9d/ME17MIIS_o.jpg');
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 100vh;

}

.heading{
  /* color: rgb(220, 35, 97); */
  color: #FF10F0;
  text-shadow:
    0 0 7px #fff,
    0 0 10px #fff,
    0 0 21px #fff,
    0 0 42px rgb(220, 35, 97),
    0 0 82px rgb(220, 35, 97),
    0 0 92px rgb(220, 35, 97),
    0 0 102px rgb(220, 35, 97),
    0 0 151px rgb(177, 37, 182);
  font-weight: bold;
}

.para{
  line-height: 1.5em;
  font-family: "Merriweather", serif;
  font-weight: 400;
  font-style: normal;
}

</style>