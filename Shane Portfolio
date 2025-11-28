<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #ffffff;
            color: #333;
            display: flex;
        }
        .sidebar {
            width: 300px;
            background: #f5f5f5;
            padding: 40px 20px;
            min-height: 100vh;
            box-sizing: border-box;
            position: fixed;
        }
        .sidebar img {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            background: #d4a017;
            display: block;
            margin: 0 auto 20px;
            object-fit: cover;
        }
        .sidebar h1 {
            text-align: center;
            font-size: 28px;
            margin: 10px 0 5px;
        }
        .sidebar h3 {
            text-align: center;
            color: #d4a017;
            margin-bottom: 30px;
        }
        nav a {
            position: relative;
            display: block;
            margin: 10px 0;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        .content {
            margin-left: 300px;
            padding: 50px;
            box-sizing: border-box;
            width: calc(100% - 300px);
        }
        h2 {
            color: #d4a017;
        }
        .project-card {
            border: 1px solid #e0e0e0;
            padding: 20px;
            margin: 15px 0;
            border-radius: 8px;
        }
        /* Smooth Scroll */
        html {
            scroll-behavior: smooth;
        }

        /* Hover & Fade-in Effects */
        nav a:hover {
            color: #d4a017;
        }

        section {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.8s ease, transform 0.8s ease;
        }

        section.show {
            opacity: 1;
            transform: translateY(0);
        }

        /* Project Card Hover Animation */
        .project-card:hover {
            transform: translateY(-5px);
            transition: 0.3s;
            border-color: #d4a017;
        }

        /* Underline animation */
        nav a::after {
            content: "";
            position: absolute;
            left: 0;
            bottom: -3px;
            width: 0%;
            height: 2px;
            background: #d4a017;
            transition: width 0.3s ease;
        }
        nav a:hover::after {
            width: 100%;
        }
</style>
</head>
<body>

<header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="home">
    <h1>Welcome to My Portfolio</h1>
    <p>Hi, I’m <strong>Michael Shane</strong> — a passionate 3D Artist and Designer bringing characters and objects to life through intuitive movements and realistic expressions.</p>
</section>

<section id="about">
    <h2>About Me</h2>
    <p>3D Artist and Designer skilled in animation, 3D modeling, texturing, motion graphics and graphic design. Proficient in industry‑standard tools like Maya, Blender, Photoshop, Illustrator, Premiere Pro and After Effects.
    <br><br>Strong storyteller and collaborative team player with excellent communication and creative thinking to deliver high‑quality animations.</p>

    <h3>Skills</h3>
    <ul>
        <li>Animation</li>
        <li>3D Modeling</li>
        <li>Graphic Designing</li>
        <li>Motion Graphic Designing</li>
        <li>Texturing</li>
    </ul>

    <h3>Software</h3>
    <ul>
        <li>Maya</li>
        <li>Photoshop</li>
        <li>Illustrator</li>
        <li>After Effects</li>
        <li>Premiere Pro</li>
        <li>Blender</li>
    </ul>
</section>

<section id="projects">
    <h2>Experience</h2>
    <div class="project-card">
        <h3>Executive - Designer</h3>
        <p>Luxon Motors Pvt. Ltd — 2025‑Present</p>
    </div>
    <div class="project-card">
        <h3>Freelance Designer / 3D Artist</h3>
        <p>2023‑Present</p>
    </div>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <p>📍 Ernakulam, Kerala, India</p>
    <p>📞 +91 9496651755</p>
    <p>✉️ michaels hane628@gmail.com</p>
    <p>🔗 <a href="https://www.behance.net/michaelshane24" target="_blank" style="color:#00aaff;">Behance Portfolio</a></p>
</section>

<footer>
    © 2025 Your Name
</footer>

<script>
    // Reveal animation when scrolling
    const sections = document.querySelectorAll('section');

    const revealOnScroll = () => {
        const scrollPos = window.scrollY + window.innerHeight;
        sections.forEach(sec => {
            if (sec.offsetTop < scrollPos - 50) {
                sec.classList.add('show');
            }
        });
    };

    window.addEventListener('scroll', revealOnScroll);
    revealOnScroll();
</script>
</body>
</html>
