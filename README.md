# SHAPEAI WEB DEV BOOTCAMP
Hi I made this project during the 7 Days Free Bootcamp, conducted by <b> SHAPEAI
</b>.
The instructor during the session was Mr. Shaurya Sinha (Data Analyst Intern at Jio). I got to
learn a lot during these 7 days and it was an amazing experience learning with SHAPEAI.
<br><br>Here's the link for you to watch the sessions as well<br>
<a href="https://youtube.com/playlist?list=PL7zl8TDRnbun7K0fECtSMCI2hOCgLBy9a"> <img src="https://github.com/ShapeAI/PYTHON-AND-DATA-ANALYTICS/blob/main/WebD%20poster.png"> </a>
<br>I got to have hands on experience on:
<li>HTML
<li>CSS
<br>during these 7 days, and everything was explained from the very basics so that
anyone with zero experience on programming can learn.
I enjoyed these 7 days, you can as well. To register for next free 7 days bootcamp, visit:
www.shapeai.tech
or follow SHAPEAI on:
<li><a href=
"https://in.linkedin.com/company/shapeai">LinkedIn</a>
<li><a href=
"https://www.instagram.com/shape.ai/?hl=en">Instagram</a>
<li><a
href=
"https://www.youtube.com/channel/UCTUvDLTW9meuDXWcbmISPdA">YouTu
be</a>
<li><a href=
"https://github.com/shapeai">GitHub</a>


<!DOCTYPE html>
<html>
<head>
  <title>Arthika Portfolio</title>
  <style>
    @charset "UTF-8";

*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Montserrat", sans-serif;
}

/* Navigation section */

.nav {
  background-color: #248b7a;
  padding: 20px;
}

.nav-ul {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  list-style: none;
  font-weight: bold;
}

.nav-ul li > a {
  text-decoration: none;
  color: #ffffff;
}

.nav-ul li {
  margin-left: 40px;
}

/* Hero section */

.hero {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: #c6f1ea;
  min-height: 25rem;
}

.hero__title {
  font-size: 5rem;
  font-weight: bold;
  color: #248b7a;
}

.hero__subtitle {
  font-size: 2.5rem;
  font-weight: normal;
  color: #248b7a;
}

.hero__social {
  font-size: 2.5rem;
  color: #248b7a;
}
.hero__social .fab {
  margin-top: 20px;
  margin-left: 20px;
  transition: all 0.2s ease-in-out;
}

.hero__social .fab:hover {
  transform: scale(1.1);
}

.hero__social > a {
  text-decoration: none;
  color: #248b7a;
}

/* About section  */

#about {
  min-height: 25rem;
}

#about > h1 {
  text-align: center;
  font-size: 2.5rem;
  color: #248b7a;
  margin: 2.5rem 1.875rem;
}

.about__row {
  display: flex;
  flex-direction: row;
  margin: 3.125rem 3.125rem;
}

.about__col-2--avatar {
  flex-basis: 50%;
  min-width: 300px;
}

.about__col-2--avatar img {
  border-radius: 50%;
  width: 200px;
  margin-left: 50px;
}

.about__col-2--txt p {
  font-size: 1.125rem;
  line-height: 1.563rem;
}

/* project section */

#projects {
  min-height: 50rem;
  background: #c6f1ea;
  padding-bottom: 1.25rem;
}

#projects > h1 {
  text-align: center;
  font-size: 2.5rem;
  color: #248b7a;
  padding-top: 3.125rem;
}

.projects__row {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  margin: 3.125rem 3.125rem;
}

.projects__col-2--project-img {
  flex-basis: 40%;
  min-width: 18.75rem;
}

.projects__col-2--project-img img {
  max-width: 100%;
  max-height: 100%;
  box-shadow: 14px 10px 42px -5px rgba(192, 186, 186, 0.79);
}

.projects__col-2--title {
  width: 37.5rem;
}
.projects__col-2--title h2 {
  text-align: center;
  color: #248b7a;
}

.projects__col-2--title p {
  font-size: 1.125rem;
  line-height: 1.563rem;
  text-align: left;
}

.projects--github-link a {
  display: inline-block;
  margin-top: 20px;
  padding-left: 150px;
  text-decoration: none;
  font-weight: bold;
  color: #248b7a;
}

/* contact section */

#contact {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: #ffffff;
  min-height: 11rem;
}

.contact__title {
  font-size: 2.5rem;
  font-weight: bold;
  color: #248b7a;
}

.contact__email {
  font-size: 1.125rem;
  margin-top: 1.25rem;
}

.contact__email a {
  text-decoration: none;
  color: #248b7a;
  font-weight: bold;
}

/* footer section */

.footer {
  display: flex;
  flex-direction: column;
  min-height: 18rem;
  background: #c6f1ea;
}

.footer__nav {
  text-align: center;
  font-size: 1.5rem;
  margin-top: 3.75rem;
}
.footer__nav--ul li {
  display: inline-block;
  margin-left: 1.875rem;
}

.footer__nav--ul a {
  text-decoration: none;
  font-weight: bold;
  color: #248b7a;
}

