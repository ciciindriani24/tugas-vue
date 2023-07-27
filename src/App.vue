<template>
  <div>
    <NavbarComponent2></NavbarComponent2>
    <CarouselComponent></CarouselComponent>
    <br>
    <br>
    <font size="10"><b>- Sejarah -</b></font>
    <br>
    <br>
    <CardComponent></CardComponent>
    <br>
    <br>
    <font size="10"><center><b>- Berita -</b></center> </font><br>
    <br>
    <CardComponent2></CardComponent2>
    <br>
    <br>
    <CardComponent3></CardComponent3>
    <footer1></footer1>

  </div>
</template>
<script setup>
import NavbarComponent2 from './components/NavbarComponent2.vue';
import CarouselComponent from './components/CarouselComponent.vue';
import CardComponent from './components/CardComponent.vue'; 
import CardComponent2 from './components/CardComponent2.vue';
import footer1 from './components/footer1.vue';
import CardComponent3 from './components/CardComponent3.vue';

</script>