<template>
  <div class="content">
    <div class="support">
      <h2>ベストサロンの転職サポート</h2>
      <div class="support-content">
        <div class="support-category">1、ご登録・問い合わせ</div>
        <div class="support-text">
          まずはお気軽にご登録ください。<br/>
          365日24時間、いつでもスマホから<br/>
          1分で登録完了できます！
        </div>
      </div>
      <div class="support-content">
        <div class="support-category">2、ヒアリング・ご相談</div>
        <div class="support-text">
          専任のアドバイザーとお電話で希望条件、<br/>
          募集状況などをお話します。気になること、<br/>
          施設には言いにくいことなんでもご相談ください。<br/>
        </div>
      </div>
      <div class="support-content">
        <div class="support-category">3、面接・サロン見学</div>
        <div class="support-text">
          給与、お休み、通勤時間などのご希望似合った<br/>
          職場をご紹介します。サロン見学や面接日程も求職者<br/>
          様がお電話いただくことなく調整いたします。<br/>
        </div>
      </div>
      <div class="support-content">
        <div class="support-category">4、ご内定・転職決定</div>
        <div class="support-text">
          おめでとうございます！現職での引継ぎや円満な<br/>
          ご退職のアドバイスから、新しい職場でのお悩み相談<br/>
          などもお任せください。<br/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Support'
}
</script>

<style scoped>
h2 {
  font-size: 30px;
}
.content {
  padding: 10px 8%;
}
.support {
  text-align: center;
  border: 2px solid #9EADBA;
  margin-top: 20px;
}
.support-content {
  height: 250px;
  padding: 70px 8%;
  border: 1px solid #9EADBA;
  margin: 50px;
}
.support-category {
  font-size: 25px;
  font-weight: bold;
}
.support-text {
  margin-top: 40px;
  line-height: 50px;
  font-size: 20px;
  font-weight: bold;
}
@media screen and (max-width: 480px) {
  h2 {
    font-size: 18px;
  }
  .support {
    margin-top: 10px;
  }
  .content {
    padding: 10px 1%;
  }
  .support-content {
    height: 130px;
    padding: 20px 8%;
    margin: 20px;
  }
  .support-category {
    font-size: 13px;
    font-weight: bold;
  }
  .support-text {
    margin-top: 20px;
    line-height: 25px;
    font-size: 10px;
    font-weight: bold;
  }
}
</style>
