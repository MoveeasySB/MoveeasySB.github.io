<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>Move Easy – Digitale Mobilität für Studierende</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">

    <style>
        :root {
            --primary: #4f46e5;
            --accent: #22c55e;
            --bg: #f9fafb;
            --white: #ffffff;
            --text: #111827;
            --muted: #6b7280;
            --radius: 14px;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', sans-serif;
        }

        body {
            background: var(--bg);
            color: var(--text);
        }

        /* ================= HERO ================= */
        .hero {
            background: var(--white);
            padding: 110px 20px 90px;
            text-align: center;
        }

        .hero h1 {
            font-size: 56px;
            font-weight: 700;
            margin-bottom: 24px;
        }

        .hero p {
            font-size: 20px;
            max-width: 820px;
            margin: auto;
            color: var(--muted);
            line-height: 1.7;
        }

        /* ================= NAV ================= */
        nav {
            background: var(--white);
            position: sticky;
            top: 0;
            z-index: 10;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            padding: 16px;
            gap: 30px;
        }

        nav a {
            text-decoration: none;
            color: var(--text);
            font-weight: 500;
        }

        nav a:hover {
            color: var(--primary);
        }

        /* ================= SECTIONS ================= */
        section {
            max-width: 1100px;
            margin: 90px auto;
            padding: 0 20px;
        }

        section h2 {
            font-size: 36px;
            margin-bottom: 24px;
        }

        section p {
            font-size: 18px;
            line-height: 1.8;
            color: var(--muted);
        }

        /* ================= GRID ================= */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .card {
            background: var(--white);
            padding: 30px;
            border-radius: var(--radius);
            box-shadow: 0 10px 25px rgba(0,0,0,0.05);
        }

        .card h3 {
            margin-bottom: 10px;
            color: var(--primary);
            font-size: 20px;
        }

        /* ================= VIDEO ================= */
        .video iframe {
            width: 100%;
            height: 450px;
            border-radius: var(--radius);
            border: none;
            margin-top: 30px;
        }

        /* ================= CTA ================= */
        .cta {
            background: linear-gradient(135deg, #eef2ff, #ecfeff);
            padding: 90px 20px;
            text-align: center;
            margin-top: 120px;
        }

        .cta h2 {
            font-size: 40px;
            margin-bottom: 20px;
        }

        .cta p {
            max-width: 700px;
            margin: auto;
        }

        .cta a {
            display: inline-block;
            margin-top: 30px;
            padding: 16px 40px;
            background: var(--primary);
            color: white;
            text-decoration: none;
            border-radius: 40px;
            font-weight: 600;
            font-size: 17px;
        }

        .cta a:hover {
            background: #4338ca;
        }

        .calendly-inline-widget {
            margin-top: 50px;
            border-radius: var(--radius);
            overflow: hidden;
        }

        /* ================= FOOTER ================= */
        footer {
            text-align: center;
            padding: 40px 20px;
            font-size: 14px;
            color: var(--muted);
        }
    </style>
</head>

<body>

<div class="hero">
    <h1>Move Easy</h1>
    <p>
        Move Easy ist eine digitale Plattform, die Studierenden dabei hilft,
        ihren täglichen Weg zur Universität effizienter, kostengünstiger
        und nachhaltiger zu gestalten.
    </p>
</div>

<nav>
    <ul>
        <li><a href="#problem">Problem</a></li>
        <li><a href="#loesung">Lösung</a></li>
        <li><a href="#nutzen">Nutzen</a></li>
        <li><a href="#video">Pitch</a></li>
        <li><a href="#termin">Termin</a></li>
    </ul>
</nav>

<section id="problem">
    <h2>Das Problem</h2>
    <p>
        Viele Studierende sind täglich auf dem Weg zur Universität mit
        hohen Kosten, unübersichtlichen Verkehrsangeboten und mangelnden
        nachhaltigen Alternativen konfrontiert.
    </p>
</section>

<section id="loesung">
    <h2>Unsere Lösung</h2>
    <p>
        Move Easy bündelt Carsharing, Bikesharing und den öffentlichen
        Nahverkehr auf einer zentralen Plattform und ergänzt diese
        durch gezielte Busverbindungen zu Hochschulen.
    </p>
</section>

<section id="nutzen">
    <h2>Was Move Easy bietet</h2>

    <div class="grid">
        <div class="card">
            <h3>Für Studierende</h3>
            <p>Einfache Planung des täglichen Arbeitswegs mit kostengünstigen und nachhaltigen Optionen.</p>
        </div>

        <div class="card">
            <h3>Für Städte</h3>
            <p>Reduzierung von Verkehrsaufkommen und Emissionen im urbanen Raum.</p>
        </div>

        <div class="card">
            <h3>Für die Zukunft</h3>
            <p>Ein skalierbares Mobilitätskonzept mit gesellschaftlichem Mehrwert.</p>
        </div>
    </div>
</section>

<section id="video" class="video">
    <h2>Pitch-Video</h2>
    <p>
        In unserem Pitch-Video stellen wir die Idee von Move Easy
        kompakt und verständlich vor.
    </p>

    <iframe src="https://www.youtube.com/embed/VIDEO_ID_HIER" allowfullscreen></iframe>
</section>

<section id="termin" class="cta">
    <h2>Termin vereinbaren</h2>
    <p>
        Sie möchten mehr über Move Easy erfahren?
        Vereinbaren Sie direkt einen Termin mit unserem Projektteam.
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
    © 2026 Move Easy · Sherin Khetib & Bayan Ateyeh · HTW Saar
</footer>

</body>
</html>
