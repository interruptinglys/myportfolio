<template>
  <section class="achievement-section" id="achievements">
    <h2>Achievements</h2>

    <div class="achievement-card achievement-card1">
      <h3>Techo Start Up - Turing Hackathon Cycle 7 (Third Place)</h3>
      <p class="date date1">11-12 to 18-20 October 2023</p>
      <div class="image-grid">
        <img src="assets/hack.jpg" alt="Turing Hackathon Team 2" />
        <img src="assets/hack2.jpg" alt="Turing Hackathon Team 3" />
        <img src="assets/hack3.jpg" alt="Turing Hackathon Team 5" />
      </div>
    </div>

    <div class="achievement-card achievement-card2">
      <h3>Camtech - Innovation Tech Challenge (Runner-Up)</h3>
      <p class="date date2">June - August 2023</p>
      <div class="image-grid">
        <img src="assets/pikrous2.jpg" alt="Turing Hackathon Team 2" />
        <img src="assets/pikrous3.jpg" alt="Turing Hackathon Team 3" />
        <img src="assets/pikrous5.jpg" alt="Turing Hackathon Team 5" />
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.achievement-section {
  background-color: #f0efeb;
  padding: 20px;
  border-radius: 30px;
  margin: 50px;
  max-width: 90%;
}

.achievement-section h2 {
  color: #696663;
  font-size: 1.5rem;
  margin-bottom: 30px;
  text-align: center;
}

.achievement-card {
  padding: 20px;
  margin-bottom: 30px;
  border-radius: 10px;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
}

.achievement-card1 {
  background-color: #854d27;
  border: 5px solid #ffddbb;
}

.achievement-card2 {
  background-color: #1c2b47;
  border: 5px solid #cae9ff;
}

.achievement-card h3 {
  font-size: 1.3rem;
  margin-bottom: 10px;
}

.achievement-card1 h3 {
  color: #ffddbb;
}

.achievement-card2 h3 {
  color: #cae9ff;
}

.date {
  margin-bottom: 10px;
}

.date1 {
  color: #ffddbb;
}

.date2 {
  color: #cae9ff;
}

/* Grid for images */
.image-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
}

.image-grid img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 10px;
  box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
}

/* Responsive adjustments */
@media (max-width: 768px) {
  .image-grid {
    grid-template-columns: repeat(2, 1fr); /* 2 images per row on tablets */
  }

  .achievement-section {
    padding: 15px;
    margin: 30px auto;
  }

  .achievement-card h3 {
    font-size: 1.2rem;
  }
}

@media (max-width: 480px) {
  .achievement-section h2 {
    font-size: 1.3rem;
  }

  .achievement-card {
    padding: 15px;
  }

  .image-grid {
    grid-template-columns: 1fr; /* Single column on mobile */
  }

  .achievement-card h3 {
    font-size: 1rem;
  }

  .date {
    font-size: 0.9rem;
  }

  .image-grid img {
    height: 150px; /* Reduce image height on very small screens */
  }
}
</style>
