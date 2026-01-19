<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Move Easy – Nachhaltige Mobilität für Studierende</title>
    <meta name="description" content="Move Easy – Die digitale Plattform für nachhaltige, günstige und einfache Mobilität für Studierende.">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', sans-serif;
        }

        body {
            background-color: #f9fafb;
            color: #1f2933;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, #0f766e, #14b8a6);
            color: white;
            padding: 80px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }

        header p {
            font-size: 1.2rem;
            max-width: 800px;
            margin: auto;
        }

        section {
            padding: 70px 20px;
            max-width: 1100px;
            margin: auto;
        }

        h2 {
            font-size: 2rem;
            margin-bottom: 20px;
            color: #0f766e;
        }

        .video-container {
            position: relative;
            padding-bottom: 56.25%;
            height: 0;
            overflow: hidden;
            border-radius: 12px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }

        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .feature-box {
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }

        .feature-box h3 {
            margin-bottom: 10px;
            color: #14b8a6;
        }

        .cta {
            background: #0f766e;
            color: white;
            text-align: center;
            padding: 80px 20px;
        }

        .cta h2 {
            color: white;
            margin-bottom: 20px;
        }

        .cta a {
            background: #14b8a6;
            color: white;
            padding: 15px 35px;
            text-decoration: none;
            border-radius: 30px;
            font-size: 1.1rem;
            font-weight: 600;
            transition: background 0.3s ease;
        }

        .cta a:hover {
            background: #0d9488;
        }

        footer {
            background: #111827;
            color: #9ca3af;
            text-align: center;
            padding: 30px 20px;
            font-size: 0.9rem;
        }
    </style>
</head>

<body>

<header>
    <h1>Move Easy</h1>
    <p>Die digitale Mobilitätsplattform für Studierende – einfacher, günstiger und nachhaltiger zur Universität.</p>
</header>

<section>
    <h2>🎥 Unser Pitch-Video</h2>
    <div class="video-container">
        <iframe 
            src="https://www.youtube.com/embed/YOUTUBE_VIDEO_ID" 
            frameborder="0" 
            allowfullscreen>
        </iframe>
    </div>
</section>

<section>
    <h2>🚀 Unsere Idee</h2>
    <p>
        <strong>Move Easy</strong> ist eine digitale Plattform für Studierende, die täglich zur Universität pendeln.
        Unser Ziel ist es, Mobilität einfacher, kostengünstiger und umweltfreundlicher zu gestalten.
    </p>
    <p>
        Die Plattform bündelt nachhaltige Mobilitätsangebote wie <strong>Carsharing</strong>,
        <strong>Bikesharing</strong> sowie Informationen zum <strong>öffentlichen Nahverkehr (ÖPNV)</strong>.
        Zusätzlich fördern wir den Einsatz von speziell eingerichteten Bussen für Universitäten und Hochschulen.
    </p>

    <div class="features">
        <div class="feature-box">
            <h3>🌱 Nachhaltig</h3>
            <p>Reduktion des CO₂-Ausstoßes durch intelligente Mobilitätslösungen.</p>
        </div>
        <div class="feature-box">
            <h3>💸 Kostengünstig</h3>
            <p>Günstige Alternativen für Studierende durch Sharing-Modelle.</p>
        </div>
        <div class="feature-box">
            <h3>⏱ Effizient</h3>
            <p>Schnell die beste Verbindung zur Universität finden – alles auf einer Plattform.</p>
        </div>
    </div>
</section>

<section>
    <h2>🎯 Unsere Vision</h2>
    <p>
        Move Easy möchte nachhaltige Mobilität im studentischen Alltag etablieren.
        Wir verbinden Innovation, Umweltbewusstsein und Nutzerfreundlichkeit, um einen
        echten gesellschaftlichen Mehrwert zu schaffen.
    </p>
</section>

<section class="cta">
    <h2>📅 Interesse geweckt?</h2>
    <p>Vereinbaren Sie jetzt einen Termin mit unserem Projektteam.</p>
    <br>
    <a href="https://calendly.com/IHRLINK" target="_blank">
        Termin buchen
    </a>
</section>

<footer>
    <p>© 2026 Move Easy | Projekt von Sherin Khetib & Bayan Ateyeh | HTW Saar</p>
</footer>

</body>
</html>

