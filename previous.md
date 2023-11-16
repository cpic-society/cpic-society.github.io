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
      grid-template-columns: repeat(auto-fit, minmax(400px, 1fr)); /* Two columns that fill available space */
      gap: 10px; /* Gap between grid items */
      row-gap: 30px; /* Space between rows */
      justify-items: center; /* Center items horizontally */
    }

    .photo-item {
      width: 100%; /* Adjust width of each photo item */
      height: auto; /* Adjust height as needed */
    }

    /* Optional: Style for responsive layout */
    @media (max-width: 768px) {
      .photo-grid {
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); /* Adjust for smaller screens */
      }
    }

    @media (max-width: 480px) {
      .photo-grid {
        grid-template-columns: 1fr; /* Single column for even smaller screens */
      }
    }
  </style>
</head>
<body>

<div class="photo-grid">
  <div class="photo-item">
    <span style="color:#398188">CπC1</span>  <span style="color:#606060">:: Valencia, Spain, 21-23.01.2010</span>  
    <a href="javascript:void(0);" onclick="openImagePopup('assets/images/cpic1_large.png')">
      <img src="assets/images/cpic1_large.png" width="400"/>
    </a>
  </div>
  <div class="photo-item">
    <span style="color:#398188">CπC2</span>  <span style="color:#606060">:: Limoges, France, 03-05.02.2011</span> 
    <a href="javascript:void(0);" onclick="openImagePopup('assets/images/cpic2_large.png')">
      <img src="assets/images/cpic2_large.png" width="400"/>
    </a>
  </div>
  <div class="photo-item">
    <span style="color:#398188">CπC3</span>  <span style="color:#606060">:: Mons, Belgium, 02-04.02.2012</span> 
    <a href="javascript:void(0);" onclick="openImagePopup('assets/images/cpic3_large.png')">
      <img src="assets/images/cpic3_large.png" width="400"/>
    </a>
  </div>
  <div class="photo-item">
    <span style="color:#398188">CπC4</span>  <span style="color:#606060">:: Marseille, France, 31.01-02.02.2013</span> 
    <a href="javascript:void(0);" onclick="openImagePopup('assets/images/cpic4_large.jpg')">
      <img src="assets/images/cpic4_large.jpg" width="400"/>
    </a>
  </div>
  <div class="photo-item">
    <span style="color:#398188">CπC5</span>  <span style="color:#606060">:: Linköping, Sweden, 05-07.02.2014</span> 
    <a href="javascript:void(0);" onclick="openImagePopup('assets/images/cpic5_large.jpg')">
      <img src="assets/images/cpic5_large.jpg" width="400"/>
    </a>
  </div>
  <div class="photo-item">
    <span style="color:#398188">CπC6</span>  <span style="color:#606060">:: Olomouc, Czech Republic, 05-07.02.2015</span> 
    <a href="javascript:void(0);" onclick="openImagePopup('assets/images/cpic6_large.jpg')">
      <img src="assets/images/cpic6_large.jpg" width="400"/>
    </a>
  </div>
  <div class="photo-item">
    <span style="color:#398188">CπC7</span>  <span style="color:#606060">:: Bordeaux, France, 12-13.02.2016</span> 
    <a href="javascript:void(0);" onclick="openImagePopup('assets/images/cpic7_large.jpg')">
      <img src="assets/images/cpic7_large.jpg" width="400"/>
    </a>
  </div>
  <div class="photo-item">
    <span style="color:#398188">CπC8</span>  <span style="color:#606060">:: Malaga, Spain, 26-28.01.2017</span> 
    <a href="javascript:void(0);" onclick="openImagePopup('assets/images/cpic8_large.jpg')">
      <img src="assets/images/cpic8_large.jpg" width="400"/>
    </a>
  </div>
  <div class="photo-item">
    <span style="color:#398188">CπC9</span>  <span style="color:#606060">:: Napoli, Italy, 18-20.01.2018</span> 
    <a href="javascript:void(0);" onclick="openImagePopup('assets/images/cpic9_large.jpg')">
      <img src="assets/images/cpic9_large.jpg" width="400"/>
    </a>
  </div>
  <div class="photo-item">
    <span style="color:#398188">CπC10</span>  <span style="color:#606060">:: Valencia, Spain, 01-02.02.2019</span> 
    <a href="javascript:void(0);" onclick="openImagePopup('assets/images/cpic10_large.jpg')">
      <img src="assets/images/cpic10_large.jpg" width="400"/>
    </a>
  </div>
  <div class="photo-item">
    <span style="color:#398188">CπC11</span>  <span style="color:#606060">:: Zagreb, Croatia, 30.-01.02.2020</span> 
    <a href="javascript:void(0);" onclick="openImagePopup('assets/images/cpic11_large.jpg')">
      <img src="assets/images/cpic11_large.jpg" width="400"/>
    </a>
  </div>
  <div class="photo-item">
    <span style="color:#398188">CπC12 Covid-19 edition</span>  <span style="color:#606060">:: Online, 18-20.01.2021</span> 
    <a href="javascript:void(0);" onclick="openImagePopup('assets/images/cpic_virtual.png')">
      <img src="assets/images/cpic_virtual.png" width="400"/>
    </a>
  </div>
  <div class="photo-item">
    <span style="color:#398188">CπC12</span>  <span style="color:#606060">:: Grenoble, France, 12-14.05.2022</span> 
    <a href="javascript:void(0);" onclick="openImagePopup('assets/images/cpic12_large.jpg')">
      <img src="assets/images/cpic12_large.jpg" width="400"/>
    </a>
  </div>
  <div class="photo-item">
    <span style="color:#398188">CπC13</span>  <span style="color:#606060">:: Madrid, Spain, 26-28.01.2023</span> 
    <a href="javascript:void(0);" onclick="openImagePopup('assets/images/cpic13_large.jpg')">
      <img src="assets/images/cpic13_large.jpg" width="400"/>
    </a>
  </div>
  <!-- Add more photo items as needed -->
</div>

<br>
<br>
<head>
  <meta charset="UTF-8">
  <title>Thin Line Example</title>
</head>
<body>
  <hr style="border: none; background-color: #000; height: 1px; margin: 20px 0;">
Next edition will take place in Donostia, Spain.<br>
<span style="color:#398188">CπC14</span>  <span style="color:#606060">:: Donostia, Spain, 08-09.02.2024</span>
</body>


<div id="imagePopup" class="image-popup">
  <span class="close-btn" onclick="closeImagePopup()">&times;</span>
  <img id="popupImage" src="" alt="Popup Image">
</div>

<script>
function openImagePopup(imageUrl) {
  var img = document.getElementById("popupImage");
  img.src = imageUrl;

  var popup = document.getElementById("imagePopup");
  popup.style.display = "block";

  var clickedImage = event.currentTarget;
  var rect = clickedImage.getBoundingClientRect();
  var popupWidth = popup.offsetWidth;
  var popupHeight = popup.offsetHeight;

  var topPosition = rect.top + window.scrollY + rect.height / 2 - popupHeight / 2;
  var leftPosition = (window.innerWidth - popupWidth) / 2;

  popup.style.top = Math.max(topPosition, 0) + "px";
  popup.style.left = Math.max(leftPosition, 0) + "px";
}

function closeImagePopup() {
  var popup = document.getElementById("imagePopup");
  popup.style.display = "none";
}
</script>

</body>
</html>
