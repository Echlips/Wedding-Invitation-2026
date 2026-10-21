<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Join us to celebrate a beautiful Islamic wedding filled with love, faith, and blessings.">
    <title>Muhsina & Abdulqudus Wedding Invitation</title>
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Amiri:wght@400;700&family=Cormorant+Garamond:wght@400;500;600;700&family=DM+Sans:wght@400;500;700&display=swap" rel="stylesheet">

<style>
:root {
    --green: #50C878;
    --deep-wine: #351421;
    --wine: #541b30;
    --antique-gold: #c5a45b;
    --light-gold: #ead8a6;
    --ivory: #f8f3e9;
    --white: #ffffff;
    --text-dark: #261b20;
    --muted: #d8c9ca;
    --black: #000000;

    --heading-font: "Cormorant Garamond", Georgia, serif;
    --body-font: "DM Sans", Arial, sans-serif;
    --arabic-font: "Amiri", Georgia, serif;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
    scroll-padding-top: 90px;
}

body {
    background: var(--ivory);
    color: var(--ivory);
    font-family: var(--body-font);
    line-height: 1.7;
}

a {
    color: inherit;
    text-decoration: none;
}

button, input, select {
    font: inherit;
}

/* Background Video */
.bg-video-container {
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    overflow: hidden;
    z-index: -2;
}

.bg-video-container video {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.bg-video-overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    background: rgba(23, 17, 19, 0.88);
    z-index: -1;
    pointer-events: none;
}

/* Marquee */
.Muhsina-Abdulqudus-banner {
    overflow: hidden;
    background: rgba(23, 17, 19, 0.95);
    border-bottom: 1px solid var(--antique-gold);
    padding: 12px 0;
    white-space: nowrap;
    position: sticky;
    top: 0;
    z-index: 1002;
}

.Muhsina-Abdulqudus-track {
    display: flex;
    align-items: center;
    gap: 45px;
    width: max-content;
    animation: Muhsina-AbdulqudusMarquee 22s linear infinite;
}

.Muhsina-Abdulqudus-track span {
    color: var(--green);
    font-family: var(--heading-font);
    font-size: 22px;
    font-weight: 600;
    letter-spacing: 2px;
}

.Muhsina-Abdulqudus-divider {
    color: var(--antique-gold);
    font-size: 16px;
}

@keyframes Muhsina-AbdulqudusMarquee {
    from { transform: translateX(0); }
    to { transform: translateX(-33.333%); }
}

/* Navigation */
header {
    position: sticky;
    top: 48px;
    z-index: 1000;
    background: rgba(23, 17, 19, 0.95);
    border-bottom: 1px solid rgba(197, 164, 91, 0.4);
    backdrop-filter: blur(12px);
    transition: all 0.3s ease-in-out;
}

nav {
    max-width: 1400px;
    margin: auto;
    padding: 18px 5%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 25px;
}

.logo {
    color: var(--light-gold);
    font-size: 24px;
    font-family: var(--arabic-font);
    white-space: nowrap;
}

nav ul {
    display: flex;
    list-style: none;
    gap: 20px;
}

nav ul li a {
    font-size: 12px;
    letter-spacing: 1px;
    color: var(--ivory);
    transition: color 0.3s ease;
}

nav ul li a:hover {
    color: var(--green);
}

header.shrink {
    background: transparent;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.4);
}

header.shrink nav {
    padding: 12px 5%;
}

/* Sections */
section {
    padding: 90px 8%;
}

h1, h2, h3 {
    font-family: var(--heading-font);
    font-weight: 500;
    line-height: 1.15;
}

h2 {
    font-size: clamp(38px, 5vw, 60px);
    margin-bottom: 20px;
}

p {
    margin-bottom: 16px;
}

/* Hero */
#home {
    min-height: 90vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    position: relative;
    overflow: hidden;
    color: var(--ivory);
    background: transparent;
}

#home > p:first-child {
    color: var(--light-gold);
    font-family: var(--arabic-font);
    font-size: clamp(32px, 5vw, 48px);
    letter-spacing: 2px;
    margin-bottom: 10px;
}

#home > p:nth-of-type(2) {
    color: var(--antique-gold);
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 3px;
    margin-bottom: 25px;
}

