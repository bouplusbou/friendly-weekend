<template>
  <div>
    <h1>home</h1>
    <div class="gallery">
      <img src="../assets/image2.jpg" class="tile" id="image2" />
      <img src="../assets/image3.jpg" class="tile" id="image3" />
      <img src="../assets/image4.jpg" class="tile" id="image4" />
      <img src="../assets/image5.jpg" class="tile" id="image5" />
      <img src="../assets/image6.jpg" class="tile" id="image6" />
      <img src="../assets/image7.jpg" class="tile" id="image7" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.gallery {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: 300px 300px 300px;
  grid-gap: 5px;
}
.tile {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
#image2 {
  grid-column-start: 1;
  grid-column-end: 3;
}
</style>