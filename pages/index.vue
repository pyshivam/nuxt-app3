<template>
  <hero> </hero>
  <about></about>
  <notion-certified></notion-certified>
  <what-we-do></what-we-do>
</template>

<script>
import About from "~~/components/home/about.vue";
import hero from "~~/components/home/hero.vue";
import NotionCertified from "~~/components/home/notion-certified.vue";
import WhatWeDo from "~~/components/home/what-we-do.vue";
export default { components: { hero, About, NotionCertified, WhatWeDo } };
</script>
