<template>
  <div class="profile-border">
    <section id="profile" class="section-profile">
      <img src="assets/profile.jpg" alt="Profile" class="profile-pic" />
      <div class="profile-desc">
        <h1>Lysa Sorkeo</h1>
        <h2 class="title">Senior in Computer Science | Paragon International School</h2>

        <p>
          I'm Lysa Sorkeo, and I am passionate about gaining new experiences, utilizing my English language proficiency, and leveraging leadership abilities to make a positive impact.
          I am a highly motivated and dedicated senior in Computer Science seeking challenging opportunities to further develop technical skills and contribute to innovative projects.
        </p>
        <hr />
        <div class="contact-info">
          <p>Email: sorkeolysa008@gmail.com</p>
          <p>Phone Number: +885 12571613</p>
          <p>Telegram: <a href="https://t.me/interrupting_lys" target="_blank">https://t.me/interrupting_lys</a></p>
          <p>Location: Russey Keo, Phnom Penh, Cambodia</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.profile-border {
  padding: 10px;
  border: 5px solid #b9b3af;
  border-radius: 35px;
  max-width: 90%;
  margin: 20px auto;
  box-shadow: 0px 10px 10px rgba(0, 0, 0, 0.1);
}

.section-profile {
  display: flex;
  align-items: center;
  padding: 20px;
  background-color: #f0efeb;
  border-radius: 30px;
}

.profile-pic {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  margin-right: 40px;
  margin-left: 20px;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
}

.profile-desc {
  flex-grow: 1;
}

h1 {
  font-size: 1.8rem;
  color: #7a6c66;
}

.title {
  font-size: 1rem;
  color: #7a6c66;
  margin: 5px 0;
}

p {
  font-size: 0.9rem;
  color: #4e4d4a;
  margin: 10px 0;
}

.contact-info p {
  color: #4e4d4a;
  font-size: 0.9rem;
  margin: 3px 0;
}

/* Responsive Design */
@media (max-width: 768px) {
  .section-profile {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .profile-pic {
    margin: 0 0 20px 0;
  }

  h1 {
    font-size: 1.5rem;
  }

  .title {
    font-size: 0.9rem;
  }

  p,
  .contact-info p {
    font-size: 0.85rem;
  }
}

@media (max-width: 480px) {
  .profile-border {
    padding: 5px;
  }

  .section-profile {
    padding: 15px;
  }

  .profile-pic {
    width: 120px;
    height: 120px;
  }

  h1 {
    font-size: 1.3rem;
  }

  .title {
    font-size: 0.85rem;
  }

  p,
  .contact-info p {
    font-size: 0.8rem;
  }
}
</style>
