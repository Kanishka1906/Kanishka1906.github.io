<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Primary Meta Tags -->
    <title>Kanishka Joshi - Portfolio</title>
    <meta name="title" content="Kanishka Joshi" />
    <meta name="description" content="A chapter to my story." />

    <!-- Twitter -->
    <meta property="twitter:card" content="summary_large_image" />
    <meta
      property="twitter:url"
      content="https://github.com/kanishkajoshi/portfolio-html"
    />
    <meta property="twitter:title" content="Kanishka Joshi - Portfolio" />
    <meta
      property="twitter:description"
      content="Explore Kanishka's projects in voice recognition and assistive tech!"
    />
    <meta
      property="twitter:image"
      content="https://user-images.githubusercontent.com/62628408/150613011-b78a7f5a-0af1-4312-aab0-0022e7258693.png"
    />

    <!-- Favicon Links -->
    <link
      rel="apple-touch-icon"
      sizes="180x180"
      href="assets/favicon/apple-touch-icon.png"
    />
    <link
      rel="icon"
      type="image/png"
      sizes="16x16"
      href="/assets/favicon/favicon-16x16.png"
    />
    <link rel="icon" type="image/x-icon" href="assets/favicon/favicon.ico" />
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.15.4/css/all.css"
      crossorigin="anonymous"
    />
    <link rel="stylesheet" href="css/style.css" />
    <link rel="stylesheet" href="css/utilities.css" />
  </head>
  <body>
    <header id="hero">
      <!-- Navbar -->
      <nav class="navbar">
        <div class="container">
          <!-- Logo -->
          <h1 id="logo">
            <img src="./assets/logo.png" alt="Logo" />
          </h1>
          <!-- Navbar links -->
          <ul class="nav-menu">
            <li><a class="nav-link" href="#projects">PROJECTS</a></li>
            <li><a class="nav-link" href="#footer">CONTACT</a></li>
            <li>
              <a
                class="nav-link btn btn-primary"
                href="./assets/res.pdf"
                target="_blank"
                >RESUME <i class="fas fa-arrow-right"></i
              ></a>
            </li>

            <!-- Toggle switch -->
            <div class="theme-switch">
              <input type="checkbox" id="switch" />
              <label class="toggle-icons" for="switch">
                <img class="sun" src="assets/sun.svg" />
                <img class="moon" src="assets/moon.svg" />
              </label>
            </div>
          </ul>
          <div class="hamburger">
            <span class="bar"></span>
            <span class="bar"></span>
            <span class="bar"></span>
          </div>
        </div>
      </nav>

      <section class="header-container">
        <img
          class="profile-image"
          src="assets/biosvgpic.svg"
          alt="Hi, it's me."
        />
        <h1>Hi, I'm Kanishka Joshi</h1>

        <div class="content-text">
          <h2>Shaping the Future with Technology</h2> 
          <h2>One Project at a Time.</h2>

          <p>
            I'm passionate about AI and tech innovation. My work focuses on projects that blend voice recognition, assistive technology, and computer vision to make a real-world impact.
          </p>
        </div>
        <a
          href="#footer"
          class="btn btn-secondary"
          target="_blank"
          >Connect With Me</a
        >
      </section>
    </header>

    <!-- Projects -->
    <section id="projects" class="project-container container">
      <div class="division"></div>
      <div class="content-text">
        <h2>Projects</h2>
        <p>Check out some of my key personal projects</p>
      </div>

      <article class="project">
        <!-- Project 1 -->
        <div class="card">
          <div class="project-info">
            <div class="project-bio">
              <h3>Voice Activated Geo Assistant</h3>
              <p>Voice Recognition, AI, Geo-Location Services</p>
            </div>

            <div class="project-link">
              <a href="#" target="_blank"><i class="fab fa-github"></i></a>
            </div>
          </div>
        </div>

        <!-- Project 2 -->
        <div class="card">
          <div class="project-info">
            <div class="project-bio">
              <h3>Object Detection Glasses for Blind People</h3>
              <p>Computer Vision, Assistive Tech, YOLO</p>
            </div>

            <div class="project-link">
              <a href="#" target="_blank"><i class="fab fa-github"></i></a>
            </div>
          </div>
        </div>
      </article>

      <a href="https://github.com/kanishkajoshi" class="btn btn-secondary"
        target="_blank" >See More <i class="fas fa-arrow-right"></i
      ></a>
    </section>

    <footer id="footer">
      <div class="container">
        <a href="mailto:kanishka.joshi@example.com">kanishka.joshi@example.com</a>
        <!-- Social links -->
        <div class="social">
          <a href="https://www.instagram.com/kanishka._" target="_blank"><img src="./assets/hashnode-icon.svg" alt="Twitter" /></a>
          <a href="https://www.linkedin.com/in/kanishka-joshi" target="_blank"
            ><img src="./assets/linkedin-icon.svg" alt="Linkedin"
          /></a>
          <a href="https://github.com/kanishkajoshi" target="_blank"><img src="./assets/github-icon.svg" alt="GitHub" /></a>
        </div>
        <p>Copyright &copy; Kanishka Joshi <span id="date"></span>, All rights reserved</p>
      </div>
    </footer>
    <script src="js/script.js"></script>
  </body>
</html>
