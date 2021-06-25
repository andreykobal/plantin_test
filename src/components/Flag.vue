<template>
  <div class="font-bold">New</div>
</template>

<script>

</script>

<style scoped>
div {
  max-width: 70px;
  background-color: #ff69b4;
  margin-right: 50px;
  position: relative;

  /* styles for demo */
  padding: 20px;
  color: #fff;
}

/* pseudoelement to simulate triangles */
div:before,
div:after {
  content: "";
  position: absolute;
  top: 0;
  left: 100%;
  width: 50px;
  height: 50%;
  background-image: linear-gradient(to left top, transparent 50%, #ff69b4 50%);
}

/* Flip triangle */
div:after {
  top: 50%;
  transform: scaleY(-1);
}
</style>