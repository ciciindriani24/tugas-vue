<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': 'https://persib.co.id/img/Default_Image.5df4475f.jpg',
    'alt': 'Picture 1',
  },
  {
    'src': 'https://asset-2.tstatic.net/makassar/foto/bank/images/skuad-persib-bandung.jpg',
    'alt': 'Picture 2',
  },
  
]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>
