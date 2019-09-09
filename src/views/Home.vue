<template>
  <span>
    <home-intro></home-intro>
    <home-summary id="summary"></home-summary>
    <home-owner id="experience"></home-owner>
    <home-footer></home-footer>
  </span>
</template>

<script>
  import HomeIntro from '@/components/HomeIntro.vue';
  import HomeSummary from '@/components/HomeSummary.vue';
  import HomeOwner from '@/components/HomeOwner.vue';
  import HomeFooter from '@/components/HomeFooter.vue';

  export default {
    components: {
      HomeIntro,
      HomeSummary,
      HomeOwner,
      HomeFooter
    }
  }
</script>
