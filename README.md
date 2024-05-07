# Ex.06 Book Front Cover Page Design
## Date: 26.04.2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:

```
<!DOCTYPE html>
<html lang="en">
<head>
<meta name="viewport"
content="width=device-width, initial-scale=1.0">
<style>
    body,html{
        height: 50%;
    }
    .bookpage{
    width: 400px;
    height: 1000%;
    color:cyan;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    background-image: url(./web\ pic\ 1.jpg);
    background-color: black;
    background-repeat: no-repeat;
    background-size: 350%;
    }
    .insight{
    color: violet;
    }
    .hrstyle{
    width:100px;
    }
    .author{
    display: inline;
    position: relative;
    color: red;
    top:190px;
    font-family:Georgia;
    font-size: medium;
    }
    .booktitle{
    font-family: 'Courier New', Courier, monospace;
    font-size: larger;
    text-align: center;
    position: relative;
    top: 30px;
    }
    .id {
    width:400px;
    position: relative;
    top:180px;
    }
    .pub{
    font-size: medium;
    position: relative;
    top:155px;
    left:330px;
    }
    .ed{
    color: red;
    font-size: medium;
    font-family: Verdana;
    position:relative;
    top:85px;
    }
    .subtitle{
    font-family:Tahoma;
    font-size: large;
    position: relative;
    top:40px;
    }
    .mypic{
    position: relative;
    top: 135px;
    left: 260px;
    width: 100px;
    height: 100px;
    background-size: cover;
    }
    </style>
<title>Book Cover Page</title>
</head>
<body>
<div class="bookpage">
<div class="insight">
SEC INSIGHT
</div>
<div class="hrstyle">
<hr style="color: green;">
</div>
<div class="booktitle">
<h1>Fundamentals of Web Application Development</h1></div>
<div class="subtitle">
HTML and CSS Combined with Django Architecture
</div>
<div class="mypic">
</div>
<div class="id">
<hr style="color: orange;">
</div>
<img src="myphoto.png" style="margin-left: 30%; width: 100px;">
<div class="author">
<p><b>Rehan Jeyan</b></p>
</div>
<div class="pub">
SEC
</div>
<div class="ed">
<b>Eighth Edition</b>
</div>
</div>
</body>
</html>

```

## OUTPUT:

![Screenshot (49)](https://github.com/eswanth2005/cover/assets/164656722/c7a40b19-9c33-4b30-b94f-0d1fefed7763)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
