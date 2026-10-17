
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Join us to celebrate a beautiful Islamic wedding filled with love, faith, and blessings.">
  
<title>Islamic Wedding Invitation</title>
<style>
/* =========================================
   LUXURY ISLAMIC WEDDING INVITATION
   Colour palette: Green, Wine, Gold, Ivory
========================================= */

:root {
    --Green: #50C878;
    --deep-wine: #351421;
    --wine: #541b30;
    --antique-gold: #c5a45b;
    --light-gold: #ead8a6;
    --ivory: #f8f3e9;
    --white: #ffffff;
    --text-dark: #261b20;
    --muted: #766b68;

    --heading-font: "Cormorant Garamond", Georgia, serif;
    --body-font: "DM Sans", Arial, sans-serif;
}


/* =========================================
   GENERAL RESET
========================================= */

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
    color: var(--text-dark);
    font-family: var(--body-font);
    line-height: 1.7;
}

a {
    color: inherit;
    text-decoration: none;
}

button,
input,
select {
    font: inherit;
}

button,
a {
    -webkit-tap-highlight-color: transparent;
}


/* =========================================
   NAVIGATION BAR
========================================= */

header {
    position: sticky;
    top: 0;
    z-index: 1000;

    background: rgba(23, 17, 19, 0.97);
    border-bottom: 1px solid rgba(197, 164, 91, 0.4);

    backdrop-filter: blur(12px);
}

nav {
    max-width: 1400px;
    margin: auto;
    padding: 16px 5%;

    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 25px;
}

.logo {
    color: var(--light-gold);
    font-size: 27px;
    font-family: "Amiri", Georgia, serif;
}

nav ul {
    list-style: none;

    display: flex;
    align-items: center;
    gap: 30px;
}

nav ul li a {
    color: var(--ivory);
    font-size: 12px;
    letter-spacing: 2px;
    text-transform: uppercase;

    transition: color 0.3s ease;
}

nav ul li a:hover {
    color: var(--antique-gold);
}


/* =========================================
   SECTION DEFAULTS
========================================= */

section {
    padding: 100px 8%;
}

h1,
h2,
h3 {
    font-family: var(--heading-font);
    font-weight: 500;
    line-height: 1.15;
}

h2 {
    font-size: clamp(42px, 6vw, 70px);
    margin-bottom: 25px;
}

p {
    margin-bottom: 18px;
}


/* =========================================
   HERO / WELCOME SECTION
========================================= */

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

    background:
        radial-gradient(
            ellipse at center,
            #542235 0%,
            #321722 50%,
            #171113 100%
        );
}

/* Decorative Islamic-inspired border */

#home::before {
    content: "";

    position: absolute;
    inset: 20px;

    border: 1px solid rgba(197, 164, 91, 0.45);

    pointer-events: none;
}

/* Decorative geometric diamond */

#home::after {
    content: "";

    position: absolute;

    width: 350px;
    height: 350px;

    border: 1px solid rgba(197, 164, 91, 0.15);

    transform: rotate(45deg);

    top: -230px;
    right: -150px;

    pointer-events: none;
}

#home > * {
    position: relative;
    z-index: 1;
}

#home > p:first-child {
    max-width: 650px;

    color: var(--antique-gold);

    font-size: 11px;
    font-weight: 600;
    letter-spacing: 3px;

    margin-bottom: 35px;
}

#home h1 {
    display: flex;
    flex-direction: column;
    align-items: center;

    margin: 25px 0;

    color: var(--light-gold);

    font-size: clamp(75px, 12vw, 145px);
    line-height: 0.85;
}

#home h1 span {
    color: var(--antique-gold);

    font-size: 45px;
    font-style: italic;

    margin: 18px 0;
}

#home p {
    max-width: 620px;
}

#home p:nth-of-type(2) {
    color: #e3d7d5;

    font-size: 16px;
    line-height: 2;
}

#home p:nth-of-type(3) {
    color: var(--antique-gold);

    font-size: 11px;
    letter-spacing: 3px;

    margin-top: 15px;
}

#home p:nth-of-type(4) {
    color: var(--light-gold);

    font-size: 14px;
    letter-spacing: 2px;

    margin: 15px 0 30px;
}


/* =========================================
   BUTTONS
========================================= */

.button,
#home > a,
#Hennah party > a,
#walima > a,
#Nikkah > a,
#Wedding Reception > a,
#closing > a {
    display: inline-block;

    padding: 15px 28px;

    border: 1px solid var(--antique-gold);

    background: var(--antique-gold);
    color: var(--green);

    font-size: 11px;
    font-weight: 700;
    letter-spacing: 2px;

    text-align: center;

    transition:
        background 0.3s ease,
        color 0.3s ease,
        transform 0.3s ease;
}