#home h2 {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 20px 0;
    color: var(--light-gold);
    font-size: clamp(28px, 4vw, 42px);
}

#home h2 span {
    color: var(--green);
    font-size: 20px;
    font-style: italic;
    font-family: var(--body-font);
    margin: 10px 0;
}

#home h1 {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 25px 0;
    color: var(--ivory);
    font-size: clamp(50px, 9vw, 110px);
    line-height: 0.95;
}

#home h1 span {
    color: var(--green);
    font-size: 35px;
    font-style: italic;
    margin: 12px 0;
}

#home p:nth-of-type(3) {
    color: var(--muted);
    font-size: 16px;
    line-height: 1.8;
    max-width: 620px;
}
/* Elegant Bride and Groom Names */

.couple-card {
    width: min(950px, 100%);
    margin: 30px auto;
    padding: 25px 10px;
    background: transparent;
    border: none;
    border-radius: 0;
    box-shadow: none;
    text-align: center;
}

.couple-card-label {
    color: var(--antique-gold);
    font-family: var(--body-font);
    font-size: 11px;
    font-weight: 700;
    letter-spacing: 4px;
    margin: 18px 0;
}

.couple-card h1 {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 8px;
    margin: 0;
    color: var(--light-gold);
    font-family: var(--heading-font);
    font-size: clamp(34px, 6vw, 65px);
    line-height: 1.12;
}

.couple-card .bride-name,
.couple-card .groom-name {
    display: block;
    max-width: 100%;
    color: var(--light-gold);
    font-size: inherit;
    font-style: normal;
    overflow-wrap: anywhere;
}

.couple-card .couple-ampersand {
    color: var(--green);
    font-size: 35px;
    font-style: italic;
    margin: 0;
}

.name-divider {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 14px;
    width: 85%;
    max-width: 550px;
    margin: 0 auto;
    color: var(--antique-gold);
}

.name-divider span {
    flex: 1;
    height: 1px;
    background: linear-gradient(
        to right,
        transparent,
        var(--antique-gold)
    );
}

.name-divider span:last-of-type {
    background: linear-gradient(
        to left,
        transparent,
        var(--antique-gold)
    );
}

.name-divider b {
    font-size: 17px;
    letter-spacing: 4px;
}

.bottom-divider {
    margin-top: 25px;
}

@media (max-width: 600px) {
    .couple-card {
        padding: 20px 0;
        margin: 20px auto;
    }

    .couple-card h1 {
        font-size: clamp(30px, 7.5vw, 43px);
    }

    .couple-card-label {
        letter-spacing: 3px;
    }

    .name-divider {
        width: 95%;
    }
}

/* Buttons */
.button, #home > a, #henna-party > a, #walima > a, #nikkah > a, #wedding-reception > a, #closing > a {
    display: inline-block;
    padding: 15px 30px;
    border: 1px solid var(--antique-gold);
    background: var(--green);
    color: var(--deep-wine);
    font-size: 11px;
    font-weight: 700;
    letter-spacing: 2px;
    text-align: center;
    border-radius: 4px;
    transition: background 0.3s ease, color 0.3s ease, transform 0.3s ease;
}

.button:hover, #home > a:hover, #henna-party > a:hover, #walima > a:hover, #nikkah > a:hover, #wedding-reception > a:hover, #closing > a:hover {
    background: transparent;
    color: var(--light-gold);
    transform: translateY(-3px);
}

/* Countdown */
#countdown {
    text-align: center;
    background: transpare;
    backdrop-filter: blur(8px);
    border-top: 1px solid rgba(197, 164, 91, 0.3);
    border-bottom: 1px solid rgba(197, 164, 91, 0.3);
}

#countdown h2 {
    color: var(--green);
}

#countdown > p {
    color: var(--muted);
}

#countdown-timer {
    max-width: 850px;
    margin: 40px auto 0;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 15px;
}

#countdown-timer > div {
    padding: 25px 10px;
    background: rgba(23, 17, 19, 0.85);
    border: 1px solid rgba(197, 164, 91, 0.5);
    border-radius: 6px;
}

#countdown-timer span {
    display: block;
    color: var(--light-gold);
    font-family: var(--heading-font);
    font-size: clamp(35px, 6vw, 55px);
    line-height: 1.2;
}

