<template>
  <div>
    <!-- Header or Navbar -->
    <!-- <header>
      <h1>My Portfolio</h1>
      <!-- Add a navigation bar if needed -->
    <!-- </header> --> 

    <Navbar />
    <!-- Main content area -->
    <main>
      <NuxtPage />
    </main>

    <!-- Footer -->
    <footer>
      <p>© 2024 My Portfolio. All rights reserved.</p>
    </footer>
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue';

export default {}
</script>

<style scoped>
/* Body or main wrapper background color */
body {
  background-color: white; /* Apply the solid color to the background */
  margin: 0;
  padding: 0;
  font-family: 'Arial', sans-serif;
}

/* Header Styling */
header {
  background-color: #fff;
  color: white;
  padding: 20px;
  text-align: center;
}

/* Main content section */
main {
  padding: 20px;
  min-height: 100vh; /* Ensures full screen height */
   /*background-color: #696663; Same background color as the body */
   background-color: white; 
}

/* Footer Styling */
footer {
  background-color: #f0efeb;
  color: rgb(65, 63, 63);
  padding: 10px;
  text-align: center;
}
</style>
