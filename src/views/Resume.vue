<template>
  <div>
    <h1>Resume</h1>

    <div class="paragraph">
      I'm <strong>Chase Lee</strong>, a current senior at the University of Hawai'i at Manoa.
      <br />After graduating from kindergarten, I've been enrolled in the army for 25 years, where I learned to destroy things in an amazing number of ways.
      <br />I joined the Delta Force because I thought it was Greek lessons, but I quickly adapted to this unexpected environment and became a key element.
      <br />I love teamwork, but I can also go in solo depending on the mission requirements.
      <br />
      <br />If you have any opportunity that I seem to fit feel free to
      <router-link to="/contact">contact me</router-link>.
      <br />
      <br />Besides Game Dev, I also have some gaming hobbies such as being on a League of Legends team and playing Pump It Up

      <div style="margin-top:20px; margin-bottom:20px;">
        <a class="download-link" href="d/Chase_Lee_Resume.pdf" target="_blank"><i class="fa fa-download fa-lg fa-fw"></i> Download as PDF 🇬🇧</a>
        <div style="clear:both"></div>
      </div>
    </div>
    <div class="photo">
      <img src="img/resume-photo.png" alt="Photo of John" />
    </div>

    <div style="clear:both"></div>

    <div class="full-content">
      <h2>Work experience</h2>

      <h3>Unity Software Engineer - KBR</h3>
      <h4>June 2021 - Present</h4>

      <div>● Constructed realistic drone flight simulation through Unity</div>
      <div>● Wrote several C# scripts for drone simulation, simulating camera aperture and environment</div>
      <div>● Reinforced drone detection models by producing simulation data for machine learning</div>

      <div class="tech-stack">Unity, Internship, Software Engineering, KANBAN, AWS, C#</div>

      <h3>Game Jam Competitions - Game Dev Club</h3>
      <a href="https://snekuchan.itch.io/" target="_blank">https://snekuchan.itch.io/</a>
      <h4>September 2020 - November 2021</h4>

      <div>● Developed a fully functioning games through Unity within a two week time limit with my peers</div>
      <div>● Directed my peers through the Unity process, moderated their work and mediated conversation about the games</div>
      <div>● Evaluated criticism and adjusted the game accordingly to improve user experience</div>

      <div class="tech-stack">Teamwork, Github, Version Control, C#</div>

      <h3>Software Engineering - Zeus</h3>
      <h4>May 2021 - December 2021</h4>

      <div>● Built a program that utilizes MongoDB and changes the data of medication and supplies in real time</div>
      <div>● Addressed concerns with the customer and made changes based on customer critiques</div>
      <div>● Developed using Javascript, CSS, HTML, and Meteor</div>
      <div class="tech-stack">Teamwork, Github, Version Control, Javascript, HTML</div>

<!--      <h2>Skills</h2>-->

<!--      <div class="skill-set">-->
<!--        <h3>Lethal</h3>-->
<!--        <SkillRate name="Handguns" :rate="5" />-->
<!--        <SkillRate name="Rifles" :rate="5" />-->
<!--        <SkillRate name="Shotguns" :rate="5" />-->
<!--        <SkillRate name="Machineguns" :rate="5" />-->
<!--        <SkillRate name="Missile launchers" :rate="5" />-->
<!--        <SkillRate name="Knives" :rate="5" />-->
<!--        <SkillRate name="Hand to hand combat" :rate="5" />-->
<!--      </div>-->

