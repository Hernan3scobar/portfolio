---
layout: default
title: Hernán Escobar-Sánchez
---

# Data Scientist

#### Technical Skills: Python, Pytorch, Stadistical Analysis.

### Education

- M.S., Physics	| Universidad de Concepción, Concepción, Chile (_September 2023_)	 			        		
- B.S., Physics | Universidad de Concepción, Concepción, Chile (_December 2020_)
  
### Work Experience
**Data Scientist - AI code reviwer @ Revelo-Scale (_July 2024 - Present_)**
- Assessing the quality of AI-generated code. 
- Resolving coding problems by crafting functional and efficient code solutions.
- Developing test cases to validate the efficiency and effectiveness of the code.
  
**Applied Scientist and Data Analyst @ Universidad San Sebastián  (_April 2023 - June 2024_)**
- Conducted experimental setup, data collection, processing, and analysis for the characterization, simulation, and modeling of nano-materials.
- Developed Physics-informed neural networks to estimate optical parameters for light absorption in nanomaterials.
- Contributed to and published a paper in an international scientific journal.

### Projects
Dogs breeds classification
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

<div class="carousel">
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
    <div class="slides">
        <img src="assets/imag/scores_accuracy.png" alt="Scores">
    </div>

    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
    <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<div class="dots" style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span> 
    <span class="dot" onclick="currentSlide(2)"></span> 
    <span class="dot" onclick="currentSlide(3)"></span> 
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
        let slides = document.getElementsByClassName("slides");
        let dots = document.getElementsByClassName("dot");
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
    }
</script>

</body>
</html>


## Publications
.- Escobar-Sánchez, H.; Carril Pardo, C.; Benito, N.; Hernández-Montelongo, J.; Nancucheo, I.; Recio-Sánchez, G. Plasmonic and Photothermal Effects of CuS Nanoparticles Biosynthesized from Acid Mine Drainage with Potential Drug Delivery Applications. Int. J. Mol. Sci. 2023, 24, 16489. [https://doi.org/10.3390/ijms242216489]

Para contactarme, puedes enviarme un correo a [miemail@example.com](mailto:miemail@example.com).
