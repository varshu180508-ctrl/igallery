# Ex.08 Design of Interactive Image Gallery
## Date:8.10.25

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :

```

gallery.html

<html>
    <head>
        <title>GALLERY</title>
        <link rel="stylesheet" href="gallery.css">
        <script src="gallery.js"></script>
    </head>
    <body>
        <h1>GALLERY - DHANVARSINI(25012184)</h1>
        <div class="gall">
            <div class="gallt">
                <img class="image" src="Screenshot 2025-10-08 162033.png" onmouseover="mousein()" onmouseout="mouseout()" id="img">
            </div>
            <div class="gallt">
                <img class="image" src="Screenshot 2025-10-08 162532.png" onmouseover="mousein()" onmouseout="mouseout()" id="img">
            </div>
            <div class="gallt">
                <img class="image" src="Screenshot 2025-10-08 162501.png" onmouseover="mousein()" onmouseout="mouseout()" id="img">
            </div>
            <div class="gallt">
                <img class="image" src="Screenshot 2025-10-08 162547.png" onmouseover="mousein()" onmouseout="mouseout()" id="img">
            </div>
            <div class="gallt">
                <img class="image" src="Screenshot 2025-10-08 162518.png" onmouseover="mousein()" onmouseout="mouseout()" id="img">
            </div>
        </div>
        <footer class="footers">
            &copy; DHANVARSINI S - (25012184)
        </footer>
        </body>
        </html>

    gallery.css

    body {
    background-color:rgb(249, 88, 142);
    text-align: center;
    margin-top: 50px;
}

.gall {
    display: flex;
    gap: 20px;
    padding-top: 50px;
    justify-content: center;;
}

.gallt{
    cursor: pointer;
    text-align: center;
    width: 200px;
    padding: 20px;
}

.gallt img{
    width: 230px;
    height: 300px;
}

.footers{
    width: 1510px;
    height: 20px;
    background-color: rgb(254, 251, 251);
    text-align: center;
    top: 130px;
    left: -20px;
    position: relative;
}


gallery.js

function mousein()
{
    document.getElementById("img").style.width="230";
    document.getElementById("img").style.height="370";
}

function mouseout()
{
    document.getElementById("img").style.width="230";
    document.getElementById("img").style.height="300";
}

```

## OUTPUT:
![alt text](<thugi/galleryapp/static/Screenshot (26).png>)
![alt text](<thugi/galleryapp/static/Screenshot (27).png>)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
