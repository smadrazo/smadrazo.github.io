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
            Accomplished technology leader with 25+ years of progressive experience spanning network security, enterprise architecture, and cloud solutions across global Fortune 500 organizations. My career journey has evolved from technical support and systems administration at Siemens to security engineering leadership at Accenture, followed by 13 years of continuous advancement at ExxonMobil culminating in senior architect roles, and now serving in executive cloud architecture positions at Amazon Web Services.
            
            Throughout my career, I have consistently demonstrated the ability to translate complex business requirements into resilient technical solutions, leading multidisciplinary teams and driving strategic initiatives. My expertise encompasses the full spectrum of enterprise technology - from foundational network infrastructure and cybersecurity frameworks to modern cloud architectures and AI implementations. I have successfully architected and implemented critical systems serving millions of users, developed automation workflows that transformed operational efficiency, and established security standards that became organizational benchmarks.
            
            As a certified professional holding CISSP, CCSP, and multiple AWS certifications, I bring deep technical proficiency combined with proven leadership capabilities. My experience spans multiple industries including energy, financial services, and technology consulting, providing me with unique insights into diverse business challenges and regulatory requirements. I excel at building high-performing teams, mentoring technical talent, and fostering innovation while maintaining strict governance and compliance standards.
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

        <div class="experience-item">
            <div class="experience-header">
                <h4 class="job-title">Network System Architect</h4>
                <span class="company">ExxonMobil</span>
                <span class="duration">August 2017 - April 2019</span>
            </div>
            <ul class="achievements">
                <li>Architected global network systems and infrastructure solutions</li>
                <li>Led network engineering and design initiatives</li>
                <li>Implemented enterprise-scale network security solutions</li>
                <li>Managed critical network infrastructure and performance</li>
            </ul>
        </div>

        <div class="experience-item">
            <div class="experience-header">
                <h4 class="job-title">Technical Lead - Global Engineering & Technical Support</h4>
                <span class="company">ExxonMobil</span>
                <span class="duration">February 2015 - August 2017</span>
            </div>
            <ul class="achievements">
                <li>Led global engineering teams and technical support operations</li>
                <li>Drove delivery of quality products and services aligned with strategic objectives</li>
                <li>Provided technical expertise and mentorship across multiple domains</li>
                <li>Interfaced with customers and senior professionals on critical initiatives</li>
                <li>Developed service strategy, workflow automation, and best practices</li>
            </ul>
        </div>

        <div class="experience-item">
            <div class="experience-header">
                <h4 class="job-title">Network & Voice - Global Engineering & Technical Support</h4>
                <span class="company">ExxonMobil</span>
                <span class="duration">February 2013 - August 2015</span>
            </div>
            <ul class="achievements">
                <li>Engineered data center solutions and network infrastructure</li>
                <li>Provided technical support for critical technologies and services</li>
                <li>Developed automation workflows and maintained service standards</li>
                <li>Managed network capacity, performance, and vendor relationships</li>
            </ul>
        </div>

        <div class="experience-item">
            <div class="experience-header">
                <h4 class="job-title">Network Security Engineering & Technical Support</h4>
                <span class="company">ExxonMobil</span>
                <span class="duration">January 2009 - February 2013</span>
            </div>
            <ul class="achievements">
                <li>Engineered and implemented network security controls and infrastructure</li>
                <li>Automated malicious site blocking with Cisco ASA</li>
                <li>Served as Cisco IPS Primary Technical Steward</li>
                <li>Implemented security threat processes and coordinated deployment activities</li>
            </ul>
        </div>

        <div class="experience-item">
            <div class="experience-header">
                <h4 class="job-title">Security Engineer Team Lead</h4>
                <span class="company">Accenture</span>
                <span class="duration">March 2008 - December 2008</span>
            </div>
            <ul class="achievements">
                <li>Led security engineering team and network security infrastructure implementation</li>
                <li>Coordinated installation of firewalls, VPN switches, and intrusion detection systems</li>
                <li>Managed network security deployment activities and customer interactions</li>
                <li>Researched and resolved technology problems in global network environments</li>
            </ul>
        </div>

        <div class="experience-item">
            <div class="experience-header">
                <h4 class="job-title">Security Engineer</h4>
                <span class="company">Accenture</span>
                <span class="duration">January 2007 - March 2008</span>
            </div>
            <ul class="achievements">
                <li>Administered global IGA firewalls (Check Point Firewall-1)</li>
                <li>Managed critical security infrastructure including DNS, authentication servers</li>
                <li>Supported incident investigations as part of CIRC processes</li>
                <li>Analyzed forensic reports and investigated security anomalies</li>
            </ul>
        </div>

        <div class="experience-item">
            <div class="experience-header">
                <h4 class="job-title">Technical Support Carrier ON - R-NCC LATINOAMERICA</h4>
                <span class="company">Siemens S.A</span>
                <span class="duration">December 1999 - January 2007</span>
            </div>
            <ul class="achievements">
                <li>Administered ICSI and ICTS systems for Siemens Latin America</li>
                <li>Designed system interfaces between ICSI and other enterprise systems</li>
                <li>Provided technical support for network equipment and management software</li>
                <li>Supported security solutions for data networks and NGN technologies</li>
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