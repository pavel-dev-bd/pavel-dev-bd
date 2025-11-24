<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pavel - Web Developer Resume</title>
    <style>
        :root {
            --primary: #2563eb;
            --secondary: #475569;
            --accent: #f59e0b;
            --light: #f8fafc;
            --dark: #1e293b;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f1f5f9;
            color: var(--dark);
            line-height: 1.6;
        }
        
        .resume-container {
            max-width: 1000px;
            margin: 2rem auto;
            background: white;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(135deg, var(--primary), #1e40af);
            color: white;
            padding: 2.5rem;
            text-align: center;
        }
        
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 5px solid rgba(255, 255, 255, 0.3);
            margin: 0 auto 1.5rem;
            background-color: #ddd;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
        }
        
        .name {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .tagline {
            font-size: 1.2rem;
            opacity: 0.9;
            margin-bottom: 1rem;
        }
        
        .contact-info {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 1.5rem;
            margin-top: 1.5rem;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .main-content {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 0;
        }
        
        .left-column {
            padding: 2.5rem;
        }
        
        .right-column {
            background-color: var(--light);
            padding: 2.5rem;
        }
        
        .section {
            margin-bottom: 2rem;
        }
        
        .section-title {
            color: var(--primary);
            font-size: 1.5rem;
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid var(--primary);
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 1rem;
        }
        
        .skill-category {
            margin-bottom: 1.5rem;
        }
        
        .skill-category h4 {
            color: var(--secondary);
            margin-bottom: 0.5rem;
        }
        
        .skill-items {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
        }
        
        .skill-tag {
            background: var(--primary);
            color: white;
            padding: 0.3rem 0.8rem;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        .project-item {
            margin-bottom: 1.5rem;
            padding-bottom: 1.5rem;
            border-bottom: 1px solid #e2e8f0;
        }
        
        .project-item:last-child {
            border-bottom: none;
        }
        
        .project-title {
            display: flex;
            justify-content: space-between;
            margin-bottom: 0.5rem;
        }
        
        .project-link {
            color: var(--primary);
            text-decoration: none;
            font-weight: 500;
        }
        
        .project-link:hover {
            text-decoration: underline;
        }
        
        .project-description {
            color: var(--secondary);
        }
        
        .about-text {
            color: var(--secondary);
            line-height: 1.7;
        }
        
        .highlight {
            color: var(--primary);
            font-weight: 600;
        }
        
        @media (max-width: 768px) {
            .main-content {
                grid-template-columns: 1fr;
            }
            
            .skills-grid {
                grid-template-columns: 1fr;
            }
            
            .header {
                padding: 1.5rem;
            }
            
            .name {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="resume-container">
        <header class="header">
            <div class="profile-img">P</div>
            <h1 class="name">Pavel</h1>
            <p class="tagline">Web Developer | WordPress | MERN | Elementor Specialist</p>
            <div class="contact-info">
                <div class="contact-item">
                    <span>📧</span>
                    <a href="mailto:pavel.dev.bd@gmail.com" style="color: white;">pavel.dev.bd@gmail.com</a>
                </div>
                <div class="contact-item">
                    <span>🌐</span>
                    <a href="https://devpavel.netlify.app/" style="color: white;">devpavel.netlify.app</a>
                </div>
            </div>
        </header>
        
        <div class="main-content">
            <div class="left-column">
                <section class="section">
                    <h2 class="section-title">About Me</h2>
                    <p class="about-text">
                        Passionate and dedicated web developer with expertise in modern web technologies, 
                        <span class="highlight">WordPress theme development</span>, and full-stack 
                        <span class="highlight">MERN applications</span>. I thrive on building real-world products, 
                        solving complex problems, and creating beautiful, intuitive UI/UX experiences. 
                        Committed to writing clean, efficient code and continuously expanding my skill set.
                    </p>
                </section>
                
                <section class="section">
                    <h2 class="section-title">Featured Projects</h2>
                    
                    <div class="project-item">
                        <div class="project-title">
                            <h3>Personal Portfolio Template</h3>
                            <a href="https://devfolio-site.netlify.app/" class="project-link" target="_blank">Live Demo</a>
                        </div>
                        <p class="project-description">
                            A responsive portfolio template built with modern HTML, CSS, and JavaScript. 
                            Features a clean design with smooth animations and optimized performance.
                        </p>
                    </div>
                    
                    <div class="project-item">
                        <div class="project-title">
                            <h3>Boindy HTML Template</h3>
                            <a href="https://boindy-html.netlify.app/" class="project-link" target="_blank">Live Demo</a>
                        </div>
                        <p class="project-description">
                            A modern business website template with responsive design, interactive elements, 
                            and optimized layout for various screen sizes.
                        </p>
                    </div>
                    
                    <div class="project-item">
                        <div class="project-title">
                            <h3>Foodies HTML Template</h3>
                            <a href="https://foodies-html.netlify.app/" class="project-link" target="_blank">Live Demo</a>
                        </div>
                        <p class="project-description">
                            A restaurant website template featuring attractive food presentation, 
                            online reservation system UI, and menu display components.
                        </p>
                    </div>
                    
                    <div class="project-item">
                        <div class="project-title">
                            <h3>WordPress Ajax Post Filter Plugin</h3>
                        </div>
                        <p class="project-description">
                            Custom WordPress plugin that enables dynamic filtering of posts using Ajax, 
                            improving user experience with seamless content updates.
                        </p>
                    </div>
                </section>
            </div>
            
            <div class="right-column">
                <section class="section">
                    <h2 class="section-title">Technical Skills</h2>
                    <div class="skills-grid">
                        <div class="skill-category">
                            <h4>Frontend</h4>
                            <div class="skill-items">
                                <span class="skill-tag">HTML</span>
                                <span class="skill-tag">CSS</span>
                                <span class="skill-tag">SCSS</span>
                                <span class="skill-tag">JavaScript</span>
                                <span class="skill-tag">Bootstrap</span>
                                <span class="skill-tag">jQuery</span>
                                <span class="skill-tag">React.js</span>
                                <span class="skill-tag">TailwindCSS</span>
                            </div>
                        </div>
                        
                        <div class="skill-category">
                            <h4>Backend</h4>
                            <div class="skill-items">
                                <span class="skill-tag">Node.js</span>
                                <span class="skill-tag">Express.js</span>
                                <span class="skill-tag">MongoDB</span>
                            </div>
                        </div>
                        
                        <div class="skill-category">
                            <h4>WordPress</h4>
                            <div class="skill-items">
                                <span class="skill-tag">Theme Development</span>
                                <span class="skill-tag">Plugin Development</span>
                                <span class="skill-tag">Elementor Widgets</span>
                                <span class="skill-tag">JetEngine</span>
                            </div>
                        </div>
                        
                        <div class="skill-category">
                            <h4>Tools & Others</h4>
                            <div class="skill-items">
                                <span class="skill-tag">REST API</span>
                                <span class="skill-tag">Ajax</span>
                                <span class="skill-tag">Git</span>
                                <span class="skill-tag">Vite</span>
                            </div>
                        </div>
                    </div>
                </section>
                
                <section class="section">
                    <h2 class="section-title">What I Do</h2>
                    <ul style="color: var(--secondary); padding-left: 1.2rem;">
                        <li>Custom WordPress plugin and theme development</li>
                        <li>Elementor custom widgets and dynamic sites</li>
                        <li>MERN stack applications with authentication & dashboard</li>
                        <li>HTML templates and modern UI designs</li>
                        <li>API integrations and automation systems</li>
                    </ul>
                </section>
                
                <section class="section">
                    <h2 class="section-title">Professional Philosophy</h2>
                    <p style="color: var(--secondary); font-style: italic;">
                        "I love creating, learning, and building things that make life easier."
                    </p>
                </section>
            </div>
        </div>
    </div>
</body>
</html>
