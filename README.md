<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>Move Easy – Smart Mobility for Students</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

    <style>
        :root {
            --primary: #0f172a;
            --secondary: #0d9488;
            --accent: #5eead4;
            --bg-light: #f8fafc;
            --text-dark: #1e293b;
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

        header {
            background: linear-gradient(135deg, #020617, #0f172a);
            color: white;
            padding: 110px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 56px;
            font-weight: 700;
            margin-bottom: 18px;
        }

        header p {
            font-size: 20px;
            max-width: 780px;
            margin: auto;
            opacity: 0.9;
        }

        nav {
            background: white;
            padding: 18px 0;
            text-align: center;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            position: sticky;
            top: 0;
            z-index: 20;
        }

        nav a {
            margin: 0 20px;
            text-decoration: none;
            color: var(--primary);
            font-weight: 600;
            font-size: 15px;
        }

        nav a:hover {
            color: var(--secondary);
        }

        section {
            max-width: 1100px;
            margin: 70px auto;
            padding: 50px;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 45px rgba(0,0,0,0.06);
        }

        h2 {
            font-size: 34px;
            color: var(--primary);
            margin-bottom: 22px;
        }

        h3 {
            color: var(--secondary);
            margin-bottom: 10px;
        }

        p {
            font-size: 17px;
            line-height: 1.8;
        }

        .two-column {
            display: flex;
            gap: 50px;
            margin-top: 35px;
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
            margin-bottom: 12px;
        }

        .highlight-box {
            margin-top: 35px;
            background: linear-gradient(135deg, #f0fdfa, #ccfbf1);
            padding: 28px;
            border-radius: 14px;
            border-left: 6px solid var(--secondary);
            font-size: 17px;
        }

        iframe {
            width: 100%;
            height: 420px;
            border-radius: 16px;
            border: none;
            margin-top: 30px;
        }

        .cta-section {
            background: linear-gradient(135deg, #0f172a, #020617);
            color: white;
            text-align: center;
            padding: 90px 30px;
            border-radius: 24px;
        }

        .cta-section h2 {
            color: white;
        }

        .cta-btn {
            display: inline-block;
            margin-top: 30px;
            background: var(--secondary);
            color: white;
            padding: 18px 38px;
            border-radius: 40px;
            text-decoration: none;
            font-size: 18px;
            font-weight: 600;
        }

        .cta-btn:hover {
            background: #0f766e;
        }

        .calendly-inline-widget {
            margin-top: 40px;
            border-radius: 20px;
            overflow: hidden;
        }

        footer {
            margin-top: 80px;
            background: #020617;
            color: #94a3b8;
            text-align: center;
            padding: 40px 20px;
            font-size: 14px;
        }
    </style>
</head>

<body>

<header>
    <h1>Move Easy</h1>
    <p>
        Die smarte Mobilitätsplattform für Studierende –  
        nachhaltig, effizient und zukunftsorientiert.
    </p>
</header>

<nav>
    <a href="#idee">Geschäftsidee</a>
    <a href="#mehrwert">Mehrwert</a>
    <a href="#video">Pitch-Video</a>
    <a href="#termin">Termin buchen</a>
</nav>

<section id="idee">
    <h2>Unsere Geschäftsidee</h2>
    <p>
        Studierende stehen täglich vor der Herausforderung, zuverlässig, günstig
        und nachhaltig zur Universität zu gelangen. Hohe Kosten, Zeitverlust und
        fehlende Alternativen erschweren den Alltag.
    </p>

    <p>
        <strong>Move Easy</strong> vereint Carsharing, Bikesharing und den
        öffentlichen Nahverkehr auf einer digitalen Plattform und ergänzt diese
        durch gezielte Busverbindungen zu Hochschulen.
    </p>

    <div class="highlight-box">
        <strong>Unsere Vision:</strong> Nachhaltige Mobilität als Standard im
        studentischen Alltag etablieren und den CO₂-Ausstoß messbar reduzieren.
    </div>
</section>

<section id="mehrwert">
    <h2>Warum Move Easy?</h2>
    <div class="two-column">
        <div>
            <h3>🎓 Für Studierende</h3>
            <ul>
                <li>Einfachere Wege zur Universität</li>
                <li>Geringere Mobilitätskosten</li>
                <li>Umweltfreundliche Alternativen</li>
            </ul>
        </div>
        <div>
            <h3>🌱 Gesellschaftlicher Nutzen</h3>
            <ul>
                <li>Reduktion von Emissionen</li>
                <li>Weniger Verkehr in Städten</li>
                <li>Zukunftsfähige Mobilitätskonzepte</li>
            </ul>
        </div>
    </div>
</section>

<section id="video">
    <h2>Pitch-Video</h2>
    <p>
        Unser Pitch-Video stellt Problem, Lösung und Mehrwert von Move Easy
        kompakt und verständlich vor.
    </p>
    <iframe src="https://www.youtube.com/embed/VIDEO_ID_HIER" allowfullscreen></iframe>
</section>

<section id="termin" class="cta-section">
    <h2>Jetzt Termin vereinbaren</h2>
    <p>
        Interesse an Move Easy? Buchen Sie direkt einen Termin
        mit unserem Projektteam.
    </p>

    <a class="cta-btn" href="https://calendly.com/IHRLINK" target="_blank">
        Termin buchen
    </a>

    <!-- Optional: Inline Calendly Widget -->
    <div class="calendly-inline-widget"
         data-url="https://calendly.com/IHRLINK"
         style="min-width:320px;height:650px;">
    </div>
</section>

<footer>
    © 2026 Move Easy · Projekt von Sherin Khetib & Bayan Ateyeh · HTW Saar
</footer>

</body>
</html>
