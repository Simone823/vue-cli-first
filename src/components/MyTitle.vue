<template>
<div class="title">
    <h1>{{title}}</h1>
</div>
</template>

<script>
export default {
  data() {
    return {
      title: "La mia prima app con Vue CLI!"
    }
  }
}
</script>

<!-- style scoped (valido solo per questo componente)-->
<style scoped lang="scss">
.title h1{
    color: red;
    text-shadow: 0 0 10px black;
}
</style>