#countdown-timer p {
    margin: 5px 0 0;
    color: var(--muted);
    font-size: 11px;
    letter-spacing: 2px;
    text-transform: uppercase;
}

/* Event Sections */
section[id$="party"], section#walima, section#nikkah, section#wedding-reception {
    background: 
       transparent;
    backdrop-filter: blur(6px);
    border-bottom: 1px solid rgba(197, 164, 91, 0.2);
}

section[id$="party"] > p:first-child,
section#walima > p:first-child,
section#nikkah > p:first-child,
section#wedding-reception > p:first-child {
    color: var(--green);
    font-size: 11px;
    letter-spacing: 3px;
    font-weight: 600;
}

section[id$="party"] h2, section#walima h2, section#nikkah h2, section#wedding-reception h2 {
    color: var(--green);
}

section[id$="party"] > p:nth-of-type(2), section#walima > p:nth-of-type(2), section#nikkah > p:nth-of-type(2), section#wedding-reception > p:nth-of-type(2) {
    max-width: 650px;
    color: var(--muted);
    line-height: 1.8;
}

.event-details {
    max-width: 650px;
    margin: 30px 0;
    border-top: 1px solid rgba(197, 164, 91, 0.4);
}

.event-details p {
    padding: 16px 0;
    margin: 0;
    border-bottom: 1px solid rgba(197, 164, 91, 0.4);
    color: var(--ivory);
    font-size: 16px;
}

.event-details strong {
    display: inline-block;
    min-width: 90px;
    color: var(--green);
}

/* Additional Info */
#details {
    text-align: center;
    background: transparent;
    backdrop-filter: blur(8px);
}

#details h2 {
    color: var(--green);
}

.information-card {
    max-width: 800px;
    margin: 25px auto;
    padding: 30px;
    background: rgba(23, 17, 19, 0.85);
    border: 1px solid rgba(197, 164, 91, 0.4);
    border-radius: 6px;
}

.information-card h3 {
    color: var(--green);
    font-size: 28px;
    margin-bottom: 10px;
}

.information-card p {
    max-width: 600px;
    margin: auto;
    color: var(--muted);
}

#calendar-button {
    margin-top: 25px;
    padding: 15px 30px;
    border: 1px solid var(--antique-gold);
    background: var(--green);
    color: var(--deep-wine);
    font-size: 11px;
    font-weight: 700;
    letter-spacing: 2px;
    cursor: pointer;
    border-radius: 4px;
    transition: 0.3s ease;
}

#calendar-button:hover {
    background: transparent;
    color: var(--light-gold);
}

/* RSVP */
#rsvp {
    text-align: center;
    background: transparent;
    backdrop-filter: blur(8px);
}

#rsvp h2 {
    color: var(--green);
}

#rsvp > p {
    color: var(--muted);
}

#rsvp-form {
    max-width: 520px;
    margin: 35px auto 0;
    display: flex;
    flex-direction: column;
    text-align: left;
}

#rsvp-form label {
    margin: 14px 0 6px;
    color: var(--green);
    font-size: 13px;
}

#rsvp-form input, #rsvp-form select {
    width: 100%;
    padding: 14px;
    border: 1px solid rgba(197, 164, 91, 0.5);
    border-radius: 4px;
    background: rgba(255, 255, 255, 0.08);
    color: var(--ivory);
    outline: none;
}

#rsvp-form input:focus, #rsvp-form select:focus {
    border-color: var(--light-gold);
}

#rsvp-form select option {
    color: var(--text-dark);
    background: var(--white);
}

#rsvp-form button {
    margin-top: 25px;
    padding: 16px;
    border: 1px solid var(--antique-gold);
    background: var(--green);
    color: var(--deep-wine);
    font-size: 12px;
    font-weight: 700;
    letter-spacing: 2px;
    cursor: pointer;
    border-radius: 4px;
    transition: 0.3s ease;
}

#rsvp-form button:hover {
    background: transparent;
    color: var(--light-gold);
}

#rsvp-message {
    margin-top: 20px;
    color: var(--light-gold);
    font-weight: 500;
}

/* Closing */
#closing {
    text-align: center;
    background: transparent;
    backdrop-filter: blur(8px);
}

