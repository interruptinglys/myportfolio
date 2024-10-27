<template>
    <section class="certificate-section" id="certificates">
      <h2>Certificates</h2>
      <p>Of Participants and Achievements</p>
  
      <!-- Achievement Card -->
      <div class="achievement-card2">
        
        <div class="image-grid">
          <!-- Display multiple images -->
          <img src="~/assets/1.jpg" alt="Image 1" />
          <img src="~/assets/4.jpg" alt="Image 1" />
          <img src="~/assets/6.jpg" alt="Image 0" />

          <img src="~/assets/2.jpg" alt="Image 2" />
          <img src="~/assets/3.jpg" alt="Image 0" />
          <img src="~/assets/0.jpg" alt="Image 0" />
          <img src="~/assets/117.jpg" alt="Image 0" />
          <img src="~/assets/118.jpg" alt="Image 1" />
          <img src="~/assets/5.jpg" alt="Image 2" />
          <img src="~/assets/7.jpg" alt="Image 1" />
          <img src="~/assets/8.jpg" alt="Image 2" />
          <img src="~/assets/9.jpg" alt="Image 0" />
          <img src="~/assets/10.jpg" alt="Image 1" />
          <img src="~/assets/11.jpg" alt="Image 2" />
          <img src="~/assets/12.jpg" alt="Image 0" />
          <img src="~/assets/13.jpg" alt="Image 1" />
          <img src="~/assets/14.jpg" alt="Image 2" />
          <img src="~/assets/15.jpg" alt="Image 2" />
          
        </div>
      </div>
  
      <!-- You can add more cards with a similar structure for other achievements -->
    </section>
  </template>
  
  <script>
  export default {
    data() {
      return {
        // No additional data needed
      };
    }
  };
  </script>
  
  <style scoped>
  .certificate-section {
  text-align: center;
  padding: 40px;
  background-color: #f0f0f0;
  color: #cad2c5;
  max-width: 90%; /* Consistent width with the above section */
  margin: 0 auto; /* Center-align the section */
  border-radius: 10px; /* Optional border radius for consistency */
}

.certificate-section h2 {
  color: #7a6c66;
  font-size: 1.5rem;
  margin-bottom: 10px;
  text-align: start;
}

.certificate-section p {
  color: #b9b3af;
  font-size: 1rem;
  margin-bottom: 20px;
  text-align: start;
}

/* Achievement card styling */
.achievement-card2 {
  background-color: #e5e6df;
  padding: 20px;
  margin-bottom: 30px;
  border-radius: 10px;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
}

/* Grid for images */
.image-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr); /* 3 columns */
  gap: 10px;
  max-width: 100%; /* Ensures images align with section width */
  margin: 0 auto; /* Center the grid */
}

.image-grid img {
  width: 100%;
  height: 330px; /* Fixed height for uniformity */
  object-fit: cover; /* Ensures images are cropped to fit */
  border-radius: 10px;
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
}

/* Responsive layout adjustments */
@media (max-width: 768px) {
  .image-grid {
    grid-template-columns: repeat(2, 1fr); /* 2 images per row on smaller screens */
  }
}

@media (max-width: 480px) {
  .image-grid {
    grid-template-columns: 1fr; /* 1 image per row on very small screens */
  }
}

  </style>
  