<template>
  <div id="app">
    <nav-bar></nav-bar>
    <base-hero></base-hero>
    <div class="virtues">
      <base-virtue>
        <template #image>image</template>
        <template #title>Title</template>
        <template #description>description</template>
      </base-virtue>
    </div>
  </div>
</template>

<style lang="scss">

</style>
<script>
  import NavBar from "./components/NavBar";
  import BaseHero from "./components/BaseHero";
  import BaseVirtue from "./components/BaseVirtue";
  export default {
    components: {BaseVirtue, BaseHero, NavBar}
  }
</script>

<style>
  body, html{
    margin: 0px;
    padding: 0px;
  }
</style>

<style lang="scss" scoped>
  .virtues{
display:flex;
  }
</style>


@font-face{

font-family: 'Open Sans - Semibold';

src: url(../../fonts/open-sans-semibold.ttf);

src: url(../../fonts/open-sans-semibold.ttf) format('ttf')

font-weight: normal;

font-style: normal;
}