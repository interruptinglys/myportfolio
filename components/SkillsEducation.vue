<template>
  <section id="skills" class="section-skills">
    <div class="info-box">
      <!-- Skills Section -->
      <div class="skills">
        <h2>Skills</h2>
        <ul>
          <li>- Programming Languages: HTML | CSS | JavaScript | PHP | Go | C++</li>
          <li>- Frameworks: Vue.js | Laravel</li>
          <li>- UI/UX Design: Proficient in Figma</li>
          <hr />
          <li>- Strong problem-solving and analytical abilities</li>
          <li>- Effective communication and collaboration skills</li>
          <li>- Excellent command of the English language</li>
        </ul>
      </div>

      <!-- Education Section -->
      <div class="education">
        <h2>Education</h2>
        <div class="education-item">
          <h3>Paragon International University, Phnom Penh</h3>
          <p>Bachelor in Computer Science (Expected Graduation: 2025)</p>
          <p>75% Scholarship || GPA: 3.29</p>
        </div>
        <div class="education-item">
          <h3>Australian Center of Education, Siem Reap</h3>
          <p>Enrolled from 2015 to 2019 | Completed 10 diploma courses.</p>
        </div>
        <div class="education-item">
          <h3>Angkor Highschool, Siem Reap</h3>
          <p>Graduated in 2021 with Grade: B</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
/* Outer section styling */
.section-skills {
  background-color: #f0efeb;
  padding: 40px;
  max-width: 90%;
  margin: 0 auto;
  border-radius: 10px;
  margin-top: 50px;
}

/* Inner box styling for skills and education */
.info-box {
  background-color: #ffffff;
  padding: 20px;
  border-radius: 10px;
  display: flex;
  justify-content: space-between;
  gap: 20px;
  max-width: 100%;
  margin: 0 auto;
}

/* Skills and Education columns */
.skills,
.education {
  flex: 1;
  margin: 0 10px;
}

/* Styling for headings */
h2 {
  color: #76726f;
  margin-bottom: 10px;
  text-decoration: underline;
  font-size: 1.5rem;
}

/* List and paragraph styling */
ul,
p {
  color: #413c39;
}

ul {
  list-style-type: none;
  padding-left: 0;
}

ul li {
  margin-bottom: 10px;
  font-size: 0.9rem;
}

/* Education items */
.education-item {
  margin-bottom: 15px;
}

h3 {
  color: #523726;
  margin-bottom: 5px;
  font-size: 1rem;
}

p {
  color: #6f5e53;
  margin-bottom: 5px;
  font-size: 0.9rem;
}

/* Responsive layout */
@media (max-width: 768px) {
  .info-box {
    flex-direction: column;
    padding: 15px;
  }

  h2 {
    font-size: 1.3rem;
  }

  ul li,
  p {
    font-size: 0.85rem;
  }

  h3 {
    font-size: 0.95rem;
  }
}

@media (max-width: 480px) {
  .section-skills {
    padding: 20px;
  }

  .info-box {
    padding: 10px;
  }

  h2 {
    font-size: 1.2rem;
  }

  ul li,
  p {
    font-size: 0.8rem;
  }

  h3 {
    font-size: 0.9rem;
  }
}
</style>
