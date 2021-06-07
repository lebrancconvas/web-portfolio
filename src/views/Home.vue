<template>
  <div class="home">
    <About />
    <Project />
    <Skill />
    <Contact /> 
  </div>
</template>

<script>
// @ is an alias to /src
import About from '@/components/About.vue'
import Project from '@/components/Project.vue'
import Skill from '@/components/Skill.vue'
import Contact from '@/components/Contact.vue'
export default {
  name: 'Home',
  components: {
    About,
    Project,
    Skill,
    Contact
  }
}
</script>
