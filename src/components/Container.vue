<template>
  <div class="container p-6 max-w-6xl mx-auto">
    <p class="py-4">Hello > Hello</p>
    <Search />
    <div class="py-8">
      <Flag />
    </div>
    <NewPost />
    <hr class="my-10"/>
    <span class="uppercase text-sm font-bold text-gray-400">Top of the day</span>
    <div class="grid lg:grid-cols-2">
      <TopPost />
      <TopPost />
    </div>
    <hr class="my-10"/>
    <span class="uppercase text-sm font-bold text-gray-400">Interesting</span>
    <div class="grid lg:grid-cols-3">
      <Post />
      <Post />
      <Post />
      <Post />
      <Post />
      <Post />
    </div>
    <CallToAction />
    <div class="grid lg:grid-cols-3">
      <Post />
      <Post />
      <Post />
      <Post />
      <Post />
      <Post />
    </div>


  </div><!--  container-->
</template>

<script>
  import Search from './Search.vue'
  import Flag from './Flag.vue'
  import NewPost from './NewPost.vue'
  import TopPost from './TopPost.vue'
  import Post from './Post.vue'
  import CallToAction from './CallToAction.vue'


  export default {
    name: 'App',
    components: {
      CallToAction,
      Flag,
      NewPost,
      TopPost,
      Post,
      Search,
    }
  }

</script>