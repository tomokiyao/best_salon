<template>
  <div class="image-content">
    <h1 class="sub-title">
      美容師・美容室の求人・転職・募集情報なら
    </h1>
    <br />
    <h1 class="title">
      ベストサロン
    </h1>
  </div>
</template>

<script>
export default {
  name: 'TopImage'
}
</script>

<style scoped>
.image-content {
  height: 450px;
  background-image: url("../../../assets/top-image.jpg");
  background-size: cover;
  padding: 10px 8%;
}
.sub-title {
  margin-top: 120px;
  font-size: 40px;
  color: #96c3ec;
}
.title {
  font-size: 50px;
  font-weight: bold;
  color: #96c3ec;
}
@media screen and (max-width: 480px) {
  .image-content {
    height: 250px;
    padding: 10px 8%;
  }
  .sub-title {
    margin-top: 60px;
    font-size: 15px;
  }
  .title {
    margin-top: 10px;
    font-size: 30px;
    font-weight: bold;
  }
}
</style>