.button:hover,
#home > a:hover,
#Henna party > a:hover,
#walima > a:hover,
#nikkah > a:hover,
#wedding reception > a:hover,
#closing > a:hover {
    background: transparent;
    color: var(--light-gold);

    transform: translateY(-3px);
}


/* =========================================
   COUNTDOWN SECTION
========================================= */

#countdown {
    text-align: center;

    background: var(--white);
    color: var(--text-dark);
}

#countdown h2 {
    color: var(--wine);
}

#countdown > p {
    color: var(--muted);
}

#countdown-timer {
    max-width: 850px;

    margin: 45px auto 0;

    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 18px;
}

#countdown-timer > div {
    padding: 30px 15px;

    background: var(--ivory);

    border: 1px solid rgba(197, 164, 91, 0.55);
}

#countdown-timer span {
    display: block;

    color: var(--wine);

    font-family: var(--heading-font);
    font-size: 55px;
    line-height: 1.2;
}

#countdown-timer p {
    margin: 8px 0 0;

    color: var(--muted);

    font-size: 11px;
    letter-spacing: 2px;
    text-transform: uppercase;
}

/* =========================================
   HENNA PARTY SECTION
========================================= */

#Henna party {
    color: var(--text-dark);

    background:
        linear-gradient(
            135deg,
            #f8f3e9,
            #eadcc5
        );
}

#Henna party > p:first-child {
    color: var(--wine);

    font-size: 12px;
    letter-spacing: 3px;
}

#Henna party h2 {
    color: var(--wine);
}

#Henna party > p:nth-of-type(2) {
    max-width: 650px;

    color: var(--muted);

    line-height: 2;
}

#henna party .event-details {
    border-top-color: rgba(84, 27, 48, 0.25);
}

#henna party .event-details p {
    border-bottom-color: rgba(84, 27, 48, 0.2);
}

#henna party .event-details strong {
    color: var(--wine);
}

#henna party > a {
    background: var(--wine);
    color: var(--ivory);
}

#henna party > a:hover {
    background: transparent;
    color: var(--wine);
}
/* =========================================
   WALIMA SECTION
========================================= */

#walima {
    color: var(--text-dark);

    background:
        linear-gradient(
            135deg,
            #f8f3e9,
            #eadcc5
        );
}

#walima > p:first-child {
    color: var(--wine);

    font-size: 12px;
    letter-spacing: 3px;
}

#walima h2 {
    color: var(--wine);
}

#walima > p:nth-of-type(2) {
    max-width: 650px;

    color: var(--muted);

    line-height: 2;
}

#walima .event-details {
    border-top-color: rgba(84, 27, 48, 0.25);
}

#walima .event-details p {
    border-bottom-color: rgba(84, 27, 48, 0.2);
}

#walima .event-details strong {
    color: var(--wine);
}

#walima > a {
    background: var(--wine);
    color: var(--ivory);
}

#walima > a:hover {
    background: transparent;
    color: var(--wine);
}

/* =========================================
   NIKKAH SECTION
========================================= */

#nikkah {
    color: var(--ivory);

    background:
        linear-gradient(
            135deg,
            var(--deep-wine),
            var(--green)
        );
}

#nikkah > p:first-child {
    color: var(--antique-gold);

    font-size: 12px;
    letter-spacing: 3px;
}

#nikkah h2 {
    color: var(--light-gold);
}

#nikkah > p:nth-of-type(2) {
    max-width: 650px;

    color: #d8c9ca;

    line-height: 2;
}

.event-details {
    max-width: 700px;

    margin: 35px 0;

    border-top: 1px solid rgba(197, 164, 91, 0.4);
}

.event-details p {
    padding: 17px 0;
    margin: 0;

    border-bottom: 1px solid rgba(197, 164, 91, 0.25);
}

.event-details strong {
    display: inline-block;

    min-width: 90px;

    color: var(--antique-gold);
}


/* =========================================
   WEDDING RECEPTION SECTION
========================================= */

#wedding reception {
    color: var(--text-dark);

    background:
        linear-gradient(
            135deg,
            #f8f3e9,
            #eadcc5
        );
}

#wedding reception > p:first-child {
    color: var(--green);

    font-size: 12px;
    letter-spacing: 3px;
}

#wedding reception h2 {
    color: var(--gold);
}

