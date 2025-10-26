---
layout: default
---

<header class="header">
    <div class="header-content">
        <h1 class="name">{{ site.name }}</h1>
        <h2 class="position">{{ site.title_position }}</h2>
        <div class="contact-info">
            <div class="contact-item">
                <i class="fas fa-envelope"></i>
                <a href="mailto:{{ site.email }}">{{ site.email }}</a>
            </div>
            <div class="contact-item">
                <i class="fas fa-phone"></i>
                <span>{{ site.phone }}</span>
            </div>
            <div class="contact-item">
                <i class="fas fa-map-marker-alt"></i>
                <span>{{ site.location }}</span>
            </div>
            <div class="contact-item">
                <i class="fab fa-linkedin"></i>
                <a href="https://{{ site.linkedin }}" target="_blank">LinkedIn</a>
            </div>
            <div class="contact-item">
                <i class="fab fa-github"></i>
                <a href="https://{{ site.github }}" target="_blank">GitHub</a>
            </div>
            {% if site.website %}
            <div class="contact-item">
                <i class="fas fa-globe"></i>
                <a href="https://{{ site.website }}" target="_blank">{{ site.website }}</a>
            </div>
            {% endif %}
        </div>
    </div>
    <button class="print-btn no-print" onclick="printResume()">
        <i class="fas fa-print"></i> Print Resume
    </button>
</header>

<main class="main-content">
    <section class="section">
        <h3 class="section-title">Professional Summary</h3>
        <p class="summary">
            Experienced software developer with 5+ years of expertise in full-stack development, 
            specializing in modern web technologies and cloud solutions. Proven track record of 
            delivering scalable applications and leading cross-functional teams.
        </p>
    </section>

    <section class="section">
        <h3 class="section-title">Experience</h3>
        
        <div class="experience-item">
            <div class="experience-header">
                <h4 class="job-title">Senior Software Developer</h4>
                <span class="company">Tech Company Inc.</span>
                <span class="duration">2021 - Present</span>
            </div>
            <ul class="achievements">
                <li>Led development of microservices architecture serving 1M+ users</li>
                <li>Reduced application load time by 40% through performance optimization</li>
                <li>Mentored 3 junior developers and established code review processes</li>
                <li>Implemented CI/CD pipelines reducing deployment time by 60%</li>
            </ul>
        </div>

        <div class="experience-item">
            <div class="experience-header">
                <h4 class="job-title">Full Stack Developer</h4>
                <span class="company">Startup Solutions</span>
                <span class="duration">2019 - 2021</span>
            </div>
            <ul class="achievements">
                <li>Built responsive web applications using React and Node.js</li>
                <li>Designed and implemented RESTful APIs and database schemas</li>
                <li>Collaborated with UX/UI designers to deliver pixel-perfect interfaces</li>
                <li>Maintained 99.9% uptime for production applications</li>
            </ul>
        </div>
    </section>

    <section class="section">
        <h3 class="section-title">Education</h3>
        
        <div class="education-item">
            <div class="education-header">
                <h4 class="degree">Bachelor of Science in Computer Science</h4>
                <span class="school">University Name</span>
                <span class="duration">2015 - 2019</span>
            </div>
            <p class="education-details">Magna Cum Laude, GPA: 3.8/4.0</p>
        </div>
    </section>

    <section class="section">
        <h3 class="section-title">Technical Skills</h3>
        
        <div class="skills-grid">
            <div class="skill-category">
                <h4 class="skill-category-title">Languages</h4>
                <div class="skills">
                    <span class="skill">JavaScript</span>
                    <span class="skill">Python</span>
                    <span class="skill">TypeScript</span>
                    <span class="skill">Java</span>
                </div>
            </div>
            
            <div class="skill-category">
                <h4 class="skill-category-title">Frameworks</h4>
                <div class="skills">
                    <span class="skill">React</span>
                    <span class="skill">Node.js</span>
                    <span class="skill">Express</span>
                    <span class="skill">Django</span>
                </div>
            </div>
            
            <div class="skill-category">
                <h4 class="skill-category-title">Tools & Technologies</h4>
                <div class="skills">
                    <span class="skill">AWS</span>
                    <span class="skill">Docker</span>
                    <span class="skill">Git</span>
                    <span class="skill">PostgreSQL</span>
                </div>
            </div>
        </div>
    </section>

    <section class="section">
        <h3 class="section-title">Projects</h3>
        
        <div class="project-item">
            <div class="project-header">
                <h4 class="project-title">E-commerce Platform</h4>
                <div class="project-links">
                    <a href="#" target="_blank"><i class="fab fa-github"></i> Code</a>
                    <a href="#" target="_blank"><i class="fas fa-external-link-alt"></i> Live</a>
                </div>
            </div>
            <p class="project-description">
                Full-stack e-commerce solution with React frontend, Node.js backend, 
                and PostgreSQL database. Features include user authentication, payment processing, 
                and admin dashboard.
            </p>
            <div class="project-tech">
                <span class="tech-tag">React</span>
                <span class="tech-tag">Node.js</span>
                <span class="tech-tag">PostgreSQL</span>
                <span class="tech-tag">Stripe API</span>
            </div>
        </div>
    </section>
</main>