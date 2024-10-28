<template>
  <nav>
    <div class="nav-container">
      <div class="hamburger" @click="toggleMenu">
        <span></span>
        <span></span>
        <span></span>
      </div>
      <ul :class="{ open: isMenuOpen }">
        <li><a href="#profile" @click="scrollToSection('profile')">About Me</a></li>
        <li><a href="#work-volunteering" @click="scrollToSection('work-volunteering')">Work and Volunteer</a></li>
        <li><a href="#achievements" @click="scrollToSection('achievements')">Achievements</a></li>
        <li><a href="#certificates" @click="scrollToSection('certificates')">Certificates</a></li>
        <li><a href="#skills" @click="scrollToSection('skills')">Skills & Education</a></li>
      </ul>
    </div>
  </nav>
</template>

<script setup>
import { ref } from 'vue';

const isMenuOpen = ref(false);

const toggleMenu = () => {
  isMenuOpen.value = !isMenuOpen.value;
};

const scrollToSection = (sectionId) => {
  const section = document.getElementById(sectionId);
  if (section) {
    section.scrollIntoView({ behavior: 'smooth' });
    isMenuOpen.value = false; // Close menu after selection
  }
};
</script>

<style scoped>
/* Basic navbar styling */
nav {
  background-color: white;
  padding: 20px 40px;
  border-bottom: 2px solid #f7d9c4;
}

.nav-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

ul {
  list-style: none;
  display: flex;
  gap: 40px;
  justify-content: flex-end;
  padding: 0;
  margin: 0;
}

li {
  margin: 0;
}

a {
  color: #7a6c66;
  text-decoration: none;
  cursor: pointer;
}

a:hover {
  text-decoration: underline;
}

/* Hamburger icon styling */
.hamburger {
  display: none;
  flex-direction: column;
  cursor: pointer;
  gap: 5px;
}

.hamburger span {
  display: block;
  width: 25px;
  height: 3px;
  background-color: #7a6c66;
}

/* Responsive design */
@media (max-width: 768px) {
  .hamburger {
    display: flex; /* Show hamburger on smaller screens */
  }

  ul {
    display: none; /* Hide menu by default on mobile */
    flex-direction: column;
    gap: 20px;
    position: absolute;
    top: 60px;
    left: 10px; /* Align the menu to the left, same side as the hamburger icon */
    background-color: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
    z-index: 10;
  }

  ul.open {
    display: flex; /* Show menu when open */
  }
}
</style>
