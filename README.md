<!DOCTYPE html>
<html lang="en">

<head>
  <title> Glassmorphism - Portfolio Website </title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="font-awesome.css">
  <link rel="stylesheet" href="style.css">
</head>

<body>

  <!-- Page Loader Start -->
  <div class="page-loader">
    <div></div>
    <div></div>
    <div></div>
  </div>
  <!-- Page Loader End -->

  <!-- Background Circles Start -->
  <div class="bg-circles">
    <div class="circle-1"></div>
    <div class="circle-2"></div>
    <div class="circle-3"></div>
    <div class="circle-4"></div>
  </div>
  <!-- Background Circles End -->

  <!-- Overlay Start -->
  <div class="overlay">
  </div>
  <!-- Overlay End -->

  <!-- Main Start -->
  <div class="main hidden">

    <!-- Header Start -->
    <header class="header">
      <div class="container">
        <div class="row flex-end">
          <button type="button" class="nav-toggler">
            <span></span>
          </button>
          <nav class="nav">
            <div class="nav-inner">
              <ul>
                <li><a href="#home" class="nav-item link-item">home</a></li>
                <li><a href="#about" class="nav-item link-item">about</a></li>
                <li><a href="#portfolio" class="nav-item link-item">portfolio</a></li>
                <li><a href="#contact" class="nav-item link-item">contact</a></li>
              </ul>
            </div>
          </nav>
        </div>
      </div>
    </header>
    <!-- Header End -->

    <!-- Home Section Start -->
    <section class="home-section align-items-center" id="home">
      <div class="container">
        <div class="row align-items-center">
          <div class="home-text">
            <p>Hello, I'm</p>
            <h1>Diana Mamytova</h1>
            <h2>student</h2>
            <a href="#about" class="btn link-item">more about me</a>
            <a href="#portfolio" class="btn link-item">portfolio</a>
          </div>
          <div class="home-img">
            <div class="img-box">
              <img src="img/photo_5332538254509069452_y.jpg" alt="profile-img">
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Home Section End -->

    <!-- About Section Start -->
    <section class="about-section sec-padding" id="about">
      <div class="container">
        <div class="row">
          <div class="section-title">
            <h2>about me</h2>
          </div>
        </div>
        <div class="row">
          <div class="about-img">
            <div class="img-box">
              <img src="img/sticker (2).webp" alt="about img">
            </div>
          </div>
          <div class="about-text">
            <p>Much attention was paid not only to training, but also to the development of universal human qualities. I realized that my future and the future of my country depended not only on knowledge, but also on my ability to work in a team, my communication and leadership skills</p>
            <h3>skills</h3>
            <div class="skills">
              <div class="skill-item">html</div>
              <div class="skill-item">css</div>
              <div class="skill-item">java</div>
              <div class="skill-item">python</div>
              <div class="skill-item">c++</div>
            </div>

            <div class="about-tabs">
              <button type="button" class="tab-item active" data-target="#education">education</button>
              <button type="button" class="tab-item" data-target="#experience">experience</button>
            </div>

            <!-- Education Start -->
            <div class="tab-content active" id="education">
              <div class="timeline">
                <div class="timeline-item">
                  <span class="date">2021-2022</span>
                  <h4>bachelor of technology - <span>Ala - Ala-Too university</span></h4>
                  <p>Completed a preparatory course for studying English at Ala-Too University</p>
                </div>
                <div class="timeline-item">
                  <span class="date">2022 - 2023</span>
                  <h4>bachelor of technology - <span>Ala-Too university</span></h4>
                  <p>I was a 1st year student at the Faculty of Computer Science at Ala-Too University.</p>
                </div>
                <div class="timeline-item">
                  <span class="date">2023 - 2024</span>
                  <h4>bachelor of technology - <span>Ala-Too university</span></h4>
                  <p>I am a 2nd year student at Ala-Too University, Faculty of Computer Engineering</p>
                </div>
              </div>
            </div>
            <!-- Education End -->

            <!-- Experience Start -->
            <div class="tab-content" id="experience">
              <div class="timeline">
                <div class="timeline-item">
                  <span class="date">python</span>
                  <h4> student</span></h4>
                </div>
                <div class="timeline-item">
                  <span class="date">css and html</span>
                  <h4>student</span></h4>
                </div>
                <div class="timeline-item">
                  <span class="date">java</span>
                  <h4>student</span></h4
              </>
            </div>
            <!-- Experience End -->
            <a href="cv.pdf" target="_blank" class="btn">download cv</a>
            <a href="#contact" class="btn link-item">contact me</a>
          </div>
        </div>
      </div>
    </section>
    <!-- About Section End -->

    <!-- Portfolio Section Start -->
    <section class="portfolio-section sec-padding" id="portfolio">
      <div class="container">
        <div class="row">
          <div class="section-title">
            <h2>recent work</h2>
          </div>
        </div>
        <div class="row">
          <!-- Portfolio Item Start -->
          <div class="portfolio-item">
            <div class="portfolio-item-thumbnail">
              <img src="img/Изображение WhatsApp 2023-11-02 в 03.17.17_308c4147.jpg" alt="portfolio item thumb">
            </div>
            <h3 class="portfolio-item-title">education course website</h3>
            <button type="button" class="btn view-project-btn">view project</button>
            <div class="portfolio-item-details">
              <div class="description"> 
              </div>
              <div class="general-info">
                <ul>
                  <li>Created - <span>4 Dec 2022</span></li>
                  <li>technologies used - <span>Html, Css</span></li>
                  <li>Role - <span>Frontend</span></li>
                  <li>View Online - <span><a href="#" target="_blank">assignsubmission</a></span></li>
                </ul>
              </div>
            </div>
          </div>
          <!-- Portfolio Item End -->
          <!-- Portfolio Item Start -->
          <div class="portfolio-item">
            <div class="portfolio-item-thumbnail">
              <img src="img/Изображение WhatsApp 2023-11-02 в 03.17.17_06c59f0d.jpg" alt="portfolio item thumb">
            </div>
            <h3 class="portfolio-item-title">personal portfolio website</h3>
            <button type="button" class="btn view-project-btn">view project</button>
            <div class="portfolio-item-details">
              <div class="description">
              </div>
              <div class="general-info">
                <ul>
                  <li>Created - <span>4 Dec </span></li>
                  <li>technologies used - <span>Bootstrap 5</span></li>
                  <li>Role - <span>Frontend</span></li>
                  <li>View Online - <span><a href="#" target="_blank">www.domain.com</a></span></li>
                </ul>
              </div>
            </div>
          </div>
          <!-- Portfolio Item End -->
          <!-- Portfolio Item Start -->
          <div class="portfolio-item">
            <div class="portfolio-item-thumbnail">
              <img src="img/Изображение WhatsApp 2023-11-02 в 03.17.16_8b77f1b1.jpg" alt="portfolio item thumb">
            </div>
            <h3 class="portfolio-item-title">app landing page</h3>
            <button type="button" class="btn view-project-btn">view project</button>
            <div class="portfolio-item-details">
              <div class="description">
              </div>
              <div class="general-info">
                <ul>
                  <li>Created - </span></li>
                  <li>technologies used - <span>Html, grafic4</span></li>
                  <li>Role - <span>designer</span></li>
                  <li>View Online - <span><a href="#" target="_blank">www.domain.com</a></span></li>
                </ul>
              </div>
            </div>
          </div>
          <!-- Portfolio Item End -->
          <!-- Portfolio Item Start -->
          <div class="portfolio-item">
            <div class="portfolio-item-thumbnail">
              <img src="img/Изображение WhatsApp 2023-11-02 в 03.17.16_8b77f1b1.jpg" alt="portfolio item thumb">
            </div>
            <h3 class="portfolio-item-title"> alatoo website</h3>
            <button type="button" class="btn view-project-btn"> project</button>
            <div class="portfolio-item-details">
              <div class="description">
              </div>
              <div class="general-info">
                <ul>
                  <li>Created - <span> 2023</span></li>
                  <li>technologies used - <span>Html, Css, </span></li>
                  <li>Role - <span>Frontend</span></li>
                  <li>View Online - <span><a href="#" target="_blank">www.domaihvn.com</a></span></li>
                </ul>
              </div>
            </div>
          </div>
          <!-- Portfolio Item End -->
          <!-- Portfolio Item Start -->
          <div class="portfolio-item">
            <div class="portfolio-item-thumbnail">
              <img src="img/Изображение WhatsApp 2023-11-02 в 03.17.16_8b77f1b1.jpg" alt="portfolio item thumb">
            </div>
            <h3 class="portfolio-item-title">personal portfolio website</h3>
            <button type="button" class="btn view-project-btn">view project</button>
            <div class="portfolio-item-details">
              <div class="description">
              </div>
              <div class="general-info">
                <ul>
                  <li>Created - <span>2023</span></li>
                  <li>technologies used - <span>Html, Css, Javascript</span></li>
                  <li>Role - <span>Frontend</span></li>
                  <li>View Online - <span><a href="#" target="_blank">assignsubmission</a></span></li>
                </ul>
              </div>
            </div>
          </div>
          <!-- Portfolio Item End -->
          <!-- Portfolio Item Start -->
          <div class="portfolio-item">
            <div class="portfolio-item-thumbnail">
              <img src="img/Изображение WhatsApp 2023-11-02 в 03.17.16_8b77f1b1.jpg" alt="portfolio item thumb">
            </div>
            <h3 class="portfolio-item-title">product landing page</h3>
            <button type="button" class="btn view-project-btn">view project</button>
            <div class="portfolio-item-details">
              <div class="description">
              </div>
              <div class="general-info">
                <ul>
                  <li>Created - <span>4 Dec 2023</span></li>
                  <li>technologies used - <span>Html, Css, 4</span></li>
                  <li>Role - <span>Frontend</span></li>
                  <li>View Online - <span><a href="#" target="_blank">https://ocs.alatoo.edu.kg/pluginfile.php/136164/assignsubmission_onlinetext/submissions_onlinetext/154290/nuraiym0i-main.zip </a></span></li>
                </ul>
              </div>
            </div>
          </div>
          <!-- Portfolio Item End -->
        </div>
      </div>
    </section>
    <!-- Portfolio Section End -->

    <!-- Contact Section Start -->
    <section class="contact-section sec-padding" id="contact">
      <div class="container">
        <div class="row">
          <div class="section-title">
            <h2>contact me</h2>
          </div>
        </div>
        <div class="row">
          <div class="contact-form">
            <form>
              <div class="row">
                <div class="input-group">
                  <input type="text" placeholder="Name" class="input-control" required>
                </div>
                <div class="input-group">
                  <input type="text" placeholder="Email" class="input-control" required>
                </div>
                <div class="input-group">
                  <input type="text" placeholder="Subject" class="input-control" required>
                </div>
                <div class="input-group">
                  <textarea placeholder="Message" class="input-control" required></textarea>
                </div>
                <div class="submit-btn">
                  <button type="submit" class="btn">send message</button>
                </div>
              </div>
            </form>
          </div>
          <div class="contact-info">
            <div class="contact-info-item">
              <h3>Email</h3>
              <p>diana.mamytova@alatoo.edu.kg</p>
            </div>
            <div class="contact-info-item">
              <h3>Phone</h3>
              <p>+996**** ****</p>
            </div>
            <div class="contact-info-item">
              <h3>follow me</h3>
              <div class="social-links">
                <a href="#" target="_blank"><i class="fab fa-facebook-f"></i></a>
                <a href="#" target="_blank"><i class="fab fa-twitter"></i></a>
                <a href="#" target="_blank"><i class="fab fa-instagram"></i></a>
                <a href="#" target="_blank"><i class="fab fa-youtube"></i></a>
                <a href="#" target="_blank"><i class="fab fa-behance"></i></a>
                <a href="#" target="_blank"><i class="fab fa-dribbble"></i></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Contact Section End -->

  </div>
  <!-- Main End -->

  <!-- Portfolio Item Details Popup Start -->
  <div class="portfolio-popup">
    <div class="pp-inner">
      <div class="pp-content">
        <div class="pp-header">
          <button type="button" class="btn pp-close"><i class="fas fa-times"></i></button>
          <div class="pp-thumbnail">
            <img src="img/portfolio/3.jpg" alt="pp-thumbnail">
          </div>
          <h3></h3>
        </div>
        <div class="pp-body">
        </div>
      </div>
    </div>
  </div>
  <!-- Portfolio Item Details Popup End -->


  <script src="script.js"></script>
</body>

</html>
