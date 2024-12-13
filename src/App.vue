<script setup lang="ts">
// Attempted import from the SwarmaKit Vue library
// import { Button } from "@swarmakit/vue";
</script>

<template>
  <div>
    <h1>Code Demo</h1>
    <!-- <Button :label="'Click Me!'" @click="handleClick"></Button> -->
     <!-- Used a normal button instead -->
     <button @click="handleClick">Click Me</button>
  </div>
</template>

<script lang="ts">
const handleClick = () => {
  alert("Button clicked!");
};
</script>

<!-- the issue seems to be from the package @swarmakit/vue. Likely related package's `package.json` or export configuration -->