<template>
  <div>
    <header>
      <span class="logo">ベストサロン</span>
    </header>
    <TopImage />
    <Support />
    <JobExample />
    <PrivateJob />
    <About />
  </div>
  <footer>
    <span class="logo">ベストサロン</span>
  </footer>
</template>

<script>
import TopImage from './parts/top/TopImage.vue'
import Support from './parts/top/Support.vue'
import JobExample from './parts/top/JobExample.vue'
import PrivateJob from './parts/top/PrivateJob.vue'
import About from './parts/top/About.vue'

export default {
  name: 'Top',
  components: {
    TopImage,
    Support,
    JobExample,
    PrivateJob,
    About
  }
}
</script>
]
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header {
  height: 30px;
  padding: 10px 8%;
  line-height: 40px;
}
.logo {
  font-weight: bold;
  font-size: 25px;
  color: #96c3ec;
}
footer {
  margin-top: 50px;
  height: 150px;
  padding: 10px 8%;
  line-height: 150px;
  text-align: center;
  background-color: #DDD;
}
@media screen and (max-width: 480px) {
  footer {
    margin-top: 25px;
  }
}
</style>