#closing > p:first-child {
    color: var(--light-gold);
    font-family: var(--arabic-font);
    font-size: clamp(24px, 4vw, 34px);
    margin-bottom: 15px;
}

#closing h2 {
    color: var(--green);
}

#closing > p:nth-of-type(2) {
    color: var(--muted);
}

#closing h3 {
    margin-top: 35px;
    color: var(--green);
    font-size: 28px;
    line-height: 1.5;
}

/* Audio Player */
.floating-audio-container {
    position: fixed;
    bottom: 20px;
    right: 20px;
    z-index: 1001;
    background: rgba(53, 20, 33, 0.95);
    border: 1px solid var(--antique-gold);
    padding: 10px 15px;
    border-radius: 30px;
    display: flex;
    align-items: center;
    gap: 10px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.4);
    backdrop-filter: blur(5px);
}

.floating-audio-container span {
    color: var(--light-gold);
    font-size: 12px;
    font-weight: 600;
    letter-spacing: 1px;
    white-space: nowrap;
}

.floating-audio-container audio {
    height: 32px;
    width: 180px;
}

/* Footer */
footer {
    display: flex;
    justify-content: space-between;
    gap: 15px;
    padding: 25px 8%;
    background: #100b0e;
    color: #b6a7aa;
    font-size: 12px;
}

footer p {
    margin: 0;
}

@media (max-width: 900px) {
    section { padding: 70px 6%; }
    nav ul { gap: 15px; }
    nav ul li a { font-size: 11px; }
    #countdown-timer { grid-template-columns: repeat(2, 1fr); }
}

@media (max-width: 600px) {
    section { padding: 60px 20px; }
    nav { flex-direction: column; gap: 10px; }
    nav ul { justify-content: center; flex-wrap: wrap; gap: 10px 15px; }
    .floating-audio-container {
        bottom: 10px; right: 10px; left: 10px;
        justify-content: center; border-radius: 8px;
    }
    .floating-audio-container audio { width: 100%; }
    footer { flex-direction: column; align-items: center; text-align: center; }
}

/* Remove unwanted horizontal lines around the couple's names */
#home hr,
.couple-card hr {
    display: none !important;
    border: none !important;
}

.couple-card {
    border-bottom: none !important;
}

.couple-card h1 {
    border-bottom: none !important;
}

/* REMOVE UNWANTED HORIZONTAL LINES */

/* Remove unwanted lines beneath event details */
.event-details p {
    border-bottom: none !important;
}

/* Remove unwanted lines separating event sections */
section[id$="party"],
section#walima,
section#nikkah,
section#wedding-reception {
    border-bottom: none !important;
}

/* Remove unwanted borders from headings */
#home h1,
#home h2,
#henna-party h2,
#walima h2,
#nikkah h2,
#wedding-reception h2 {
    border-bottom: none !important;
    text-decoration: none !important;
}

/* Keep the couple's name card clean */
.couple-card {
    border-bottom: 1px solid var(--antique-gold);
}

/* Prevent decorative elements from creating unwanted lines */
.couple-card h1,
.couple-card .bride-name,
.couple-card .groom-name,
.couple-card .couple-ampersand {
    border: none !important;
    text-decoration: none !important;
}
</style>
</head>
<body>

<!-- Background Video -->
<div class="bg-video-container">
    <video autoplay muted loop playsinline>
        <source src="379500_medium.mp4" type="video/mp4">
        Your browser does not support HTML5 video.
    </video>
</div>
<div class="bg-video-overlay"></div>

<!-- Marquee Banner -->
<div class="Muhsina-Abdulqudus-banner">
    <div class="Muhsina-Abdulqudus-track">
        <span>Muhsina & Abdulqudus</span>
        <span class="Muhsina-Abdulqudus-divider">💗</span>
        <span>Muhsina & Abdulqudus</span>
        <span class="Muhsina-Abdulqudus-divider">💗</span>
        <span>Muhsina & Abdulqudus</span>
        <span class="Muhsina-Abdulqudus-divider">💗</span>
        <span>Muhsina & Abdulqudus</span>
    </div>
</div>

