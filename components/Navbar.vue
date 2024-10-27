<template>
  <nav>
    <ul>
      <li><a href="#profile" @click="scrollToSection('profile')">About Me</a></li>
      <li><a href="#work-volunteering" @click="scrollToSection('work-volunteering')">Work and Volunteer</a></li>
      <li><a href="#achievements" @click="scrollToSection('achievements')">Achievements</a></li>
      <li><a href="#certificates" @click="scrollToSection('certificates')">Certificates</a></li>
      <li><a href="#skills" @click="scrollToSection('skills')">Skills & Education</a></li>
    </ul>
  </nav>
</template>

<script setup>
const scrollToSection = (sectionId) => {
  const section = document.getElementById(sectionId);
  if (section) {
    section.scrollIntoView({ behavior: 'smooth' });
  }
};
</script>

<style scoped>
nav {
  /*background-color: #696663;*/
  background-color: white; 
  padding: 40px;
  border-bottom: 2px solid #f7d9c4; /* Thin line at the bottom of the nav */
}

ul {
  list-style: none;
  display: flex;
  gap: 40px;
  justify-content: flex-end; /* Align items to the right */
  padding: 0;
  margin: 0;
}

li {
  margin: 0; /* Ensure no extra margin is added */
}

a {
  color: #7a6c66;
  text-decoration: none;
  cursor: pointer; /* Ensure pointer cursor */
}

a:hover {
  text-decoration: underline;
}
</style>
