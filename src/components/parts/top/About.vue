<template>
  <div class="content">
    <div class="about">
      <h2>ベストサロンとは</h2>
      <div class="about-content">
        ベストサロンは美容師一人ひとり希望条件や状況、キャリアプランに合わせて『あなたにとってベストな職場（サロン）』
        を検索、またはご紹介する、美容業界専門の求人、転職支援サービスです。<br />
        <br />
        ご希望やご状況を細くお伺いし、一人ひとりにあったサロンのご提案を大切にしています。<br />
        まずは、あなたのお話をお聞かせください。精一杯、お手伝いさせて頂きます。
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutJob'
}
</script>

<style scoped>
h2 {
  font-size: 30px;
}
.content {
  padding: 10px 8%;
}
.about {
  text-align: center;
  border: 2px solid #9EADBA;
  margin-top: 40px;
}
.about-content {
  text-align: left;
  margin: 50px auto;
  line-height: 50px;
  font-size: 22px;
  width: 80%;
  font-weight: bold;
}
@media screen and (max-width: 480px) {
  h2 {
    font-size: 18px;
  }
  .content {
    padding: 10px 1%;
  }
  .about {
    margin-top: 10px;
  }
  .about-content {
    margin: 30px auto;
    line-height: 38px;
    font-size: 15px;
    width: 80%;
  }
}
</style>
