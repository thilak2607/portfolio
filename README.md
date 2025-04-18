<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Thilageshwar R - Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Orbitron', sans-serif;
      background-color: #0d1117;
      color: #c9d1d9;
      line-height: 1.6;
    }
    header {
      background: url('bike image thilak.jpg') no-repeat center center/cover;
      height: 300px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: white;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.7);
      position: relative;
    }
    header h1 {
      font-size: 3rem;
      animation: slideIn 2s ease-out forwards;
    }
    header p {
      font-size: 1.2rem;
      animation: fadeIn 4s ease-in-out infinite alternate;
    }
    @keyframes slideIn {
      from { transform: translateY(-50px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
    @keyframes fadeIn {
      from { opacity: 0.6; }
      to { opacity: 1; }
    }
    .profile-pic {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 4px solid white;
      position: absolute;
      bottom: -75px;
      left: 50%;
      transform: translateX(-50%);
      object-fit: cover;
    }
    main {
      padding: 5rem 2rem 2rem;
      max-width: 900px;
      margin: auto;
    }
    .section {
      background-color: #161b22;
      padding: 1.5rem;
      margin-bottom: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.3);
      animation: fadeIn 2s ease-in-out;
    }
    h2 {
      color: #58a6ff;
    }
    ul li {
      margin: 0.5rem 0;
    }
    .contact-icons a {
      color: #58a6ff;
      margin-right: 15px;
      text-decoration: none;
      transition: transform 0.3s;
    }
    .contact-icons a:hover {
      transform: scale(1.2);
    }
    footer {
      text-align: center;
      padding: 2rem;
      background-color: #0d1117;
      color: #8b949e;
    }
  </style>
</head>
<body>
  <header>
    <h1>Thilageshwar R</h1>
    <p>Aspiring Full Stack Developer</p>
    <img src="beach image thilak.jpg" alt="Profile Picture" class="profile-pic">
  </header>
  <main>
    <div class="section">
      <h2>About Me</h2>
      <p>I’m a 2nd year Computer Science Engineering student at R P Sarathy Institute of Technology. I aim to become a full stack developer with strong knowledge in cloud computing, data science, and IoT.</p>
    </div>
    <div class="section">
      <h2>Skills</h2>
      <ul>
        <li>Full Stack Development</li>
        <li>Cloud Computing</li>
        <li>Data Science & Analytics</li>
        <li>IoT</li>
      </ul>
    </div>
    <div class="section">
      <h2>Certificates</h2>
      <ul>
        <li>Introduction to Generative AI - Simplilearn</li>
        <li>CSS, HTML - Udemy</li>
        <li>Excel Beginner to Expert - Udemy</li>
        <li>Learning Python - Infosys Springboard</li>
        <li>Full Stack Development 101 - Simplilearn</li>
        <li>CSS, Bootstrap, JavaScript & Python Stack - Udemy</li>
        <li>Machine Learning & Data Science with LangChain & LLMs</li>
        <li>JavaScript - IBM</li>
        <li>AI for Beginners - HP</li>
        <li>Data Science & Analytics - HP</li>
      </ul>
    </div>
    <div class="section">
      <h2>Internships</h2>
      <ul>
        <li>JavaScript (2.1.25 - 22.1.25)</li>
        <li>IoT & Embedded System (13.2.2024 - 22.02.2024)</li>
        <li>Data Science (31.7.24 - 4.8.24)</li>
        <li>Full Stack Web Development (1.3.25 - 1.8.25)</li>
      </ul>
    </div>
    <div class="section">
      <h2>Languages</h2>
      <p>Tamil, English, Telugu</p>
    </div>
    <div class="section">
      <h2>Contact</h2>
      <p>Email: thilageshwar2607@gmail.com</p>
      <p>Location: Tamil Nadu, India</p>
      <div class="contact-icons">
        <a href="https://www.linkedin.com/in/thilageshwar-r-683631300" target="_blank">LinkedIn</a>
        <a href="https://github.com/thilak2607" target="_blank">GitHub</a>
        <a href="https://instagram.com/thilak_2607" target="_blank">Instagram</a>
        <a href="https://twitter.com/thilak_2607" target="_blank">Twitter</a>
      </div>
    </div>
  </main>
  <footer>
    <p>&copy; 2025 Thilageshwar R. All rights reserved.</p>
  </footer>
</body>
</html>
