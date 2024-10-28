<template>
  <section class="certificate-section" id="certificates">
    <h2>Certificates</h2>
    <p>Of Participants and Achievements</p>

    <!-- Achievement Card -->
    <div class="achievement-card2">
      <div class="image-grid">
        <!-- Display multiple images -->
        <img src="~/assets/1.jpg" alt="Image 1" />
        <img src="~/assets/4.jpg" alt="Image 4" />
        <img src="~/assets/6.jpg" alt="Image 6" />
        <img src="~/assets/2.jpg" alt="Image 2" />
        <img src="~/assets/3.jpg" alt="Image 3" />
        <img src="~/assets/0.jpg" alt="Image 0" />
        <img src="~/assets/117.jpg" alt="Image 117" />
        <img src="~/assets/118.jpg" alt="Image 118" />
        <img src="~/assets/5.jpg" alt="Image 5" />
        <img src="~/assets/7.jpg" alt="Image 7" />
        <img src="~/assets/8.jpg" alt="Image 8" />
        <img src="~/assets/9.jpg" alt="Image 9" />
        <img src="~/assets/10.jpg" alt="Image 10" />
        <img src="~/assets/11.jpg" alt="Image 11" />
        <img src="~/assets/12.jpg" alt="Image 12" />
        <img src="~/assets/13.jpg" alt="Image 13" />
        <img src="~/assets/14.jpg" alt="Image 14" />
        <img src="~/assets/15.jpg" alt="Image 15" />
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.certificate-section {
  text-align: center;
  padding: 40px;
  background-color: #f0f0f0;
  color: #cad2c5;
  max-width: 90%;
  margin: 0 auto;
  border-radius: 10px;
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
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
  max-width: 100%;
  margin: 0 auto;
}

.image-grid img {
  width: 100%;
  height: 330px;
  object-fit: cover;
  border-radius: 10px;
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
}

/* Responsive layout adjustments */
@media (max-width: 768px) {
  .image-grid {
    grid-template-columns: repeat(2, 1fr);
  }

  .certificate-section h2 {
    font-size: 1.3rem;
  }

  .certificate-section p {
    font-size: 0.9rem;
  }
}

@media (max-width: 480px) {
  .image-grid {
    grid-template-columns: 1fr;
  }

  .certificate-section h2 {
    font-size: 1.2rem;
  }

  .certificate-section p {
    font-size: 0.85rem;
  }

  .image-grid img {
    height: 250px; /* Reduced height for mobile */
  }
}
</style>
