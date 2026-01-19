<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>Move Easy – Sustainable Student Mobility</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

    <style>
        :root {
            --primary: #020617;
            --secondary: #0d9488;
            --bg-light: #f8fafc;
            --text-dark: #1e293b;
            --text-muted: #64748b;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', sans-serif;
        }

        body {
            background: var(--bg-light);
            color: var(--text-dark);
        }

        /* HERO */
        header {
            background: linear-gradient(135deg, #020617, #0f172a);
            color: white;
            padding: 130px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 60px;
            font-weight: 700;
            letter-spacing: -1px;
            margin-bottom: 22px;
        }

        header p {
            font-size: 22px;
            max-width: 820px;
            margin: auto;
            color: #cbd5e1;
            line-height: 1.6;
        }

        /* NAV */
        nav {
            background: white;
            padding: 18px 0;
            text-align: center;
            box-shadow: 0 6px 20px rgba(0,0,0,0.08);
            position: sticky;
            top: 0;
            z-index: 20;
        }

        nav a {
            margin: 0 22px;
            text-decoration: none;
            color: var(--primary);
            font-weight: 600;
            font-size: 15px;
        }

        nav a:hover {
            color: var(--secondary);
        }

        /* SECTIONS */
        section {
            max-width: 1120px;
            margin: 80px auto;
            padding: 60px;
            background: white;
            border-radius: 26px;
            box-shadow: 0 25px 60px rgba(0,0,0,0.06);
        }

        h2 {
            font-size: 38px;
            margin-bottom: 26px;
            letter-spacing: -0.5px;
        }

        h3 {
            font-size: 20px;
            color: var(--secondary);
            margin-bottom: 12px;
        }

        p {
            font-size: 18px;
            line-height: 1.85;
            color: var(--text-dark);
        }

        .muted {
            color: var(--text-muted);
        }

        .two-column {
            display: flex;
            gap: 60px;
            margin-top: 40px;
            flex-wrap: wrap;
        }

        .two-column div {
            flex: 1;
            min-width: 280px;
        }

        ul {
            padding-left: 22px;
        }

        li {
            margin-bottom: 14px;
            font-size: 17px;
        }

        .highlight-box {
            margin-top: 45px;
            background: linear-gradient(135deg, #f0fdfa, #ccfbf1);
            padding: 34px;
            border-radius: 20px;
            border-left: 6px solid var(--secondary);
            font-size: 18px;
        }

        iframe {
            width: 100%;
            height: 440px;
            border-radius: 20px;
            border: none;
            margin-top: 35px;
        }

        /* CTA */
        .cta-section {
            background: linear-gradient(135deg, #020617, #0f172a);
            color: white;
            text-align: center;
            padding: 100px 40px;
            border-radius: 30px;
        }

        .cta-section h2 {
            color: white;
        }

        .cta-section p {
            color: #cbd5e1;
        }

        .cta-btn {
            display: inline-block;
            margin-top: 36px;
            background: var(--secondary);
            color: white;
            padding: 20px 44px;
            border-radius: 50px;
            text-decoration: none;
            font-size: 18px;
            font-weight: 600;
        }

        .cta-btn:hover {
            background: #0f766e;
        }

        .calendly-inline-widget {
            margin-top: 50px;
            border-radius: 24px;
            overflow: hidden;
        }

        footer {
            margin-top: 90px;
            background: #020617;
            color: #94a3b8;
            text-align: center;
            padding: 45px 20px;
            font-size: 14px;
        }
    </style>
</head>

<body>

<header>
    <h1>Move Easy</h1>
    <p>
        A digital mobility platform designed to make commuting to university  
        simpler, more affordable and environmentally sustainable.
    </p>
</header>

<nav>
    <a href="#idee">Concept</a>
    <a href="#mehrwert">Value Proposition</a>
    <a href="#video">Pitch</a>
    <a href="#termin">Contact</a>
</nav>

<section id="idee">
    <h2>Our Concept</h2>
    <p class="muted">
        Daily commuting remains a major challenge for students — rising costs,
        limited flexibility and environmental impact are key concerns.
    </p>

    <p>
        <strong>Move Easy</strong> addresses this challenge by combining
        car sharing, bike sharing and public transport information into one
        centralized digital platform, complemented by dedicated university bus routes.
    </p>

    <div class="highlight-box">
        <strong>Vision:</strong> To establish sustainable mobility as the standard
        for students while actively reducing CO₂ emissions in urban environments.
    </div>
</section>

<section id="mehrwert">
    <h2>Value Proposition</h2>
    <div class="two-column">
        <div>
            <h3>For Students</h3>
            <ul>
                <li>Faster and simpler daily commuting</li>
                <li>Lower transportation costs</li>
                <li>Access to sustainable alternatives</li>
            </ul>
        </div>
        <div>
            <h3>For Society</h3>
            <ul>
                <li>Reduced traffic congestion</li>
                <li>Lower environmental impact</li>
                <li>Future-oriented mobility solutions</li>
            </ul>
        </div>
    </div>
</section>

<section id="video">
    <h2>Pitch Video</h2>
    <p class="muted">
        This short pitch introduces the problem, our solution and the impact of Move Easy.
    </p>
    <iframe src="https://www.youtube.com/embed/VIDEO_ID_HIER" allowfullscreen></iframe>
</section>

<section id="termin" class="cta-section">
    <h2>Schedule a Meeting</h2>
    <p>
        Interested in Move Easy?  
        Book a meeting directly with our project team.
    </p>

    <a class="cta-btn"
       href="https://calendly.com/sherinkhetib/neues-meeting"
       target="_blank">
        Book an Appointment
    </a>

    <div class="calendly-inline-widget"
         data-url="https://calendly.com/sherinkhetib/neues-meeting"
         style="min-width:320px;height:650px;">
    </div>
</section>

<footer>
    © 2026 Move Easy · Project by Sherin Khetib & Bayan Ateyeh · HTW Saar
</footer>

</body>
</html>