#wedding reception > p:nth-of-type(2) {
    max-width: 650px;

    color: var(--muted);

    line-height: 2;
}

#Wedding reception .event-details {
    border-top-color: rgba(84, 27, 48, 0.25);
}

#wedding reception .event-details p {
    border-bottom-color: rgba(84, 27, 48, 0.2);
}

#wedding reception .event-details strong {
    color: var(--ivory);
}

#wedding reception > a {
    background: var(--wine);
    color: var(--Green);
}

#wedding reception > a:hover {
    background: transparent;
    color: var(--ivory);
}


/* =========================================
   ADDITIONAL INFORMATION
========================================= */

#details {
    text-align: center;

    background: var(--white);
}

#details h2 {
    color: var(--wine);
}

.information-card {
    max-width: 850px;

    margin: 25px auto;
    padding: 30px;

    background: var(--ivory);

    border: 1px solid rgba(197, 164, 91, 0.5);
}

.information-card h3 {
    color: var(--wine);

    font-size: 32px;

    margin-bottom: 12px;
}

.information-card p {
    max-width: 650px;

    margin: auto;

    color: var(--muted);
}

#calendar-button {
    margin-top: 25px;

    padding: 15px 25px;

    border: 1px solid var(--wine);

    background: var(--wine);
    color: var(--ivory);

    font-size: 11px;
    font-weight: 700;
    letter-spacing: 2px;

    cursor: pointer;

    transition: 0.3s ease;
}

#calendar-button:hover {
    background: transparent;
    color: var(--wine);
}


/* =========================================
   RSVP SECTION
========================================= */

#rsvp {
    text-align: center;

    color: var(--ivory);

    background:
        radial-gradient(
            ellipse at top,
            #552337,
            #211219 75%
        );
}

#rsvp h2 {
    color: var(--light-gold);
}

#rsvp > p {
    color: #d8c9ca;
}

#rsvp-form {
    max-width: 550px;

    margin: 35px auto 0;

    display: flex;
    flex-direction: column;

    text-align: left;
}

#rsvp-form label {
    margin: 14px 0 8px;

    color: var(--light-gold);

    font-size: 13px;
}

#rsvp-form input,
#rsvp-form select {
    width: 100%;

    padding: 15px;

    border: 1px solid rgba(197, 164, 91, 0.5);
    border-radius: 0;

    background: rgba(255, 255, 255, 0.06);

    color: var(--white);

    outline: none;
}

#rsvp-form input:focus,
#rsvp-form select:focus {
    border-color: var(--light-gold);
}

#rsvp-form select option {
    color: var(--text-dark);
    background: var(--white);
}

#rsvp-form button {
    margin-top: 25px;

    padding: 17px;

    border: 1px solid var(--antique-gold);

    background: var(--antique-gold);
    color: var(--black);

    font-size: 12px;
    font-weight: 700;
    letter-spacing: 2px;

    cursor: pointer;

    transition: 0.3s ease;
}

#rsvp-form button:hover {
    background: transparent;
    color: var(--light-gold);
}

#rsvp-message {
    margin-top: 20px;
    color: var(--light-gold);
}


/* =========================================
   CLOSING SECTION
========================================= */

#closing {
    text-align: center;

    color: var(--ivory);

    background: var(--black);
}

#closing > p:first-child {
    color: var(--light-gold);

    font-family: "Amiri", Georgia, serif;
    font-size: 30px;
}

#closing h2 {
    color: var(--light-gold);
}

#closing > p:nth-of-type(2) {
    color: #d8c9ca;
}

#closing h3 {
    margin-top: 45px;

    color: var(--antique-gold);

    font-size: 32px;
    line-height: 1.6;
}


/* =========================================
   FOOTER
========================================= */

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


/* =========================================
   TABLET RESPONSIVENESS
========================================= */

@media (max-width: 900px) {

    section {
        padding: 80px 6%;
    }

    nav {
        padding: 15px 4%;
    }

    nav ul {
        gap: 15px;
    }

    nav ul li a {
        font-size: 10px;
        letter-spacing: 1px;
    }

    #countdown-timer {
        gap: 10px;
    }

    #countdown-timer span {
        font-size: 45px;
    }

}


/* =========================================
   MOBILE RESPONSIVENESS
========================================= */

