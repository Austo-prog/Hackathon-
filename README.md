# Hackathon-
<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Austin Ongwae - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            transition: background 0.3s, color 0.3s;
        }
        header {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        nav ul {
            list-style: none;
            padding: 0;
            text-align: center;
            background: #444;
            margin: 0;
        }
        nav ul li {
            display: inline;
            padding: 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }
        section {
            padding: 50px;
            text-align: center;
        }
        .blog-post {
            background: white;
            margin: 20px auto;
            padding: 20px;
            border-radius: 10px;
            width: 80%;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            background: #333;
            color: white;
            padding: 20px;
            margin-top: 20px;
        }
        .dark-mode {
            background-color: #222;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Austin Ongwae</h1>
        <p>Web Developer | Learning & Growing</p>
        <button id="dark-mode-toggle">Toggle Dark Mode</button>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#blog">Blog</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="about">
        <h2>About Me</h2>
        <p>I'm Austin Ongwae, a beginner web developer with skills in HTML, CSS, and Python. I'm currently building my skills and working on exciting projects.</p>
        <p>Check out my GitHub: <a href="https://github.com/Austo-prog" target="_blank">Austo-prog</a></p>
    </section>
    <section id="blog">
        <h2>Blog</h2>
        <p>Welcome to my blog! Here are some articles:</p>
        <div id="blog-posts">
            <article class="blog-post">
                <h3>Sample Blog Post</h3>
                <p>This is a sample article. More posts coming soon!</p>
            </article>
        </div>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:austinondari@gmail.com">austinondari@gmail.com</a></p>
    </section>
    <footer>
        <p>&copy; 2025 Austin Ongwae. All rights reserved.</p>
    </footer>
    <script>
        document.getElementById('dark-mode-toggle').addEventListener('click', () => {
            document.body.classList.toggle('dark-mode');
        });
    </script>
</body>
</html>
