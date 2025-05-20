# Ex.08 Design of Interactive Image Gallery
## Developed by : **P KEVIN**
## Reg No : **212224040159**
### Date : 18 - 05 - 2025
## AIM
  To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS

### Step 1:

Clone the github repository and create Django admin interface

### Step 2:

Change settings.py file to allow request from all hosts.

### Step 3:

Use CSS for positioning and styling.

### Step 4:

Write JavaScript program for implementing interactivit

### Step 5:

Validate the HTML and CSS code

### Step 6:

Publish the website in the given URL.

## PROGRAM
### Gallery.html

```!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Fav</title>
    <link rel="stylesheet" href="Gallery.css">
</head>
<body>
       <h1>Hall of Legends</h1>

    <div class="gallery" onclick="openLightbox(event)">
        <img src="Images/Vijay.jpg"
            alt="Vijay">
        <img src="Images/Ashwin.jpeg"
            alt="Ashwin">
        <img src="Images/AR Rahman.jpeg"
            alt="AR Rahman">
        <img src="Images/PVK.jpg"
            alt="PVK">
  
    </div>

    <div id="lightbox">
        <span id="close-btn" onclick="closeLightbox()">&times;</span>

        <img id="lightbox-img" src="" alt="lightbox image">

        <div id="thumbnail-container">
        </div>
        <button id="prev-btn" onclick="changeImage(-1)">&lt; Prev</button>
        <button id="next-btn" onclick="changeImage(1)">Next &gt;</button>
    </div>
    <script src="Gallery.js"></script>

</body>
</html>
```
Galler.css and Gallery .js are attached to the Repository.

## OUTPUT
![Screenshot 2025-05-20 192514](https://github.com/user-attachments/assets/60cbafd1-1ab5-4001-bde6-5b1943defe46)

## RESULT
  The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
