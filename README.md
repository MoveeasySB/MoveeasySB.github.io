<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>Move Easy – Nachhaltige Mobilität für Studierende</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">

    <style>
        /* ===============================
           Globale Variablen
        =============================== */
        :root {
            --color-primary: #2563eb;
            --color-secondary: #10b981;
            --color-bg: #f8fafc;
            --color-white: #ffffff;
            --color-text: #1e293b;
            --color-text-light: #64748b;
            --border-radius: 16px;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
        }

        body {
            background-color: var(--color-bg);
            color: var(--color-text);
            line-height: 1.7;
        }

        /* ===============================
           Header / Hero
        =============================== */
        header {
            background: linear-gradient(135deg, #eff6ff, #ecfeff);
            padding: 100px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 52px;
            font-weight: 700;
            margin-bottom: 20px;
        }

        header p {
            font-size: 20px;
            max-width: 800px;
            margin: 0 auto;
            color: var(--color-text-light);
        }

        /* ===============================
           Navigation
        =============================== */
        nav {
            background-color: var(--color-white);
            padding: 16px 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 10;
            box-shadow: 0 4px 12px rgba(0,0,0,0.06);
        }

        nav a {
            margin: 0 18px;
            text-decoration: none;
            font-weight: 600;
            color: var(--color-primary);
            font-size: 15px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* ===============================
           Sections
        =============================== */
        section {
            max-width: 1100px;
            margin: 70px auto;
            padding: 50px;
            background-color: var(--color-white);
            border-radius: var(--border-radius);
            box-shadow: 0 15px 35px rgba(0,0,0,0.05);
        }

        section h2 {
            font-size: 34px;
            margin-bottom: 24px;
        }

        section p {
            font-size: 17px;
            margin-bottom: 16px;
        }

        .two-column {
            display: flex;
            gap: 40px;
            flex-wrap: wrap;
            margin-top: 30px;
        }

        .two-column > div {
            flex: 1;
            min-width: 280px;
        }

        ul {
            padding-left: 20px;
        }

        li {
            margin-bottom: 12px;
        }

        /* ===============================
           Highlight Box
        =============================== */
        .highlight {
            margin-top: 30px;
            padding: 28px;
            background-color: #f0fdf4;
            border-left: 6px solid var(--color-secondary);
            border-radius: 12px;
            font-size: 17px;
        }

        /* ===============================
           Video
        =============================== */
        iframe {
            width: 100%;
            height: 420px;
            border-radius: 14px;
            border: none;
            margin-top: 25px;
        }

        /* ===============================
           Call to Action
        =============================== */
        .cta {
            text-align: center;
            background: #f1f5f9;
        }

        .cta a {
            display: inline-block;
            margin-top: 25px;
            padding: 16px 36px;
            background-color: var(--color-primary);
            color: white;
            text-decoration: none;
            border-radius: 40px;
            font-size: 17px;
            font-weight: 600;
        }

        .cta a:hover {
            background-color: #1d4ed8;
        }

        .calendly-inline-widget {
            margin-top: 40px;
            border-radius: 14px;
            overflow: hidden;
        }

        /* ===============================
           Footer
        =============================== */
        footer {
            text-align: center;
            padding: 40px 20px;
            color: var(--color-text-light);
            font-size: 14px;
        }
    </style>
</head>

<body>

<header>
    <h1>Move Easy</h1>
    <p>
        Eine digitale Plattform, die Studierenden hilft,
        einfacher, günstiger und nachhaltiger zur Universität zu gelangen.
    </p>
</header>

<nav>
    <a href="#idee">Geschäftsidee</a>
    <a href="#mehrwert">Mehrwert</a>
    <a href="#video">Pitch-Video</a>
    <a href="#termin">Termin buchen</a>
</nav>

<section id="idee">
    <h2>Geschäftsidee</h2>
    <p>
        Viele Studierende pendeln täglich zur Universität und stehen dabei vor
        Herausforderungen wie steigenden Kosten, Zeitverlust und fehlenden
        nachhaltigen Alternativen.
    </p>
    <p>
        <strong>Move Easy</strong> bündelt Carsharing, Bikesharing und Informationen
        zum öffentlichen Nahverkehr auf einer zentralen Plattform und ergänzt diese
        durch gezielte Busverbindungen zu Hochschulen.
    </p>

    <div class="highlight">
        <strong>Vision:</strong> Nachhaltige Mobilität im studentischen Alltag
        etablieren und den CO₂-Ausstoß langfristig reduzieren.
    </div>
</section>

<section id="mehrwert">
    <h2>Mehrwert von Move Easy</h2>
    <div class="two-column">
        <div>
            <h3>Für Studierende</h3>
            <ul>
                <li>Einfachere und schnellere Wege zur Universität</li>
                <li>Kostengünstige Mobilitätslösungen</li>
                <li>Umweltfreundliche Alternativen</li>
            </ul>
        </div>
        <div>
            <h3>Gesellschaftlicher Nutzen</h3>
            <ul>
                <li>Reduzierung von Emissionen</li>
                <li>Entlastung des Stadtverkehrs</li>
                <li>Förderung nachhaltiger Mobilitätskonzepte</li>
            </ul>
        </div>
    </div>
</section>

<section id="video">
    <h2>Pitch-Video</h2>
    <p>
        Das Pitch-Video stellt Problem, Lösung und Ziel von Move Easy
        kompakt und verständlich vor.
    </p>
    <iframe src="https://www.youtube.com/embed/VIDEO_ID_HIER" allowfullscreen></iframe>
</section>

<section id="termin" class="cta">
    <h2>Termin vereinbaren</h2>
    <p>
        Bei Interesse an Move Easy können Sie hier direkt
        einen Termin mit dem Projektteam buchen.
    </p>

    <a href="https://calendly.com/sherinkhetib/neues-meeting" target="_blank">
        Termin buchen
    </a>

    <div class="calendly-inline-widget"
         data-url="https://calendly.com/sherinkhetib/neues-meeting"
         style="min-width:320px;height:650px;">
    </div>
</section>

<footer>
    © 2026 Move Easy · Projekt von Sherin Khetib & Bayan Ateyeh · HTW Saar
</footer>

</body>
</html>
