<template>
  <div style="margin-bottom: 80px;">
    <h1>Howdy!</h1>

    <div class="paragraph">
      <div>
        I'm <strong>Chase Lee</strong>, a current senior at the University of Hawai'i at Manoa.<br/>
        I often spend a lot of time making video games using the Unity engine and organizing events for my Game Dev
        Club members.
      </div>

      <div style="margin-top: 20px;">I've worked on  <router-link to="/game-projects">games</router-link>, <router-link to="/other-projects">other projects</router-link>, and a <router-link to="/resume">resume</router-link> for quick viewing as well.</div>

      <div style="margin-top: 40px;">I'm <strong>currently looking for a job</strong> as a game designer, to fulfill my dream of creating a video game. You can reach me at <a href="mailto:chaselee65@gmail.com">chaselee65@gmail.com</a> or <router-link to="/contact">through here</router-link>.</div>
    </div>

    <div class="photo">
      <img src="img/avatar.png" alt="Avatar of John" /> 
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

.photo {
  margin-top: 50px;
  text-align: center;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 10px;
    padding-left: 80px;
  }
}

</style>