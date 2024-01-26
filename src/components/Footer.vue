<template>
  <footer>
    <p>Make Your Burguer &copy; {{ year }}</p>
  </footer>
</template>

<script>
let date = new Date();

export default {
  name: "Footer",
  data() {
    return {
       year: date.getFullYear()
    };
  },
};
</script>

<style scoped>
footer {
  height: 200px;
  background-color: #333;
  border-top: 4px solid #111;
  color: #fcba03;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
}
</style>