<!-- Navigation Bar -->
<header>
    <nav>
        <div class="logo">Muhsina & Abdulqudus</div>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#henna-party">Henna</a></li>
            <li><a href="#walima">Walima</a></li>
            <li><a href="#nikkah">Nikkah</a></li>
            <li><a href="#wedding-reception">Reception</a></li>
            <li><a href="#details">Details</a></li>
            <li><a href="#rsvp">RSVP</a></li>
        </ul>
    </nav>
</header>

<!-- Hero Section -->
<section id="home">
    <p lang="ar" dir="rtl">بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ</p> 
    <p>IN THE NAME OF ALLAH, THE MOST GRACIOUS, THE MOST MERCIFUL</p>
    
    <blockquote style="font-style: italic; border-left: 3px solid var(--antique-gold); padding-left: 15px; margin-bottom: 25px; text-align: center;">
        <p style="font-size: 0.95rem; color: var(--light-gold);">"And among His signs is that He created for you mates from among yourselves, that you may find tranquility in them; and He placed between you affection and mercy." (Surah Ar-Rum 30:21)</p>
    </blockquote>

    <p>It is with great joy and humble hearts, in gratitude to Allah (SWT), that the families of</p>
    <h2> 
      Alhaji Musa Moyosore 
      <span>and that of</span>
      Mallam Abdulganiyu Salman
    </h2>
    <p>cordially invite you to celebrate the union of their children.</p>
<!-- Bride and Groom Names -->
<div class="couple-card">

    <div class="name-divider">
        <span></span>
        <b>✦ ❖ ✦</b>
        <span></span>
    </div>

    <p class="couple-card-label">THE BRIDE &amp; GROOM</p>

    <h1>
        <span class="bride-name">Muhsina Musa</span>
        <span class="couple-ampersand">&amp;</span>
        <span class="groom-name">
            Abdulqudus Abdulganiyu Mayowa
        </span>
    </h1>

    <div class="name-divider bottom-divider">
        <span></span>
        <b>✦ ❖ ✦</b>
        <span></span>
    </div>
</div>
    <a href="#details" style="margin-top: 20px;">EXPLORE THE INVITATION</a>
</section>

<!-- Countdown Section -->
<section id="countdown">
    <h2>Counting Down to Our Special Day</h2>
    <p>We look forward to celebrating this blessed occasion with you.</p>

    <div id="countdown-timer">
        <div>
            <span id="days">00</span>
            <p>Days</p>
        </div>
        <div>
            <span id="hours">00</span>
            <p>Hours</p>
        </div>
        <div>
            <span id="minutes">00</span>
            <p>Minutes</p>
        </div>
        <div>
            <span id="seconds">00</span>
            <p>Seconds</p>
        </div>
    </div>
</section>

<!-- Henna Party -->
<section id="henna-party">
    <p>THE CELEBRATION</p>
    <h2>The Henna Party</h2>
    <div class="event-details">
        <p><strong>Date:</strong> Thursday, 17 December 2026</p>
        <p><strong>Time:</strong> 04:00 PM</p>
        <p><strong>Venue:</strong> Olaiya Street, Sawmill, Ilorin, Kwara State</p>
    </div>
    <a href="https://maps.app.goo.gl/UYoaEdBAcsaC67EA7" target="_blank" rel="noopener noreferrer">VIEW HENNA VENUE</a>
</section>

<!-- Walima -->
<section id="walima">
    <p>THE CELEBRATION</p>
    <h2>The Walima</h2>
    <p>Your presence will make our celebration even more special. We look forward to sharing this joyful occasion with you.</p>
    <div class="event-details">
        <p><strong>Date:</strong> Friday, 18 December 2026</p>
        <p><strong>Time:</strong> 10:00 PM</p>
        <p><strong>Venue:</strong> Agbaji Central Mosque, Ilorin, Kwara State</p>
    </div>
    <a href="https://maps.app.goo.gl/aE7gednJv4J1DJ93A" target="_blank" rel="noopener noreferrer">VIEW WALIMA VENUE</a>
</section>

<!-- Nikkah -->
<section id="nikkah">
    <p>THE CEREMONY</p>
    <h2>The Nikkah</h2>
    <p>With gratitude to Allah, we invite you to witness and celebrate the solemnisation of our marriage.</p>
    <div class="event-details">
        <p><strong>Date:</strong> Saturday, 19 December 2026</p>
        <p><strong>Time:</strong> 10:00 AM</p>
        <p><strong>Venue:</strong> Agbaji Central Mosque, Ilorin, Kwara State</p>
    </div>
    <a href="https://maps.app.goo.gl/aE7gednJv4J1DJ93A" target="_blank" rel="noopener noreferrer">VIEW NIKAH VENUE</a>
