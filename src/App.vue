<script setup lang="ts">
import { Button } from "@swarmakit/vue";
</script>

<template>
  <div>
    <h1>Code Demo</h1>
    <Button :label="'Click Me!'" @click="handleClick"></Button>
  </div>
</template>

<script lang="ts">
const handleClick = () => {
  alert("Button clicked!");
};
</script>

<!-- the issue seems to be from the package @swarmakit/vue as it is installed correctly -->