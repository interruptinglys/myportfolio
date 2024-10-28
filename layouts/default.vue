<template>
  <div>
    <!-- Header or Navbar -->
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
/* Body and main wrapper background color */
body {
  background-color: white;
  margin: 0;
  padding: 0;
  font-family: 'Arial', sans-serif;
}

/* Header Styling */
header {
  background-color: #fff;
  color: black;
  padding: 20px;
  text-align: center;
}

/* Main content section */
main {
  padding: 20px;
  min-height: 100vh;
  background-color: white;
}

/* Footer Styling */
footer {
  background-color: #f0efeb;
  color: rgb(65, 63, 63);
  padding: 10px;
  text-align: center;
}

/* Responsive design */
@media (max-width: 768px) {
  main {
    padding: 15px;
  }

  footer {
    padding: 15px;
    font-size: 14px;
  }
}

@media (max-width: 480px) {
  header, footer {
    padding: 10px;
    font-size: 12px;
  }

  main {
    padding: 10px;
  }
}
</style>