</section>

<!-- Reception -->
<section id="wedding-reception">
    <p>THE CELEBRATION</p>
    <h2>Wedding Reception</h2>
    <p>Let’s share this beautiful day together, filled with love and prayers.</p>
    <div class="event-details">
        <p><strong>Date:</strong> Saturday, 19 December 2026</p>
        <p><strong>Time:</strong> 12:00 PM</p>
        <p><strong>Venue:</strong> Al-Kareem Event Centre, Oloje, Ilorin</p>
    </div>
    <a href="https://maps.app.goo.gl/j8abducSFKp56Hxq6" target="_blank" rel="noopener noreferrer">VIEW RECEPTION VENUE</a>
</section>

<!-- Additional Information -->
<section id="details">
    <h2>Celebrate With Us</h2>
    <div class="information-card">
        <h3>Dress Code</h3>
        <p>Elegant and modest attire. Guests are encouraged to dress beautifully while respecting the Islamic nature of the occasion.</p>
    </div>
    <div class="information-card">
        <h3>Kindly Be Punctual</h3>
        <p>Please arrive early so that the ceremony can begin on time.</p>
    </div>
    <div class="information-card">
        <h3>Your Prayers Mean Everything</h3>
        <p>Your presence, prayers, and good wishes are deeply appreciated.</p>
    </div>
    <button id="calendar-button">ADD TO CALENDAR</button>
</section>

