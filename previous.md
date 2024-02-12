---
title: "Previous editions"
layout: columns
---

<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Photo Grid</title>
  <style>
    /* Basic styling for the grid */
    .photo-grid {
      display: grid;
      gap: 10px; /* Gap between grid items */
      row-gap: 50px; /* Space between rows */
      justify-items: center; /* Center items horizontally */
    }

    .photo-item {
      display: grid;
      grid-template-columns: 1fr 1fr; /* Divide each photo item into two columns */
      align-items: center; /* Center items vertically */
      gap: 20px; /* Gap between text/image and photo */
      width: 100%; /* Adjust width of each photo item */
      max-width: 800px; /* Limit maximum width */
      box-sizing: border-box; /* Include padding and border in the element's total width and height */
      margin: 0 auto; /* Center the item within the container */
    }

    .photo-info {
      text-align: left;
    }

    /* Style for the larger text */
    .larger-text {
      color: #398188; /* Text color */
      font-size: 1.15em; /* Larger font size */
      font-weight: bold; /* Optionally, you can set the font weight */
      display: inline-block; /* Display inline to maintain elements on the same line */
    }

    /* Style for the smaller text */
    .smaller-text {
      color: #606060; /* Text color */
      font-size: 1.05em; /* Regular font size */
      display: block; /* Display block to ensure elements appear on separate lines */
    }
  </style>
</head>
<body>

