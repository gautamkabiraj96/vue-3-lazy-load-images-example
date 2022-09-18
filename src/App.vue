<template>
  <div>
    <div class="np-header">
      <h3>Vue 3 Lazy Load Images Example</h3>
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/1/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/2/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/3/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/4/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/5/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/6/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/7/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/8/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/9/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/10/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/11/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/12/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/13/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/14/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/15/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/16/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/17/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/18/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/19/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/20/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/21/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/22/500/400" />
    </div>
    <div class="np-ht">
      <v-lazy-image src="https://picsum.photos/id/23/500/400" />
    </div>
    <!--
      www.nightprogrammer.com
    -->
  </div>
</template>

<script>
import VLazyImage from "v-lazy-image";

export default {
  name: "App",
  components: {
    "v-lazy-image": VLazyImage,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.np-ht {
  height: 600px;
}

.np-header {
  padding: 30px;
  background: #eee;
  max-width: 500px;
  margin: 0 auto;
  margin-bottom: 40px;
}
</style>
