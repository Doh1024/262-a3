<script setup>
  defineProps({
    title:{
      type: String,
      default: "Hello World!",
    },
    info:{
      type: String,
      default: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis praesentium, numquam magnam eos qui minima. Delectus omnis accusamus nam consequuntur!"
    }
  });
</script>

<template>
  <header class="text-center border-y-2 border-black">
    <h1 class="pl-12 py-10 text-4xl font-bold lg:text-5xl"> {{title}}</h1>
    <p class="text-lg pb-3 lg:text-xl"> {{info}} </p>
    <slot name="button"></slot>
  </header>
</template>