@media (max-width: 600px) {

    section {
        padding: 70px 22px;
    }

    nav {
        flex-direction: column;
        gap: 12px;
    }

    nav ul {
        justify-content: center;
        flex-wrap: wrap;
        gap: 12px 18px;
    }

    nav ul li a {
        font-size: 10px;
    }

    .logo {
        font-size: 25px;
    }

    #home {
        min-height: 85vh;
    }

    #home::before {
        inset: 10px;
    }

    #home > p:first-child {
        font-size: 9px;
        letter-spacing: 1.5px;
    }

    #home h1 {
        font-size: clamp(65px, 17vw, 95px);
    }

    #home h1 span {
        font-size: 35px;
    }

    #home p:nth-of-type(2) {
        font-size: 14px;
    }

    #home p:nth-of-type(3) {
        font-size: 9px;
        letter-spacing: 1.5px;
    }

    #home p:nth-of-type(4) {
        font-size: 12px;
    }

    h2 {
        font-size: 45px;
    }

    #countdown-timer {
        grid-template-columns: repeat(2, 1fr);
        gap: 12px;
    }

    #countdown-timer > div {
        padding: 22px 10px;
    }

    #countdown-timer span {
        font-size: 45px;
    }

    .event-details strong {
        min-width: 75px;
    }

    .information-card {
        padding: 25px 18px;
    }

    .information-card h3 {
        font-size: 28px;
    }

    #closing > p:first-child {
        font-size: 23px;
    }

    footer {
        flex-direction: column;
        align-items: center;
        text-align: center;
    }

}


/* =========================================
   REDUCED MOTION ACCESSIBILITY
========================================= */

@media (prefers-reduced-motion: reduce) {

    html {
        scroll-behavior: auto;
    }

    *,
    *::before,
    *::after {
        transition-duration: 0.01ms !important;
    }

}
</style>
</head>
<body>
<!-- NAVIGATION BAR -->
<header>
    <nav>
        <div class="logo">
            بِسْمِ اللَّهِ 
        </div>

        <ul>
            <li><a href="#home">Home</a></li>
             <li><a href="#Henna party">Henna party</a></li>
            <li><a href="#walima">Walima</a></li>
            <li><a href="#nikah">Nikah</a></li>
            <li><a href="#Wedding Reception">Wedding Reception</a></li>
           
            <li><a href="#details">Details</a></li>
            <li><a href="#rsvp">RSVP</a></li>
        </ul>
    </nav>
</header>


<!-- HERO / WELCOME SECTION -->
<section id="home">

    <p>IN THE NAME OF ALLAH, THE MOST GRACIOUS, THE MOST MERCIFUL</p>

    <h1>
         Muhsina Musa 
        <span>&amp;</span>
        Abdulkudus Abdulganiyu Mayowa
    </h1>

    <p>
        Together with their families, they joyfully invite you
        to celebrate the beginning of their new chapter.
    </p>

    <p>
        A CELEBRATION OF LOVE, FAITH AND FAMILY
    </p>

    <p>
        Saturday, 12 December 2026
    </p>

    <a href="#details">EXPLORE THE INVITATION</a>

</section>


<!-- WEDDING COUNTDOWN SECTION -->
<section id="countdown">

    <h2>Counting Down to Our Special Day</h2>

    <p>
        We look forward to celebrating this blessed occasion with you.
    </p>

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


<section id="Henna party">

    <p>THE CELEBRATION</p>

    <h2>The Henna party</h2>


    <div class="event-details">

        <p>
            <strong>Date:</strong>
            Thursday, 17 December 2026
        </p>

        <p>
            <strong>Time:</strong>
            04:00 PM
        </p>

        <p>
            <strong>Venue:</strong>
            Olaiya street, sawmill Ilorin, Kwara State 
        </p>

    </div>

    <a
        href="https://maps.app.goo.gl/UYoaEdBAcsaC67EA7"
        target="_blank"
        rel="noopener noreferrer">

        VIEW WALIMA VENUE

    </a>

</section>


<section id="walima">

    <p>THE CELEBRATION</p>

    <h2>The Walima</h2>

    <p>
        Your presence will make our celebration even more special.
        We look forward to sharing this joyful occasion with you.
    </p>

    <div class="event-details">

        <p>
            <strong>Date:</strong>
            Friday, 18 December 2026
        </p>

        <p>
            <strong>Time:</strong>
            1:00 PM
        </p>

        <p>
            <strong>Venue:</strong>
            Ile saura Agbaji, Ilorin, Kwara State.
        </p>

    </div>

    <a
        href="https://maps.app.goo.gl/aE7gednJv4J1DJ93A"
        target="_blank"
        rel="noopener noreferrer">

        VIEW WALIMA VENUE

    </a>

