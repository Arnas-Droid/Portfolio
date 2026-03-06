---
layout: post
title: "The Witch Forest"
---

<html>
<body>
  <!-- Video Section -->
  <div style="text-align: center; margin-bottom: 20px;">
    <iframe width="560" height="315" 
      src="https://www.youtube.com/embed/hXlKtwVcpxY" 
      frameborder="0" 
      allowfullscreen>S
    </iframe>
  </div>

  <!-- Description Section -->
  <div style="padding: 0 20px; text-align: justify;">
    <p>Description: Using DirectX11, I learned more about graphic pipelines and how to create a 3D environment that utilized the pipeline for rendering lighting and shading models. Drawing inspiration from my heritage, I created the "witch forest" scene. My biggest challenge came when I was working on the scene graph hierarchy. I struggled with the idea of using functions to access different files. Although it worked when created in the main function, it felt a bit messy and harder to follow from an external viewpoint. Ultimately, I managed to build it, but there were issues I would approach differently in future projects. It's currently my favorite piece of work.</p>
  </div>

<script>
  let slideIndex = 1;
  showSlides(slideIndex);

  function plusSlides(n) {
  showSlides(slideIndex += n);
  }

  function currentSlide(n) {
    showSlides(slideIndex = n);
  }

  function showSlides(n) {
    let i;
    let slides = document.getElementsByClassName("slide");
    let dots = document.getElementsByClassName("demo");
    let captionText = document.getElementById("caption");
    if (n > slides.length) {slideIndex = 1}
    if (n < 1) {slideIndex = slides.length}
    for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
    }
    for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex-1].style.display = "block";
    dots[slideIndex-1].className += " active";
    captionText.innerHTML = dots[slideIndex-1].alt;
  }
</script>
</body>
</html>