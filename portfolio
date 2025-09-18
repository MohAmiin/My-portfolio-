<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohamed Amiin Abdirahman Hassan - Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        :root {
            --primary-color: #2563eb;
            --secondary-color: #1e40af;
            --accent-color: #3b82f6;
            --dark-color: #1e293b;
            --light-color: #f8fafc;
            --text-color: #334155;
            --text-light: #64748b;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            color: var(--text-color);
            line-height: 1.6;
            background-color: var(--light-color);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .section {
            padding: 80px 0;
        }

        .section-title {
            text-align: center;
            margin-bottom: 50px;
            position: relative;
        }

        .section-title h2 {
            font-size: 2.5rem;
            color: var(--dark-color);
            margin-bottom: 15px;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 70px;
            height: 4px;
            background: linear-gradient(to right, var(--primary-color), var(--secondary-color));
            border-radius: 2px;
        }

        .btn {
            display: inline-block;
            padding: 12px 30px;
            background: linear-gradient(to right, var(--primary-color), var(--secondary-color));
            color: white;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }

        /* Header Styles */
        header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            z-index: 1000;
            background-color: rgba(255, 255, 255, 0.95);
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            padding: 15px 0;
        }

        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--dark-color);
            text-decoration: none;
        }

        .logo span {
            color: var(--primary-color);
        }

        .nav-links {
            display: flex;
            list-style: none;
        }

        .nav-links li {
            margin-left: 30px;
        }

        .nav-links a {
            text-decoration: none;
            color: var(--text-color);
            font-weight: 500;
            transition: color 0.3s ease;
        }

        .nav-links a:hover {
            color: var(--primary-color);
        }

        .menu-toggle {
            display: none;
            font-size: 1.5rem;
            cursor: pointer;
        }

        /* Hero Section */
        .hero {
            padding-top: 150px;
            padding-bottom: 100px;
            background: linear-gradient(135deg, rgba(37, 99, 235, 0.1) 0%, rgba(30, 64, 175, 0.1) 100%);
        }

        .hero-content {
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .hero-text {
            flex: 1;
            padding-right: 30px;
        }

        .hero-text h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            color: var(--dark-color);
        }

        .hero-text h1 span {
            color: var(--primary-color);
        }

        .hero-text p {
            font-size: 1.2rem;
            margin-bottom: 30px;
            color: var(--text-light);
        }

        .hero-buttons {
            display: flex;
            gap: 15px;
        }

        .btn-outline {
            background: transparent;
            border: 2px solid var(--primary-color);
            color: var(--primary-color);
        }

        .btn-outline:hover {
            background: var(--primary-color);
            color: white;
        }

        .hero-image {
            flex: 1;
            text-align: center;
            position: relative;
        }

        .hero-image img {
            max-width: 100%;
            border-radius: 50%;
            border: 5px solid white;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }

        .floating-icon {
            position: absolute;
            width: 60px;
            height: 60px;
            background: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            animation: float 3s ease-in-out infinite;
        }

        .floating-icon:nth-child(1) {
            top: 20%;
            left: 10%;
            background: var(--primary-color);
            color: white;
        }

        .floating-icon:nth-child(2) {
            top: 60%;
            right: 10%;
            background: var(--secondary-color);
            color: white;
        }

        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-15px);
            }
        }

        /* About Section */
        .about-content {
            display: flex;
            align-items: center;
            gap: 50px;
        }

        .about-text {
            flex: 1;
        }

        .about-text h3 {
            font-size: 2rem;
            margin-bottom: 20px;
            color: var(--dark-color);
        }

        .about-text p {
            margin-bottom: 15px;
            color: var(--text-light);
        }

        .about-stats {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
            margin-top: 30px;
        }

        .stat-box {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            text-align: center;
        }

        .stat-box h4 {
            font-size: 2rem;
            color: var(--primary-color);
            margin-bottom: 5px;
        }

        .about-image {
            flex: 1;
            text-align: center;
        }

        .about-image img {
            max-width: 100%;
            border-radius: 10px;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }

        /* Skills Section */
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 30px;
        }

        .skill-card {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            text-align: center;
            transition: transform 0.3s ease;
        }

        .skill-card:hover {
            transform: translateY(-10px);
        }

        .skill-card i {
            font-size: 3rem;
            color: var(--primary-color);
            margin-bottom: 20px;
        }

        .skill-card h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
        }

        /* Experience Section */
        .timeline {
            position: relative;
            max-width: 800px;
            margin: 0 auto;
        }

        .timeline::after {
            content: '';
            position: absolute;
            width: 6px;
            background-color: var(--primary-color);
            top: 0;
            bottom: 0;
            left: 50%;
            margin-left: -3px;
        }

        .timeline-item {
            padding: 10px 40px;
            position: relative;
            width: 50%;
            box-sizing: border-box;
        }

        .timeline-item:nth-child(odd) {
            left: 0;
        }

        .timeline-item:nth-child(even) {
            left: 50%;
        }

        .timeline-content {
            padding: 20px;
            background-color: white;
            position: relative;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }

        .timeline-content h3 {
            color: var(--primary-color);
            margin-bottom: 10px;
        }

        .timeline-content p {
            color: var(--text-light);
            margin-bottom: 10px;
        }

        .timeline-date {
            font-weight: bold;
            color: var(--secondary-color);
        }

        /* Projects Section */
        .projects-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
            gap: 30px;
        }

        .project-card {
            background-color: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-10px);
        }

        .project-image {
            height: 200px;
            overflow: hidden;
        }

        .project-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }

        .project-card:hover .project-image img {
            transform: scale(1.1);
        }

        .project-info {
            padding: 20px;
        }

        .project-info h3 {
            font-size: 1.5rem;
            margin-bottom: 10px;
        }

        .project-info p {
            color: var(--text-light);
            margin-bottom: 15px;
        }

        .project-tags {
            display: flex;
            flex-wrap: wrap;
            margin-bottom: 15px;
        }

        .project-tags span {
            background-color: rgba(37, 99, 235, 0.1);
            color: var(--primary-color);
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 0.8rem;
            margin-right: 8px;
            margin-bottom: 8px;
        }

        /* Contact Section */
        .contact-content {
            display: flex;
            gap: 50px;
        }

        .contact-info {
            flex: 1;
        }

        .contact-info h3 {
            font-size: 1.8rem;
            margin-bottom: 20px;
        }

        .contact-info p {
            margin-bottom: 20px;
            color: var(--text-light);
        }

        .contact-details {
            margin-top: 30px;
        }

        .contact-details div {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
        }

        .contact-details i {
            width: 40px;
            height: 40px;
            background: linear-gradient(to right, var(--primary-color), var(--secondary-color));
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
        }

        .contact-form {
            flex: 1;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
        }

        .form-group textarea {
            height: 150px;
            resize: vertical;
        }

        /* Footer */
        footer {
            background-color: var(--dark-color);
            color: white;
            padding: 50px 0 20px;
        }

        .footer-content {
            display: flex;
            justify-content: space-between;
            margin-bottom: 30px;
        }

        .footer-about {
            flex: 1;
            padding-right: 30px;
        }

        .footer-about h3 {
            font-size: 1.5rem;
            margin-bottom: 20px;
        }

        .footer-links {
            flex: 1;
        }

        .footer-links h3 {
            font-size: 1.5rem;
            margin-bottom: 20px;
        }

        .footer-links ul {
            list-style: none;
        }

        .footer-links li {
            margin-bottom: 10px;
        }

        .footer-links a {
            color: #ddd;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .footer-links a:hover {
            color: var(--primary-color);
        }

        .social-links {
            display: flex;
            margin-top: 20px;
        }

        .social-links a {
            width: 40px;
            height: 40px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 10px;
            transition: all 0.3s ease;
        }

        .social-links a:hover {
            background: linear-gradient(to right, var(--primary-color), var(--secondary-color));
            transform: translateY(-3px);
        }

        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }

        /* Responsive Styles */
        @media (max-width: 992px) {
            .hero-content,
            .about-content,
            .contact-content {
                flex-direction: column;
            }

            .hero-text,
            .about-text,
            .contact-info {
                padding-right: 0;
                margin-bottom: 40px;
            }

            .footer-content {
                flex-direction: column;
            }

            .footer-about {
                margin-bottom: 30px;
                padding-right: 0;
            }
        }

        @media (max-width: 768px) {
            .menu-toggle {
                display: block;
            }

            .nav-links {
                position: fixed;
                top: 70px;
                left: -100%;
                width: 100%;
                height: calc(100vh - 70px);
                background-color: white;
                flex-direction: column;
                align-items: center;
                justify-content: center;
                transition: all 0.3s ease;
            }

            .nav-links.active {
                left: 0;
            }

            .nav-links li {
                margin: 15px 0;
            }

            .hero-text h1 {
                font-size: 2.5rem;
            }

            .section-title h2 {
                font-size: 2rem;
            }

            .timeline::after {
                left: 31px;
            }

            .timeline-item {
                width: 100%;
                padding-left: 70px;
                padding-right: 25px;
            }

            .timeline-item:nth-child(even) {
                left: 0;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <nav class="navbar">
                <a href="#" class="logo">Mohamed<span>Amiin</span></a>
                <div class="menu-toggle" id="menu-toggle">
                    <i class="fas fa-bars"></i>
                </div>
                <ul class="nav-links" id="nav-links">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#experience">Experience</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="hero-content">
                <div class="hero-text">
                    <h1>Hi, I'm <span>Mohamed Amiin</span></h1>
                    <p>Air Traffic Controller with 9+ years of experience and a passion for web design, problem solving, and technology solutions.</p>
                    <div class="hero-buttons">
                        <a href="#projects" class="btn">View My Work</a>
                        <a href="#contact" class="btn btn-outline">Contact Me</a>
                    </div>
                </div>
                <div class="hero-image">
                    <img src="https://via.placeholder.com/400x400" alt="Mohamed Amiin">
                    <div class="floating-icon">
                        <i class="fas fa-plane"></i>
                    </div>
                    <div class="floating-icon">
                        <i class="fas fa-code"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="section" id="about">
        <div class="container">
            <div class="section-title">
                <h2>About Me</h2>
            </div>
            <div class="about-content">
                <div class="about-text">
                    <h3>Dedicated professional with expertise in ATC and technology</h3>
                    <p>I'm Mohamed Amiin Abdirahman Hassan, a dedicated and results-driven professional with a growing expertise in technology and digital solutions. With a strong foundation in problem-solving, web development, and continuous learning, I'm passionate about building innovative tools and practical solutions that add value.</p>
                    <p>With over 9 years of experience as an Air Traffic Controller, I've developed strong analytical skills, attention to detail, and the ability to perform under pressure. These skills translate well into my technology pursuits where I aim to create impactful projects while expanding my knowledge in modern technologies and software development.</p>
                    
                    <div class="about-stats">
                        <div class="stat-box">
                            <h4>9+</h4>
                            <p>Years of ATC Experience</p>
                        </div>
                        <div class="stat-box">
                            <h4>15+</h4>
                            <p>Projects Completed</p>
                        </div>
                        <div class="stat-box">
                            <h4>5+</h4>
                            <p>Technical Skills</p>
                        </div>
                        <div class="stat-box">
                            <h4>100%</h4>
                            <p>Client Satisfaction</p>
                        </div>
                    </div>
                </div>
                <div class="about-image">
                    <img src="https://via.placeholder.com/500x600" alt="About Mohamed Amiin">
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="section" id="skills" style="background-color: #f9f9f9;">
        <div class="container">
            <div class="section-title">
                <h2>My Skills</h2>
            </div>
            <div class="skills-container">
                <div class="skill-card">
                    <i class="fas fa-tower-broadcast"></i>
                    <h3>Air Traffic Control</h3>
                    <p>9+ years of experience in managing air traffic, ensuring safety, and coordinating operations.</p>
                </div>
                <div class="skill-card">
                    <i class="fas fa-code"></i>
                    <h3>Web Development</h3>
                    <p>HTML, CSS, JavaScript, and responsive design for creating functional websites.</p>
                </div>
                <div class="skill-card">
                    <i class="fas fa-paint-brush"></i>
                    <h3>Graphic Design</h3>
                    <p>Creating visually appealing designs and user interfaces for digital products.</p>
                </div>
                <div class="skill-card">
                    <i class="fas fa-chart-line"></i>
                    <h3>Data Analysis</h3>
                    <p>Analyzing and interpreting complex data to derive meaningful insights.</p>
                </div>
                <div class="skill-card">
                    <i class="fas fa-lightbulb"></i>
                    <h3>Problem Solving</h3>
                    <p>Identifying issues and developing effective solutions in high-pressure environments.</p>
                </div>
                <div class="skill-card">
                    <i class="fas fa-project-diagram"></i>
                    <h3>Project Management</h3>
                    <p>Planning, executing, and finalizing projects according to specifications.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section class="section" id="experience">
        <div class="container">
            <div class="section-title">
                <h2>My Experience</h2>
            </div>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-content">
                        <h3>Air Traffic Controller</h3>
                        <span class="timeline-date">2014 - Present</span>
                        <p>Managing air traffic flow and ensuring safety in controlled airspace. Coordinating with pilots, ground staff, and other controllers to maintain efficient and safe operations.</p>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-content">
                        <h3>Web Designer & Developer</h3>
                        <span class="timeline-date">2018 - Present</span>
                        <p>Creating responsive websites and web applications. Specializing in user-friendly interfaces and functional designs that meet client requirements.</p>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-content">
                        <h3>Graphic Designer</h3>
                        <span class="timeline-date">2016 - Present</span>
                        <p>Designing visual content for digital and print media. Creating logos, banners, and marketing materials that effectively communicate brand messages.</p>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-content">
                        <h3>Data Analyst</h3>
                        <span class="timeline-date">2019 - Present</span>
                        <p>Collecting, processing, and performing statistical analyses on large datasets. Creating visualizations and reports to support decision-making processes.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="section" id="projects" style="background-color: #f9f9f9;">
        <div class="container">
            <div class="section-title">
                <h2>My Projects</h2>
            </div>
            <div class="projects-container">
                <div class="project-card">
                    <div class="project-image">
                        <img src="https://via.placeholder.com/600x400" alt="Crypto Profit Calculator">
                    </div>
                    <div class="project-info">
                        <h3>Crypto Profit Calculator</h3>
                        <p>A web application that calculates potential profits from cryptocurrency investments based on market data.</p>
                        <div class="project-tags">
                            <span>HTML</span>
                            <span>CSS</span>
                            <span>JavaScript</span>
                            <span>Web Design</span>
                        </div>
                        <a href="https://mohamiin.github.io/Cryptoproftcalculator/" class="btn">View Project</a>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image">
                        <img src="https://via.placeholder.com/600x400" alt="ATC Training Simulator">
                    </div>
                    <div class="project-info">
                        <h3>ATC Training Simulator</h3>
                        <p>A training tool for air traffic controllers that simulates various scenarios and conditions.</p>
                        <div class="project-tags">
                            <span>UI Design</span>
                            <span>Simulation</span>
                            <span>Training</span>
                        </div>
                        <a href="#" class="btn">View Project</a>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image">
                        <img src="https://via.placeholder.com/600x400" alt="Data Visualization Dashboard">
                    </div>
                    <div class="project-info">
                        <h3>Data Visualization Dashboard</h3>
                        <p>An interactive dashboard for visualizing complex data sets and generating insights.</p>
                        <div class="project-tags">
                            <span>Data Analysis</span>
                            <span>JavaScript</span>
                            <span>Charts</span>
                        </div>
                        <a href="#" class="btn">View Project</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="section" id="contact">
        <div class="container">
            <div class="section-title">
                <h2>Get In Touch</h2>
            </div>
            <div class="contact-content">
                <div class="contact-info">
                    <h3>Let's Talk About Your Project</h3>
                    <p>I'm currently available for freelance work and open to new opportunities. Feel free to reach out if you have a project in mind or just want to say hello!</p>
                    <div class="contact-details">
                        <div>
                            <i class="fas fa-envelope"></i>
                            <p>Moeamiinabdi@gmail.com</p>
                        </div>
                        <div>
                            <i class="fas fa-phone"></i>
                            <p>+252 63 4740002</p>
                        </div>
                        <div>
                            <i class="fas fa-phone"></i>
                            <p>+252 65 9740002</p>
                        </div>
                    </div>
                </div>
                <div class="contact-form">
                    <form id="contactForm">
                        <div class="form-group">
                            <input type="text" placeholder="Your Name" required>
                        </div>
                        <div class="form-group">
                            <input type="email" placeholder="Your Email" required>
                        </div>
                        <div class="form-group">
                            <input type="text" placeholder="Subject" required>
                        </div>
                        <div class="form-group">
                            <textarea placeholder="Your Message" required></textarea>
                        </div>
                        <button type="submit" class="btn">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-about">
                    <h3>Mohamed Amiin</h3>
                    <p>Air Traffic Controller and Technology Enthusiast passionate about creating digital experiences that make a difference.</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-linkedin-in"></i></a>
                        <a href="#"><i class="fab fa-github"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
                <div class="footer-links">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#about">About</a></li>
                        <li><a href="#skills">Skills</a></li>
                        <li><a href="#experience">Experience</a></li>
                        <li><a href="#projects">Projects</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2023 Mohamed Amiin Abdirahman Hassan. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        const menuToggle = document.getElementById('menu-toggle');
        const navLinks = document.getElementById('nav-links');

        menuToggle.addEventListener('click', () => {
            navLinks.classList.toggle('active');
        });

        // Close mobile menu when clicking on a link
        document.querySelectorAll('.nav-links a').forEach(link => {
            link.addEventListener('click', () => {
                navLinks.classList.remove('active');
            });
        });

        // Form submission
        const contactForm = document.getElementById('contactForm');
        contactForm.addEventListener('submit', (e) => {
            e.preventDefault();
            alert('Thank you for your message! I will get back to you soon.');
            contactForm.reset();
        });
    </script>
</body>
</html>
