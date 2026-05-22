<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>

<title>Mirza Uzair Baig Portfolio</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    background:#0f172a;
    color:white;
    font-family:Arial, Helvetica, sans-serif;
    line-height:1.7;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
    padding:40px 0;
}

h1,h2,h3{
    margin-bottom:15px;
}

h1{
    font-size:55px;
    color:#ff0000;
    text-align:center;
    text-shadow:0 0 15px red;
}

.main-heading{
    text-align:center;
    color:#cbd5e1;
    margin-bottom:30px;
    font-size:22px;
}

.section{
    background:#111c34;
    padding:30px;
    margin-top:30px;
    border-radius:20px;
    border:1px solid #1e293b;
    transition:0.4s;
}

.section:hover{
    transform:translateY(-5px);
    box-shadow:0 0 25px rgba(255,0,0,0.2);
}

.section h2{
    color:#ff4d4d;
    margin-bottom:20px;
    font-size:32px;
}

pre{
    background:#020617;
    color:#38bdf8;
    padding:20px;
    border-radius:12px;
    overflow:auto;
    margin-top:20px;
}

p{
    color:#e2e8f0;
}

.contact-icons{
    display:flex;
    justify-content:center;
    align-items:center;
    flex-wrap:wrap;
    gap:15px;
    margin-top:20px;
}

.contact-icons a img{
    transition:0.3s;
}

.contact-icons a img:hover{
    transform:scale(1.1);
}

.contact-info{
    margin-top:25px;
    text-align:center;
    font-size:18px;
}

.contact-info a{
    color:#38bdf8;
    text-decoration:none;
}

.tech-stack{
    text-align:center;
    margin-top:20px;
}

.project{
    background:#0b1120;
    padding:20px;
    margin-top:20px;
    border-radius:15px;
    border-left:5px solid red;
}

.project h3{
    color:#38bdf8;
}

ul{
    padding-left:20px;
    margin-top:10px;
}

li{
    margin-top:8px;
}

.stats{
    display:flex;
    justify-content:center;
    align-items:center;
    flex-wrap:wrap;
    gap:20px;
    margin-top:20px;
}

.stats img{
    width:100%;
    max-width:450px;
    border-radius:15px;
}

blockquote{
    background:#020617;
    padding:20px;
    border-left:5px solid red;
    border-radius:10px;
    font-size:20px;
    color:#f8fafc;
}

footer{
    text-align:center;
    padding:40px 0;
}

@media(max-width:768px){

    h1{
        font-size:38px;
    }

    .main-heading{
        font-size:18px;
    }

    .section h2{
        font-size:26px;
    }

}

</style>

</head>

<body>

<div class="container">

    <!-- HERO SECTION -->

    <h1>⚡ MIRZA UZAIR BAIG ⚡</h1>

    <h3 class="main-heading">
        Frontend Developer • JavaScript Developer • Firebase Enthusiast
    </h3>

    <p align="center">
        <img 
        src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=FF0000&center=true&vCenter=true&width=850&lines=Building+Modern+Web+Experiences;JavaScript+%26+Firebase+Developer;Currently+Learning+Full+Stack+Development;Passionate+About+Clean+UI+Design;Creating+Professional+Web+Applications"
        />
    </p>

    <!-- ABOUT -->

    <div class="section">

        <h2>💫 About Me</h2>

