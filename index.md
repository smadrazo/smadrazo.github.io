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
            Senior ProServe Cloud Architect at Amazon Web Services with extensive expertise in designing and implementing secure cloud architectures. Specialized in translating complex business objectives into resilient, compliant solutions using TOGAF methodologies and enterprise architecture principles. Proven track record in cybersecurity framework implementation, infrastructure automation, and leading multidisciplinary teams to deliver strategic cloud solutions for enterprise clients, particularly in the financial services sector. Expert in both on-premises and cloud infrastructure with deep proficiency in AWS and Azure platforms.
        </p>
    </section>

    <section class="section">
        <h3 class="section-title">Experience</h3>
        
        <div class="experience-item">
            <div class="experience-header">
                <h4 class="job-title">Sr. ProServe Cloud Architect, Single Threaded Leader (STL)</h4>
                <span class="company">Amazon Web Services (AWS)</span>
                <span class="duration">January 2025 - Present</span>
            </div>
            <ul class="achievements">
                <li>Leading strategic cloud architecture initiatives as Single Threaded Leader</li>
                <li>Designing and implementing secure cloud architectures using TOGAF methodologies</li>
                <li>Translating customer business objectives into resilient, compliant solutions</li>
                <li>Leading multidisciplinary teams to deliver enterprise cloud solutions</li>
            </ul>
        </div>

        <div class="experience-item">
            <div class="experience-header">
                <h4 class="job-title">Sr. Customer Delivery Architect</h4>
                <span class="company">Amazon Web Services (AWS)</span>
                <span class="duration">November 2021 - January 2025</span>
            </div>
            <ul class="achievements">
                <li>Orchestrated solutions for complex business challenges in cloud environments</li>
                <li>Applied infrastructure automation and enhanced CI/CD pipelines</li>
                <li>Ensured strategic alignment with cybersecurity objectives</li>
                <li>Delivered cloud solutions for enterprise clients, particularly in financial services</li>
            </ul>
        </div>

        <div class="experience-item">
            <div class="experience-header">
                <h4 class="job-title">Data Center Solution Architect, IT Fellow</h4>
                <span class="company">ExxonMobil</span>
                <span class="duration">February 2021 - November 2021</span>
            </div>
            <ul class="achievements">
                <li>Architected enterprise data center solutions and infrastructure</li>
                <li>Led technical design and implementation of critical systems</li>
                <li>Provided expertise across multiple technical domains</li>
                <li>Mentored technical teams and drove strategic initiatives</li>
            </ul>
        </div>

        <div class="experience-item">
            <div class="experience-header">
                <h4 class="job-title">Cloud Connectivity System Architect</h4>
                <span class="company">ExxonMobil</span>
                <span class="duration">April 2019 - February 2021</span>
            </div>
            <ul class="achievements">
                <li>Designed cloud connectivity solutions for global enterprise infrastructure</li>
                <li>Implemented network architecture for hybrid cloud environments</li>
                <li>Developed automation workflows and best practices</li>
                <li>Managed network capacity and performance optimization</li>
            </ul>
        </div>
    </section>

    <section class="section">
        <h3 class="section-title">Education</h3>
        
        <div class="education-item">
            <div class="education-header">
                <h4 class="degree">Computer Science, Engineering</h4>
                <span class="school">Universidad de Palermo</span>
                <span class="duration">2004 - 2012</span>
            </div>
        </div>

        <div class="education-item">
            <div class="education-header">
                <h4 class="degree">CISSP® - Certified Information Systems Security Professional</h4>
                <span class="school">ISC2</span>
                <span class="duration">2010</span>
            </div>
            <p class="education-details">Computer and Information Systems Security/Information Assurance</p>
        </div>

        <div class="education-item">
            <div class="education-header">
                <h4 class="degree">CCSP (ISC)2 Certified Cloud Security Professional</h4>
                <span class="school">ISC2</span>
                <span class="duration">2019</span>
            </div>
            <p class="education-details">Cloud Security</p>
        </div>

        <div class="education-item">
            <div class="education-header">
                <h4 class="degree">CCSP - Cisco Certified Security Professional</h4>
                <span class="school">Cisco Education</span>
                <span class="duration">2008 - 2010</span>
            </div>
            <p class="education-details">Network Security</p>
        </div>
    </section>

    <section class="section">
        <h3 class="section-title">Technical Skills</h3>
        
        <div class="skills-grid">
            <div class="skill-category">
                <h4 class="skill-category-title">Architecture & Security</h4>
                <div class="skills">
                    <span class="skill">Security Architecture</span>
                    <span class="skill">Enterprise Architecture</span>
                    <span class="skill">Cloud Architecture</span>
                    <span class="skill">Network Architecture</span>
                </div>
            </div>
            
            <div class="skill-category">
                <h4 class="skill-category-title">Cloud Platforms</h4>
                <div class="skills">
                    <span class="skill">AWS</span>
                    <span class="skill">Azure</span>
                    <span class="skill">Infrastructure Automation</span>
                    <span class="skill">CI/CD Pipelines</span>
                </div>
            </div>
            
            <div class="skill-category">
                <h4 class="skill-category-title">Specializations</h4>
                <div class="skills">
                    <span class="skill">CyberSecurity</span>
                    <span class="skill">Financial Services</span>
                    <span class="skill">Team Leadership</span>
                    <span class="skill">TOGAF</span>
                </div>
            </div>
        </div>
    </section>

    <section class="section">
        <h3 class="section-title">Certifications</h3>
        
        <div class="skills-grid">
            <div class="skill-category">
                <h4 class="skill-category-title">AWS Certifications</h4>
                <div class="skills">
                    <span class="skill">AWS Certified AI Practitioner</span>
                    <span class="skill">AWS Generative AI Foundational (L100)</span>
                    <span class="skill">AWS Knowledge: Networking Core</span>
                    <span class="skill">AWS Partner: Cloud Economics Accreditation</span>
                </div>
            </div>
            
            <div class="skill-category">
                <h4 class="skill-category-title">Security & Cloud</h4>
                <div class="skills">
                    <span class="skill">CISSP® - Certified Information Systems Security Professional</span>
                    <span class="skill">CCSP (ISC)2 Certified Cloud Security Professional</span>
                    <span class="skill">Microsoft Certified: Azure Fundamentals</span>
                </div>
            </div>
            
            <div class="skill-category">
                <h4 class="skill-category-title">Network & Infrastructure</h4>
                <div class="skills">
                    <span class="skill">CCSP - Cisco Certified Security Professional</span>
                </div>
            </div>
        </div>
    </section>

   <!-- <section class="section">
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
    </section> -->
</main>