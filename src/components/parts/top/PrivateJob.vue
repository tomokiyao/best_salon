<template>
  <div class="content">
    <div class="private-job">
      <h2>美容師の非公開求人とは</h2>
      <div class="private-job-content">
        ベストサロンには『求人サイトで失敗した経験があり掲載していない』
        『求人を掲載したいが手が回っていない』『ギリギリ足りてはいるが、良い人がいれば採用したい』
        などの理由により一般の求人サイトには公開されていない美容師（スタイリスト・アシスタント等）の
        採用依頼があります。<br />
        <br />
        ベストサロンでは、こうした求人を『非公開求人』と呼び、転職相談サービスを利用いただいている
        皆様にご紹介しています。
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'PrivateJob'
}
</script>

<style scoped>
h2 {
  font-size: 30px;
}
.content {
  padding: 10px 8%;
}
.private-job {
  text-align: center;
  border: 2px solid #9EADBA;
  margin-top: 40px;
}
.private-job-content {
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
  .private-job {
    margin-top: 10px;
  }
  .private-job-content {
    margin: 30px auto;
    line-height: 38px;
    font-size: 15px;
    width: 80%;
  }
}
</style>