<pre>
const uzair = {

    role: "Frontend Developer",

    technologies: [
        "HTML",
        "CSS",
        "JavaScript",
        "Firebase"
    ],

    currentlyLearning: [
        "Full Stack Development",
        "Advanced JavaScript",
        "REST APIs"
    ],

    portfolioGoal:
    "Building Professional & Modern Web Applications"

};
</pre>

        <p>
            💻 Passionate about creating responsive and interactive web applications with clean UI and smooth user experiences.
            <br><br>

            🚀 Currently learning Full Stack Development and improving real-world development skills through modern projects.
            <br><br>

            ⚡ Strong interest in JavaScript logic, Firebase integration, backend concepts, and creative UI design.
        </p>

    </div>

    <!-- CONTACT -->

    <div class="section">

        <h2>🌐 Contact Information</h2>

        <div class="contact-icons">

            <!-- Gmail -->

            <a href="mailto:mirzauzair448@gmail.com">
                <img src="https://img.shields.io/badge/Gmail-red?style=for-the-badge&logo=gmail&logoColor=white"/>
            </a>

            <!-- GitHub -->

            <a href="https://github.com/uzairBaig395" target="_blank">
                <img src="https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github&logoColor=white"/>
            </a>

            <!-- LinkedIn -->

            <a href="https://www.linkedin.com/in/uzair-baig-1699563ab/" target="_blank">
                <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white"/>
            </a>

            <!-- Facebook -->

            <a href="https://www.facebook.com/profile.php?id=61584799112383" target="_blank">
                <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"/>
            </a>

            <!-- Phone -->

            <a href="tel:03072274835">
                <img src="https://img.shields.io/badge/Phone-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
            </a>

        </div>

        <div class="contact-info">

            📧 Email:
            <a href="mailto:mirzauzair448@gmail.com">
                mirzauzair448@gmail.com
            </a>

            <br><br>

            📱 Phone:
            <a href="tel:03072274835">
                03072274835
            </a>

            <br><br>

            💻 GitHub:
            <a href="https://github.com/uzairBaig395" target="_blank">
                github.com/uzairBaig395
            </a>

            <br><br>

            🔗 LinkedIn:
            <a href="https://www.linkedin.com/in/uzair-baig-1699563ab/" target="_blank">
                Uzair Baig
            </a>

            <br><br>

            📘 Facebook:
            <a href="https://www.facebook.com/profile.php?id=61584799112383" target="_blank">
                Facebook Profile
            </a>

        </div>

    </div>

    <!-- TECH STACK -->

    <div class="section">

        <h2>🛠️ Tech Stack</h2>

        <div class="tech-stack">

            <img src="https://skillicons.dev/icons?i=html,css,javascript,firebase,git,github,vscode" />

        </div>

    </div>

    <!-- PROJECTS -->

    <div class="section">

        <h2>🚀 Featured Projects</h2>

        <div class="project">

            <h3>🔥 Firebase Todo Application</h3>

            <ul>
                <li>Firebase Firestore Integration</li>
                <li>Real-time Data Handling</li>
                <li>Responsive Modern UI</li>
                <li>Dynamic Task Management</li>
            </ul>

        </div>

        <div class="project">

            <h3>🛒 Ecommerce Web Projects</h3>

            <ul>
                <li>Modern Responsive Layouts</li>
                <li>Product Showcase UI</li>
                <li>Interactive Components</li>
                <li>Clean Design Principles</li>
            </ul>

        </div>

        <div class="project">

            <h3>🎮 JavaScript Game Projects</h3>

            <ul>
                <li>DOM Manipulation</li>
                <li>JavaScript Logic Building</li>
                <li>Interactive User Experience</li>
                <li>Dynamic Gameplay Features</li>
            </ul>

        </div>

    </div>

    <!-- GITHUB STATS -->

    <div class="section">

        <h2>📊 GitHub Analytics</h2>

        <div class="stats">

            <img src="https://github-readme-stats.vercel.app/api?username=uzairBaig395&show_icons=true&theme=radical&hide_border=true"/>

            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=uzairBaig395&layout=compact&theme=radical&hide_border=true"/>

        </div>

    </div>

    <!-- STREAK -->

    <div class="section">

        <h2>🔥 Contribution Streak</h2>

        <p align="center">

            <img src="https://streak-stats.demolab.com?user=uzairBaig395&theme=radical&hide_border=true"/>

        </p>

    </div>

    <!-- CURRENT FOCUS -->

    <div class="section">

        <h2>🧠 Current Focus</h2>

        <ul>
            <li>Full Stack Development</li>
            <li>Advanced JavaScript Concepts</li>
            <li>Firebase Authentication</li>
            <li>REST APIs</li>
            <li>UI/UX Improvements</li>
            <li>Clean & Scalable Web Development</li>
        </ul>

    </div>

    <!-- GOALS -->

    <div class="section">

        <h2>🎯 2026 Goals</h2>

        <ul>
            <li>Become a Full Stack Developer</li>
            <li>Build Professional Portfolio Projects</li>
            <li>Learn Backend Development Deeply</li>
            <li>Contribute To Open Source</li>
            <li>Create Full Stack Applications</li>
        </ul>

    </div>

    <!-- MINDSET -->

    <div class="section">

        <h2>⚡ Developer Mindset</h2>

        <blockquote>
            “Consistency and continuous learning build great developers.”
        </blockquote>

    </div>

    <!-- VISITOR COUNTER -->

    <div class="section">

        <h2>👀 Profile Visitors</h2>

        <p align="center">

            <img src="https://komarev.com/ghpvc/?username=Uzairbaig395&color=blue&style=for-the-badge"/>

        </p>

    </div>

    <!-- FOOTER -->

    <footer>

        <img src="https://capsule-render.vercel.app/api?type=waving&color=ff0000&height=120&section=footer"/>

    </footer>

</div>

</body>
</html>
