<template>
  <div class="container">
    <div class="content">
      <h6 class="decor">
        &#9472 patisserie &#9472
      </h6>
      &nbsp;
      <h1>Lorem Ipsum</h1>
      <p class="comment">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
      </p>
    </div>
  <ul class="gallery flex-container">
    <li v-for="item in cards"
      class="card">

      <Card :card = item />

    </li>
  </ul>
</div>
</template>
<script setup>
import Card from './Card.vue'
import { dish_1 } from './lib/dish_1.json'

const cards = [
  {
    img: dish_1,
    title: "Pain au Cranberry",
    description: "A delightful spiral pastry filled with light French vanilla cream and studded with seasonal berries.",
    formFactor: 6,
    price: 128   
  },
  {
    img: dish_1,
    title: "Pain au Cranberry",
    description: "A delightful spiral pastry filled with light French vanilla cream and studded with seasonal berries.",
    formFactor: 6,
    price: 128   
  },
  {
    img: dish_1,
    title: "Pain au Cranberry",
    description: "A delightful spiral pastry filled with light French vanilla cream and studded with seasonal berries.",
    formFactor: 6,
    price: 128   
  },
  {
    img: dish_1,
    title: "Pain au Cranberry",
    description: "A delightful spiral pastry filled with light French vanilla cream and studded with seasonal berries.",
    formFactor: 6,
    price: 128   
  },
  {
    img: dish_1,
    title: "Pain au Cranberry",
    description: "A delightful spiral pastry filled with light French vanilla cream and studded with seasonal berries.",
    formFactor: 6,
    price: 128   
  }
]

</script>
<style lang="scss">
.container {
  width: 100%;
  height: 100%;
  text-align: center;

  .content {
    display: inline-block;
    width: 960px;
    height: 100%;
    position: unset;
  }
  .gallery {
    width: 100%;
    height: 687px;
    display: flex;
    flex-direction: row;
    gap: 32px;
    flex-wrap: nowrap;
    justify-content: space-between;
    overflow: hidden;

    .card {
      display: inline-block;
    }
    
  }
}
</style>
