<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>Move Easy</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

   

    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: #f4f6f9;
            color: #222;
        }

        header {
            background: #111;
            color: white;
            padding: 80px 20px;
            text-align: center;
        }

        header img {
            width: 180px;
            margin-bottom: 20px;
        }

        header h1 {
            font-size: 46px;
            margin: 10px 0;
        }

        header p {
            font-size: 20px;
            max-width: 700px;
            margin: 0 auto;
            opacity: 0.9;
        }

        nav {
            background: #ffffff;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
            padding: 15px 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 10;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #111;
            font-weight: bold;
        }

        nav a:hover {
            color: #0a58ff;
        }

        section {
            max-width: 1000px;
            margin: 40px auto;
            padding: 30px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0,0,0,0.08);
        }

        h2 {
            color: #0a58ff;
            margin-bottom: 15px;
            font-size: 30px;
        }

        p {
            font-size: 17px;
            line-height: 1.6;
        }

        .two-column {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            margin-top: 20px;
        }

        .two-column div {
            flex: 1;
            min-width: 300px;
        }

        ul {
            padding-left: 18px;
        }

        li {
            margin-bottom: 10px;
        }

        .highlight-box {
            background: #eef3ff;
            padding: 20px;
            border-left: 5px solid #0a58ff;
            border-radius: 5px;
            margin-top: 25px;
        }

        iframe {
            width: 100%;
            height: 360px;
            border-radius: 10px;
            margin-top: 20px;
            border: none;
        }

        .cta-btn {
            display: inline-block;
            background: #0a58ff;
            color: white;
            padding: 14px 26px;
            border-radius: 8px;
            margin-top: 20px;
            text-decoration: none;
            font-size: 17px;
        }

        .cta-btn:hover {
            background: #003ecb;
        }

        footer {
            background: #111;
            color: #bbb;
            text-align: center;
            padding: 30px 10px;
            margin-top: 50px;
        }

        footer a {
            color: #fff;
            text-decoration: none;
        }
    </style>
</head>
<body>

<header>
    <img src="logo.png" alt="Startup Logo">
    <h1>< Move Easy </h1>
    <p>Unsere Lösung vereinfacht Prozesse, spart Zeit und schafft echten Mehrwert.</p>

    <!-- Calendly Popup Button -->
    <a class="cta-btn"
       href="#"
       onclick="Calendly.initPopupWidget({url: 'https://calendly.com/deinname/erstgespraech'}); return false;">
        Termin vereinbaren
    </a>
</header>

<nav>
    <a href="#idee">Geschäftsidee</a>
    <a href="#vorteile">Vorteile</a>
    <a href="#video">Pitch-Video</a>
    <a href="#calendly">Kontakt</a>
</nav>

<section id="idee">
    <h2>Unsere Geschäftsidee</h2>
    <p>
        Unsere Startup-Idee adressiert ein konkretes Problem im Markt. Viele Nutzer
        kämpfen mit ineffizienten Abläufen und fehlender Transparenz. Genau hier
        setzt unsere digitale Lösung an.
    </p>

    <div class="highlight-box">
        <strong>Vision:</strong> Eine benutzerfreundliche Plattform, die Abläufe
        vereinfacht und nachhaltige Entscheidungen ermöglicht.
    </div>
</section>

<section id="vorteile">
    <h2>Vorteile auf einen Blick</h2>
    <div class="two-column">
        <div>
            <h3>Für Nutzer</h3>
            <ul>
                <li>Einfache Bedienung</li>
                <li>Zeit- und Kostenersparnis</li>
                <li>Hohe Transparenz</li>
            </ul>
        </div>
        <div>
            <h3>Für Stakeholder</h3>
            <ul>
                <li>Skalierbares Geschäftsmodell</li>
                <li>Klares Nutzenversprechen</li>
                <li>Marktpotenzial</li>
            </ul>
        </div>
    </div>
</section>

<section id="video">
    <h2>MVP Pitch-Video</h2>
    <p>Das folgende Video stellt unsere Idee, das Problem und die Lösung kompakt vor.</p>
    <iframe src="https://www.youtube.com/embed/VIDEO_ID_HIER" allowfullscreen></iframe>
</section>

<section id="calendly">
    <h2>Termin buchen</h2>
    <p>
        Vereinbaren Sie direkt einen Termin mit dem Projektleiter oder Projektteam.
    </p>

    <!-- Calendly Inline Widget -->
    <div class="calendly-inline-widget"
         data-url="https://calendly.com/deinname/erstgespraech"
         style="min-width:320px;height:630px;">
    </div>
</section>

<footer>
    <p>&copy; 2026 – Startup Name ·
        <a href="mailto:kontakt@startup.de">kontakt@startup.de</a>
    </p>
</footer>

</body>
</html>


