<!doctype html>
<html lang="de">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Move Easy — Nachhaltig zur Uni</title>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&family=Poppins:wght@600;700&display=swap" rel="stylesheet">

<!-- Basic styling (inline für einfache Handhabung in Notepad++) -->
<style>
:root{
--green: #4CAF50;
--blue: #1976D2;
--muted: #f5f7f9;
--text: #1f2937;
--card-bg: #ffffff;
--max-width: 1100px;
}
*{box-sizing:border-box}
html,body{height:100%;margin:0;font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;color:var(--text);background:var(--muted);line-height:1.5}
a{color:var(--blue);text-decoration:none}
header{background:linear-gradient(90deg, rgba(25,118,210,0.06), rgba(76,175,80,0.04));border-bottom:1px solid #e6eef7;position:sticky;top:0;z-index:40}
.container{max-width:var(--max-width);margin:0 auto;padding:24px;}
nav{display:flex;align-items:center;justify-content:space-between;gap:16px}
.logo{display:flex;align-items:center;gap:12px}
.logo svg{width:44px;height:44px}
.nav-links{display:flex;gap:14px}
.nav-links a{padding:8px 12px;border-radius:8px;font-weight:600}
.nav-links a:hover{background:rgba(0,0,0,0.04)}
.hero{display:grid;grid-template-columns:1fr;gap:20px;padding:40px 0;align-items:center}
.hero-inner{display:flex;flex-direction:column;gap:18px}
h1{font-family:Poppins,Inter;font-size:2rem;margin:0;color:var(--text)}
p.lead{margin:0;color:#374151}
.cta-row{display:flex;gap:12px;flex-wrap:wrap}
.btn{display:inline-block;padding:10px 16px;border-radius:10px;font-weight:600;cursor:pointer}
.btn-primary{background:var(--green);color:white}
.btn-outline{background:white;border:1px solid #e3eef6}
/* features */
.features{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin:28px 0}
.card{background:var(--card-bg);padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(13,38,59,0.04);border:1px solid rgba(0,0,0,0.03)}
.card h3{margin:10px 0 6px;font-size:1.05rem}
.small{font-size:0.92rem;color:#4b5563}
/* two-column sections */
.two-col{display:grid;grid-template-columns:1fr 420px;gap:22px;align-items:center}
.video-wrap iframe{width:100%;height:260px;border-radius:10px;border:0}
/* timeline */
.timeline{display:flex;flex-direction:column;gap:12px}
.timeline .item{display:flex;gap:12px;align-items:flex-start}
.dot{width:12px;height:12px;border-radius:50%;background:var(--blue);margin-top:6px}
/* team */
.team{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:14px}
.person{display:flex;gap:12px;align-items:center}
.avatar{width:64px;height:64px;border-radius:12px;background:linear-gradient(135deg,var(--green),var(--blue));display:flex;align-items:center;justify-content:center;color:white;font-weight:700}
footer{padding:28px 0;border-top:1px solid #e6eef7;margin-top:30px}
.muted{color:#6b7280}
/* responsive */
@media (max-width:900px){
.two-col{grid-template-columns:1fr}
.hero{padding:28px 0}
h1{font-size:1.6rem}
}
</style>

</head>
<body>

<header>
<div class="container">
<nav>
<div class="logo">
<!-- Einfaches SVG-Logo: kombiniert Fahrrad + Bus + Blatt -->
<svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
<rect width="64" height="64" rx="12" fill="#fff" />
<g transform="translate(8,8)">
<circle cx="8" cy="36" r="6" fill="#1976D2"/>
<circle cx="40" cy="36" r="6" fill="#1976D2"/>
<rect x="6" y="6" width="30" height="18" rx="3" fill="#4CAF50"/>
<path d="M2 22c6-6 18-6 24 0" fill="none" stroke="#fff" stroke-width="2" stroke-linecap="round"/>
</g>
</svg>
<div>
<div style="font-weight:700">Move Easy</div>
<div style="font-size:12px;color:#6b7280">Nachhaltig zur Uni</div>
</div>
</div>

<div class="nav-links" role="navigation" aria-label="Hauptnavigation">
<a href="#konzept">Konzept</a>
<a href="#funktionen">Funktionen</a>
<a href="#video">Video</a>
<a href="#team">Team</a>
</div>
</nav>
</div>
</header>

<main>
<section class="container hero" id="home">
<div class="hero-inner">
<h1>Nachhaltig zur Uni — schnell, einfach & günstig</h1>
<p class="lead">Move Easy bündelt Carsharing, Bikesharing und ÖPNV-Infos, damit Studierende die beste, umweltfreundlichste Verbindung zur Hochschule finden.</p>

<div class="cta-row">
<a class="btn btn-primary" href="#video">Pitch-Video ansehen</a>
<a class="btn btn-outline" href="#konzept">Mehr zum Konzept</a>
</div>

<!-- Kurze Feature-Highlight-Karten -->
<div class="features" aria-hidden="false">
<div class="card">
<strong>ÖPNV & Zusatzbusse</strong>
<p class="small">Informationen zu Linien, Verbindungen und speziellen Busangeboten zur Hochschule.</p>
</div>
<div class="card">
<strong>Carsharing</strong>
<p class="small">Schneller Zugriff auf Carsharing-Partner für kurze und günstige Fahrten.</p>
</div>
<div class="card">
<strong>Bikesharing</strong>
<p class="small">Fahrradstationen in Campusnähe anzeigen und nachhaltiger unterwegs sein.</p>
</div>
</div>
</div>
</section>

<!-- Konzept -->
<section class="container card" id="konzept" style="margin-top:18px;">
<h2 style="margin-top:0">Was ist Move Easy?</h2>
<p>Move Easy ist eine digitale Plattform, die nachhaltige Mobilitätsangebote für Studierende bündelt. Ziel ist es, CO₂ zu reduzieren und gleichzeitig die tägliche Anfahrt zur Hochschule einfacher und günstiger zu machen. Die Plattform stellt Informationen zu Carsharing, Bikesharing und ÖPNV zusammen und bietet Vorschläge für die beste Kombination.</p>

<div style="margin-top:16px;" class="two-col">
<div>
<h3>Unsere Mission</h3>
<p class="small">Move Easy fördert nachhaltige Mobilität im studentischen Alltag, reduziert Emissionen und bietet kostengünstige Alternativen zum individuellen Auto.</p>

<h3 style="margin-top:12px">In Scope</h3>
<ul class="small" style="padding-left:18px;margin-top:6px">
<li>Konzept und Prototyp-Webseite</li>
<li>Design & Branding</li>
<li>Pitch-Video & Präsentation</li>
</ul>

<h3 style="margin-top:12px">Out of Scope</h3>
<ul class="small" style="padding-left:18px;margin-top:6px">
<li>Mobile App-Entwicklung (später möglich)</li>
<li>Komplette Buchungssysteme</li>
</ul>
</div>

<div class="card small">
<strong>Projektziele</strong>
<p class="small">Erstellung eines überzeugenden Konzepts, Produktion eines professionellen Pitch-Videos und Aufbau einer informativen Landingpage (Fertigstellung: 13. Januar 2026).</p>

<div style="margin-top:10px">
<strong>Erwartete Vorteile</strong>
<p class="small">Geringere Kosten für Studierende, weniger CO₂-Ausstoß, verbesserte Erreichbarkeit der Hochschule.</p>
</div>
</div>
</div>
</section>

<!-- Funktionen -->
<section class="container" id="funktionen" style="margin-top:18px;">
<h2>Funktionen (Mockup)</h2>
<div class="features" style="margin-top:12px;">
<div class="card">
<h3>Routen- & Verbindungsübersicht</h3>
<p class="small">Zeigt mehrere Optionen (ÖPNV, Fahrrad, Carsharing) und deren CO₂-Einsparung.</p>
</div>
<div class="card">
<h3>Nachhaltigkeitsfilter</h3>
<p class="small">Filter für emissionsarme Verbindungen, kürzeste Zeit oder niedrigste Kosten.</p>
</div>
<div class="card">
<h3>Partnerintegration</h3>
<p class="small">Anbindung an Carsharing- und Bikesharing-Anbieter (Infos & Links, keine direkte Buchung).</p>
</div>
</div>
</section>

<!-- Video -->
<section class="container card" id="video" style="margin-top:18px;">
<h2>Pitch-Video</h2>
<p class="small">Hier wird das Pitch-Video eingebettet, das unsere Idee, Storyline und Ziele präsentiert.</p>

<div style="margin-top:12px" class="video-wrap">
<!-- TODO: YouTube-ID ersetzen (z.B. ABC123xyz) -->
<iframe src="https://www.youtube.com/embed/VIDEO_ID" title="Move Easy Pitch-Video" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
</section>

<!-- Timeline / Meilensteine -->
<section class="container" style="margin-top:18px;">
<div class="card">
<h2>Projektmeilensteine</h2>
<div class="timeline" style="margin-top:8px">
<div class="item"><div class="dot" aria-hidden="true"></div><div><strong>11.2025</strong> — Ideenfindung & Teamrollen</div></div>
<div class="item"><div class="dot" aria-hidden="true"></div><div><strong>11.2025</strong> — Storyboard & Konzept</div></div>
<div class="item"><div class="dot" aria-hidden="true"></div><div><strong>11.2025 - 12.2025</strong> — Design & Entwicklung der Webseite</div></div>
<div class="item"><div class="dot" aria-hidden="true"></div><div><strong>12.2025 - 01.2026</strong> — Video-Produktion</div></div>
<div class="item"><div class="dot" aria-hidden="true"></div><div><strong>01.2026</strong> — Abschluss & Upload</div></div>
</div>
</div>
</section>

<!-- Team -->
<section class="container card" id="team" style="margin-top:18px;">
<h2>Team</h2>
<div class="team" style="margin-top:12px">
<div class="person">
<div class="avatar" aria-hidden="true">SK</div>
<div>
<strong>Sherin Khetib</strong>
<div class="muted small">Projektleiterin & Webdesignerin — Webentwicklung, Dokumentation, Recherche</div>
</div>
</div>

<div class="person">
<div class="avatar" aria-hidden="true">BA</div>
<div>
<strong>Bayan Ateyeh</strong>
<div class="muted small">Projektleiterin & Webdesignerin — Organisation, Webentwicklung, Dokumentation</div>
</div>
</div>
</div>
</section>

<!-- Kontakt / Footer -->
<footer>
<div class="container">
<div style="display:flex;flex-direction:column;gap:10px">
<div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
<div>
<strong>Move Easy</strong>
<div class="muted small">Teil eines Hochschulprojekts (HTW Saar)</div>
</div>

<div class="muted small">Projektkontakt: <a href="mailto:move-easy@example.com">move-easy@example.com</a> — GitHub: <a href="#">Repository</a></div>
</div>

<div style="margin-top:8px;font-size:12px;color:#9ca3af">Impressum: Diese Webseite ist Teil eines studentischen Projekts; keine kommerzielle Anwendung.</div>
</div>
</div>
</footer>
</main>

<!-- Kleine JS für glattes Scrollen (einfach und kompatibel) -->
<script>
// Smooth scroll for internal links
document.querySelectorAll('a[href^="#"]').forEach(a=>{
a.addEventListener('click', function(e){
const target = document.querySelector(this.getAttribute('href'));
if(target){
e.preventDefault();
window.scrollTo({ top: target.getBoundingClientRect().top + window.scrollY - 16, behavior: 'smooth' });
}
});
});
</script>

</body>
</html>
</html>