<div class="photo-grid">
  <div class="photo-item">
    <div class="photo-info">
      <span class="larger-text">CπC1</span>
      <span class="smaller-text">Valencia, Spain, 21-23.01.2010</span>
      <p>Organizer: Begoña Milián-Medina, Johannes Gierschner<br>Participants: 24</p>
      <img src="assets/images/logo_cpic1.png" alt="Small Image" width="150">
    </div>
    <div class="photo-display">
      <a href="#" onclick="openImagePopup('assets/images/cpic1_large.png', event)">
        <img class="smallImage" src="assets/images/cpic1_large.png" width="500" />
      </a>
    </div>
  </div>
  <div class="photo-item">
    <div class="photo-info">
      <span class="larger-text">CπC2</span>
      <span class="smaller-text">Limoges, France, 03-05.02.2011</span>
      <p>Organizer: Patrick Trouillas<br>Participants: 36</p>
      <img src="assets/images/logo_cpic2.png" alt="Small Image" width="150">
    </div>
    <div class="photo-display">
      <a href="#" onclick="openImagePopup('assets/images/cpic2_large.png', event)">
        <img class="smallImage" src="assets/images/cpic2_large.png" width="500" />
      </a>
    </div>
  </div>
  <div class="photo-item">
    <div class="photo-info">
      <span class="larger-text">CπC3</span>
      <span class="smaller-text">Mons, Belgium, 02-04.02.2012</span>
      <p>Organizer: Yoann Olivier<br>Participants: 58</p>
      <img src="assets/images/logo_cpic3.png" alt="Small Image" width="150">
    </div>
    <div class="photo-display">
      <a href="#" onclick="openImagePopup('assets/images/cpic3_large.png', event)">
        <img class="smallImage" src="assets/images/cpic3_large.png" width="500" />
      </a>
    </div>
  </div>
  <div class="photo-item">
    <div class="photo-info">
      <span class="larger-text">CπC4</span>
      <span class="smaller-text">Marseille, France, 31.01-02.02.2013</span>
      <p>Organizer: Philippe Marsal<br>Participants: 28</p>
      <img src="assets/images/logo_cpic4.png" alt="Small Image" width="150">
    </div>
    <div class="photo-display">
      <a href="#" onclick="openImagePopup('assets/images/cpic4_large.jpg', event)">
        <img class="smallImage" src="assets/images/cpic4_large.jpg" width="500" />
      </a>
    </div>
  </div>
  <div class="photo-item">
    <div class="photo-info">
      <span class="larger-text">CπC5</span>
      <span class="smaller-text">Linköping, Sweden, 05-07.02.2014</span>
      <p>Organizer: Mathieu Linares<br>Participants: 43</p>
      <img src="assets/images/logo_cpic5.png" alt="Small Image" width="150">
    </div>
    <div class="photo-display">
      <a href="#" onclick="openImagePopup('assets/images/cpic5_large.jpg', event)">
        <img class="smallImage" src="assets/images/cpic5_large.jpg" width="500" />
      </a>
    </div>
  </div>
  <div class="photo-item">
    <div class="photo-info">
      <span class="larger-text">CπC6</span>
      <span class="smaller-text">Olomouc, Czech Republic, 05-07.02.2015</span>
      <p>Organizer: Michal Otyepka, Karel Berka<br>Participants: 48</p>
      <img src="assets/images/logo_cpic6.png" alt="Small Image" width="90">
    </div>
    <div class="photo-display">
      <a href="#" onclick="openImagePopup('assets/images/cpic6_large.jpg', event)">
        <img class="smallImage" src="assets/images/cpic6_large.jpg" width="500" />
      </a>
    </div>
  </div>
  <div class="photo-item">
    <div class="photo-info">
      <span class="larger-text">CπC7</span>
      <span class="smaller-text">Bordeaux, France, 12-13.02.2016</span>
      <p>Organizer: Luca Muccioli, Frédéric Castet, Lionel Truflandier<br>Participants: 56</p>
      <img src="assets/images/logo_cpic7.png" alt="Small Image" width="200">
    </div>
    <div class="photo-display">
      <a href="#" onclick="openImagePopup('assets/images/cpic7_large.jpg', event)">
        <img class="smallImage" src="assets/images/cpic7_large.jpg" width="500" />
      </a>
    </div>
  </div>
  <div class="photo-item">
    <div class="photo-info">
      <span class="larger-text">CπC8</span>
      <span class="smaller-text">Malaga, Spain, 26-28.01.2017</span>
      <p>Organizer: M<sup>a</sup> C. Ruiz Delgado, J. C. Sancho Garcia<br>Participants: 62</p>
      <img src="assets/images/logo_cpic8.png" alt="Small Image" width="200">
    </div>
    <div class="photo-display">
      <a href="#" onclick="openImagePopup('assets/images/cpic8_large.jpg', event)">
        <img class="smallImage" src="assets/images/cpic8_large.jpg" width="500" />
      </a>
    </div>
  </div>
  <div class="photo-item">
    <div class="photo-info">
      <span class="larger-text">CπC9</span>
      <span class="smaller-text">Napoli, Italy, 18-20.01.2018</span>
      <p>Organizer: Roberto Improta<br>Participants: 45</p>
      <img src="assets/images/logo_cpic9.png" alt="Small Image" width="200">
    </div>
    <div class="photo-display">
      <a href="#" onclick="openImagePopup('assets/images/cpic9_large.jpg', event)">
        <img class="smallImage" src="assets/images/cpic9_large.jpg" width="500" />
      </a>
    </div>
  </div>
  <div class="photo-item">
    <div class="photo-info">
      <span class="larger-text">CπC10</span>
      <span class="smaller-text">Valencia, Spain, 01-02.02.2019</span>
      <p>Organizer: Begoña Milián-Medina, Johannes Gierschner<br>Participants: 52</p>
      <img src="assets/images/logo_cpic10.png" alt="Small Image" width="120">
    </div>
    <div class="photo-display">
      <a href="#" onclick="openImagePopup('assets/images/cpic10_large.jpg', event)">
        <img class="smallImage" src="assets/images/cpic10_large.jpg" width="500" />
      </a>
    </div>
  </div>
  <div class="photo-item">
    <div class="photo-info">
      <span class="larger-text">CπC11</span>
      <span class="smaller-text">Zagreb, Croatia, 30.-01.02.2020</span>
      <p>Organizer: Luca Grisanti, Aurora Ponzi<br>Participants: 53</p>
      <img src="assets/images/logo_cpic11.png" alt="Small Image" width="120">
    </div>
    <div class="photo-display">
      <a href="#" onclick="openImagePopup('assets/images/cpic11_large.jpg', event)">
        <img class="smallImage" src="assets/images/cpic11_large.jpg" width="500" />
      </a>
    </div>
  </div>
  <div class="photo-item">
    <div class="photo-info">
      <span class="larger-text">CπC Covid-19 edition</span>
      <span class="smaller-text">Online, 18-20.01.2021</span>
      <p>Organizer: G. d'Avino, L. Grisanti, G. Prampolini, M. Linares<br>Participants: 100</p>
    </div>
    <div class="photo-display">
      <a href="#" onclick="openImagePopup('assets/images/cpic_virtual.png', event)">
        <img class="smallImage" src="assets/images/cpic_virtual.png" width="500" />
      </a>
    </div>
  </div>
  <div class="photo-item">
    <div class="photo-info">
      <span class="larger-text">CπC12</span>
      <span class="smaller-text">Grenoble, France, 12-14.05.2022</span>
      <p>Organizer: Gabriele d'Avino<br>Participants: 60</p>
      <img src="assets/images/logo_cpic12.png" alt="Small Image" width="200">
    </div>
    <div class="photo-display">
      <a href="#" onclick="openImagePopup('assets/images/cpic12_large.jpg', event)">
        <img class="smallImage" src="assets/images/cpic12_large.jpg" width="500" />
      </a>
    </div>
  </div>
  <div class="photo-item">
    <div class="photo-info">
      <span class="larger-text">CπC13</span>
      <span class="smaller-text">Madrid, Spain, 26-28.01.2023</span>
      <p>Organizer: Javier Cerezo, Lara Martínez<br>Participants: 64</p>
      <img src="assets/images/logo_cpic13.png" alt="Small Image" width="150">
    </div>
    <div class="photo-display">
      <a href="#" onclick="openImagePopup('assets/images/cpic13_large.jpg', event)">
        <img class="smallImage" src="assets/images/cpic13_large.jpg" width="500" />
      </a>
    </div>
  </div>
  <div class="photo-item">
    <div class="photo-info">
      <span class="larger-text">CπC14</span>
      <span class="smaller-text">Donostia, Spain, 08-09.02.2024</span>
      <p>Organizer: Claire Tonnelé<br>Participants: 74</p>
      <img src="assets/images/logo_cpic14.png" alt="Small Image" width="170">
    </div>
    <div class="photo-display">
      <a href="#" onclick="openImagePopup('assets/images/cpic14_large.jpg', event)">
        <img class="smallImage" src="assets/images/cpic13_large.jpg" width="500" />
      </a>
    </div>
  </div>
  <!-- Repeat the above structure for other photo items -->
