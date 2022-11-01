<template>
  <div>
    <img class="self" src="@/assets/Biography/me.webp" />
    <h2 class="header">John Gutierrez</h2>
    <h4 class="subtitle" style="padding-bottom: 10px;">
      Freelance Web Developer | Graphic Designer | UI/UX Designer
    </h4>
    <h4 class="subtitle">Winston-Salem 📍</h4>
    <div class="badge-grid">
      <img
        class="badge"
        alt="Java"
        src="https://img.shields.io/badge/-Java-orange"
      />
      <img
        class="badge"
        alt="SQL"
        src="https://img.shields.io/badge/-SQL-grey"
      />
      <img
        class="badge"
        alt="HTML/CSS"
        src="https://img.shields.io/badge/-HTML%2FCSS-blue"
      />
      <img
        class="badge"
        alt="Python"
        src="https://img.shields.io/badge/-Python-teal"
      />
      <img
        class="badge"
        alt="JavaScript"
        src="https://img.shields.io/badge/-Javascript-yellow"
      />
      <img
        class="badge"
        alt="Git"
        src="https://img.shields.io/badge/-Git-critical"
      />
      <img
        class="badge"
        alt="Vue"
        src="https://img.shields.io/badge/-VueJS-61b083"
      />
      <img
        class="badge"
        alt="React"
        src="https://img.shields.io/badge/-React-61dafb"
      />
    </div>
    <div class="inner-content">
      <h3 class="heading"><b>About Me</b></h3>
      <p class="paragraph">
        Hello there! I am John from Winston-Salem and I am extremely passionate
        in both programming and design for both the web and video game platform.
        I am currently a student in college pursuing a Bachelors in Computer
        Science.
      </p>
      <p class="paragraph">
        I have worked with a mixture of design and frontend/backend
        technologies, be it for Web Development or Video Game Development.
      </p>
      <p>
        I also love to do photography in my free time, take a look at my photos
        by clicking on the photos file.
      </p>
    </div>
    <div class="inner-content">
      <h2 class="heading">
        <b>Leadership & Involvement</b>
      </h2>
    </div>
    <div class="inner-content">
      <h3 class="heading">
        <b>Sinclair Cares & Salvation Army - Your Neighbor Needs You</b>
      </h3>

      <p class="paragraph">
        Sinclair Cares: Your Neighbor Needs You is a COVID-19 relief fundraising
        partnership between Sinclair Broadcast Group and The Salvation Army. In
        addition to matching donations up to $100,000, Sinclair also produced
        over 240 unique stories across over 80 news stations.
      </p>
      <p class="paragraph">
        Support was provided directly into your local communities, helping The
        Salvation Army deliver food, shelter, and hope.
      </p>
      <p class="paragraph">
        My duty was to produce a commercial to promote the campaign suitable for
        broadcast via television.
        <a
          style="color: #0000f6;"
          href="https://youtu.be/QB2n0jRfSnE"
          target="_blank"
        >
          Click here to view the campaign!</a
        >
      </p>
    </div>

    <div class="inner-content">
      <h3 class="heading">
        <b>Triad Cultural Arts, Inc. Juneteenth Festival Live</b>
      </h3>

      <p class="paragraph">
        Triad Cultural Arts, Inc. (TCA) was founded in 2007 as a nonprofit,
        community based, multi-disciplinary cultural arts organization. A leader
        in bringing recognition to Black American history and culture, TCA is
        dedicated to presenting programming that contributes to a culturally
        competent community so that significant and lasting improvements can be
        made in our society.
      </p>

      <p class="paragraph">
        Culturally immersive experiences including festivals, tours, and special
        events are sponsored to preserve, interpret, and exhibit the heritage of
        Black Americans – for all people.
      </p>
      <p class="paragraph">
        My duty was to orchestrate the live stream event and promote it on MY48
        Television.
        <a
          style="color: #0000f6;"
          href="https://youtu.be/-skAHrU_EyI"
          target="_blank"
          >You can view the promotion here!
        </a>
      </p>
    </div>

    <div class="inner-content">
      <h3 class="heading"><b>Honda Dealers of the Carolinas</b></h3>
      <p class="paragraph">
        Create a promotion for television to promote the honda model clearance
        pricing.
      </p>
      <p class="paragraph">
        <a
          style="color: #0000f6;"
          href="https://youtu.be/vZCnn13tAGE"
          target="_blank"
          >You can view the promotion here!</a
        >
      </p>
    </div>

    <div class="inner-content">
      <h3 class="heading"><b>Web Developer</b></h3>
      <p class="paragraph">
        As a web developer, I have also had a lot of chances to practice and
        participate in projects to further hone my skills. I have plenty of
        experience with Html & CSS as well as databases using SQL solutions. But
        most of my time is dedicated to frontend development using Vuejs and
        elaborate styling of websites (such as this one 😁).
      </p>
    </div>

    <div class="inner-content">
      <h3 class="heading"><b>UI/UX Designer</b></h3>
      <p class="paragraph">
        Fullstack development is very sought after nowadays and I have made sure
        to keep up with such trends by honing my skills in UI/UX design as well.
        I am thankful for the various opportunities I have had to work alongside
        industry expert and have also taken the chance to learn and hone my
        UI/UX design skills with tools such as Figma.
      </p>
    </div>
    <!-- 
    <div class="inner-content">
      <h3 class="heading"><b>Résumé</b></h3>
      <a
        style="color: #0000f6;"
        href="/files/John_Gutierrez_Resume.pdf"
        class="paragraph"
        >Check out my résumé here.</a
      >
    </div> -->
  </div>
</template>

<style scoped>
.badge-grid {
  display: table;
  align-items: center;
  margin-top: 20px;
}

.badge {
  width: auto;
  height: 20px;
  border-radius: 0px;
  font-size: 12px;
  padding-right: 10px;
  /* box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.12), 0 6px 20px 0 rgba(0, 0, 0, 0.1); */
}

.self {
  width: 100%;
  height: auto;
  /* border-radius: 5px; */
}

.subtitle {
  font-size: 12px;
  color: gray;
}

.heading {
  padding-bottom: 5px;
}

.header {
  padding-top: 20px;
  padding-bottom: 20px;
}

.inner-content {
  padding-top: 30px;
}

h2,
h4,
h3 {
  padding: 0;
  margin: 0;
}
</style>
