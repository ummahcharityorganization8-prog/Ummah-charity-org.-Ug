<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>UMMAH CHARITY ORGANIZATION</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background: #f9f9f9;
}

/* HEADER */
header {
    background: #0a7d3b;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 15px 20px;
}

header img {
    height: 60px;
}

header h1 {
    font-size: 22px;
    margin-left: 10px;
}

.header-left {
    display: flex;
    align-items: center;
}

/* MENU */
.menu {
    position: relative;
}

.menu-btn {
    font-size: 28px;
    cursor: pointer;
}

.menu-content {
    display: none;
    position: absolute;
    right: 0;
    background: white;
    color: black;
    min-width: 220px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    z-index: 1;
}

.menu-content a {
    display: block;
    padding: 12px;
    text-decoration: none;
    color: black;
    border-bottom: 1px solid #eee;
}

.menu-content a:hover {
    background: #0a7d3b;
    color: white;
}

/* BUTTONS */
.btn {
    background: #0a7d3b;
    color: white;
    padding: 12px 18px;
    text-decoration: none;
    border-radius: 5px;
    display: inline-block;
    margin: 10px 0;
    font-weight: bold;
}

.btn:hover {
    background: #065c2a;
}

/* SECTIONS */
section {
    padding: 40px 20px;
    background: white;
    margin-bottom: 10px;
}

section h2 {
    color: #0a7d3b;
}

.programs ul, .donations ul {
    list-style: none;
    padding: 0;
}

.programs li, .donations li {
    padding: 8px 0;
}

/* IMAGES */
.image-section img {
    max-width: 100%;
    border-radius: 8px;
    margin: 10px 0;
}

/* FOOTER */
footer {
    background: #0a7d3b;
    color: white;
    padding: 30px 20px;
}

footer h3 {
    margin-top: 0;
}

footer a {
    color: #ffdd57;
    text-decoration: none;
}
</style>
</head>

<body>

<!-- HEADER -->
<header>
    <div class="header-left">
        <img src="LOGO_055830.jpg" alt="">
        <h1>UMMAH CHARITY ORGANIZATION</h1>
    </div>

    <div class="menu">
        <div class="menu-btn" onclick="toggleMenu()">☰</div>
        <div class="menu-content" id="menu">
            <a href="#home">Home</a>
            <a href="#about">About Us</a>
            <a href="#programs">Our Programs</a>
            <a href="#donate">Donate</a>
            <a href="https://wa.me/2567568959" target="_blank">Contact WhatsApp</a>
            <a href="#language">Change Language</a>
        </div>
    </div>
</header>

<!-- HOME -->
<section id="home">
    <h2>Welcome to Ummah Charity Organization 🤲</h2>
    <p>
        <strong>“Whoever feeds a fasting person will have a reward 
        like that of the fasting person.” (Hadith)</strong>
    </p>
    <p>
        We warmly welcome our dear donors and supporters. 
       Your generosity brings hope, dignity and life to the poor, widows, orphans and needy families.
        Ummah Charity Organization follows a <strong>100% donation policy</strong> – your donation reaches the beneficiaries directly.
    </p>

    <p>
        We provide full transparency through <strong>videos, photos and reports</strong> showing exactly how your donations are used.
    </p>

    <a class="btn" href="https://wa.me/2567568959" target="_blank">Donate via WhatsApp</a>
</section>

<!-- IMAGES -->
<section class="image-section">
    <img src="1767850309675.jpg" alt="Ramadan Iftar Appeal">
    <img src="1768216048046.jpg" alt="Children Receiving Food">
</section>

<!-- DONATE -->
<section id="donate">
    <h2>Donate Now 💚</h2>
    <div class="donations">
        <ul>
            <li>Orphan Feeding – <strong>1€ per person</strong></li>
            <li>Food Pack – <strong>30€</strong></li>
            <li>Water Well – <strong>400€</strong></li>
            <li>Water Tap – <strong>200€</strong></li>
            <li>Wheel Chair – <strong>300€</strong></li>
            <li>Masjid Construction – <strong>10,000€</strong></li>
            <li>Sheep – <strong>80€</strong></li>
            <li>Goat – <strong>70€</strong></li>
            <li>Cow – <strong>300€</strong></li>
            <li>Camel – <strong>800€</strong></li>
        </ul>
    </div>

    <p><strong>Donation Methods:</strong> Western Union | MoneyGram | PayPal</p>
</section>

<!-- PROGRAMS -->
<section id="programs" class="programs">
    <h2>Our Programs 🌍</h2>
    <ul>
        <li>🍲 Food Pack Distribution</li>
        <li>🐄 Qurban & Aqiqah Sacrifice</li>
        <li>💰 Zakat Distribution</li>
        <li>🕌 Masjid Construction</li>
        <li>👶 Orphans Sponsorship</li>
        <li>📖 Quran Distribution</li>
        <li>🚨 Emergency Relief</li>
    </ul>
</section>

<!-- RAMADAN -->
<section>
    <h2>Ramadan Appeal 2026 🌙</h2>
    <p>
        During Ramadan, many families struggle to find food and clean water.
        Support Ummah Charity Organization to provide iftar meals, food packs and water to fasting Muslims.
    </p>
    <p><strong>“The best charity is that given in Ramadan.”</strong></p>
</section>

<!-- LANGUAGE -->
<section id="language">
    <h2>Change Language 🌐</h2>
    <div id="google_translate_element"></div>
</section>

<!-- FOOTER -->
<footer id="about">
    <h3>About Us</h3>
    <p>
        Ummah Charity Organization is a non-profit organization dedicated to providing clean and safe water,
        food, education and emergency relief to under-privileged communities across Uganda.
    </p>

    <h3>Contact Us</h3>
    <p>
        📍 Eastern Uganda, Africa <br>
        📧 ummahcharityorganization8@gmail.com <br>
        📞 WhatsApp: +256756897359
    </p>
</footer>

<!-- SCRIPTS -->
<script>
function toggleMenu() {
    var menu = document.getElementById("menu");
    menu.style.display = menu.style.display === "block" ? "none" : "block";
}
</script>

<script type="text/javascript">
function googleTranslateElementInit() {
  new google.translate.TranslateElement({
    pageLanguage: 'en',
    includedLanguages: 'tr,bs,mk,ar,bg',
  }, 'google_translate_element');
}
</script>

<script src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

</body>
</html>
