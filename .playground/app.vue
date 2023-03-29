<template>
  <div>
    <h1>My app</h1>
    <Button>mi boton</Button>
    {{ mensaje }}
  </div>
</template>
<script setup>
const { mensaje } = useHello();
</script>