<!--      <div class="skill-set">-->
<!--        <h3>Non-lethal</h3>-->
<!--        <SkillRate name="Sneaking" :rate="1" />-->
<!--        <SkillRate name="Negotiation" :rate="1" />-->
<!--        <SkillRate name="Seduction" :rate="1" />-->
<!--        <SkillRate name="Sense of humor" :rate="2" />-->
<!--      </div>-->
<!--      <div style="clear:both" />-->

      <h2>Education</h2>

      <h3>University of Hawai’i at Manoa</h3>
      <h4>Bachelor of Science in Computer Science</h4>
      <h4>Relevant Courses</h4>
      <div>● ICS 212: Scripting or C/C++ - Fundamentals of C/C++ and their applications.</div>
      <div>● ICS 311: Algorithms - Improving knowledge of data structures and algorithms.</div>
      <div>● ICS 314: Software Engineering I - Utilizing Javascript, CSS, and HTML to create sites that serve a function.</div>
      <div>● ICS 321: Database Systems - Understanding the fundamentals of SQL and organizing databases.</div>
      <div>● ICS 485: Video Game Design - Study gamification and the Unity Engine in order to understand how to create games and how games are made.</div>
      <div>● ICS 496: Capstone Project - Student-driven project utilizing Azure Kinects and the Unity Engine to track poses.</div>

      <h2>Extra-curriculars</h2>

      <h3>Game Dev Club at UHM - President</h3>
      <h4>August 2020 - Present</h4>

      <div>● Led group discussions in multiple topics of game design and organized game design events.</div>
      <div>● Prepared Unity workshops and directed members how to use Unity and later collaborated using Github</div>
      <div>● Organized club participation in game jams and held meetings to design various games</div>
      <div class="tech-stack">Teamwork, Github, Version Control, Unity, C#</div>

      <h3>International Student Association - Public Relations Officer</h3>
      <h4>August 2021 - December 2021</h4>

      <div>● Organized events and gathered students across the entire UH system to join.</div>
      <div>● Discussed with peers and maintained healthy and professional relationships with other clubs.</div>
      <div class="tech-stack">Leadership, Communication, Teamwork</div>

      <h3>UH Black - Sub Player</h3>
      <h4>August 2020 - Present</h4>

      <div>● Players </div>
      <div>● Prepared Unity workshops and directed members how to use Unity and later collaborated using Github</div>
      <div>● Organized club participation in game jams and held meetings to design various games</div>
      <div class="tech-stack">Communcation, Games, Teamwork</div>


<!--      <h2>Besides...</h2>-->
<!--      <div>-->
<!--        <h3>I ❤️ Violence</h3>-->
<!--        <div>I find it really soothing to just shoot at bad guys</div>-->

<!--        <h3>I 🧡 Sports</h3>-->
<!--        <div>I used to be thin but then I ingested 10 kilos of steroids and proteins a day while doing 1000 push-ups.</div>-->

<!--        <h3>I 💛 Politics</h3>-->
<!--        <div>I hope I can have a career here someday but I might have temper issues.</div>-->

<!--        <h3>I 💚 Flowers</h3>-->
<!--        <div>Especially the big ones, with the trunk and leaves.</div>-->

<!--      </div>-->
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import SkillRate from "@/components/SkillRate.vue";

export default Vue.extend({
  name: "Resume",
  // components: {
  //   SkillRate,
  // },
});
</script>

<style scoped>
h2 {
  font-weight: 100;
  font-size: 2em;
  margin: 0px;
  padding: 0px;
  padding-top: 50px;
}
h3 {
  font-weight: 100;
  font-size: 1.6em;
  margin: 0px;
  padding: 0px;
  padding-top: 30px;
}
h4 {
  font-weight: 100;
  font-size: 1.3em;
  margin: 0px;
  padding: 0px;
  padding-top: 15px;
  font-style: italic;
}

.paragraph {
  max-width: 700px;
}

.download-link {
  float:left;
  margin-right: 50px;
}

.full-content div {
  max-width: 800px;
}

.skill-set h3 {
  padding-bottom: 10px;
}

.photo img {
  height: 300px;
  width: 300px;
}

.tech-stack {
  font-style: italic;
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
    padding: 30px;
    padding-left: 80px;
  }

  .skill-set {
    float: left;
    padding-right: 60px; 
  }
}
</style>