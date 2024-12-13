<script setup lang="ts">
// Attempted import from the SwarmaKit Vue library
// import { Button } from "@swarmakit/vue";
</script>

<template>
  <div>
    <h1>Code Demo</h1>
    <!-- <Button :label="'Click Me!'" @click="handleClick"></Button> -->
     <button @click="handleClick">Click Me</button>
  </div>
</template>

<script lang="ts">
const handleClick = () => {
  alert("Button clicked!");
};
</script>

<!-- the issue seems to be from the package @swarmakit/vue as it is installed correctly -->