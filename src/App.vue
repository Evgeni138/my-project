<template>
  <Heading></Heading>
  <!-- <Homepage></Homepage> -->
  <!-- <Blog></Blog> -->
  <!-- <BlogDetails></BlogDetails> -->
  <Project/>
  <Footing></Footing>
</template>

<script>
import Heading from '@/components/Heading.vue';
import Footing from '@/components/Footing.vue';
import Homepage from '@/components/Homepage.vue';
import Blog from '@/components/Blog.vue';
import BlogDetails from '@/components/BlogDetails.vue';
import Project from './components/Project.vue';

export default {
  name: 'App',
  components: {
    Heading, Footing, Homepage, Blog, BlogDetails, Project
  }
}
</script>

<style lang="scss">

</style>
