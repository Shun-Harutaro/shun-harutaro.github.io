<template>
  <div class="home">
    <div class="top">
      <img alt="Vue logo" src="../assets/logo.png" class="logo">
      <h1>Shun_Harutaro</h1>
    </div>
    <About class="inner"/>
    <Skill class="inner"/>
    <Work class="inner"/>
    <Social class="inner"/>
    <hr>
    <small>Copyright &copy; 2020 Shun_Harutaro</small>
  </div>
</template>

<style>
  .top {
  width: 100%;
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  }
  .logo {
    width: 200px;
    border-radius: 50%;
  }
  .inner {
    margin: 50px 0;
  }
</style>
<script>
// @ is an alias to /src
import About from '@/components/About.vue'
import Skill from '@/components/Skill.vue'
import Work from '@/components/Work.vue'
import Social from '@/components/Social.vue'

export default {
  name: 'Home',
  components: {
    About,
    Skill,
    Work,
    Social
  }
}
</script>
