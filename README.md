# lusineavetisyan.github.io
personal profile
<!DOCTYPE html>
<html>
<head>
  <style>
.page-top {
  background-color: darkgrey;
  height: 50px;
  width: 100%;
  text-align: center;
  padding-top: 1%;
  position: absolute;
  left: 0;
}

.page-footer {
  background-color: darkgrey;
  width: 100%;
  text-align: center;
  left: 0;
  clear: both;
  height: 70px;
  position: fixed;
  bottom: 0;
}

.body-color {
  background: grey;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  min-height: 80vh;
  font-family: Montserrat, sans-serif;
}

nav a {
  font-size: 40px;
  color: #fff;
  text-decoration: none;
  padding: 20px;
  text-align: center;
}

nav {
  position: fixed;
  left: 0;
  z-index: 50;
  display: flex;
  justify-content: space-around;
  flex-direction: column;
  height: 80vh;
}

section {
  position: absolute;
  top: 0;
  height: 80vh;
  width: 0;
  opacity: 0;
  transition: all ease-in .5s;
  display: flex;
  justify-content: center;
  align-items: center;
}

section h1 {
  color: #fff;
  font-size: 50px;
  text-transform: uppercase;
  opacity: 0;
}

/* Styles applied on trigger */
section:target {
  opacity: 1;
  position: absolute;
  left: 0;
  top: 7%;
  width: 100%;
  height: 80%;
  z-index: 10;
}

section:target h1 {
  opacity: 0;
  animation: 2s fadeIn forwards .5s;
}

#first {
  background: #EEC5DC;
}

#second {
  background: #A3D0C8;
}

#third {
  background: #EAE7BB;
}

#fourth {
  background: #CCBACF;
}

@keyframes fadeIn {
  100% {
    opacity: 1
  }
}

.contacts {
  width: 150px;
  height: 150px;
  background: darkgrey;
  margin: 3% 5% 2% 5%;
  display: inline-grid;
  color: #fff;
  font-size: 50px;
  text-transform: uppercase;

}

.profile-description {
  width: 350px;
  height: 350px;
  background: darkgrey;
}

.content {
  height: 250px;
  width: 385px;
  float: left;
  margin: 10% 0 0 40%;
}

.fit-picture {
  width: 400px;
}

.about-me {
  margin-right: 50px;
  margin-left: 215px;
  margin-top: 80px;
  border-radius: 100%;
  width: 300px;
  height: 400px;
  align: center;
}

.about-me2 {
  margin-right: 100px;
  margin-left: 50px;
  margin-top: 80px;
  border-radius: 100%;
  width: 300px;
  height: 400px;
  align: right;
}

.education-info {
  margin-left: 400px;
  margin-bottom: 500px;
}

.about-me-info {
  width: 316px;
}

.demo-wrap {
  margin-bottom: 92px;
  margin-left: 320px;
}

.demo-bg {
  opacity: 0.6;
  position: absolute;
  width: 370px;
  height: 370px;
}

.demo-content {
  position: relative;
  margin: 65px 0 0 41px;
}

.work-info {
  width: 300px;
  height: 300px;
  color: black;
  text-align: center;
}

a:link, a:visited {
  background-color: grey;
  color: white;
  padding: 14px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}

a:hover, a:active {
  background-color: grey;
}

.personal-info {
  text-align: center;
}

  </style>
</head><header>
  <div class="page-top">Lusine Avetisyan</div>
</header>
<body class="body-color">
<div>
  <nav class="slidebar">
    <a href="#first">HOME</a>
    <a href="#second">ABOUT ME</a>
    <a href="#third">EXPERIENCE</a>
    <a href="#fourth">CONTACTS</a>
  </nav>
  <div class="content">
    <h1>Lusine Avetisyan Portfolio</h1>
  </div>
</div>
<div class='container'>
  <section id='first'>
    <div class="profile-info">
      <h1>Hello, I am Lusi</h1>
      <h2>A student at LCC International University</h2>
    </div>
    <div class="profile-description">
      <img class="no-roundness" src="C:\Users\user\Desktop\Pictures\68472742_861152584255474_8049311566505443328_o.jpg"
           alt="Flex Picture" width="400" height="401" align="center"/>
    </div>
  </section>
  <section id='second'>
    <img src="C:\Users\user\Desktop\Pictures\IMG_5860.jpg" class="about-me">
    <div class="about-me-info">
      <p class="personal-info">
        My name is Lusine Avetisyan, and I am a sophomore at LCC International University.
        I am majoring in contemporary communications and hope to work in the film industry in the future.
        I am completely obsessed with photography, filming, and editing. The "Flex" program is one of the most
        significant aspects of my life.
        It provided me with the opportunity to spend a year in the United States.
        I grew so much as a person. The second critical factor is LCC.
        This is where my obsessions and interests collide. To get to know me well, you need know that my main pleasure
        is traveling.
        Exploring cultures is the most enjoyable thing in the world.
      </p>
    </div>
    <img src="C:\Users\user\Desktop\Pictures\IMG_6363.JPG" class="about-me2">
  </section>
  <section id='third'>
    <div class="demo-wrap">
      <h1>Work experience</h1>
      <img
        class="demo-bg"
        src="C:\Users\user\Desktop\Pictures\IMG_0728.jpg"
        alt="">
      <div class="demo-content">
        <p class="work-info"> I have been working in filmmaking since 2018.I have worked on video clips for various
          celebs.
          Now I work as a media specialist for an international corporation in Klaipeda.
          I increased my customer service, content development, and audience targeting abilities.
          In addition, I have photography and videographing skills that may be useful for the work.
          I stood out because of my great communication and quick learning ability while building these talents.
          My ambition is to continue applying these talents as a communication manager
          while also learning new ones in both media management and customer service.
        </p>
      </div>
    </div>
    <div class="demo-wrap">
      <h1>Volunteering Experience</h1>
      <img
        class="demo-bg"
        src="C:\Users\user\Desktop\Pictures\IMG_20190518_070546.jpg"
        alt="">
      <div class="demo-content">
        <p class="work-info"> Throughout all my life I have been volunteering in many companies and organizations.
          One of the broadest examples of these is when I was volunteering in the United States and actually got 100+
          hours.
          I have helped children to learn English. I had a few clubs for this.
          I helped Armenian army to gather food and supplies. Even tho I am studying and working now I still do my best
          to help people.
          Volunteering is such an amazing way to grow up and develeop as a person.
          In adiition I always try to encourage my friends to do the same.
        </p>
      </div>
    </div>
  </section>

  <section id='fourth'>

    <div class="contacts">
      <a href="file:///C:/Users/user/Desktop/final%20resume-CV,LA%201-.pdf">Link to Resume</a>
    </div>
    <div class="contacts">

      <a href="https://www.facebook.com/profile.php?id=100010822202909">Link to FaceBook</a>
    </div>
  </section>
</div>
</body>
<footer>
  <div class="page-footer">Lusi, October 11, 2022</div>
</footer>
</html>