.footer__copyright {
  text-align: center;
  font-size: 1.125rem;
  margin-top: 1.25rem;
}

.footer__social {
  text-align: center;
  font-size: 2rem;
  color: #248b7a;
}

.linkedin{
  height: 30px;
}

.footer__social .fab {
  margin-top: 20px;
  margin-left: 15px;
  transition: all 0.2s ease-in-out;
}

.footer__social .fab:hover {
  transform: scale(1.1);
}

.footer__social > a {
  text-decoration: none;
  color: #248b7a;
}

/* media queries */

@media (min-width: 481px) and (max-width: 767px) and (orientation: landscape) {
  /* About section  */

  #about > h1 {
    display: none;
  }

  .about__row {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    margin: 3.125rem 3.125rem;
  }

  .about__col-2--avatar img {
    border-radius: 50%;
    width: 160px;
    margin-left: 13.75rem;
    margin-top: -6.875rem;
  }

  .about__col-2--txt p {
    margin-top: 1.875rem;
    font-size: 1.125rem;
    line-height: 1.563rem;
  }

  /* project section */

  .projects__row {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
    margin: 3.125rem 3.125rem;
  }

  .projects__col-2--project-img {
    flex-basis: 40%;
    min-width: 18.75rem;
    order: 1;
    margin-left: 150px;
    margin-top: 20px;
  }

  .projects__col-2--project-img img {
    max-width: 90%;
    max-height: 90%;
    box-shadow: 14px 10px 42px -5px rgba(192, 186, 186, 0.79);
  }
}

/* 
 Mostly all smartphones
*/

@media (max-width: 576px) {
  #about > h1 {
    display: none;
  }

  .about__row {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    margin: 3.125rem 3.125rem;
  }

  .about__col-2--avatar img {
    border-radius: 50%;
    width: 160px;
    margin-left: 8.75rem;
    margin-top: -6.875rem;
  }

  .about__col-2--txt p {
    margin-top: 1.875rem;
    font-size: 1.125rem;
    line-height: 1.563rem;
  }

  /* project section */

  .projects__row {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
    margin: 3.125rem 3.125rem;
  }

  .projects__col-2--project-img {
    flex-basis: 40%;
    min-width: 18.75rem;
    order: 1;
    margin-left: 50px;
    margin-top: 20px;
  }

  .projects__col-2--project-img img {
    max-width: 90%;
    max-height: 90%;
    box-shadow: 14px 10px 42px -5px rgba(192, 186, 186, 0.79);
  }
}

  </style>
</head>
<body>
<!-- header section -->
<section id="header">
  <nav class="nav">
    <ul class="nav-ul">
      <li><a href="#header">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#contact">Contact</a></li>
      <li><a href="#projects">Certifications</a></li>
    </ul>
  </nav>
</section>

<!-- Hero section -->
<section class="hero">
  <h1 class="hero__title">Arthika G</h1>
  <h2 class="hero__subtitle">Web Developer</h2>
  <div class="hero__social">
    <a href="https://www.linkedin.com/in/arthikag/" target="_blank"><img class="linkedin" src="https://lh3.googleusercontent.com/proxy/_PplJuOQQwlQRcdx80xRqbmec267hfrCvRAUKie67z2IaXzp2incZAQk04rC5WQSYEHBdNS9Ocznkgn_a_uvDvOawzW-wIuw79pfg5O85rAdmol-ikU3WF7Hd28cRqwOTOk"></a>
    <a href="https://github.com/arthikag" target="_blank"><img class="linkedin" src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png"></a>
    <a href="https://twitter.com/ArthikaGanesan" target="_blank"><img class="linkedin" src="http://assets.stickpng.com/images/580b57fcd9996e24bc43c53e.png"></a>
    <a href="https://devpost.com/20eucs015" target="_blank"><img class="linkedin" src="https://img.favpng.com/11/23/21/logo-computer-icons-font-png-favpng-vb1Rt9tabfa32j3PAZkpYEzqR_t.jpg"></a>
    <a href="https://drive.google.com/file/d/1zR0wl9JlgKPdSt5YuyGATGLXd1cEIgTp/view" target="_blank"><img class="linkedin" src="https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/a821629507501.560d4c2a6b211.png"></a>
  </div>
</section>

<!-- About section -->

<section id="about">
  <h1>About</h1>
  <div class="about__row">
    <div class="about__col-2--avatar">
      <img src="https://avatars.githubusercontent.com/u/74757067?s=400&u=78c2d6332fe43deeed36c04b9d5860f9661930cf&v=4" alt="ArthikaGanesan" />
    </div>
    <div class="about__col-2--txt">
      <p>
        I've have been and always will be fascinated by the creativity I can usher &experience first hand whenever I lay my hands on the key pad to code. 
      </p>
      <br />
      <p>
        It helps me unlock an ardent and a passionate side of me which I enjoy, Always seeking to learn new concepts and things as much as I can and wish to grow as much in this dimension of freedom I enjoy the most! 
      </p>
    </div>
  </div>
