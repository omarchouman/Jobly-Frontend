<template>
  <div class="Login">
    <NavBar />
    <CommonHeroSection
      title="Login"
      description="Login as a Jobseeker or Employer"
    />
    <LoginRegisterSection formType="Login" />
    <FooterSection />
  </div>
</template>
<script>
// @ is an alias to /src
import NavBar from "@/components/NavBar.vue";
import CommonHeroSection from "@/components/CommonHeroSection.vue";
import LoginRegisterSection from "@/components/LoginRegisterSection.vue";
import FooterSection from "@/components/FooterSection.vue";

export default {
  name: "Login",
  title: "Login  | jobly",
  components: {
    NavBar,
    CommonHeroSection,
    LoginRegisterSection,
    FooterSection,
  },
};
</script>
