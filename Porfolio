<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Danish | Creative Developer</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>

:root {
    --primary: #00f2fe;    
    --secondary: #4facfe;  
    --accent: #f093fb;     
    --bg-dark: #0f172a;    
    --text-main: #ffffff;
    --text-muted: #cbd5e1;
    --footer-bg: #020617;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
    scroll-behavior: smooth;
}

body {
    background-color: var(--bg-dark);
    color: var(--text-main);
    overflow-x: hidden;
    background: linear-gradient(-45deg, #0f172a, #1e1b4b, #0f172a, #172554);
    background-size: 400% 400%;
    animation: gradientBG 15s ease infinite;
}

@keyframes gradientBG {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}


::-webkit-scrollbar { width: 10px; }
::-webkit-scrollbar-track { background: var(--bg-dark); }
::-webkit-scrollbar-thumb { background: #334155; border-radius: 5px; }
::-webkit-scrollbar-thumb:hover { background: var(--primary); }


nav {
    position: fixed;
    width: 100%;
    padding: 20px 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: rgba(15, 23, 42, 0.8);
    backdrop-filter: blur(15px);
    z-index: 1000;
    border-bottom: 1px solid rgba(255,255,255,0.05);
    transition: 0.3s;
}

.logo {
    font-size: 28px;
    font-weight: 700;
    color: white;
    text-decoration: none;
    position: relative;
}

.logo span { color: var(--primary); }

.nav-links {
    display: flex;
    list-style: none;
}

.nav-links li { margin-left: 30px; }

.nav-links a {
    color: var(--text-muted);
    text-decoration: none;
    font-weight: 500;
    transition: 0.3s;
    position: relative;
}

.nav-links a:hover { color: var(--primary); }
.nav-links a::after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px;
    bottom: -5px;
    left: 0;
    background: var(--primary);
    transition: 0.3s;
}
.nav-links a:hover::after { width: 100%; }

.menu-toggle { display: none; color: white; font-size: 24px; cursor: pointer; }


section {
    padding: 100px 10%;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.section-title {
    font-size: 35px;
    margin-bottom: 60px;
    text-align: center;
    font-weight: 600;
    position: relative;
    display: inline-block;
    align-self: center;
}

.section-title span { color: var(--primary); }


.hero-container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 50px;
}

.hero-text { flex: 1; }

.hero-text h3 {
    font-size: 22px;
    color: var(--secondary);
    margin-bottom: 10px;
    font-weight: 500;
}

.hero-text h1 {
    font-size: 58px;
    line-height: 1.1;
    margin-bottom: 20px;
    font-weight: 700;
}

.hero-text p {
    color: var(--text-muted);
    font-size: 16px;
    line-height: 1.7;
    margin-bottom: 30px;
    max-width: 500px;
}


.hero-img-box {
    flex: 1;
    display: flex;
    justify-content: center;
    position: relative;
}

.hero-img {
    width: 310px;
    height: 420px;
    object-fit: cover;
    border-radius: 50% 70% 80% 30% / 40% 50% 60% 50%;
    animation: morph 8s ease-in-out infinite, float 6s ease-in-out infinite;
    box-shadow: 0 0 30px rgba(0, 242, 254, 0.2);
    border: 2px solid rgba(255,255,255,0.1);
    z-index: 2;
}

.hero-glow {
    position: absolute;
    width: 350px;
    height: 350px;
    background: var(--primary);
    filter: blur(80px);
    opacity: 0.2;
    border-radius: 50%;
    z-index: 1;
    animation: float 6s ease-in-out infinite reverse;
}

@keyframes float {
    0% { transform: translateY(0px); }
    50% { transform: translateY(-20px); }
    100% { transform: translateY(0px); }
}

@keyframes morph {
    0% { border-radius: 40% 60% 70% 30% / 40% 50% 60% 50%; }
    50% { border-radius: 60% 40% 30% 70% / 60% 30% 70% 40%; }
    100% { border-radius: 40% 60% 70% 30% / 40% 50% 60% 50%; }
}


.btn {
    padding: 12px 30px;
    background: linear-gradient(90deg, var(--primary), var(--secondary));
    color: white;
    border: none;
    border-radius: 30px;
    font-weight: 600;
    cursor: pointer;
    text-decoration: none;
    display: inline-block;
    transition: 0.3s;
    box-shadow: 0 5px 15px rgba(0, 242, 254, 0.3);
}

.btn:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 25px rgba(0, 242, 254, 0.5);
}

