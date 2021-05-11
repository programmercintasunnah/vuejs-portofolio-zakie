<template>
  <div class="home">
    <!-- <Navbar /> -->

    <Header />
      <Skill />
    <Pendidikan />
  </div>
</template>

<script>
// @ is an alias to /src

// import Navbar from "@/components/Navbar.vue";
import Header from "@/components/Header.vue";
import Pendidikan from "@/components/Pendidikan.vue";
import Skill from "@/components/Skill.vue";

export default {
  name: "Home",
  components: {
    // Navbar,
    Header,
    Pendidikan,
    Skill,
  },
};
</script>
