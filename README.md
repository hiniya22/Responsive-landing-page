<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Landing Page</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <!-- Navigation -->
    <nav class="navbar" id="navbar">
        <div class="nav-container">
            <a href="#home" class="logo">My College</a>
            <ul class="nav-menu" id="nav-menu">
                <li class="nav-item">
                    <a href="#home" class="nav-link">Home</a>
                </li>
                <li class="nav-item">
                    <a href="#about" class="nav-link">About</a>
                </li>
                <li class="nav-item">
                    <a href="#services" class="nav-link">Services</a>
                </li>
                <li class="nav-item">
                    <a href="#portfolio" class="nav-link">Technologies</a>
                </li>
                <li class="nav-item">
                    <a href="#contact" class="nav-link">Contact</a>
                </li>
            </ul>
            <div class="hamburger" id="hamburger">
                <span class="bar"></span>
                <span class="bar"></span>
                <span class="bar"></span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <div id="collegeCarousel" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://res.cloudinary.com/dethm1ien/image/upload/v1754491970/Screenshot_2025-08-06_202029_ntxevt.png" class="d-block w-100" alt="College 1">
          </div>
          <div class="carousel-item">
            <img src="https://res.cloudinary.com/dethm1ien/image/upload/v1754492074/Screenshot_2025-08-06_201929_c657qx.png" class="d-block w-100" alt="College 2">
          </div>
          <div class="carousel-item">
            <img src="https://res.cloudinary.com/dethm1ien/image/upload/v1754492130/Screenshot_2025-08-06_201905_gijl5l.png" class="d-block w-100" alt="College 3">
          </div>
        </div>
      
        <!-- Carousel Controls -->
        <button class="carousel-control-prev" type="button" data-bs-target="#collegeCarousel" data-bs-slide="prev">
          <span class="carousel-control-prev-icon"></span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#collegeCarousel" data-bs-slide="next">
          <span class="carousel-control-next-icon"></span>
        </button>
      </div>
    <section id="home" class="hero">
        <div class="hero-content">
            <div class="hero-text">
                <h1 class="hero-title">Welcome to GRT institute of engineering and technology</h1>
                <p class="hero-subtitle">"Where innovation meets education to shape tomorrow's engineers."</p>
                <div class="hero-buttons">
                    <a href="#about" class="btn btn-primary">Get Started</a>
                    <a href="#portfolio" class="btn btn-secondary">View More</a>
                </div>
            </div>
        </div>
        <div class="hero-background"></div>
    </section>

    <!-- About Section -->
    <section id="about" class="section">
        <div class="container">
            <h2 class="section-title">About Us</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>GRT Institute of Engineering and Technology (GRTIET), located in Tiruttani, Tamil Nadu, is affiliated with Anna University and approved by AICTE.
                        Founded by the GRT Group, the college is known for its focus on technical excellence and innovation.
                        It offers well-structured engineering programs supported by modern labs and experienced faculty.
                        GRTIET emphasizes skill development, industry exposure, and value-based education.
                        Students are encouraged to grow through projects, events, and hands-on learning opportunities.</p>
                    <div class="features">
                        <div class="feature">
                            <div class="feature-icon">🚀</div>
                            <h3>Industry relevant education</h3>
                            <p>GRTIET offers AICTE-approved, Anna University-affiliated programs with a strong focus on practical learning, coding skills, and industry trends, preparing students for real-world tech careers.</p>
                        </div>
                        <div class="feature">
                            <div class="feature-icon">⚡</div>
                            <h3>Modern infrastructure and Expert faculty</h3>
                            <p>GRTIET offers AICTE-approved, Anna University-affiliated programs with a strong focus on practical learning, coding skills, and industry trends, preparing students for real-world tech careers.</p>
                        </div>
                        <div class="feature">
                            <div class="feature-icon">🎨</div>
                            <h3>Holistic Student Development</h3>
                            <p>Beyond academics, students are encouraged to grow through tech fests, coding competitions, internships, soft-skill training, and career-focused programs</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="section section-dark">
        <div class="container">
            <h2 class="section-title">Skill Development Initiatives</h2>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">💻</div>
                    <h3>Conducting Workshops</h3>
                    <p>Conducts hands-on workshops on emerging technolgies like AI, Web development.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">📱</div>
                    <h3>Placement Training</h3>
                    <p>Offers dedicated placement training in aptitude, communication and technical interviews.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">🎯</div>
                    <h3>Emphasizes Practical learning</h3>
                    <p>Emphasizes practical learning through real-time coding, lab sessions, and mini projects.</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">☁</div>
                    <h3>Webinars</h3>
                    <p>Hosts regular Webinars and tech talks by industry experts to stay updated</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="section">
        <div class="container">
            <h2 class="section-title">Technologies</h2>
            <div class="portfolio-grid">
                <div class="portfolio-item">
                    <div class="portfolio-image"></div>
                    <div class="portfolio-content">
                        <h3>Programming Languages</h3>
                        <p>Programming Languages like Python, Java, C, etc has been taught here</p>
                    </div>
                </div>
                <div class="portfolio-item">
                    <div class="portfolio-image"></div>
                    <div class="portfolio-content">
                        <h3>Web Technologies</h3>
                        <p>Web technologies like HTML, CSS, Javascript and some Frameworks</p>
                    </div>
                </div>
                <div class="portfolio-item">
                    <div class="portfolio-image"></div>
                    <div class="portfolio-content">
                        <h3>Soft Skills</h3>
                        <p>Soft Skills like Communication, Teamwork, Problem Solving</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section section-dark">
        <div class="container">
            <h2 class="section-title">Get In Touch</h2>
            <div class="contact-content">
                <div class="contact-info">
                    <h3>Let's Work Together</h3>
                    <p>Ready to explore more!</p>
                    <div class="contact-details">
                        <div class="contact-item">
                            <span class="contact-icon">📧</span>
                            <span>grtiet@gmail.com</span>
                        </div>
                        <div class="contact-item">
                            <span class="contact-icon">📱</span>
                            <span>7020859930</span>
                        </div>
                        <div class="contact-item">
                            <span class="contact-icon">📍</span>
                            <span>GRT Institute of Engineering and Technology, Tiruthani.</span>
                        </div>
                    </div>
                </div>
                <form class="contact-form">
                    <input type="text" placeholder="Your Name" required>
                    <input type="email" placeholder="Your Email" required>
                    <textarea placeholder="Your Message" rows="5" required></textarea>
                    <button type="submit" class="btn btn-primary">Send Message</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2025 TechVision. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>

</html>
