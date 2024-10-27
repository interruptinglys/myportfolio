<template>
    <div>
      <ProfileSection />
      <WorkExperience />
      <AchievementsSection />  
      <CertificateSection />
      <SkillsEducation />
    </div>
  </template>
  
  <script >
  import ProfileSection from '~/components/ProfileSection.vue'
  import SkillsEducation from '~/components/SkillsEducation.vue'
  import CertificateSection from '~/components/CertificateSection.vue'
  import WorkExperience from '~/components/WorkExperience.vue'
  import AchievementsSection from '~/components/AchievementsSection.vue';
  
  export default {
    components: {
      ProfileSection,
      SkillsEducation,
      AchievementsSection,
      CertificateSection,
      WorkExperience
      
    }
  }
  </script>
  