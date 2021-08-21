<template>
  <div>
   

    <h1 v-text="titulo"></h1>

    <h2>Juegos de PC y consolas</h2>

    
   
  </div>
</template>
<script>
// import { mapState } from "vuex";

export default {
    computed: {
    titulo() {
      return "32bits";
    },
}
};
</script>
