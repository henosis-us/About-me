<template>
  <!-- This is where we write the HTML template for our App component -->
  <div id="app">
    <!-- Everything inside the header tag will be placed in the header area of our website -->
    <header>
      <!-- Our Navbar component will appear here -->
      <navbar></navbar>
    </header>
    <!-- Everything inside the main tag will be main content of our website -->
    <main>
      <!-- The AboutMe component will be displayed here, followed by the ProjectSummary component -->
      <AboutMe></AboutMe>
      <ProjectSummary></ProjectSummary>
    </main>
    <!-- Everything inside the footer tag will be placed in the footer area of our website -->
    <footer>
      <!-- Your footer contents go here -->
    </footer>
  </div>
</template>

<script>
  // We import the components we want to use
  import Navbar from './components/Navbar.vue'
  import AboutMe from './components/AboutMe.vue'
  import ProjectSummary from './components/ProjectSummary.vue'

  export default {
    // Here we name our component
    name: 'App',
    // We tell Vue.js what components this component (App) uses
    components: {
      Navbar,
      AboutMe,
      ProjectSummary
    }
  }
</script>

<style>
  /* Here, we can write global CSS styles that will apply to our entire Vue app */
</style>