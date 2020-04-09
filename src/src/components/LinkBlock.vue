<template>
  <div class="link-block">
    <h1>{{ msg }}</h1>
    <p>
      <a v-bind:href="link" target="_blank" rel="noopener"
        >{{ msg }}</a
      >
      👀  
    </p>
  </div>
</template>

<script>
export default {
  name: 'LinkBlock',
  props: {
    msg: String,
    link: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
  color: #2b2b2b;
}
a {
  color: #e74040;
}
.link-block{
  background-color: #5bd5eb93;
  border-radius: 3px;
  padding: 1rem;
}
</style>
