<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>Move Easy – Nachhaltige Mobilität für Studierende</title>
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
            font-size: 54px;
            margin-bottom: 15px;
        }

        header p {
            font-size: 22px;
            max-width: 800px;
            margin: 0 auto 35px;
            opacity: 0.95;
        }

        .cta-btn {
            display: inline-block;
            background: #ffffff;
            color: #0a58ff;
            padding: 16px 34px;
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
            padding: 45px;
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

