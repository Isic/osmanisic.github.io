<!DOCTYPE html>
<html>
<title>Osman Isić</title>
<link href="favicon.png" rel="icon" type="image/x-icon" />
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<body>

<!-- Navigacijska traka(Meni) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-wide w3-padding w3-card">
    <a href="#home" class="w3-bar-item w3-button"><b>Osman Isić</b> Početna stranica</a>
    <!-- Linkovi na desno,sakriveni na manjim ekranima -->
    <div class="w3-right w3-hide-small">
      <a href="#projects" class="w3-bar-item w3-button">Primjeri</a>
      <a href="#about" class="w3-bar-item w3-button">O meni</a>
      <a href="#contact" class="w3-bar-item w3-button">Kontakt</a>
    </div>
  </div>
</div>

<!-- Header -->
<header class="w3-display-container w3-content w3-wide" style="max-width:1500px;" id="home">
  <picture>
  <img src="slika.jpg" alt="Osman Isic" width=100%; height=100%;>
</picture>
</header>

<!-- Sadrzaj stranice -->
<div class="w3-content w3-padding" style="max-width:1564px">

  <!-- Sekcija za projekte -->
  <div class="w3-container w3-padding-32" id="projects">
    <h3 class="w3-border-bottom w3-border-black w3-padding-16">Primjeri</h3>
  </div>
<br>
<br>
  <div class="w3-row-padding">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container">
        <div class="w3-display-topleft w3-black w3-padding"><a href="Javascript.html" target="_blank">JavaScript</a></div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container">
        <div class="w3-display-topleft w3-black w3-padding"><a href="CSSInLine.html" target="_blank">CSS InLine</a></div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container">
        <div class="w3-display-topleft w3-black w3-padding"><a href="CSSHeader.html" target="_blank">CSS Header</a></div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-display-container">
        <div class="w3-display-topleft w3-black w3-padding"><a href="CSSInCSS.html" target="_blank">CSS u CSS datoteci</a></div>
      </div>
    </div>
  </div>
  <br>
  <br>
  <br>

  <!-- Sekcija o meni -->
  <div class="w3-container w3-padding-32" id="about">
    <h3 class="w3-border-bottom w3-border-black w3-padding-16">O meni</h3>
    <p> Ja sam Osman Isić. Rođen sam 12.11.2000 u Zenici. Imam 18 godina. Pohađam Mješovitu Srednju Školu u Tešnju,<br>
      zanimanje Elektrotehničar računarstva. Odličan sam učenik.
    </p>
    <hr>
<h1 style="font-size:15pt;">Iskustvo: </h1>
      Jezici:                     C++, Visual Basic, HTML.<br>
      Platforme:                  Windows Seven, XP, Linux.<br>
      Koncepti:                   Mreže, Operativni sistemi.
<hr>
<h1 style="font-size:15pt;">Sposobnosti: </h1>
      Nivo znanja:              MS Word, MS Excel, Power point.<br>
      Praksa:                   4 godine.
<hr>
<h1 style="font-size:15pt;">Lične osobine: </h1>
                                  1.Realnost.<br>
                                  2.Timski rad.<br>
                                  3.Spremnost na izazove.
<hr>  
<h1 style="font-size:15pt;">Jezici:</h1>
                                  Engleski i Njemački.
<hr>                   
<h1 style="font-size:15pt;">Hobi:</h1>
                                  1.Pretraživanje interneta<br>
                                  2.Čitanje knjiga<br>
                                  3.Slušanje muzike
<hr>
  </div>
  <!-- Sekcija kontakt -->
  <div class="w3-container w3-padding-32" id="contact">
    <h3 class="w3-border-bottom w3-border-black w3-padding-16">Kontakt</h3>
    <p></p>
    <form action="/action_page.php" target="_blank">
      <input class="w3-input w3-border" type="text" placeholder="Ime" required name="Name">
      <input class="w3-input w3-section w3-border" type="text" placeholder="Email" required name="Email">
      <input class="w3-input w3-section w3-border" type="text" placeholder="Predmet" required name="Subject">
      <input class="w3-input w3-section w3-border" type="text" placeholder="Komentar" required name="Comment">
      <button class="w3-button w3-black w3-section" type="submit">
        <i class="fa fa-paper-plane"></i> POŠALJI
      </button>
    </form>
  </div>
  
<!-- Kraj stranice -->
</div>
<center>
<a href="#home" class="w3-button w3-black"><i class="fa fa-arrow-up w3-margin-center"></i>Na početak ↑</a>
<br>
<br>
</center>
<!-- Footer -->
<footer class="w3-center w3-black w3-padding-16">
  <p>by <a href="https://www.instagram.com/osmanisic/" title="Insta" target="_blank" class="w3-hover-text-green">Osman Isić</a></p>
</footer>

</body>
</html>
