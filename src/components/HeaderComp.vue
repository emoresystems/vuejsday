<template>
  <div>
    <div class="header">
      <h1>{{ header }}</h1>
      <p>
        {{ description }}
      </p>
      <button v-on:click="showMore">read more</button>
    </div>
  </div>
</template>
<script>
export default {
  name: "HeaderComp",

  methods: {
    showMore() {
      alert("welcome back");
    },
  },

  data() {
    return {
      header: "Welcome to my website",
      description:
        "excepturi neque, libero itaque doloremque aliquam impedit deserun",
    };
  },
};
</script>

<style scoped>
.header {
  background-color: chartreuse;
  text-align: center;
  padding: 10px;
}
</style>