</section>


<!-- NIKKAH CEREMONY SECTION -->
<section id="nikah">

    <p>THE CEREMONY</p>

    <h2>The Nikkah</h2>

    <p>
        With gratitude to Allah, we invite you to witness
        and celebrate the solemnisation of our marriage.
    </p>

    <div class="event-details">

        <p>
            <strong>Date:</strong>
            Saturday, 19 December 2026
        </p>

        <p>
            <strong>Time:</strong>
            10:00 AM
        </p>

        <p>
            <strong>Venue:</strong>
            Agbaji Mosque, Ilorin Kwara State 
        </p>

    </div>

    <a
        href="https://maps.app.goo.gl/aE7gednJv4J1DJ93A"
        target="_blank"
        rel="noopener noreferrer">

        VIEW NIKAH VENUE

    </a>

</section>

 <!-- WEDDING RECEPTION SECTION -->
<section id="wedding reception">

    <p>THE CELEBRATION</p>

    <h2>wedding reception</h2>

    <p>
        Let’s share this beautiful day together,


filled with love and prayers.

    <div class="event-details">

        <p>
            <strong>Date:</strong>
            Saturday, 19 December 2026
        </p>

        <p>
            <strong>Time:</strong>
            12:00 PM
        </p>

        <p>
            <strong>Venue:</strong>
            Al-kareem event centre oloje Ilorin 
        </p>

    </div>

    <a
        href="https://maps.app.goo.gl/j8abducSFKp56Hxq6"
        target="_blank"
        rel="noopener noreferrer">

        VIEW RECEPTION VENUE

    </a>

</section>



<!-- ADDITIONAL WEDDING INFORMATION -->
<section id="details">

    <h2>Celebrate With Us</h2>

    <div class="information-card">

        <h3>Dress Code</h3>

        <p>
            Elegant and modest attire.
            Guests are encouraged to dress beautifully
            while respecting the Islamic nature of the occasion.
        </p>

    </div>

    <div class="information-card">

        <h3>Kindly Be Punctual</h3>

        <p>
            Please arrive early so that the ceremony
            can begin on time.
        </p>

    </div>

    <div class="information-card">

        <h3>Your Prayers Mean Everything</h3>

        <p>
            Your presence, prayers and good wishes
            are deeply appreciated.
        </p>

    </div>

    <button id="calendar-button">
        ADD TO CALENDAR
    </button>

</section>


<!-- RSVP SECTION -->
<section id="rsvp">

    <h2>Will You Join Us?</h2>

    <p>
        Kindly confirm whether you will be attending.
    </p>

    <form id="rsvp-form">

        <label for="guest-name">
            Full Name
        </label>

        <input
            type="text"
            id="guest-name"
            name="guest-name"
            placeholder="Enter your full name"
            required
        >

        <label for="guest-phone">
            Phone Number
        </label>

        <input
            type="tel"
            id="guest-phone"
            name="guest-phone"
            placeholder="+234..."
        >

        <label for="attendance">
            Attendance Confirmation
        </label>

        <select
            id="attendance"
            name="attendance"
            required
        >

            <option value="">
                Select an option
            </option>

            <option value="attending">
                Joyfully Accepts
            </option>

            <option value="not-attending">
                Regretfully Declines
            </option>

        </select>

        <label for="guest-count">
            Number of Guests
        </label>

        <select
            id="guest-count"
            name="guest-count"
        >

            <option value="1">1 Guest</option>
            <option value="2">2 Guests</option>
            <option value="3">3 Guests</option>
            <option value="4">4 Guests</option>
            <option value="5">5 Guests</option>

        </select>

        <button type="submit">
            SEND RSVP
        </button>

    </form>

    <p id="rsvp-message"></p>

</section>


<!-- CLOSING SECTION -->
<section id="closing">

    <p lang="ar" dir="rtl">
        بارك الله لكما وبارك عليكما وجمع بينكما في خير
    </p>

    <h2>May Allah Bless This Union</h2>

    <p>
        We look forward to celebrating with you.
    </p>

    <a
        href="https://wa.me/"
        target="_blank"
        rel="noopener noreferrer">

        CONTACT THE ORGANISERS

    </a>

    <h3>
        With Love,
        <br>
        Muhsina &amp; Abdulkudus
    </h3>

</section>


<!-- FOOTER -->
<footer>

    <p>
        Made with love, faith and du'a.
    </p>

    <p>
        &copy; 2026 Muhsina &amp; Abdulkudus
    </p>

</footer>
</body>
</html>

