<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>Move Easy – Smarter Umzug, weniger Stress</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Calendly -->
    <link href="https://assets.calendly.com/assets/external/widget.css" rel="stylesheet">
    <script src="https://assets.calendly.com/assets/external/widget.js" async></script>

    <style>
        body {
            margin: 0;
            font-family: "Segoe UI", Arial, sans-serif;
            background: #f4f6f9;
            color: #222;
            line-height: 1.6;
        }

        /* HERO */
        header {
            background: linear-gradient(135deg, #0a58ff, #003ecb);
            color: white;
            padding: 90px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 52px;
            margin-bottom: 15px;
        }

        header p {
            font-size: 22px;
            max-width: 750px;
            margin: 0 auto 30px;
            opacity: 0.95;
        }

        .cta-btn {
            display: inline-block;
            background: #ffffff;
            color: #0a58ff;
            padding: 16px 32px;
            border-radius: 30px;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            transition: 0.3s;
        }

        .cta-btn:hover {
            background: #e8eeff;
        }

        /* NAV */
        nav {
            background: #ffffff;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            padding: 15px 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 10;
        }

        nav a {
            margin: 0 18px;
            text-decoration: none;
            color: #111;
            font-weight: 600;
        }

        nav a:hover {
            color: #0a58ff;
        }

        /* SECTIONS */
        section {
            max-width: 1100px;
            margin: 60px auto;
            padding: 40px;
            background: white;
            border-radius: 14px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.08);
        }

        h2 {
            font-size: 34px;
            margin-bottom: 20px;
            color: #0a58ff;
        }

        /* CARDS */
        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 25px;
            margin-top: 30px;
        }

        .card {
            background: #f7f9ff;
            padding: 25px;
            border-radius: 12px;
            border-left: 5px solid #0a58ff;
        }

        .card h3 {
            margin-top: 0;
        }

        /* VIDEO */
        iframe {
            width: 100%;
            height: 420px;
            border-radius: 12px;
            border: none;
            margin-top: 20px;
        }

        .video-cta {
            text-align: center;
            margin-top: 30px;
        }

        /* FOOTER */
        footer {
            background: #111;
            color: #bbb;
            text-align: center;
            padding: 35px 10px;
        }

        footer a {
            color: #fff;
            text-decoration: none;
        }
    </style>
</head>

<body>

<!-- HERO -->
<header>
    <h1>Move Easy</h1>
    <p>
        Die digitale Plattform für einen stressfreien, transparenten und effizienten Umzug –
        von der Planung bis zur Durchführung.
    </p>

    <a class="cta-btn"
       href="#"
       onclick="Calendly.initPopupWidget({url: 'https://calendly.com/deinname/erstgespraech'}); return false;">
        Jetzt Gespräch vereinbaren
    </a>
</header>

<!-- NAV -->
<nav>
    <a href="#idee">Idee</a>
    <a href="#vorteile">Vorteile</a>
    <a href="#video">Pitch-Video</a>
    <a href="#calendly">Kontakt</a>
</nav>

<!-- IDEE -->
<section id="idee">
    <h2>Unsere Geschäftsidee</h2>
    <p>
        Umzüge sind für viele Menschen stressig, unübersichtlich und zeitintensiv.
        <strong>Move Easy</strong> löst dieses Problem mit einer digitalen Plattform,
        die alle Schritte eines Umzugs zentral bündelt und transparent steuert.
    </p>

    <div class="cards">
        <div class="card">
            <h3>Problem</h3>
            <p>Hoher Organisationsaufwand, fehlende Transparenz, unzuverlässige Anbieter.</p>
        </div>
        <div class="card">
            <h3>Lösung</h3>
            <p>Eine zentrale Plattform zur Planung, Koordination und Buchung von Umzugsservices.</p>
        </div>
        <div class="card">
            <h3>Vision</h3>
            <p>Der Umzug soll so einfach sein wie das Buchen einer Reise.</p>
        </div>
    </div>
</section>

<!-- VORTEILE -->
<section id="vorteile">
    <h2>Mehrwert & Vorteile</h2>

    <div class="cards">
        <div class="card">
            <h3>Für Nutzer</h3>
            <p>✔ Zeitersparnis<br>✔ Klare Kostenübersicht<br>✔ Weniger Stress</p>
        </div>
        <div class="card">
            <h3>Für Unternehmen</h3>
            <p>✔ Digitale Auftragsabwicklung<br>✔ Skalierbarkeit<br>✔ Neue Kundenzugänge</p>
        </div>
        <div class="card">
            <h3>Für Investoren</h3>
            <p>✔ Wachsender Markt<br>✔ Plattformmodell<br>✔ Hohe Skalierbarkeit</p>
        </div>
    </div>
</section>

<!-- VIDEO -->
<section id="video">
    <h2>Pitch-Video</h2>
    <p>
        In unserem maximal 45-sekündigen Pitch-Video erklären wir Zielgruppe,
        Problem, Lösung und unseren Mehrwert – inklusive klarer Handlungsaufforderung.
    </p>

    <!-- YouTube Video -->
    <iframe src="https://www.youtube.com/embed/VIDEO_ID_HIER" allowfullscreen></iframe>

    <div class="video-cta">
        <a class="cta-btn"
           href="#"
           onclick="Calendly.initPopupWidget({url: 'https://calendly.com/deinname/erstgespraech'}); return false;">
            Jetzt Termin nach dem Pitch buchen
        </a>
    </div>
</section>

<!-- CALENDLY -->
<section id="calendly">
    <h2>Termin buchen</h2>
    <p>
        Sie möchten mehr erfahren oder Feedback geben?
        Buchen Sie direkt einen Termin mit dem Projektteam.
    </p>

    <div class="calendly-inline-widget"
         data-url="https://calendly.com/deinname/erstgespraech"
         style="min-width:320px;height:650px;">
    </div>
</section>

<!-- FOOTER -->
<footer>
    <p>
        &copy; 2026 – Move Easy ·
        <a href="mailto:kontakt@moveeasy.de">kontakt@moveeasy.de</a>
    </p>
</footer>

</body>
</html>
