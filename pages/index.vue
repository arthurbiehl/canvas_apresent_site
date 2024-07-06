<template>
  <main>
    
    <Component_header></Component_header>

    <ComponentCover></ComponentCover>

    <ComponentAbout></ComponentAbout>

    <ComponentItem></ComponentItem>

    <ComponentFooter></ComponentFooter>

    
    
  </main>
  
</template>

<script setup>

  useHead({
    title: 'Minecraft Wike - Items'
  });

</script>

<style scoped>

  main {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

</style>