</section>
<!-- projects section -->
<section id="projects">
  <h1>Certifications</h1>
  <div class="projects__row">
    <div class="projects__col-2--project-img">
      <img src="https://media-exp1.licdn.com/dms/image/sync/C4D27AQFFwvf7DgzTig/articleshare-shrink_800/0/1619237974409?e=1619676000&v=beta&t=AHfrS0ATOeOSaMGjhwPPWufSFCIdBe746Pn8QhlVFYc" alt="" />
    </div>
    <div class="projects__col-2--title">
      <h2>Coursera  Python Basics</h2>
      <br />
      <p>
        University of Michigan - Python Basics
      </p>
      <div class="projects--github-link">
        <a href="https://github.com/arthikag">
          <p>GitHub</p>
        </a>
        <a href="https://github.com/arthikag">
          <p>Demo</p>
        </a>
      </div>
    </div>
  </div>

  <div class="projects__row">
    <div class="projects__col-2--title">
      <h2>GUVI - Face Recognition Application</h2>
      <br />
      <p>
       GUVI Geek Networks, IITM Research Park - Python completion certificate
Issued on - 27 March 2021 #guvi #python<br>
Build a Face Recognition Application using Python
      </p>
      <div class="projects--github-link">
        <a href="https://github.com/arthikag">
          <p>GitHub</p>
        </a>
        <a href="https://github.com/arthikag">
          <p>Demo</p>
        </a>
      </div>
    </div>
    <div class="projects__col-2--project-img">
      <img src="https://media-exp1.licdn.com/dms/image/C4D22AQGdNr4IVMhJUQ/feedshare-shrink_800/0/1618908471784?e=1622678400&v=beta&t=k5HL_0ytO0p-msbVfgv94TuP3vL2n8HTwM9-YnAH710" alt="" />
    </div>
  </div>

  <div class="projects__row">
    <div class="projects__col-2--project-img">
      <img src="https://media-exp1.licdn.com/dms/image/C4D22AQFDV-_Ha2N8iQ/feedshare-shrink_800/0/1608125251054?e=1622678400&v=beta&t=z_jgQSJ9wvtT1mtr7x6lWVbJvYxZsqfRUw6Bjhs8VaM" alt="" />
    </div>
    <div class="projects__col-2--title">
      <h2>Amazon Web Services Cloudcomputing service</h2>
      <br />
      <p>
        Hello everyone view my Verified achievement from Amazon Web Services (AWS) Digital Badge Credentials#cloudcomputing service #badge
      </p>
      <div class="projects--github-link">
        <a href="https://github.com/arthikag">
          <p>GitHub</p>
        </a>
        <a href="https://github.com/arthikag">
          <p>Demo</p>
        </a>
      </div>
    </div>
  </div>

  <div class="projects__row">
    <div class="projects__col-2--title">
      <h2>Amazon Web Services Inventor</h2>
      <br />
      <p>
        Hello everyone view my Verified achievement from Amazon Web Services (AWS) Digital Badge Credentials#Inventor #badge
      </p>
      <div class="projects--github-link">
        <a href="https://github.com/arthikag">
          <p>GitHub</p>
        </a>
        <a href="https://github.com/arthikag">
          <p>Demo</p>
        </a>
      </div>
    </div>
    <div class="projects__col-2--project-img">
      <img src="https://media-exp1.licdn.com/dms/image/C4D22AQFnkkSKUQC7Yg/feedshare-shrink_800/0/1608125189740?e=1622678400&v=beta&t=0rm0jxmvvhCEFHozGB7ukX1ya77xHtNmxB_mAHR3_os" alt="" />
    </div>
  </div>
</section>
<!-- contact section -->
<section id="contact">
  <h1 class="contact__title">Contact</h1>
  <p class="contact__email">
    Email me at
    <a href="mailto:arthika7777@gmail.com?subject=Hello! Arthika">arthika7777@gmail.com</a>.
  </p>
</section>
<!-- footer section -->
<section class="footer">
  <nav class="footer__nav">
    <ul class="footer__nav--ul">
      <li><a href="#header">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
    </ul>
  </nav>
  <p class="footer__copyright">Copyright &copy; 2021</p><br>
  <div class="footer__social">
    <a href="https://www.linkedin.com/in/arthikag/" target="_blank"><img class="linkedin" src="https://lh3.googleusercontent.com/proxy/_PplJuOQQwlQRcdx80xRqbmec267hfrCvRAUKie67z2IaXzp2incZAQk04rC5WQSYEHBdNS9Ocznkgn_a_uvDvOawzW-wIuw79pfg5O85rAdmol-ikU3WF7Hd28cRqwOTOk">
    <a href="https://github.com/arthikag" target="_blank"><img class="linkedin" src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png"></a>
    <a href="https://twitter.com/ArthikaGanesan" target="_blank"><img class="linkedin" src="http://assets.stickpng.com/images/580b57fcd9996e24bc43c53e.png"></a>
    <a href="https://devpost.com/20eucs015" target="_blank"><img class="linkedin" src="https://img.favpng.com/11/23/21/logo-computer-icons-font-png-favpng-vb1Rt9tabfa32j3PAZkpYEzqR_t.jpg"></a>
  </div>
</section>
</body>
</html>