<!-- RSVP Section -->
<section id="rsvp">
    <h2>Will You Join Us?</h2>
    <p>Kindly confirm whether you will be attending.</p>
    <form id="rsvp-form">
        <label for="guest-name">Full Name</label>
        <input type="text" id="guest-name" name="guest-name" placeholder="Enter your full name" required>

        <label for="guest-phone">Phone Number</label>
        <input type="tel" id="guest-phone" name="guest-phone" placeholder="+234...">

        <label for="attendance">Attendance Confirmation</label>
        <select id="attendance" name="attendance" required>
            <option value="">Select an option</option>
            <option value="attending">Will Attend (Bi'idhnillah)</option>
            <option value="not-attending">Regretfully Declines</option>
        </select>

        <label for="guest-count">Number of Guests</label>
        <select id="guest-count" name="guest-count">
            <option value="1">1 Guest</option>
            <option value="2">2 Guests</option>
            <option value="3">3 Guests</option>
            <option value="4">4 Guests</option>
            <option value="5">5 Guests</option>
        </select>

        <button type="submit">SEND RSVP</button>
    </form>
    <p id="rsvp-message"></p>
</section>

<!-- Closing Section -->
<section id="closing">
    <p lang="ar" dir="rtl">بارك الله لكما وبارك عليكما وجمع بينكما في خير</p>
    <h2>May Allah Bless This Union</h2>
    <p>We look forward to celebrating with you.</p>
    <a href="https://wa.me/2349033891473" target="_blank" rel="noopener noreferrer" style="margin-top: 20px;">CONTACT THE ORGANISERS</a>
    <h3>With Love,<br>Muhsina &amp; Abdulqudus</h3>
</section>

  <!-- FLOATING MUSIC PLAYER -->
<div class="floating-audio-container">
    <span>🎵 Our Song</span>

    <audio id="bgMusic" controls autoplay loop preload="auto">
        <source src="For The Rest of My Life - Maher Zain (karaoke) AAN.mp3" type="audio/mpeg">
        Your browser does not support audio.
    </audio>
</div>

<!-- Footer -->
<footer>
    <p>Made with love, faith, and du'a.</p>
    <p>&copy; 2026 Muhsina &amp; Abdulqudus</p>
</footer>

<script>
window.addEventListener("scroll", function () {
    const header = document.querySelector("header");
    if (window.scrollY > 50) {
        header.classList.add("shrink");
    } else {
        header.classList.remove("shrink");
    }
});

document.addEventListener("DOMContentLoaded", function () {
    const weddingDate = new Date("2026-12-19T10:00:00+01:00").getTime();

    function updateCountdown() {
        const now = Date.now();
        const distance = weddingDate - now;
        const daysElement = document.getElementById("days");
        const hoursElement = document.getElementById("hours");
        const minutesElement = document.getElementById("minutes");
        const secondsElement = document.getElementById("seconds");

        if (!daysElement || !hoursElement || !minutesElement || !secondsElement) return;

        if (distance <= 0) {
            daysElement.textContent = "00";
            hoursElement.textContent = "00";
            minutesElement.textContent = "00";
            secondsElement.textContent = "00";
            return;
        }

        daysElement.textContent = String(Math.floor(distance / (1000 * 60 * 60 * 24))).padStart(2, "0");
        hoursElement.textContent = String(Math.floor((distance / (1000 * 60 * 60)) % 24)).padStart(2, "0");
        minutesElement.textContent = String(Math.floor((distance / (1000 * 60)) % 60)).padStart(2, "0");
        secondsElement.textContent = String(Math.floor((distance / 1000) % 60)).padStart(2, "0");
    }
    updateCountdown();
    setInterval(updateCountdown, 1000);
});

const calendarButton = document.getElementById("calendar-button");
if (calendarButton) {
    calendarButton.addEventListener("click", function () {
        const calendarContent = [
            "BEGIN:VCALENDAR", "VERSION:2.0", "PRODID:-//Wedding Invitation//EN", "CALSCALE:GREGORIAN",
            "BEGIN:VEVENT", "UID:muhsina-abdulqudus-wedding-2026@example.com",
            "DTSTAMP:" + new Date().toISOString().replace(/[-:]/g, "").replace(/\.\d{3}/, ""),
            "DTSTART:20261219T090000Z", "DTEND:20261219T130000Z",
            "SUMMARY:Wedding of Muhsina Musa and Abdulqudus Abdulganiyu Mayowa",
            "DESCRIPTION:Nikkah at 10:00 AM and wedding reception at 12:00 PM.",
            "LOCATION:Ilorin, Kwara State, Nigeria", "END:VEVENT", "END:VCALENDAR"
        ].join("\r\n");

        const file = new Blob([calendarContent], { type: "text/calendar;charset=utf-8" });
        const fileURL = URL.createObjectURL(file);
        const downloadLink = document.createElement("a");
        downloadLink.href = fileURL;
        downloadLink.download = "Muhsina-Abdulqudus-Wedding.ics";
        document.body.appendChild(downloadLink);
        downloadLink.click();
        downloadLink.remove();
        setTimeout(() => URL.revokeObjectURL(fileURL), 1000);
        alert("Your wedding calendar invitation has been downloaded!");
    });
}

const rsvpForm = document.getElementById("rsvp-form");
if (rsvpForm) {
    rsvpForm.addEventListener("submit", function (event) {
        event.preventDefault();
        const name = document.getElementById("guest-name").value.trim();
        const phone = document.getElementById("guest-phone").value.trim();
        const attendance = document.getElementById("attendance").value;
        const guestCount = document.getElementById("guest-count").value;
        const messageElement = document.getElementById("rsvp-message");

        if (!name || !attendance) {
            alert("Please enter your name and select your attendance.");
            return;
        }

        const attendanceText = attendance === "attending" ? "Will Attend (Bi'idhnillah)" : "Regretfully Declines";
        const message = `WEDDING RSVP 💍\n\nWedding of Muhsina Musa & Abdulqudus Abdulganiyu Mayowa\nDate: Saturday, 19 December 2026\n\nGuest Name: ${name}\nPhone: ${phone || "Not provided"}\nAttendance: ${attendanceText}\nGuests: ${guestCount}\n\nSent via online wedding invitation.`;

        const whatsappURL = `https://wa.me/2349033891473?text=${encodeURIComponent(message)}`;
        if (messageElement) messageElement.textContent = "Opening WhatsApp to send your RSVP...";
        window.location.href = whatsappURL;
    });
}
// Try to start the wedding music automatically
const weddingMusic = document.getElementById("bgMusic");

if (weddingMusic) {
    window.addEventListener("load", function () {
        weddingMusic.play().catch(function () {
            console.log("Tap the play button to start the wedding music.");
        });
    });
}

</script>
</body>
</html>
