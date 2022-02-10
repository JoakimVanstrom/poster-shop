<template>
  <div class="header-info">
    <img id="navicon" src="../assets/navicon.svg" alt="" />
    <h1>Poster Shop</h1>
    <img id="ninjahead" src="../assets/ninjahead.svg" alt="" />
  </div>
</template>

<script>
export default {};
</script>

<style scoped lang="scss">
.header-info {
  width: 600px;
  height: 300px;
  background-color: lightgreen;
  display: grid;
  grid-template-columns: repeat(1, 1fr);
  grid-template-rows: auto;
  h1 {
    grid-row: 1;
    grid-column: 1;
    justify-self: center;
    align-self: end;
  }

  #ninjahead {
    grid-row: 2;
    width: 10rem;
    place-self: end;
    justify-self: center;
  }
}
#navicon {
  grid-row: 1;
  grid-column: 1;
  width: 1.5rem;
  padding: 1rem 0 0 1rem;
}
</style>
