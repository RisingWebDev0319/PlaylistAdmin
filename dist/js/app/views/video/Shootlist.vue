<template lang="html">
  <main class="video-education">
    <simple-header inverse></simple-header>
    <div class="video-education-frame">
      <iframe src="https://www.youtube.com/embed/bLHMSHNBF9g" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <p class="video-education-text">
      <span class="fugaz">Shootlist</span>  נולדה ממציאות מאתגרת: בעידן השקיעה במסכים מתרופף מאוד החיבור המשפחתי והחברתי, והמסכים הקרים דוחקים את היחד המשפחתי החם.
      <br> <br>
      כמענה לזה מציעה <span class="fugaz">Shootlist</span> רשימת שאלות לשיחה זורמת ותוססת
    </p>
    <div class="video-education-spacer"></div>
    <div class="video-education-button">
      <button @click="$router.push('/shootlist-options')" class="theme-button-outline">התחל</button>
    </div>
  </main>
</template>

<script>
import SimpleHeader from './../../components/SimpleHeader.vue';
export default {
  components: {
    SimpleHeader,
  }
}
</script>

<style lang="scss" scoped>

@import '~@/vars.scss';

main {

}

</style>
