<template>
  <Heading></Heading>
  <Homepage></Homepage>
  <!-- <Blog></Blog> -->
  <!-- <BlogDetails></BlogDetails> -->
  <Footing></Footing>
</template>

<script>
import Heading from '@/components/Heading.vue';
import Footing from '@/components/Footing.vue';
import Homepage from '@/components/Homepage.vue';
import Blog from '@/components/Blog.vue';
import BlogDetails from '@/components/BlogDetails.vue';

export default {
  name: 'App',
  components: {
    Heading, Footing, Homepage, Blog, BlogDetails
  }
}
</script>

<style lang="scss">

</style>