.btn-outline {
    background: transparent;
    border: 2px solid var(--secondary);
    color: white;
    margin-left: 15px;
    box-shadow: none;
}

.btn-outline:hover {
    background: rgba(79, 172, 254, 0.1);
    transform: translateY(-3px);
}


.about-card {
    background: rgba(255, 255, 255, 0.03);
    border: 1px solid rgba(255, 255, 255, 0.05);
    padding: 40px;
    border-radius: 20px;
    backdrop-filter: blur(10px);
}

.about-card p {
    line-height: 1.8;
    color: var(--text-muted);
    margin-bottom: 20px;
}


.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
    gap: 25px;
    width: 100%;
}

.skill-card {
    background: rgba(255, 255, 255, 0.05);
    border: 1px solid rgba(255, 255, 255, 0.05);
    padding: 30px 20px;
    border-radius: 15px;
    text-align: center;
    transition: 0.3s;
    position: relative;
    overflow: hidden;
}

.skill-card:hover {
    transform: translateY(-10px);
    background: rgba(255, 255, 255, 0.1);
    border-color: var(--primary);
    box-shadow: 0 10px 30px rgba(0, 242, 254, 0.15);
}

.skill-card i {
    font-size: 50px;
    margin-bottom: 15px;
    color: var(--text-muted);
    transition: 0.3s;
}

