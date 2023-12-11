<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./css/style.css">
    <link rel="stylesheet" href="./css/btn1.css">
    <link rel="stylesheet" href="./css/btn2.css">
    <!-- css link for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <title>Button Animations</title>
</head>

<body>
    <a href="https://github.com/tilakjain123/Buttons">
        <div id="contribute" onmouseover="document.getElementById('message').style.display='block'" onmouseout="document.getElementById('message').style.display='none'"><i class="fab fa-github"></i></div>
    </a>
    <div id="message">Fork Me on Github?</div>
    <div class="main">
        <h2>Button designs | Only CSS</h2>
        <label>With Gradient Background</label>
        <div>
            <button id="bg1">Btn1</button>
            <button id="bg2">Btn2</button>
            <button id="bg3">Btn3</button><br>
            <h4>For gradient you can use <a href="https://www.w3schools.com/colors/colors_gradient.asp" target="_blank">W3
                School's gradient color genrator</a></h4>
            <hr>
            <label>With Hover Effects</label><br>
            <button href="#" class="hvr-underline-from-center">Underline From Center</button>
            <button href="#" class="hvr-underline-from-left">Underline From Left</button>
            <button href="#" class="hvr-underline-from-right">Underline From Right</button>
            <button href="#" class="hvr-overline-from-center">Overline From Center</button>
            <button href="#" class="hvr-overline-from-left">Overline From Left</button>
            <button href="#" class="hvr-overline-from-right">Overline From Right</button>
            <button href="#" class="hvr-overlay-from-center">Overlay From Center</button>
            <button href="#" class="hvr-overlay-from-bottom">Overlay From Bottom</button>
            <button href="#" class="hvr-overlay-from-top">Overlay From Top</button>
            <button href="#" class="hvr-overlay-from-left">Overlay From Left</button>
            <button href="#" class="hvr-overlay-from-right">Overlay From Right</button>
            <button href="#" class="hvr-glow">Glow</button>
            <button href="#" class="hvr-glow-inset">Glow Inset</button><br>
            <button href="#" id="running">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            Running
        </button>
            <button class="glow-on-hover" type="button">Glow on Hover</button>
            <br>
            <button id="btn1-1">Button1</button>
            <button id="btn1-2">Button2</button>
            <button id="btn1-3">Button3</button>
            <button id="btn1-4">Button4</button>
            <button id="btn1-5">Button5</button>
            <button id="btn1-6">Button6</button>
        </div>
        <hr>
        <label>With Icons</label>
        <div>
            <button href="#"><i class="fa fa-home"></i> Home</button>
            <button href="#"><i class="fa fa-bars"></i> Menu</button>
            <button href="#"><i class="fa fa-download"></i> Download</button>
            <button href="#"><i class="fa fa-file"></i> File</button>
            <button href="#">Read More <i class="fas fa-angle-double-right"></i></button>
            <button href="#">Upload <i class="fas fa-upload"></i></button>
        </div>
        <hr>
        <label>Hover Animation with Icons</label>
        <div>
            <button class="iconhover1"><span>More</span></button>
            <button class="iconhover2">Icon Wobble Right <i class="fa fa-arrow-right hvr-icon"></i></button>
        </div>
        <hr>
        <label>Click Animations</label>
        <div>
            <button class="animate1">Click Me1</button>
            <button class="animate2">Click Me2</button>
            <button class="animate3">Push Me</button>
        </div>
        <hr>
        <label>Other designs</label>
        <div>
            <button id="other1">Btn with img</button>
            <button class="hvr-show">Reveal on hover</button>
            <button class="hvr-message">Message on hover</button>
        </div>
    </div>
    <section id="featuring">
        Still thinking more? Want to Contribute? &nbsp;
        <a href="https://github.com/tilakjain123/Buttons" class="feature">Go to <i class="fa fa-github"> Github</i></a><br>
        <small>Icons by <a href="https://fontawesome.com" target="_blank">FontAwesome</a></small>
        <div id="quick-links">
            <h3>Quick Links</h3>
            <ul>
                <li><a href="https://github.com/tilakjain123">Github</a></li>
            </ul>
        </div>
    </section>
    <!-- js link for icons  -->
    <script src="https://kit.fontawesome.com/0852d65046.js" crossorigin="anonymous"></script>
</body>

</html>
