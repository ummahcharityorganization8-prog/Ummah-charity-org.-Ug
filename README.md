<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>UMMAH CHARITY ORGANIZATION</title>

<style>
body{
    margin:0;
    font-family: Arial, sans-serif;
    background:#f9f9f9;
}

/* Moving Ramadan Appeal */
.marquee{
    background:#000;
    color:#fff;
    padding:8px;
    font-weight:bold;
    white-space:nowrap;
    overflow:hidden;
}
.marquee span{
    display:inline-block;
    animation: move 10s linear infinite;
}
@keyframes move{
    from{transform:translateX(100%);}
    to{transform:translateX(-100%);}
}

/* Header */
header{
    background:green;
    color:white;
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:10px 20px;
    position:relative;
}
header img{
    height:60px;
}
header h1{
    flex:1;
    text-align:center;
    font-size:22px;
}


/* MENU */
.menu-container {
    position: relative;
}

.menu-icon {
    font-size: 30px;
    cursor: pointer;
}

.menu {
    position: absolute;
    right: 0;
    top: 40px;
    background: white;
    width: 200px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.3);
    display: none;
}

.menu a {
    display: block;
    padding: 10px;
    color: black;
    text-decoration: none;
}

.menu a:hover {
    background: #e0e0e0;
}

.menu-container:hover .menu {
    display: block;
}

/* Floating Chat Button */
.chat-btn{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    padding:15px;
    border-radius:50%;
    text-decoration:none;
    font-weight:bold;
}

/* Sections */
section{
    padding:30px;
    background:white;
    margin:10px;
}
section img{
    max-width:100%;
}

/* Table */
table{
    width:100%;
    border-collapse:collapse;
}
table, th, td{
    border:1px solid #333;
}
th, td{
    padding:10px;
    text-align:left;
}

/* Footer */
footer{
    background:#222;
    color:white;
    padding:20px;
}
</style>

<script>
function toggleMenu(){
    const menu=document.getElementById("menu");
    menu.style.display = menu.style.display==="block" ? "none" : "block";
}

function showMore(id){
    document.getElementById(id).style.display="block";
}

function googleTranslate(lang){
    window.location.href="https://translate.google.com/translate?hl="+lang+"&sl=auto&tl="+lang+"&u="+window.location.href;
}
</script>
</head>

<body>

<div class="marquee">
    <span>RAMADAN APPEAL 2026</span>
</div>

<header>
    <img src="Logo.png" alt="Logo">
    <h1>UMMAH CHARITY ORGANIZATION</h1>
     
 <div class="menu-container">
        <div class="menu-icon">&#9776;</div>
        <div class="menu">
            <a href="#">Home</a>
            <a href="#">About Us</a>
            <a href="https://translate.google.com/">Change Language</a>
            <a href="#">Our Programs</a>
            <a href="#">Contact Us</a>
        </div>
</div>
    
</header>

<div style="text-align:center;">
    <a class="btn" href="http://wa.me/+256756897359">Book Now</a>
</div>

<a class="chat-btn" href="http://wa.me/+256756897359">Chat</a>

<!-- HOME -->
<section>
    <img src="iftar appeal.jpg">
    <img src="1766519358260.jpg">
    <img src="image 3.jpg">
    <h2>
        Assalam aleikum our dear brothers and sisters we request for your collaboration
        and support of our organization to provide smiles on the cheeks of the orphans
        inshallah click in
    </h2>
</section>

<section>
    <a class="btn" href="#prices">Donation Prices</a>
</section>

<!-- DONATION PRICES -->
<section id="prices">
<h2>Donation Prices</h2>
<table>
<tr><th>#</th><th>Program</th><th>Price</th></tr>
<tr><td>1</td><td>Orphan feeding per person</td><td>1€</td></tr>
<tr><td>2</td><td>Water well</td><td>400€</td></tr>
<tr><td>3</td><td>Tap</td><td>200€</td></tr>
<tr><td>4</td><td>Wheel chair</td><td>300€</td></tr>
<tr><td>5</td><td>Masjid construction</td><td>10000€</td></tr>
<tr><td>6</td><td>Food pack</td><td>30€</td></tr>
<tr><td>7</td><td>Sheep</td><td>80€</td></tr>
<tr><td>8</td><td>Goat</td><td>70€</td></tr>
<tr><td>9</td><td>Cow</td><td>300€</td></tr>
<tr><td>10</td><td>Camel</td><td>800€</td></tr>
<tr><td>11</td><td>Clothing per orphan</td><td>30€</td></tr>
</table>
</section>

<!-- PROGRAMS -->
<section>
<h2>Our Programs</h2>
<ol>
<li>Food pack distribution</li>
<li>Qurban & Aqiqah sacrifice</li>
<li>Zakat distribution</li>
<li>Masjid construction</li>
<li>Orphans sponsorship</li>
<li>Quran distribution</li>
<li>Emergency relief</li>
</ol>
</section>

<!-- IMPORTANCE -->
<section>
<h2>Importance of Your Donation</h2>
<p>
Your donation can help to provide clean and safe water to my community members through
installation of water wells and boreholes and the water will be used for domestic purposes
and masjid purposes this is sadaka jariyah which where you continue to get blessings as long
as people are still using this water
</p>
<a href="#" onclick="showMore('more1')">Next</a>
<p id="more1" style="display:none;">
Your donation can help to feed, cloth and provide food pack to the widows in Uganda Africa
this helps to save many communities from hunger and provide smiles to every moslem ummah
across Uganda
</p>
</section>

<section>
<img src="food pack.jpg">
<img src="kurban akika.jpg">
</section>

<section>
<h2>Why You Need to Donate</h2>
<p>
Many people in Uganda Africa move long distances to collect water for use at home and masjid
but this water is not clean and safe for drinking this has lead to outbreak of diseases like
cholera and diahroea which has lead to death of many lives your charity can help to solve this
inshallah remember the prophet of Allah said that the best charity is giving water
</p>
<a href="#" onclick="showMore('more2')">Read more</a>
<p id="more2" style="display:none;">
Many children die on streets every day in Uganda Africa because they lack what to eat therefore
your donation can help to provide food to them inshallah.
</p>
</section>

<!-- DONATION METHODS -->
<section>
<h2>Ways of Donation</h2>
<ol>
<li>Western Union</li>
<li>PayPal</li>
<li>MoneyGram</li>
<li>Ria</li>
</ol>
</section>

<!-- COMMENTS -->
<section>
<h2>Leave a Comment Here</h2>
<textarea style="width:100%;height:100px;"></textarea><br><br>
<button class="btn">Submit</button>
</section>

<footer>
<p>
Ummah Charity Organization is a non profit organization dedicated to providing clean and safe
water, food, education and emergency relief to under privileged communities across Uganda.
</p>
<p>📞 +256756897359</p>
<p>📍 Eastern Uganda Africa</p>
<p>📧 ummahcharityorganization8@gmail.com</p>
<p>© Copyright reserved by Ummah Charity Organization</p>
</footer>

</body>
</html>
