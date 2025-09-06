<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abbas Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: #f0f0f0;
            line-height: 1.6;
            padding: 20px;
            text-align: center;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            margin-bottom: 40px;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: #64ffda;
        }
        
        h2 {
            font-size: 2rem;
            margin: 30px 0 15px;
            color: #64ffda;
        }
        
        p {
            font-size: 1.1rem;
            margin-bottom: 20px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .profile-img {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #64ffda;
            margin: 20px auto;
            display: block;
        }
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin: 30px 0;
        }
        
        .skill-item {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            padding: 15px;
            width: 140px;
            transition: transform 0.3s ease;
        }
        
        .skill-item:hover {
            transform: translateY(-5px);
            background: rgba(100, 255, 218, 0.2);
        }
        
        .skill-item img {
            width: 60px;
            height: 60px;
            margin-bottom: 10px;
            object-fit: contain;
        }
        
        .contact-links {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 30px;
        }
        
        .contact-link {
            display: inline-block;
            padding: 12px 25px;
            background: rgba(100, 255, 218, 0.2);
            color: #64ffda;
            text-decoration: none;
            border-radius: 5px;
            transition: all 0.3s ease;
            border: 1px solid #64ffda;
        }
        
        .contact-link:hover {
            background: rgba(100, 255, 218, 0.3);
            transform: scale(1.05);
        }
        
        .divider {
            height: 2px;
            background: linear-gradient(90deg, transparent, #64ffda, transparent);
            margin: 40px auto;
            width: 80%;
            max-width: 600px;
        }
        
        @media (max-width: 768px) {
            .skills {
                gap: 15px;
            }
            
            .skill-item {
                width: 120px;
                padding: 10px;
            }
            
            .contact-links {
                flex-direction: column;
                align-items: center;
                gap: 15px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <img src="https://github.com/abbasbayat0/abbasbayat0/assets/120355368/e708bd4a-852f-469a-823a-b735d7133652" alt="Header" style="max-width:100%; border-radius:10px; margin-bottom:30px;">
            <h1>Hello There</h1>
            <p>My name is <strong>ABBAS</strong>, a passionate Front-End Developer who loves new challenges and problem solving. With research and continuous learning, I have the ability to accomplish any task.</p>
        </header>
        
        <h2>Front-End Developer</h2>
        
        <div class="divider"></div>
        
        <h2>My Skills</h2>
        <div class="skills">
            <div class="skill-item">
                <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="Next.js">
                <p>Next.js</p>
            </div>
            <div class="skill-item">
                <img src="https://cdn.worldvectorlogo.com/logos/react-2.svg" alt="React">
                <p>React</p>
            </div>
            <div class="skill-item">
                <img src="https://cdn.worldvectorlogo.com/logos/typescript.svg" alt="TypeScript">
                <p>TypeScript</p>
            </div>
            <div class="skill-item">
                <img src="https://cdn.worldvectorlogo.com/logos/tailwind-css-2.svg" alt="Tailwind CSS">
                <p>Tailwind CSS</p>
            </div>
            <div class="skill-item">
                <img src="https://cdn.worldvectorlogo.com/logos/redux.svg" alt="Redux Toolkit">
                <p>Redux Toolkit</p>
            </div>
            <div class="skill-item">
                <img alt="react-query-seeklogo" src="https://github.com/user-attachments/assets/838644da-1bff-4ac4-9045-271f032acb8d">
                <p>React Query</p>
            </div>
            <div class="skill-item">
                <img src="https://cdn.worldvectorlogo.com/logos/git-icon.svg" alt="Git">
                <p>Git</p>
            </div>
            <div class="skill-item">
                <img src="https://cdn.worldvectorlogo.com/logos/npm-2.svg" alt="NPM">
                <p>NPM</p>
            </div>
        </div>
        
        <div class="divider"></div>
        
        <h2>Contact Me</h2>
        <div class="contact-links">
            <a href="https://t.me/abbasbayat" target="_blank" class="contact-link">Telegram</a>
            <a href="https://www.instagram.com/abbasbayat0" target="_blank" class="contact-link">Instagram</a>
        </div>
    </div>
</body>
</html>
