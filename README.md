# Port
I made this one
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | Portfolio 2026</title>
    <style>
        :root {
            --bg: #0f172a;
            --text: #f8fafc;
            --accent: #38bdf8;
        }
        body {
            background-color: var(--bg);
            color: var(--text);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0 20px;
        }
        .container { max-width: 800px; margin: 0 auto; padding-top: 50px; }
        header { text-align: center; margin-bottom: 50px; }
        h1 { color: var(--accent); margin-bottom: 0; }
        .tagline { opacity: 0.8; font-size: 1.2rem; }
        section { margin-bottom: 40px; }
        .project-card {
            border: 1px solid #334155;
            padding: 20px;
            border-radius: 8px;
            transition: 0.3s;
            margin-bottom: 15px;
        }
        .project-card:hover { border-color: var(--accent); }
        a { color: var(--accent); text-decoration: none; font-weight: bold; }
        a:hover { text-decoration: underline; }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Your Name</h1>
            <p class="tagline">Developer & Problem Solver | 2026</p>
        </header>

        <section id="about">
            <h2>About Me</h2>
            <p>I am a developer focused on building scalable web applications. Currently exploring AI-integrated workflows and front-end performance.</p>
        </section>

        <section id="projects">
            <h2>Featured Projects</h2>
            <div class="project-card">
                <h3>Project Alpha</h3>
                <p>A high-performance dashboard built with React and FastAPI.</p>
                <a href="#">View Source</a> | <a href="#">Live Demo</a>
            </div>
            <div class="project-card">
                <h3>Project Beta</h3>
                <p>Open-source library for data visualization in Python.</p>
                <a href="#">View Source</a>
            </div>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:yourname@example.com">yourname@example.com</a></p>
            <p>Links: <a href="
          
