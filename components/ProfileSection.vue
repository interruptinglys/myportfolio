<template>
  <div class="profile-border">
  <section id="profile" class="section-profile">
    <img src="assets/profile.jpg" alt="Profile" class="profile-pic" />
     <div class="profile-desc">
      <h1>Lysa Sorkeo</h1>
      <h2 class="title"> Senior in Computer Science | Paragon Inernational School </h2>

      <p>
        I'm Lysa Sorkeo, and I am passionate about gaining new experiences, utilizing my English language proficiency, and leveraging leadership abilities to make a positive impact.
        I am a highly motivated and dedicated senior in Computer Science seeking challenging opportunities to further develop technical skills and contribute to innovative projects.
      </p>
      <!-- <p>I am a senior at Paragon International School, majoring in Computer Science, with a passion for both technical development and design. As a UX/UI Designer at Saat, I contributed to projects like Saat Menu, Saat Owner, Kand Topup, and Saat App, focusing on creating user-friendly and impactful designs. Beyond design, I have experience managing social media and digital marketing for small e-commerce businesses. I’ve also taken on leadership roles, such as being a team leader for She Can Code, and participated in the Clean Energy Youth Program at EnergyLab Cambodia. My achievements include placing third in the Techo Start Up - Turing Hackathon and being a runner-up in the Camtech Innovation Tech Challenge.</p> -->
      <hr>
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
export default {}
</script>

<style scoped>

.profile-border {
  padding: 10px; /* Adjusted space around the inner profile box */
  border: 5px solid #b9b3af; /* Border color and thickness */
  border-radius: 35px;
  max-width: 90%;
  margin: 20px auto; /* Reduced margin to shorten height */
  box-shadow: 0px 10px 10px rgba(0, 0, 0, 0.1);
}

.section-profile {
  display: flex;
  align-items: center;
  padding: 20px; /* Reduced padding inside the profile section */
  background-color: #f0efeb;
  border-radius: 30px;
}

.profile-pic {
  width: 150px; /* Slightly smaller picture size */
  height: 150px;
  border-radius: 50%;
  margin-right: 40px; /* Reduced margin to bring elements closer */
  margin-left: 20px;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
}

.profile-desc {
  flex-grow: 1;
}

h1 {
  font-size: 1.8rem; /* Adjusted size to reduce height */
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
  margin: 10px 0; /* Reduced margin between paragraphs */
}

.contact-info p {
  color: #4e4d4a;
  font-size: 0.9rem;
  margin: 3px 0; /* Reduced space for contact info to save height */
}

</style>
