<script setup>
  let arr = ['Toy', 'walrus', 'pig', 'dog', 'clubbing', 'wine'];
</script>

<template>
  <ul v-for ="item in arr" :key="item.id" class="pt-8">
    <li class="pl-10">
      {{item}}
    </li>
  </ul>
</template>