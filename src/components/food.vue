<template>
  <div>
    <ul>
      <li v-for="item in food">
        {{ item }}
      </li>
    </ul>
  </div>
</template>

<script setup lang="ts">
const food:Array<string> = ["Pizza", "French fries", "Spaghetti"];
</script>
