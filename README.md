# debello.main.github.io
Chuletas CSS

color
background-color
font-famlily (Arial, Times New Roman, Monospace, sans, sans-serif)
font-size
font-style (italic, oblique, normal)
font-weight (bold, bolder, normal, lighter, 100-900)

font (all) 30px solid italic red


text-align
text-decoration (underline)
line-height n / nem


---------------------------------------------------


* añadir github
           
            table .emperor {
                background-color: red;
            }
            
            .reign {
                font-family: monospace;
            }
            table .reign {
                background-color: aqua;
                
                
                -------------------------------------
            
            
   
   
            warning
            first
            
            
            
            p class="first warning"
            // affects warning and first
            p.warning
            // affects warning who is in p


*           a:hover
            active
            visited
            link
            visited
            focus
            
* grouping selectors
            h1, h2{
            etc
            }
            
* <p id="main-paragraph" class="info-paragraph important">


* inline styles

    <h1 style="background: salmon; color: white;">Salmon Mania</h1>

* external stylesheets
        <link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/pamelafox/69f97167ba32e3473cda/raw/336006010d620847f275b0bd25bbf7c665b2e1a1/hopper.css">
    
    
* Summary DOM access
https://www.khanacademy.org/computing/computer-programming/html-css-js/html-js-dom-access/a/summary-dom-access-methods
    
 
 *
        
                    var imageEls = document.getElementsByTagName("img");
            for (var i = 0; i < imageEls.length; i++) {
                imageEls[i].src = "https://www.kasandbox.org/programming-images/animals/cat.png";
            }
        
        
        var linkEls = document.querySelectorAll("a[href*=\"Dog\"]");
            for (var i = 0; i < linkEls.length; i++) {
                linkEls[i].href = "http://en.wikipedia.org/wiki/Cat";
        
        
*

    var colorEl = document.getElementById("trendy-color");
    var handEl  = document.getElementById("trendy-handwriting");
    var frameEl = document.getElementById("trendy-frame");
    
    colorEl.innerHTML = "red";
    colorEl.style.color = "red";
    
    handEl.innerHTML = "monospace";
    handEl.style.fontFamily = "monospace";
    
    frameEl.style.borderStyle = "dotted";
    
    
*


            body {
                background-color: black;
                padding: 10px;
            }
            .planet {
                width: 100px;
                height: 100px;
                border-radius: 50%;
                text-align: center;
                padding: 10px;
                position: relative;
            }
            .moon {
                position: absolute;
                width: 30px;
                height: 30px;
                border-radius: 50%;
                background: rgb(237, 237, 237);
            }
        </style>
    </head>
    <body>

    
    <script>
        var divEl = document.createElement("div");
        
        divEl.className = "planet";
        divEl.style.backgroundColor = "red";
        document.body.appendChild(divEl); 
      
        var divElTwo = document.createElement("div");
        
        divElTwo.className = "moon";
        divElTwo.style.backgroundColor = "blue";
        divEl.appendChild(divElTwo);
        
        
    </script>
        
        
* Resume
https://www.khanacademy.org/computing/computer-programming/html-css-js/html-js-dom-access/a/summary-dom-access-methods        

https://www.khanacademy.org/computing/computer-programming/html-css-js/html-js-dom-modification/a/summary-dom-modification-techniques