.skill-card:hover i.fa-html5 { color: #e34c26; }
.skill-card:hover i.fa-css3-alt { color: #264de4; }
.skill-card:hover i.fa-js { color: #f0db4f; }
.skill-card:hover i.fa-php { color: #777bb4; }
.skill-card:hover i.fa-laravel { color: #ff2d20; }
.skill-card:hover i.fa-bootstrap { color: #7952b3; }
.skill-card:hover i.fa-database { color: #00758f; }
.skill-card:hover i.fa-git-alt { color: #f1502f; }

.skill-card h3 {
    font-size: 18px;
    color: white;
    font-weight: 500;
}


.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
}

.project-card {
    background: rgba(30, 41, 59, 0.5);
    border: 1px solid rgba(255, 255, 255, 0.05);
    border-radius: 15px;
    overflow: hidden;
    transition: 0.3s;
    position: relative;
}

.project-card:hover {
    transform: translateY(-10px);
    border-color: var(--primary);
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
}

.project-img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.project-content {
    padding: 25px;
}

.project-content h3 { margin-bottom: 10px; font-size: 20px; }
.project-content p { color: var(--text-muted); font-size: 14px; margin-bottom: 15px; }


.contact-box {
    background: rgba(255, 255, 255, 0.03);
    padding: 40px;
    border-radius: 20px;
    max-width: 600px;
    width: 100%;
    margin: 0 auto;
    border: 1px solid rgba(255, 255, 255, 0.05);
}

.contact-box input, .contact-box textarea {
    width: 100%;
    padding: 15px;
    margin-bottom: 20px;
    background: rgba(0, 0, 0, 0.3);
    border: 1px solid rgba(255, 255, 255, 0.1);
    border-radius: 8px;
    color: white;
    font-family: 'Poppins', sans-serif;
}

.contact-box input:focus, .contact-box textarea:focus {
    outline: none;
    border-color: var(--primary);
}


footer {
    background: var(--footer-bg);
    position: relative;
    padding-top: 100px; 
    margin-top: 50px;
    font-size: 15px;
    color: var(--text-muted);
}


.wave-top {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
}

.wave-top svg {
    position: relative;
    display: block;
    width: calc(100% + 1.3px);
    height: 80px;
}

.wave-top .shape-fill {
    fill: var(--footer-bg);
}

.footer-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 40px;
    padding: 0 10% 50px 10%;
}

.footer-col h3 {
    color: white;
    font-size: 20px;
    margin-bottom: 25px;
    position: relative;
    padding-bottom: 10px;
}

.footer-col h3::after {
    content: '';
    position: absolute;
    left: 0;
    bottom: 0;
    width: 40px;
    height: 3px;
    background: var(--primary);
    border-radius: 2px;
}

.footer-col p {
    line-height: 1.8;
    margin-bottom: 20px;
}

.footer-col .footer-logo {
    font-size: 26px;
    font-weight: 700;
    color: white;
    text-decoration: none;
    margin-bottom: 15px;
    display: inline-block;
}
.footer-logo span { color: var(--primary); }


.footer-links {
    list-style: none;
}

.footer-links li {
    margin-bottom: 12px;
}

.footer-links a {
    color: var(--text-muted);
    text-decoration: none;
    transition: 0.3s;
    display: flex;
    align-items: center;
}

.footer-links a:hover {
    color: var(--primary);
    padding-left: 5px;
}

.footer-links i {
    margin-right: 10px;
    color: var(--secondary);
    font-size: 14px;
}


.contact-item {
    display: flex;
    align-items: flex-start;
    margin-bottom: 20px;
}

.contact-item i {
    font-size: 18px;
    color: var(--primary);
    margin-right: 15px;
    margin-top: 5px;
}


.footer-socials {
    display: flex;
    gap: 15px;
    margin-top: 20px;
}

.footer-socials a {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 40px;
    height: 40px;
    background: rgba(255,255,255,0.05);
    color: white;
    border-radius: 50%;
    text-decoration: none;
    transition: 0.3s;
    border: 1px solid rgba(255,255,255,0.05);
}

.footer-socials a:hover {
    background: var(--primary);
    color: var(--footer-bg);
    transform: translateY(-3px);
    border-color: var(--primary);
}


.footer-bottom {
    background: #01030f;
    padding: 20px 10%;
    text-align: center;
    border-top: 1px solid rgba(255,255,255,0.05);
    font-size: 14px;
}


#toast {
    visibility: hidden;
    min-width: 250px;
    background-color: var(--primary);
    color: #0f172a;
    text-align: center;
    border-radius: 50px;
    padding: 16px;
    position: fixed;
    z-index: 2000;
    left: 50%;
    bottom: 30px;
    transform: translateX(-50%);
    font-weight: 600;
    box-shadow: 0 5px 15px rgba(0,0,0,0.3);
    opacity: 0;
    transition: opacity 0.3s, bottom 0.3s;
}

#toast.show {
    visibility: visible;
    opacity: 1;
    bottom: 50px;
}

#backToTop {
    position: fixed;
    bottom: 30px;
    right: 30px;
    background: var(--primary);
    color: #0f172a;
    width: 45px;
    height: 45px;
    border-radius: 50%;
    border: none;
    font-size: 20px;
    cursor: pointer;
    display: none; 
    align-items: center;
    justify-content: center;
    z-index: 999;
    box-shadow: 0 0 15px rgba(0, 242, 254, 0.4);
    transition: 0.3s;
}

#backToTop:hover {
    transform: translateY(-3px);
    background: white;
}


@media(max-width: 991px) {
    .hero-container { flex-direction: column-reverse; text-align: center; }
    .hero-text h1 { font-size: 40px; }
    .hero-text p { margin: 0 auto 30px auto; }
    .hero-img { width: 280px; height: 280px; margin-bottom: 30px; }
    .hero-glow { width: 280px; height: 280px; }
    .footer-container { grid-template-columns: 1fr 1fr; }
}

@media(max-width: 768px) {
    nav { padding: 15px 20px; }
    .menu-toggle { display: block; }
    .nav-links {
        position: fixed; top: 70px; left: 0; width: 100%;
        background: #0f172a; flex-direction: column;
        padding: 30px; text-align: center;
        transform: translateY(-150%); transition: 0.4s;
        border-bottom: 1px solid rgba(255,255,255,0.1);
    }
    .nav-links.active { transform: translateY(0); }
    .nav-links li { margin: 15px 0; }
    .footer-container { grid-template-columns: 1fr; }
}


.fade-in { opacity: 0; transform: translateY(30px); transition: 0.8s ease-out; }
.fade-in.active { opacity: 1; transform: translateY(0); }

</style>
</head>
<body>


<nav>
    <a href="#" class="logo">Muhammad Danish<span></span></a>
    <div class="menu-toggle" id="mobile-menu">
        <i class="fas fa-bars"></i>
    </div>
    <ul class="nav-links" id="nav-list">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>


<section id="home" class="fade-in">
    <div class="hero-container">
        <div class="hero-text">
            <h3>Hello, I am</h3>
            <h1>Muhammad Danish 
                <span style="color:var(--primary); font-size: 0.7em; display:block; margin-top:5px;">Frontend Developer</span>
            </h1>
            <p>A passionate Frontend Developer. I turn complex problems into beautiful, responsive, and user-friendly web interfaces.</p>
            <div class="btn-group">
                <a href="#contact" class="btn">Hire Me</a>
                <a href="#projects" class="btn btn-outline">View Work</a>
            </div>
        </div>

        <div class="hero-img-box">
            
            <img src="danish.jpeg" alt="Danish" class="hero-img" onerror="this.src='https://picsum.photos/seed/danish/400/500'">
            <div class="hero-glow"></div>
        </div>
    </div>
</section>


<section id="about" class="fade-in">
    <h2 class="section-title">About <span>Me</span></h2>
    <div class="about-card">
        <p>
            I am currently pursuing my <strong>ADSE (Advanced Diploma in Software Engineering)</strong> from Aptech. I love coding and designing things that live on the internet.
        </p>
        <p>
            My interest in web development started back in 2023 when I decided to try editing custom themes — turns out hacking together HTML & CSS is fun! Since then, I've worked on various projects using PHP, MySQL, and JavaScript.
        </p>
        <div style="margin-top: 25px;">
            <a href="cv.pdf" download class="btn" style="font-size: 14px; padding: 10px 20px;">
                <i class="fas fa-download"></i> Download CV
            </a>
        </div>
    </div>
</section>


<section id="skills" class="fade-in">
    <h2 class="section-title">My <span>Skills</span></h2>
    <div class="skills-grid">
        <div class="skill-card"><i class="fab fa-html5"></i><h3>HTML5</h3></div>
        <div class="skill-card"><i class="fab fa-css3-alt"></i><h3>CSS3</h3></div>
        <div class="skill-card"><i class="fab fa-js"></i><h3>JavaScript</h3></div>
        <div class="skill-card"><i class="fab fa-bootstrap"></i><h3>Bootstrap</h3></div>
        <div class="skill-card"><i class="fab fa-php"></i><h3>PHP</h3></div>
        <div class="skill-card"><i class="fas fa-database"></i><h3>MySQL</h3></div>
        <div class="skill-card"><i class="fab fa-laravel"></i><h3>Laravel</h3></div>
        <div class="skill-card"><i class="fab fa-git-alt"></i><h3>Git</h3></div>
    </div>
</section>


<section id="projects" class="fade-in">
    <h2 class="section-title">Recent <span>Projects</span></h2>
    <div class="projects-grid">
        <div class="project-card">
            <img src="mall.png" class="project-img" alt="Project">
            <div class="project-content">
                <h3>Mall Shopping</h3>
                <p>Mall management system built with HTML and css Javascrit </p>
                <a href="#" class="btn" style="font-size: 12px; padding: 8px 15px;">View Code</a>
            </div>
        </div>
        <div class="project-card">
            <img src="organic.png" class="project-img" alt="Project">
            <div class="project-content">
                <h3>Star Organic</h3>
                <p>Star Organic built with HTML and css Javascrit</p>
                <a href="#" class="btn" style="font-size: 12px; padding: 8px 15px;">View Code</a>
            </div>
        </div>
        <div class="project-card">
            <img src="personal.png" class="project-img" alt="Project">
            <div class="project-content">
                <h3>Portfolio Website</h3>
                <p>My first portfolio using pure HTML and CSS.</p>
                <a href="#" class="btn" style="font-size: 12px; padding: 8px 15px;">View Code</a>
            </div>
        </div>
    </div>
</section>


<section id="contact" class="fade-in">
    <h2 class="section-title">Contact <span>Me</span></h2>
    <div class="contact-box">
        <form id="contactForm">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea rows="5" placeholder="Your Message" required></textarea>
            <button type="submit" class="btn" style="width: 100%;">Send Message</button>
        </form>
    </div>
</section>


<footer>
   
    <div class="wave-top">
        <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
            <path d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.78,31,906.67,72,985.66,92.83c70.05,18.48,146.53,26.09,214.34,3V0H0V27.35A600.21,600.21,0,0,0,321.39,56.44Z" class="shape-fill"></path>
        </svg>
    </div>

    <div class="footer-container">
        
        
        <div class="footer-col">
            <a href="#" class="footer-logo">Danish<span>.</span></a>
            <p>Building digital experiences with passion and clean code. I turn your ideas into reality.</p>
            <div class="footer-socials">
                <a href="#"><i class="fab fa-github"></i></a>
                <a href="#"><i class="fab fa-linkedin-in"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
            </div>
        </div>
        
        
        <div class="footer-col">
            <h3>Quick Links</h3>
            <ul class="footer-links">
                <li><a href="#home"><i class="fas fa-chevron-right"></i> Home</a></li>
                <li><a href="#about"><i class="fas fa-chevron-right"></i> About Me</a></li>
                <li><a href="#skills"><i class="fas fa-chevron-right"></i> My Skills</a></li>
                <li><a href="#projects"><i class="fas fa-chevron-right"></i> Projects</a></li>
                <li><a href="#contact"><i class="fas fa-chevron-right"></i> Contact</a></li>
            </ul>
        </div>
        
        
        <div class="footer-col">
            <h3>Contact Info</h3>
            <div class="contact-item">
                <i class="fas fa-map-marker-alt"></i>
                <span>Karachi, Pakistan</span>
            </div>
            <div class="contact-item">
                <i class="fas fa-envelope"></i>
                <span>danish22@gmail.com</span>
            </div>
            <div class="contact-item">
                <i class="fas fa-phone-alt"></i>
                <span>+92 300 1234567</span>
            </div>
        </div>

    </div>
    
    <div class="footer-bottom">
        <p>&copy; 2026 Danish. All Rights Reserved.</p>
    </div>
</footer>


<button id="backToTop" title="Go to top">
    <i class="fas fa-arrow-up"></i>
</button>


<div id="toast">Message Here</div>

<script>

const menu = document.getElementById('mobile-menu');
const nav = document.getElementById('nav-list');
const links = document.querySelectorAll('.nav-links li a');

menu.addEventListener('click', () => {
    nav.classList.toggle('active');
    const icon = menu.querySelector('i');
    if(nav.classList.contains('active')){
        icon.classList.remove('fa-bars');
        icon.classList.add('fa-times');
    } else {
        icon.classList.remove('fa-times');
        icon.classList.add('fa-bars');
    }
});

links.forEach(link => {
    link.addEventListener('click', () => {
        nav.classList.remove('active');
        menu.querySelector('i').classList.remove('fa-times');
        menu.querySelector('i').classList.add('fa-bars');
    });
});


const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if(entry.isIntersecting){
            entry.target.classList.add('active');
        }
    });
}, { threshold: 0.1 });

document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));


const backToTopBtn = document.getElementById("backToTop");

window.onscroll = function() {
    if (document.body.scrollTop > 300 || document.documentElement.scrollTop > 300) {
        backToTopBtn.style.display = "flex";
    } else {
        backToTopBtn.style.display = "none";
    }
};

backToTopBtn.addEventListener("click", function(){
    window.scrollTo({top: 0, behavior: 'smooth'});
});

function showToast(message) {
    const toast = document.getElementById("toast");
    toast.innerText = message;
    toast.className = "show";
    setTimeout(function(){ toast.className = toast.className.replace("show", ""); }, 3000);
}



document.getElementById('contactForm').addEventListener('submit', function(e){
    e.preventDefault();
    const btn = this.querySelector('button');
    const originalText = btn.innerText;
    
    btn.innerText = "Sending...";

    
    setTimeout(() => {
        showToast("Message Sent Successfully!");
        btn.innerText = "Message Sent!";
        btn.style.background = "#10b981";
        this.reset();
        
        setTimeout(() => {
            btn.innerText = originalText;
            btn.style.background = "";
        }, 3000);
    }, 1500);
});
</script>

</body>
</html>
