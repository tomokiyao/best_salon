<template>
  <div class="content">
    <div class="job-example">
      <h2>美容師の求人例</h2>
      <div class="example-content">
        <div class="example-title">美容師求人例（東京都/正社員）</div>
        <h3 class="catchphrase">最高月収45万円！</h3>
        <div class="job">
          月給<span class="salary">28</span>万円〜
        </div>
      </div>
      <div class="example-content">
        <div class="example-title">美容師求人例（東京都/業務委託）</div>
        <h3 class="catchphrase">集客好調！即日勤務可♪</h3>
        <div class="job">
          歩合<span class="salary">70</span>％以上
        </div>
      </div>
      <div class="example-content">
        <div class="example-title">美容師求人例（神奈川県/正社員）</div>
        <h3 class="catchphrase">完全週休2日制の落ち着いたサロン</h3>
        <div class="job">
          月給<span class="salary">26</span>万円〜
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'JobExample'
}
</script>

<style scoped>
h2 {
  font-size: 30px;
}
.content {
  padding: 10px 8%;
}
.job-example {
  text-align: center;
  border: 2px solid #9EADBA;
  margin-top: 40px;
}
.example-content {
  height: 500px;
  border: 1px solid #9EADBA;
  margin: 50px auto;
  width: 70%;
}
.example-title {
  height: 70px;
  line-height: 70px;
  font-weight: bold;
  font-size: 25px;
  background-color: #96c3ec;
  border-bottom: 1px solid #9EADBA;
}
.catchphrase {
  margin-top: 60px;
  font-weight: bold;
  font-size: 35px;
}
.job {
  margin-top: 100px;
  font-size: 30px;
  font-weight: bold;
}
.salary {
  font-size: 90px;
  padding: 30px;
}
@media screen and (max-width: 480px) {
  h2 {
    font-size: 18px;
  }
  .content {
    padding: 10px 1%;
  }
  .job-example {
    margin-top: 10px;
  }
  .example-content {
    height: 300px;
    margin: 20px auto;
    width: 90%;
  }
  .example-title {
    height: 50px;
    line-height: 50px;
    font-size: 16px;
  }
  .catchphrase {
    margin-top: 35px;
    font-weight: bold;
    font-size: 20px;
  }
  .job {
    margin-top: 50px;
    font-size: 20px;
    font-weight: bold;
  }
  .salary {
    font-size: 50px;
    padding: 20px;
  }
}
</style>
