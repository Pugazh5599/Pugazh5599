<html lang="en"><head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="mediaqueries.css">
  </head>
  <body>
    <nav id="desktop-nav">
      <div class="logo">Kevin Leander Louis Amalraj</div>
      <div>
        <ul class="nav-links">
          <li><a href="#about">About</a></li>
          <li><a href="#experience">Skills</a></li>
          <li><a href="#projects">Experience</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </div>
    </nav>
    <nav id="hamburger-nav">
      <div class="logo">Kevin Leander Louis Amalraj</div>
      <div class="hamburger-menu">
        <div class="hamburger-icon" onclick="toggleMenu()">
          <span></span>
          <span></span>
          <span></span>
        </div>
        <div class="menu-links">
          <li><a href="#about" onclick="toggleMenu()">About</a></li>
          <li><a href="#experience" onclick="toggleMenu()">Skills</a></li>
          <li><a href="#projects" onclick="toggleMenu()">Experience</a></li>
          <li><a href="#contact" onclick="toggleMenu()">Contact</a></li>
        </div>
      </div>
    </nav>
    <section id="profile">
      <div class="section__pic-container">
        <img src="./assets/profile-pic.png" alt="KL profile picture">
      </div>
      <div class="section__text">
        <p class="section__text__p1">Hello, I'm</p>
        <h1 class="title">Kevin Leander Louis Amalraj</h1>
        <p class="section__text__p2">Mainframe Modernization Analyst</p>
        <div class="btn-container">
          <button class="btn btn-color-2" onclick="window.open('./assets/kevin_resume.pdf')">
            Download CV
          </button>
          <button class="btn btn-color-1" onclick="location.href='./#contact'">
            Contact Info
          </button>
        </div>
        <div id="socials-container">
          <img src="./assets/linkedin.png" alt="My LinkedIn profile" class="icon" onclick="location.href='https://www.linkedin.com/in/kevin-leander-louis-5199b6237/">
          <img src="./assets/github.png" alt="My Github profile" class="icon" onclick="location.href='https://github.com/'">
        </div>
      </div>
    </section>
    <section id="about">
      <p class="section__text__p1">Get To Know More</p>
      <h1 class="title">About Me</h1>
      <div class="section-container">
        <div class="section__pic-container">
          <img src="./assets/about-pic.jpeg" alt="Profile picture" class="about-pic">
        </div>
        <div class="about-details-container">
          <div class="about-containers">
            <div class="details-container">
              <img src="./assets/experience.png" alt="Experience icon" class="icon">
              <h3>Experience</h3>
              <p>10+ years <br>Mainframe Development</p>
            </div>
            <div class="details-container">
              <img src="./assets/education.png" alt="Education icon" class="icon">
              <h3>Education</h3>
              <p>Bachelor's in Mechnical Engineering | Anna University (2013), Chennai, India<br>Postgraduate's in Cloud Computing | Durham College (2024), Oshawa, Canada</p>
            </div>
          </div>
          <div class="text-container">
            <p>
              Dynamic software development leader known for delivering successful application maintenance and platform migration projects, consistently ensuring customer satisfaction. Over the course of 10-year career, I've showcased expertise in hands-on development and project management, especially in large-scale enterprise initiatives within highly regulated settings. Extensive experience encompasses IBM Mainframes, with a strong command of COBOL, JCL, and DB2
            </p>
          </div>
        </div>
      </div>
      <img src="./assets/arrow.png" alt="Arrow icon" class="icon arrow" onclick="location.href='./#experience'">
    </section>
    <section id="experience">
      <p class="section__text__p1">Explore My</p>
      <h1 class="title">Skills</h1>
      <div class="experience-details-container">
        <div class="about-containers">
          <div class="details-container">
            <h2 class="experience-sub-title">Mainframe Stack</h2>
            <div class="article-container">
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>COBOL</h3>
                </div>
              </article>
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>JCL</h3>
              
                </div>
              </article>
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>DB2</h3>
             
                </div>
              </article>
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>VSAM</h3>
          
                </div>
              </article>
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>Innowake</h3>
                  
                </div>
              </article>
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>Meta COBOL</h3>
             
                </div>
              </article>
            </div>
          </div>
          <div class="details-container">
            <h2 class="experience-sub-title">Others</h2>
            <div class="article-container">
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>Java</h3>
              
                </div>
              </article>
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>C and C++</h3>
               
                </div>
              </article>
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>Python</h3>
          
                </div>
              </article>
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>Business Rule Mining</h3>
                 
                </div>
              </article>
            </div>
          </div>
        </div>
      </div>
      <img src="./assets/arrow.png" alt="Arrow icon" class="icon arrow" onclick="location.href='./#projects'">
    </section>
    <section id="projects">
      <p class="section__text__p1">Browse My Recent</p>
      <h1 class="title">Experience</h1>
      <div class="experience-details-container">
        <div class="about-containers">
          <div class="details-container color-container">
            <div class="article-container">
              <img src="./assets/project-1.png" alt="Project 1" class="project-img">
            </div>
            <h2 class="experience-sub-title project-title">Deloitte - 
              Mainframe Modernization Analyst</h2>
            <div class="btn-container">
              <p>Played a pivotal role in a mainframe modernization initiative, where
                we harnessed the capabilities of an innovative tool called InnoWake
                •
                This tool facilitated the discovery and mining process, enabling us to
                meticulously discern the intricacies of the existing legacy system's
                application structure
                •
                In doing so, we were able to systematically extract and document
                critical business rules, a process integral to the overarching
                modernization effort.</p>
            </div>
          </div>
          <div class="details-container color-container">
            <div class="article-container">
              <img src="./assets/project-2.png" alt="Project 2" class="project-img">
            </div>
            <h2 class="experience-sub-title project-title"> Wipro - Senior Engineer</h2>
            <div class="btn-container">
              <p>Analysed Java stored procedures and create business logic, input
                validation documents for the same.
                Capitalized on extensive mainframe experience to lead the business
                analysis of this modernization project which created the complete
                application in Java/MongoDB/pivotal cloud from scratch keeping the
                existing mainframe-based application as a reference.
                </p>
            </div>
          </div>
          <div class="details-container color-container">
            <div class="article-container">
              <img src="./assets/project-3.png" alt="Project 3" class="project-img">
            </div>
            <h2 class="experience-sub-title project-title">IBM - Senior Engineer</h2>
            <div class="btn-container">
              <p>To code COBOL programs from scratch for provider application that
                acts as a backbone for a leading healthcare provider in US.</p>

            </div> 
          </div>
          <div class="details-container color-container">
            <div class="article-container">
              <img src="./assets/project-4.png" alt="Project 3" class="project-img">
            </div>
            <h2 class="experience-sub-title project-title">Accenture - Senior Software Engineer</h2>
            <div class="btn-container">
              <p>Worked on enhancement, development and production support for premiums and claims application that acted as a backbone for US based insurance client.</p>
            </div> 
            
        </div>
      </div>
      <img src="./assets/arrow.png" alt="Arrow icon" class="icon arrow" onclick="location.href='./#contact'">
    </div></section>
    <section id="contact">
      <p class="section__text__p1">Get in Touch</p>
      <h1 class="title">Contact Me</h1>
      <div class="contact-info-upper-container">
        <div class="contact-info-container">
          <img src="./assets/email.png" alt="Email icon" class="icon contact-icon email-icon">
          <p><a href="mailto:examplemail@gmail.com">kevinmozilla@gmail.com</a></p>
        </div>
        <div class="contact-info-container">
          <img src="./assets/linkedin.png" alt="LinkedIn icon" class="icon contact-icon">
          <p><a href="https://www.linkedin.com/in/kevin-leander-louis-5199b6237/">LinkedIn</a></p>
        </div>
      </div>
    </section>
    <footer>
      <nav>
        <div class="nav-links-container">
          <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Skills</a></li>
            <li><a href="#projects">Experience</a></li>
            <li><a href="#contact">Contact</a></li>
          </ul>
        </div>
      </nav>
      <p>Copyright © 2023 Kevin Leander Louis Amalraj. All Rights Reserved.</p>
    </footer>
    <script src="script.js"></script>
  

</body></html>
