<template>
  <section class="portfolio-experience" id="work-volunteering">
    <h2>Work and Volunteering Experiences</h2>
    
    <!-- Experience Cards in Two Columns -->

    <div class="experience-grid">
      <!-- Fullstack Developer - SAAT -->
      <div class="experience-card">
        <h3>UX/UI Designer - SAAT</h3>
        <p class="date-range">2024 - Ongoing</p>
        <p>
          - Designed and developed user interfaces for multiple company products, ensuring a seamless and engaging user experience.
        </p>
        <p>- Key projects: Saat Menu, Saat Owner, Kang Topup, Saat App</p>
        <p><strong>Technologies:</strong> Figma, Canva</p>
      </div>

      <div class="experience-card">
        <h3>Freelance in Content Creating for Small E-Commerce Businesses </h3>
        <p class="date-range">March 2023- Ongoing</p>
        <p>
          - Social Media Management: Facebook Page, Instagram, Tiktok 
        </p>
        <p>- Create and post posters, videos, pictures, stories</p>
        <p>- Content Strategy and Creation for e-commerce businesses</p>
        <p><strong>Technologies:</strong> Canva, Capcut, Picsart, Tiktok</p>
      </div>

      <div class="experience-card">
        <h3>Team Leader, She Can Code , Paragon International University</h3>
        <p class="date-range">2022 and 2023</p>
        <p>
          - Demonstrated leadership skills in the Mentor team, Technical Support team, and Certificate Team
        </p>
        <p>- Organized and led workshops, hackathons, and coding competitions</p>
      </div>

      <div class="experience-card">
         <h3>Liaison Officer for the National Election Committee, Phnom Penh</h3>
         <p class="date-range">20th - 24th, July 2023</p>
         <p> - Served as a liaison between the office of His Excellency KP Sharma Oli, former Prime Minister of Nepal.    </p>
         <p> - Assisted in organizing high-level meetings and events, fostering stronger relationships between all nations.  </p>
      </div>

      <div class="experience-card">
        <h3>Volunteer, Clean Energy Youth Program - EnergyLab Cambodia  </h3>
        <p class="date-range">December 2023</p>
        <p>
          - Participated in the Clean Energy Week 2023, contributing to promoting clean energy awareness and sustainable practices.
        </p>
        <p>- Collaborated with organizers to engage youth in discussions and activities focused on clean energy solutions.</p>
      </div>

      <div class="experience-card">
        <h3>Charity Organizer, Chongcham</h3>
        <p class="date-range">March-May 2022</p>
        <p> - Helped organize and coordinate the Chongcham Project to raise funds to purchase technologies for students in the countryside </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
/* Section styling */
.portfolio-experience {
  background-color: #f0efeb;
  padding: 20px;
  border-radius: 30px;
  margin: 50px;
  max-width: 90%;
}

.portfolio-experience h2 {
  color: #5e5a56; /* Text color */
  font-size: 1.5rem;
  margin-bottom: 30px;
  
}

/* Grid container for exactly 2 columns */
.experience-grid {
  display: grid;
  grid-template-columns: 1fr 1fr; /* Always two columns */
  gap: 20px; /* Space between cards */
}

/* Experience card styling */
.experience-card {
  border: 5px solid #b9b3af;
  background-color: #ffffff;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
}

.experience-card h3 {
  color: #605d59;
  font-size: 1rem;
}

.experience-card .date-range {
  color: #686760;
  margin-bottom: 10px;
}

.experience-card p {
  color: #6f6f6f;
  margin-bottom: 10px;
  font-size: 0.8rem;
}

.experience-card a {
  color: #D8DEE9;
  text-decoration: none;
}

.experience-card a:hover {
  text-decoration: underline;
}

/* Force 2 columns even on small screens */
@media (max-width: 768px) {
  .experience-grid {
    grid-template-columns: 1fr 1fr; /* Keep two columns on smaller screens */
  }
}
</style>
