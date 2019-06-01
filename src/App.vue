<template>
  <div id="app">
  	
  
  	
    <blog-header></blog-header>
  	<router-view></router-view>
   
  </div>
</template>

<script>
	import ShowBlogs from './components/ShowBlogs'
  import AddBlog from './components/AddBlog'
 import BlogHeader from './components/BlogHeader'
export default {
  name: 'App',
  components: {
ShowBlogs,AddBlog,BlogHeader
  }
}
</script>

<style>

</style>
