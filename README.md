<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>Move Easy – Nachhaltige Mobilität für Studierende</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, sans-serif;
            background: #f4f6f9;
            color: #1f2933;
        }

        header {
            background: linear-gradient(135deg, #0f766e, #14b8a6);
            color: white;
            padding: 80px 20px;
            text-align: center;
        }

        /* Container für Logo und H1 nebeneinander */
        .logo-title-container {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 20px; /* Abstand zwischen Logo und Text */
            margin-bottom: 15px;
        }

        header h1 {
            font-size: 52px;
            margin: 0; /* Margin entfernt für bessere Zentrierung zum Logo */
        }

        header .header-logo {
            height: 70px; /* Größe des Logos im Header */
            width: auto;
        }

        header p {
            font-size: 20px;
            max-width: 750px;
            margin: 0 auto;
            opacity: 0.95;
        }

        nav {
            background: #ffffff;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            padding: 15px 30px;
            position: sticky;
            top: 0;
            z-index: 10;
            display: flex;
            justify-content: center; /* Zentriert die Links in der Nav */
        }

        nav a {
            margin: 0 18px;
            text-decoration: none;
            color: #0f766e;
            font-weight: 600;
            font-size: 16px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            max-width: 1050px;
            margin: 50px auto;
            padding: 40px;
            background: white;
            border-radius: 14px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.08);
        }

        h2 {
            color: #0f766e;
            margin-bottom: 20px;
            font-size: 32px;
        }

        p {
            font-size: 17px;
            line-height: 1.7;
        }

        .two-column {
            display: flex;
            flex-wrap: wrap;
            gap: 40px;
            margin-top: 25px;
        }

        .two-column div {
            flex: 1;
            min-width: 280px;
        }

        ul {
            padding-left: 20px;
        }

        li {
            margin-bottom: 12px;
            font-size: 16px;
        }

        .highlight-box {
            background: #e6f4f1;
            padding: 25px;
            border-left: 6px solid #14b8a6;
            border-radius: 8px;
            margin-top: 30px;
            font-size: 17px;
        }

        iframe {
            width: 100%;
            height: 400px;
            border-radius: 12px;
            margin-top: 25px;
            border: none;
        }

        .cta-section {
            background: linear-gradient(135deg, #0f766e, #14b8a6);
            color: white;
            text-align: center;
            padding: 70px 30px;
            border-radius: 16px;
        }

        .cta-section h2 {
            color: white;
        }

        .cta-btn {
            display: inline-block;
            background: white;
            color: #0f766e;
            padding: 16px 34px;
            border-radius: 30px;
            margin-top: 25px;
            text-decoration: none;
            font-size: 18px;
            font-weight: 600;
        }

        .cta-btn:hover {
            background: #f0fdfa;
        }

        footer {
            background: #111827;
            color: #9ca3af;
            text-align: center;
            padding: 35px 10px;
            margin-top: 60px;
            font-size: 14px;
        }
    </style>
</head>

<body>

<header>
    <div class="logo-title-container">
        <img src="moveeasy-logo.png" alt="Move Easy Logo" class="header-logo">
        <h1>Move Easy</h1>
    </div>
    <p>
        Die digitale Mobilitätsplattform für Studierende –  
        einfacher, günstiger und nachhaltiger zur Universität.
    </p>
</header>

<nav>
    <a href="#idee">Geschäftsidee</a>
    <a href="#mehrwert">Mehrwert</a>
    <a href="#video">Pitch-Video</a>
    <a href="#kontakt">Kontakt</a>
</nav>

<section id="idee">
    <h2>Unsere Geschäftsidee</h2>
    <p>
        Viele Studierende pendeln täglich zur Universität und stehen dabei vor
        Herausforderungen wie hohen Kosten, Zeitverlust und fehlenden nachhaltigen
        Alternativen. Genau hier setzt <strong>Move Easy</strong> an.
    </p>

    <p>
        Move Easy ist eine digitale Plattform, die nachhaltige Mobilitätsangebote
        wie <strong>Carsharing</strong>, <strong>Bikesharing</strong> sowie
        Informationen zum <strong>öffentlichen Nahverkehr (ÖPNV)</strong>
        übersichtlich bündelt.
    </p>

    <div class="highlight-box">
        <strong>Vision:</strong> Nachhaltige Mobilität im studentischen Alltag
        etablieren und den CO₂-Ausstoß langfristig reduzieren.
    </div>
</section>

<section id="mehrwert">
    <h2>Der Mehrwert von Move Easy</h2>
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
                <li>Reduktion von Verkehr und Emissionen</li>
                <li>Förderung nachhaltiger Mobilitätskonzepte</li>
