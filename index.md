---
layout: default
title: Hernán Escobar-Sánchez
---

# Data Scientist

#### Technical Skills: Python, Pytorch, Stadistical Analysis.

## Education

- M.S., Physics	| Universidad de Concepción, Concepción, Chile (_September 2023_)	 			        		
- B.S., Physics | Universidad de Concepción, Concepción, Chile (_December 2020_)
  
## Work Experience
**Data Scientist - AI code reviwer @ Revelo-Scale (_July 2024 - Present_)**
- Assessing the quality of AI-generated code. 
- Resolving coding problems by crafting functional and efficient code solutions.
- Developing test cases to validate the efficiency and effectiveness of the code.
  
**Applied Scientist and Data Analyst @ Universidad San Sebastián  (_April 2023 - June 2024_)**
- Conducted experimental setup, data collection, processing, and analysis for the characterization, simulation, and modeling of nano-materials.
- Developed Physics-informed neural networks to estimate optical parameters for light absorption in nanomaterials.
- Contributed to and published a paper in an international scientific journal.

## Projects
### Dogs breeds classification
- The model's accuracy improves significantly over 10 epochs, reaching 98.84% in training and 99.67% in testing, with corresponding decreases in loss from 1.1626 to 0.03894 and 0.6186 to 0.0206, respectively.
[GitHub repository](https://github.com/Hernan3scobar/CNN_images_classification/tree/main)





<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hernán Escobar-Sánchez</title>
    <style>
        * { box-sizing: border-box; }
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
        .carousel { position: relative; max-width: 1000px; margin: auto; }
        .slides { display: none; }
        img { vertical-align: middle; width: 500px; height: auto; }
        .prev, .next { 
            cursor: pointer;
            position: absolute;
            top: 50%;
            width: auto;
            margin-top: -22px;
            padding: 16px;
            color: white;
            font-weight: bold;
            font-size: 18px;
            transition: 0.6s ease;
            border-radius: 0 3px 3px 0;
            user-select: none;
        }
        .next { right: 0; border-radius: 3px 0 0 3px; }
        .prev:hover, .next:hover { background-color: rgba(0,0,0,0.8); }
        .dots { text-align: center; padding: 20px; background: #ddd; }
        .dot {
            cursor: pointer;
            height: 15px;
            width: 15px;
            margin: 0 2px;
            background-color: #bbb;
            border-radius: 50%;
            display: inline-block;
            transition: background-color 0.6s ease;
        }
        .active, .dot:hover { background-color: #717171; }
    </style>
</head>
<body>

<!-- First Carousel -->
<div class="carousel" id="carousel1">
    <div class="slides">
        <img src="assets/imag/prediction_vs_true.png" alt="Predictions">
    </div>
    <div class="slides">
        <img src="assets/imag/cnm.png" alt="Confution Matrix">
    </div>
    <div class="slides">
        <img src="assets/imag/loss.png" alt="Losses">
    </div>
    <div class="slides">
        <img src="assets/imag/accuracy.png" alt="Accuracy">
    </div>
    <a class="prev" onclick="plusSlides(-1, 'carousel1')">&#10094;</a>
    <a class="next" onclick="plusSlides(1, 'carousel1')">&#10095;</a>
</div>
<br>
<div class="dots" id="dots1">
    <span class="dot" onclick="currentSlide(1, 'carousel1', 'dots1')"></span> 
    <span class="dot" onclick="currentSlide(2, 'carousel1', 'dots1')"></span> 
    <span class="dot" onclick="currentSlide(3, 'carousel1', 'dots1')"></span> 
    <span class="dot" onclick="currentSlide(4, 'carousel1', 'dots1')"></span> 
</div>


## Projects
### Dogs breeds classification
- The model's accuracy improves significantly over 10 epochs, reaching 98.84% in training and 99.67% in testing, with corresponding decreases in loss from 1.1626 to 0.03894 and 0.6186 to 0.0206, respectively.
[GitHub repository](https://github.com/Hernan3scobar/CNN_images_classification/tree/main)


<!-- Second Carousel -->
<div class="carousel" id="carousel2">
    <div class="slides">
        <img src="assets/imag/sample.png" alt="Second Image 1">
    </div>
    <div class="slides">
        <img src="assets/imag/results.png" alt="Second Image 2">
    </div>
   
    <a class="prev" onclick="plusSlides(-1, 'carousel2')">&#10094;</a>
    <a class="next" onclick="plusSlides(1, 'carousel2')">&#10095;</a>
</div>
<br>
<div class="dots" id="dots2">
    <span class="dot" onclick="currentSlide(1, 'carousel2', 'dots2')"></span> 
    <span class="dot" onclick="currentSlide(2, 'carousel2', 'dots2')"></span> 
   
</div>

<script>
    // Function to show the slides for a specific carousel
    function showSlides(n, carouselId, dotsId) {
        let i;
        let slides = document.getElementById(carouselId).getElementsByClassName("slides");
        let dots = document.getElementById(dotsId).getElementsByClassName("dot");
        if (n > slides.length) {n = 1}    
        if (n < 1) {n = slides.length}
        for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";  
        }
        for (i = 0; i < dots.length; i++) {
            dots[i].className = dots[i].className.replace(" active", "");
        }
        slides[n-1].style.display = "block";  
        dots[n-1].className += " active";
    }

    // Function to handle the next/prev button click
    function plusSlides(n, carouselId) {
        let currentSlide = parseInt(document.getElementById(carouselId).getAttribute("data-slide-index")) || 1;
        currentSlide += n;
        showSlides(currentSlide, carouselId, 'dots' + carouselId.charAt(carouselId.length - 1));
        document.getElementById(carouselId).setAttribute("data-slide-index", currentSlide);
    }

    // Function to handle the dot click
    function currentSlide(n, carouselId, dotsId) {
        showSlides(n, carouselId, dotsId);
    }

    // Initialize slides for all carousels
    showSlides(1, 'carousel1', 'dots1');
    showSlides(1, 'carousel2', 'dots2');
</script>

</body>
</html>
## Publications
.- Escobar-Sánchez, H.; Carril Pardo, C.; Benito, N.; Hernández-Montelongo, J.; Nancucheo, I.; Recio-Sánchez, G. Plasmonic and Photothermal Effects of CuS Nanoparticles Biosynthesized from Acid Mine Drainage with Potential Drug Delivery Applications. Int. J. Mol. Sci. 2023, 24, 16489. [https://doi.org/10.3390/ijms242216489]

For inquiries, feel free to email me at: [hernanescobarsanchez@gmail.com](mailto:hernanescobarsanchez@gmail.com).
