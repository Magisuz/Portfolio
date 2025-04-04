!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Professional Portfolio</title>
    <meta name="description" content="Professional Portfolio Site" />
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
  </head>
  <body>
    <header>
      <div class="container">
        <nav id="navbar">
          <h1 class="logo">My Portfolio</h1>
          <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#interests">Interests</a></li>
            <li><a href="#contact">Contact</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <section id="hero">
      <div class="container">
        <div class="hero-content">
          <h1>Welcome to My Portfolio</h1>
          <p>Web Developer & Database Specialist</p>
          <a href="#contact" class="btn">Get in Touch</a>
        </div>
      </div>
    </section>

    <section id="about">
      <div class="container">
        <h2 class="section-title">About Me</h2>
        <div class="about-content">
          <div class="about-img">
            <div class="img-placeholder">
                <img src="me.jpeg" alt="Image Description" style="width: 100%; height: auto; border-radius: 8px;">
            </div>
            
            
          </div>
          <div class="about-text">
            <p>Hello! I'm a passionate web developer with expertise in HTML, CSS, and MySQL. I enjoy creating responsive and user-friendly websites that solve real-world problems.</p>
            <p>With a strong foundation in front-end development and database management, I strive to build applications that are both functional and aesthetically pleasing.</p>
            <p>My goal is to continue growing as a developer and contribute to meaningful projects that make a difference.</p>
          </div>
        </div>
      </div>
    </section>

    <section id="skills">
      <div class="container">
        <h2 class="section-title">Skills</h2>
        <div class="skills-container">
          <div class="skill-card">
            <h3>HTML</h3>
            <div class="skill-bar">
              <div class="skill-level" style="width: 90%"></div>
            </div>
            <p>Semantic HTML, Accessibility, Forms</p>
          </div>
          <div class="skill-card">
            <h3>CSS</h3>
            <div class="skill-bar">
              <div class="skill-level" style="width: 85%"></div>
            </div>
            <p>Responsive Design, Flexbox, Grid, Animations</p>
          </div>
          <div class="skill-card">
            <h3>MySQL</h3>
            <div class="skill-bar">
              <div class="skill-level" style="width: 80%"></div>
            </div>
            <p>Database Design, CRUD Operations, Optimization</p>
          </div>
        </div>
      </div>
    </section>

    <section id="education" class="dark-section">
      <div class="container">
        <h2 class="section-title">Education</h2>
        <div class="timeline">
          <div class="timeline-item">
            <div class="timeline-content">
              <h3>Diploma Information Technology</h3>
              <p class="timeline-date">2011-2013</p>
              <p>TECHNICAL UNIVERSITY OF KENYA </p>
              <p>Studied core computer science principles, database management, and web development technologies.</p>
            </div>
          </div>
          <div class="timeline-item">
            <div class="timeline-content">
              <h3>Computer Studies</h3>
              <p class="timeline-date">2009-2010</p>
              <p>Kenya Polytechnic University College</p>
              <p>Introduction to Computer Technology and basics</p>
            </div>
          </div>
        </div>
        
        <!-- CV Download Section -->
        <div class="cv-section">
          <h3>My Curriculum Vitae</h3>
          <p>Download my complete CV to learn more about my experience and qualifications.</p>
          <a href="cv.pdf" download class="btn cv-btn">
            
            <i class="fas fa-download"></i> Download CV
          </a>
        </div>
      </div>
    </section>

    <section id="projects">
      <div class="container">
        <h2 class="section-title">Projects</h2>
        <div class="projects-grid">
          <div class="project-card">
            <div class="project-img">
              <img src="python.jpg" alt="Python photo" style="width: 100%; height: 200px; border-radius: 8px;">
            <h3>Python projects</h3>
            <p>Simple and clean Python projects.</p>
            <p class="tech-stack">python</p>
            <a href="#" class="btn-small">View Project</a>
          </div>
          </div>
          <div class="project-card">
            <div class="project-img">
            <img src="sql.jpg" alt="Python photo" style="width: 100%; height: 200px; border-radius: 8px;">
            <h3>Data Base</h3>
            <p>A well elaborated SQL codes.</p>
            <p class="tech-stack">SQL</p>
            <a href="#" class="btn-small">View Project</a>
          </div>
          </div>
          <div class="project-card">
            <div class="project-img"></div>
            <h3>Simple HTML and CSS codes</h3>
            <p>A well simple structured HTML and CSS codes.</p>
            <p class="tech-stack">HTML, CSS</p>
            <a href="#" class="btn-small">View Project</a>
          </div>
          </div>
      </div>
    </section>

    <section id="interests">
      <div class="container">
        <h2 class="section-title">Interests</h2>
        <div class="interests-container">
          <div class="interest-item">
            <h3>Web Development</h3>
            <p>Exploring new frameworks and techniques for building modern websites.</p>
          </div>
          <div class="interest-item">
            <h3>Database Design</h3>
            <p>Creating efficient and scalable database structures for various applications.</p>
          </div>
          <div class="interest-item">
            <h3>UI/UX Design</h3>
            <p>Studying user experience principles to create intuitive interfaces.</p>
          </div>
          <div class="interest-item">
            <h3>Open Source</h3>
            <p>Contributing to community projects and learning from collaborative development.</p>
          </div>
        </div>
      </div>
    </section>

    <section id="contact">
      <div class="container">
        <h2 class="section-title">Contact Me</h2>
        <div class="contact-container">
          <div class="contact-info">
            <div class="contact-item">
              <h3>Email</h3>
              <p>magisuz@gmail.com</p>
            </div>
            <div class="contact-item">
              <h3>Phone</h3>
              <p>+254 712 537180</p>
            </div>
            <div class="contact-item">
              <h3>Location</h3>
              <p>Mombasa, Kenya</p>
            </div>
          </div>
          <div class="contact-form">
            <form>
              <div class="form-group">
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>
              </div>
              <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>
              </div>
              <div class="form-group">
                <label for="message">Message</label>
                <textarea id="message" name="message" rows="5" required></textarea>
              </div>
              <button type="submit" class="btn">Send Message</button>
            </form>
          </div>
        </div>
      </div>
    </section>

    <footer class="dark-section">
      <div class="container">
        <p>&copy; 2025 My Portfolio. All Rights Reserved.</p>
        <div class="social-links">
          <a href="https://www.linkedin.com/in/esperanza-margaret-susan-akinyi-37855a68/" class="social-link"><i class="fab fa-linkedin"></i></a>
          <a href="https://github.com/Magisuz"class="social-link"><i class="fab fa-github"></i></a>
          <a href="https://x.com/magisuz" class="social-link"><i class="fab fa-twitter"></i></a>
        </div>
      </div>
    </footer>
    
    <script src="https://cdn.gpteng.co/gptengineer.js" type="module"></script>
  </body>
</html>
