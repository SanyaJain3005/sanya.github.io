<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sanya Jain - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }
        header {
            background: #0073e6;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 10px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            font-size: 1.2rem;
        }
        section {
            padding: 20px;
        }
        .container {
            max-width: 1100px;
            margin: auto;
            overflow: hidden;
            padding: 0 20px;
        }
        .skills, .projects {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }
        .card {
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 20px;
            flex: 1;
            max-width: calc(33% - 40px);
            background: #f9f9f9;
        }
        .card img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: #fff;
            margin-top: 20px;
        }
        @media (max-width: 768px) {
            .card {
                max-width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Sanya Jain</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#experience">Experience</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about" class="container">
        <h2>About Me</h2>
        <p>Hello, I'm Sanya Jain, a second-year MBA candidate at Chicago Booth specializing in Strategy, General Management, and Finance. My experience spans technology, supply chain, finance, and entrepreneurship.</p>
    </section>

    <section id="experience" class="container">
        <h2>Experience</h2>
        <div class="skills">
            <div class="card">
                <h3>Amazon</h3>
                <p>Incoming MBA Leadership Development Program Associate</p>
            </div>
            <div class="card">
                <h3>Procter & Gamble</h3>
                <p>Market Availability Leader, South Asian Markets</p>
                <p>Highlights: $66M annual revenue, new market entry, cost reductions.</p>
            </div>
            <div class="card">
                <h3>Evercore Partners</h3>
                <p>Investment Banking Summer Associate</p>
            </div>
        </div>
    </section>

    <section id="projects" class="container">
        <h2>Projects</h2>
        <div class="projects">
            <div class="card">
                <img src="https://via.placeholder.com/300" alt="Cultural Differences Study">
                <h3>Cultural Differences Study</h3>
                <p>Analyzed risk aversion between Chile and the USA.</p>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/300" alt="Market Penetration">
                <h3>Market Penetration Strategy</h3>
                <p>Collaborated with startups to optimize market strategies.</p>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/300" alt="Pampers Launch">
                <h3>Pampers Product Launch</h3>
                <p>Launched a new variant delivering $7M YoY savings.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="container">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:sanya.jain@chicagobooth.edu">sanya.jain@chicagobooth.edu</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/sanyajain">Sanya Jain</a></p>
        <p>Twitter: <a href="https://twitter.com/sanyajain">@sanyajain</a></p>
    </section>

    <footer>
        <p>&copy; 2025 Sanya Jain</p>
    </footer>
</body>
</html>
