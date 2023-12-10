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
      <div class="logo">Abinaya Elangovan</div>
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
      <div class="logo">Abinaya Elangovan</div>
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
        <h1 class="title">Abinaya Elangovan</h1>
        <p class="section__text__p2">Cloud Computing Student</p>
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
              <p>2+ years <br>Systems Engineer</p>
            </div>
            <div class="details-container">
              <img src="./assets/education.png" alt="Education icon" class="icon">
              <h3>Education</h3>
              <p>Bachelor's in Computer Science | Anna University (2021), Chennai, India<br>Postgraduate's in Cloud Computing | Durham College (2024), Oshawa, Canada</p>
            </div>
          </div>
          <div class="text-container">
            <p>
               Experienced IT professional with expertise in Microsoft PowerPoint, Python, Amazon Web Services (AWS), Microsoft Excel, Carbonite, SRM, VMware, and VMWare ESXi. Experience varies from creating captivating PowerPoint presentations to utilizing the power of Python for programming jobs. Also, excel at data analysis with Microsoft Excel and have a solid foundation in data backup technologies such as Carbonite. Knowledge includes SRM for disaster recovery and VMware virtualization technologies such as VMWare ESXi. Excited about applying these skills to drive IT innovation and efficiency.
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
            <h2 class="experience-sub-title">Systems Engineer</h2>
            <div class="article-container">
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>VMotion</h3>
                </div>
              </article>
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>AWS</h3>
              
                </div>
              </article>
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>Azure</h3>
             
                </div>
              </article>
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>Nutanix</h3>
          
                </div>
              </article>
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>Disaster recovery</h3>
                  
                </div>
              </article>
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>VMWare</h3>
             
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
                  <h3>JavaScript</h3>
              
                </div>
              </article>
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>C programming</h3>
               
                </div>
              </article>
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>HTML</h3>
          
                </div>
              </article>
              <article>
                <img src="./assets/checkmark.png" alt="Experience icon" class="icon">
                <div>
                  <h3>CSS</h3>
                 
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

            <h2 class="experience-sub-title project-title">Sify Technologies Limited - 
              Systems Engineert</h2>
            <div class="btn-container">
              <p>Played a pivotal role in Installing, configuring, and maintaining Windows Server operating systems and network services. Designing, implementing, and managing the network infrastructure, including LANs and WANs. Further, I have experience in Devops, and object-oriented programming.

</p>
        
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
          <p><a href="mailto:examplemail@gmail.com">abinayaelangovan26@gmail.com</a></p>
        </div>
        <div class="contact-info-container">
          <img src="./assets/linkedin.png" alt="LinkedIn icon" class="icon contact-icon">
          <p><a href="https://www.linkedin.com/in/abinaya-elangovan-5993321b6/">LinkedIn</a></p>
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
      <p>Copyright © 2023 Abinaya Elangovan. All Rights Reserved.</p>
    </footer>
    <script src="script.js"></script>
  

</body></html>
