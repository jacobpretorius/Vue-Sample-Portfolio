<template>
  <div class="home">
    <h1>Home page</h1>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
      veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
      commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
      velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
      cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id
      est laborum.
    </p>
    <div class="link-area">
      <LinkBlock
        msg="Check out my Github"
        link="https://github.com/jacobpretorius"
      />

      <LinkBlock msg="Check out this website" link="https://jcpretorius.com/" />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import LinkBlock from '@/components/LinkBlock.vue';

export default {
  name: 'Home',
  components: {
    LinkBlock,
  },
};
</script>
<style scoped lang="scss">
.link-area{
  display: flex;
  justify-content: space-around;
  margin: 2rem;
}
</style>
