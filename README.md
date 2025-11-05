<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional CV</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f5f5f5;
            padding: 20px;
        }
        
        .cv-container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 5px;
            overflow: hidden;
        }
        
        /* Header Styles */
        .header {
            background: #2c3e50;
            color: white;
            padding: 30px;
            text-align: center;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 5px;
        }
        
        .header p {
            font-size: 1.1rem;
            opacity: 0.9;
        }
        
        .contact-info {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 15px;
        }
        
        .contact-item {
            margin: 0 15px;
            display: flex;
            align-items: center;
        }
        
        .contact-item i {
            margin-right: 5px;
        }
        
        /* Section Styles */
        .section {
            padding: 25px 30px;
            border-bottom: 1px solid #eee;
        }
        
        .section:last-child {
            border-bottom: none;
        }
        
        .section-title {
            color: #2c3e50;
            margin-bottom: 15px;
            padding-bottom: 8px;
            border-bottom: 2px solid #3498db;
            font-size: 1.4rem;
        }
        
        /* Experience and Education Items */
        .item {
            margin-bottom: 20px;
        }
        
        .item-header {
            display: flex;
            justify-content: space-between;
            margin-bottom: 5px;
        }
        
        .item-title {
            font-weight: bold;
            font-size: 1.1rem;
        }
        
        .item-date {
            color: #7f8c8d;
            font-style: italic;
        }
        
        .item-subtitle {
            color: #3498db;
            margin-bottom: 8px;
        }
        
        /* Skills */
        .skills-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .skill {
            background: #ecf0f1;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        /* Responsive */
        @media (max-width: 600px) {
            .header {
                padding: 20px;
            }
            
            .header h1 {
                font-size: 2rem;
            }
            
            .section {
                padding: 15px 20px;
            }
            
            .item-header {
                flex-direction: column;
            }
            
            .contact-info {
                flex-direction: column;
                align-items: center;
            }
            
            .contact-item {
                margin: 5px 0;
            }
        }
    </style>
</head>
<body>
    <div class="cv-container">
        <!-- Header Section -->
        <header class="header">
            <h1>John Doe</h1>
            <p>Frontend Developer & UI/UX Designer</p>
            <div class="contact-info">
                <div class="contact-item">
                    <i>📧</i> salimlemma@gmail.com
                </div>
                <div class="contact-item">
                    <i>📱</i> +251926152093
                </div>
                <div class="contact-item">
                    <i>📍</i> Ethiopia, Addis Ababa
                    <i></i> https://github.com/salimlemma-sys/Xsalim/edit/main/README.md
                </div>
                <div class="contact-item">
                    <i>🔗</i> linkedin.com/in/salim.lemma
                </div>
            </div>
        </header>
        
        <!-- Professional Summary -->
        <section class="section">
            <h2 class="section-title">Professional Summary</h2>
            <p>Creative and detail-oriented Frontend Developer with 5+ years of experience building responsive and user-friendly web applications. Proficient in HTML, CSS, JavaScript, and modern frameworks like React. Passionate about creating intuitive user experiences and clean, maintainable code.</p>
        </section>
        
        <!-- Work Experience -->
        <section class="section">
            <h2 class="section-title">Work Experience</h2>
            
            <div class="item">
                <div class="item-header">
                    <div class="item-title">Senior Frontend Developer</div>
                    <div class="item-date">2020 - Present</div>
                </div>
                <div class="item-subtitle">Tech Solutions Inc., New York, NY</div>
                <ul>
                    <li>Led development of responsive web applications using React and TypeScript</li>
                    <li>Improved website performance by 40% through code optimization</li>
                    <li>Mentored junior developers and conducted code reviews</li>
                    <li>Collaborated with UX designers to implement pixel-perfect interfaces</li>
                </ul>
            </div>
            
            <div class="item">
                <div class="item-header">
                    <div class="item-title">Frontend Developer</div>
                    <div class="item-date">2018 - 2020</div>
                </div>
                <div class="item-subtitle">Digital Creations LLC, Boston, MA</div>
                <ul>
                    <li>Developed and maintained client websites using HTML, CSS, and JavaScript</li>
                    <li>Implemented responsive designs for mobile and tablet devices</li>
                    <li>Worked with back-end developers to integrate REST APIs</li>
                    <li>Participated in agile development processes and sprint planning</li>
                </ul>
            </div>
        </section>
        
        <!-- Education -->
        <section class="section">
            <h2 class="section-title">Education</h2>
            
            <div class="item">
                <div class="item-header">
                    <div class="item-title">Bachelor of Science in Information Technology</div>
                    <div class="item-date">2014 - 2018</div>
                </div>
                <div class="item-subtitle"> Bule HOra University, MA</div>
                <p>Graduated IT with a 3.5 GPA</p>
            </div>
        </section>
        
        <!-- Skills -->
        <section class="section">
            <h2 class="section-title">Skills</h2>
            
            <div class="skills-list">
                <div class="skill">HTML5</div>
                <div class="skill">CSS3</div>
                <div class="skill">JavaScript</div>
                <div class="skill">React</div>
                <div class="skill">TypeScript</div>
                <div class="skill">Git</div>
                <div class="skill">Responsive Design</div>
                <div class="skill">UI/UX Design</div>
                <div class="skill">Web Performance</div>
                <div class="skill">Agile Methodologies</div>
            </div>
        </section>
        
        <!-- Projects -->
        <section class="section">
            <h2 class="section-title">Projects</h2>
            
            <div class="item">
                <div class="item-header">
                    <div class="item-title">E-commerce Platform Redesign</div>
                </div>
                <p>Led the complete redesign of a major e-commerce platform, resulting in a 25% increase in conversion rates and improved user satisfaction scores.</p>
            </div>
            
            <div class="item">
                <div class="item-header">
                    <div class="item-title">Mobile Banking App</div>
                </div>
                <p>Developed a responsive mobile banking application with React Native, featuring secure authentication and intuitive transaction management.</p>
            </div>
        </section>
    </div>
</body>
</html>
