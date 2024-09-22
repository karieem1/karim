<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Karim</title>
    <link rel="icon" href="assets/img/hero.png" type="hero__img">

    <!--=================== Google Fonts ====================-->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&display=swap"
        rel="stylesheet">

        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <!--=================== Remixicons ====================-->
    <link href="https://cdn.jsdelivr.net/npm/remixicon@2.5.0/fonts/remixicon.css" rel="stylesheet">

    <!--=================== SwiperJS CSS ====================-->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.css" />


    <!--=================== Main CSS ====================-->
    <link rel="stylesheet" href="assets/css/main.css">

</head>

<body>

    <!--=================== Header ====================-->
    <header id="header" class="header">
        <div class="container">
            <nav class="nav">
                <a class='nav__brand' href='#'>
                    <i class="fa-solid fa-robot"></i>Karim
                </a>
                <div class="nav__menu" id="nav-menu">
                    <ul class="nav__list">
                        <li class="nav__item">
                            <a href="#hero" class="nav__link"><i class="fa-solid fa-house"></i></a>
                        </li>
                        <li class="nav__item">
                            <a href="#about" class="nav__link">About</a>
                        </li>
                        <li class="nav__item">
                            <a href="#qualification" class="nav__link">Qualification</a>
                        </li>
                        <li class="nav__item">
                            <a href="#service" class="nav__link">Services</a>
                        </li>
                        <li class="nav__item">
                            <a href="#project" class="nav__link">Projects</a>
                        </li>
                        <li class="nav__item">
                            <a href="#contact" class="nav__link">Contact</a>
                        </li>
                           
                    </ul>
                </div>
                <div class="nav__toggle">
                    <i id="nav-toggle" class="ri-menu-3-line"></i>
                </div>
                 <!-- ضع هذا الكود قبل إغلاق علامة </nav> -->
                 <div class="theme-toggle" id="theme-toggle">
                    <i class="fas fa-sun" id="icon"></i>
                </div>
                                   
            </nav>
            
        </div>
    </header>
    <!--=================== main ====================-->
    <main class="main">
        <!--=================== Hero ====================-->
        <section id="hero" class="hero">
            <div class="container">
                <div class="d-grid hero__wrapper">
                    <div class="hero__content">
                        <h1 class="hero__title">Hi, I'm Karim<br></h1>
                        <p class="hero__description">I'm Mechatronics Engineer passionate about advanced technology and the integration of software and hardware systems into a unified and cohesive system.</p>
                        <div class="hero__info">
                            <div class="hero__info-wrapper">
                                <p class="hero__info-number">01</p>
                                <h2 class="hero__info-title">Years<br>Experience</h2>
                            </div>
                            <div class="hero__info-wrapper">
                                <p class="hero__info-number">+20</p>
                                <h2 class="hero__info-title">Projects<br>Completed</h2>
                            </div>
                        </div>
                    </div>
                    <img src="assets/img/hero.png" alt="Karim" class="hero__img">
                </div>
            </div>
        </section>

        <!--=================== About ====================-->
        <section id="about" class="section about">
            <div class="container">
                <div class="section__header">
                    <h2 class="section__title">About Me</h2>
                    <span class="section__subtitle">Who am I ?!!</span>
                </div>
                <div class="d-grid about__wrapper">
                    <div class="about__content">
                        <h3 class="about__title">I'm Junior Mechatronics Engineer.</h3>
                        <p class="about__description">specializing in software and hardware. I work on integrating artificial intelligence with robotics to create innovative and advanced solutions. I believe in balancing technology and creativity to develop cutting-edge integrated systems.</p>
                        <a href="#" class="btn btn--primary">Know More</a>
                    </div>
                    <div class="skills">
                        <h3 class="skills__title">Technologies I've been working with:</h3>
                        <div class="skills__wrapper">
                            <div class="skills__content">
                                <h4 class="skills__subtitle">Software</h4>
                                <ul class="skills__list">
                                    <li class="skills__item"><i class="ri-arrow-right-s-fill"></i>
                                        Machine learning</li>
                                    <li class="skills__item"><i class="ri-arrow-right-s-fill"></i>
                                        Python</li>
                                    <li class="skills__item"><i class="ri-arrow-right-s-fill"></i>
                                        AI</li>    
                                    <li class="skills__item"><i class="ri-arrow-right-s-fill"></i>
                                        C</li>
                                    <li class="skills__item"><i class="ri-arrow-right-s-fill"></i>
                                       MatLab</li>                                               
                                    <li class="skills__item"><i class="ri-arrow-right-s-fill"></i>
                                        Arduino</li>
                                </ul>
                            </div>
                            <div class="skills__content">
                                <h4 class="skills__subtitle">Hardware</h4>
                                <ul class="skills__list">
                                    <li class="skills__item"><i class="ri-arrow-right-s-fill"></i>
                                        Robotics</li>
                                    <li class="skills__item"><i class="ri-arrow-right-s-fill"></i>
                                        MEC Design</li>
                                    <li class="skills__item"><i class="ri-arrow-right-s-fill"></i>
                                        Electromechanics</li>                                 
                                    <li class="skills__item"><i class="ri-arrow-right-s-fill"></i>
                                        CNC Machines</li>
                                    <li class="skills__item"><i class="ri-arrow-right-s-fill"></i>
                                            Control System</li>
                                    <li class="skills__item"><i class="ri-arrow-right-s-fill"></i>
                                            Chat Bots</li>
                                    
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!--=================== Qualification ====================-->
        <section id="qualification" class="section qualification">
            <div class="container">
                <div class="section__header">
                    <h2 class="section__title">Qualification</h2>
                    <span class="section__subtitle">Experience & Education</span>
                </div>
                <!--============== Professional Experience ============-->
                <div class="qualification__wrapper">
                    <h3 class="qualification__name">
                        <i class="ri-briefcase-fill"></i>
                        Professional Experience
                    </h3>
                    <div class="d-grid qualification__content">
                        <!-- Experience 1-->
                        <div class="qualification__item">
                            <h3 class="qualification__title">Control Systems</h3>
                            <p class="qualification__description">SCADA Systems Specialist Trainee
                                Specialized in SCADA systems, focusing on real-time monitoring and control of water treatment processes.
                                Developed skills in configuring and managing SCADA software and hardware.
                                Participated in system maintenance and performance evaluation.</p>
                            <span class="qualification__date">2024</span>
                        </div>
                        <!-- Experience 2-->
                        <div class="qualification__item">
                            <h3 class="qualification__title">The Arab Contractors</h3>
                            <p class="qualification__description">Internship provided hands-on experience in designing, installing, and maintaining electromechanical systems. Assisted in troubleshooting, optimizing system performance, and supporting operational efficiency through practical, real-world problem-solving. </p>
                            <span class="qualification__date">2023</span>
                        </div>
                        <!-- Experience 3-->
                        <div class="qualification__item">
                            <h3 class="qualification__title">Embedded System</h3>
                            <p class="qualification__description">Received intensive training in embedded systems, where I gained skills in software development, hardware control, and hardware integration, enhancing my ability to design and analyze embedded systems effectively.</p>
                            <span class="qualification__date">2022</span>
                        </div>
                    </div>
                </div>
                <!--============== Education ============-->
                <div class="qualification__wrapper">
                    <h3 class="qualification__name">
                        <i class="ri-booklet-fill"></i>
                        Education
                    </h3>
                    <div class="d-grid qualification__content">
                        <!-- Education 1-->
                      

                        <div class="qualification__item">
                            <h3 class="qualification__title">DEPI</h3>
                            <p class="qualification__description">Participated in a comprehensive program focused on machine learning and artificial intelligence. Worked on data analysis, algorithm development, and AI implementation. Acquired skills in remote learning technologies and advanced AI techniques.</p>
                            <span class="qualification__date">2024</span>
                        </div>
                        <!-- Education 2-->
                       



                        <div class="qualification__item">
                            <h3 class="qualification__title">Mansoura University</h3>
                            <p class="qualification__description">I studied Mechatronics Engineering at Mansoura University, gaining extensive knowledge in all areas essential for developing integrated systems and mastering the necessary skills for effective system design and implementation.</p>
                            <span class="qualification__date">2020 - 2025</span>
                        </div>



                        <!-- Education 3
                        <div class="qualification__item">
                            <h3 class="qualification__title">Web Developer</h3>
                            <p class="qualification__description">Lorem ipsum dolor sit amet consectetur.
                                Facilisi vitae bibendum praesent sodales
                                urna vel molestie neque augue.</p>
                            <span class="qualification__date">2018 - 2019</span>
                        </div>-->
                    </div>
                </div>
                <div class="qualification__footer">
                    <p class="qualification__footer-text">See my full resume</p>
                    <a href="assets/cv/Karim_CV.pdf" class="btn btn--primary" download>Resume</a>
                </div>
            </div>
        </section>

        <!--=================== services ====================-->
        <section id="service" class="section service">
            <div class="container">
                <div class="section__header">
                    <h2 class="section__title">Services</h2>
                    <span class="section__subtitle">What I do</span>
                </div>
                <div class="d-grid service__wrapper">
                    <!--========= service card 1 =========-->
                    <div class="service__card">
                        <div class="service__icon">
                            <i class="fa-duotone fa-solid fa-microchip"></i>
                        </div>
                        <h3 class="service__title">Machine learning<br>  & AI </h3>
                        <!--==============<a href="#" class="service__link"> Know More</a>============-->
                    </div>
                    <!--========= service card 2 =========-->
                    <div class="service__card">
                        <div class="service__icon">
                            <i class="fa-solid fa-laptop"></i>
                        </div>
                        <h3 class="service__title">Control Systems</h3>
                        <!--==============<a href="#" class="service__link">Know More</a>============-->   
                     </div>
                    <!--========= service card 3 =========-->
                     <div class="service__card">
                        <div class="service__icon">
                            <i class="fa-solid fa-robot"></i>
                        </div>
                        <h3 class="service__title">Robotics<br> </h3>
                        <!--==============<a href="#" class="service__link"> Know More</a>============-->   
                                     </div>
                </div>
            </div>
        </section>

        <!--=================== Projects ====================-->
        <section id="project" class="section project">
            <div class="container">
                <div class="section__header">
                    <h2 class="section__title">Projects</h2>
                    <span class="section__subtitle">My recent work</span>
                </div>
                <div class="d-grid project__wrapper">




                    
                    <!--============== project 1 =============-->
                    <div class="project__content">
                        <img src="assets/img/project1.jpg" alt="Sumo car" class="project__img">
                        <h3 class="project__title">Sumo car</h3>
                        <p class="project__description">Sumo Car is a small, autonomous robot designed to compete in sumo wrestling matches, using sensors and motors to detect and push opponents out of the ring.</p>
                       <a href="https://github.com/karieem1/arduino-sumo-car" class="project__link">View Project
                            <i class="ri-arrow-right-line"></i></a>
                    </div>
                    <!--============== project 2 =============-->
                    <div class="project__content">
                        <img src="assets/img/project2.jpg" alt="Guide Glove" class="project__img">
                        <h3 class="project__title">Guide Glove</h3>
                        <p class="project__description">Guide Glove features ultrasonic sensors and an alert system to help the visually impaired avoid obstacles.</p>
                         <a href="https://github.com/karieem1/The-third-eye-project" class="project__link">View Project
                            <i class="ri-arrow-right-line"></i></a>
                    </div>
                    <!--============== project 3 =============-->
                    <div class="project__content">
                        <img src="assets/img/project3.jpg" alt="Smart Fire fighter" class="project__img">
                        <h3 class="project__title">Smart Fire fighter</h3>
                        <p class="project__description">Fire Fighter is a robotic model designed to detect and extinguish fires using advanced sensors and control techniques.</p>
                        <a href="https://github.com/karieem1/fire-fighter-robot-using-arduino" class="project__link">View Project
                            <i class="ri-arrow-right-line"></i></a>
                    </div>
                </div>
            </div>
        </section>

            </div>
        </section>

        <!--=================== Contact ====================-->
        <section id="contact" class="section contact">
            <div class="container">
                <div class="d-grid contact__wrapper">
                    <div class="contact__content">
                        <h2 class="contact__title">Interested in working together? </h2>
                        <p class="contact__description">
                            Let's talk and explore how we can collaborate to bring innovative solutions to life. Whether it's integrating cutting-edge technology or creating seamless systems, I'm always here to new opportunities.
                        </p>
                    </div>
                    <div class="contact__btn">
                        <a href="https://wa.me/+201150623115" class="btn btn--secondary">Get in touch</a>
                    </div>
                </div>
            </div>
        </section>
    </main>
    <!--=================== footer ====================-->
    <footer id="footer" class="footer">
        <div class="container">
            <div class="d-grid footer__wrapper">
                <div class="footer__content">
                    <h4 class="footer__title">Follow Me</h4>
                    <ul class="footer__social-list">
                        <li class="footer__social-item">
                            <a href="https://www.facebook.com/karim.elhosiney?mibextid=ZbWKwL" class="footer__social-link">
                                <i class="ri-facebook-fill"></i>
                            </a>
                        </li>
                        <li class="footer__social-item">
                            <a href="https://www.instagram.com/karim_elhosiney/profilecard/?igsh=b2N5cTN2amhweXR4" class="footer__social-link">
                                <i class="ri-instagram-fill"></i>
                            </a>
                        </li>
                        </li>
                        <li class="footer__social-item">
                            <a href="https://www.linkedin.com/in/karim-elsayed-a2171a2a6?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" class="footer__social-link">
                                <i class="ri-linkedin-fill"></i>
                            </a>
                        </li>
                        <li class="footer__social-item">
                            <a href="https://github.com/karieem1" class="footer__social-link">
                                <i class="ri-github-fill"></i>
                            </a>
                        </li>
                        <li><a href="https://www.kaggle.com/karieemalsayed"><i class="fab fa-kaggle"></i></a></li>
                        </ul>
                </div>
                <div class="footer__content">
                    <h4 class="footer__title">Email Me</h4>
                    <a href="mailto:karieemalsayed6@gmail.com"class="footer__contact">karieemalsayed6@mail.com</a>
                </div>
                <div class="footer__content">
                    <h4 class="footer__title">Call Me</h4>
                    <a href="https://wa.me/+201150623115" class="footer__contact">(+20) 1150623115 </a>
                </div>
            </div>
            <p class="footer__copyright">&copy; 2024. KEMOO All Rights Reserved</p>
        </div>
    </footer>

    <!--=================== SwiperJS  ====================-->
    <script src="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.js"></script>

    <!--=================== ScrollReveal ==================-->
    <script src="https://unpkg.com/scrollreveal"></script>

    <!--=================== Main JS ====================-->
    <script src="assets/js/main.js"></script>
</body>

</html>