</div>

<br>
<br>
<head>
  <meta charset="UTF-8">
  <title>Thin Line Example</title>
</head>
<body>
  <hr style="border: none; background-color: #000; height: 1px; margin: 20px 0;">
Next edition will take place in Siena, Italy.<br>
<span style="color:#398188">CπC15</span>  <span style="color:#606060">:: Siena, Italy, 2025</span>
</body>


<div id="imagePopup" class="image-popup" style="display: none;">
  <span class="close-btn" onclick="closeImagePopup()">&times;</span>
  <img id="popupImage" src="" alt="Popup Image" />
</div>

<script>
function openImagePopup(imageUrl, event) {
  event.preventDefault();

  var img = document.getElementById("popupImage");
  img.src = imageUrl;

  var popup = document.getElementById("imagePopup");
  popup.style.display = "block";

  var smallImage = event.currentTarget.querySelector("img.smallImage");
  var rect = smallImage.getBoundingClientRect();

  var popupWidth = popup.offsetWidth;
  var popupHeight = popup.offsetHeight;

  var leftPosition = rect.left + window.scrollX + (rect.width / 2) - (popupWidth / 2);
  var topPosition = rect.top + window.scrollY + (rect.height / 2) - (popupHeight / 2);

  popup.style.left = leftPosition + "px";
  popup.style.top = topPosition + "px";

  document.addEventListener("click", closeOnClickOutside);
}

function closeImagePopup() {
  var popup = document.getElementById("imagePopup");
  popup.style.display = "none";
  document.removeEventListener("click", closeOnClickOutside);
}

function closeOnClickOutside(event) {
  var popup = document.getElementById("imagePopup");
  var smallImages = document.querySelectorAll(".smallImage");

  var isClickInsidePopup = popup.contains(event.target);
  var isClickOnSmallImage = Array.from(smallImages).some((image) => image.contains(event.target));

  if (!isClickInsidePopup && !isClickOnSmallImage) {
    popup.style.display = "none";
    document.removeEventListener("click", closeOnClickOutside);
  }
}
</script>

</body>
</html>
