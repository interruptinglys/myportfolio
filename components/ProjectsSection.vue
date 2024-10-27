<template>
    <section id="projects" class="section-projects">
      <h2>Projects</h2>
      <div class="projects-grid">
        <div class="project">
          <h3>Project 1</h3>
          <p>A short description of the project.</p>
          <a href="https://your-project-link.com" target="_blank">View Project</a>
        </div>
        <!-- Add more projects -->
      </div>
    </section>
  </template>
  
  <script>
  export default {
    // Add props or data for dynamic projects if needed
  }
  </script>
  
  <style scoped>
  .section-projects {
    padding: 50px;
    background-color: #f4f4f4;
  }
  
  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 20px;
  }
  
  .project {
    background-color: #fff;
    padding: 20px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  }
  
  .project a {
    display: inline-block;
    margin-top: 10px;
    text-decoration: none;
    color: #3498db;
  }
  </style>
  