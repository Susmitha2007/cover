# Ex.05 Book Front Cover Page Design
## Date:15-02-2026

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
    <meta charset="UTF-8">
    <title>Build Your Own Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="cover">

    <div class="title">BUILD YOUR OWN PORTFOLIO</div>

    <div class="subtitle">
        Showcase your skills, projects, and growth
    </div>

    <div class="role">
        Web Developer • Data Science Student • AI Enthusiast
    </div>

    <div class="divider"></div>

    <div class="icons">
        <span>💻</span>
        <span>🌐</span>
        <span>📊</span>
        <span>🤖</span>
    </div>

    <!-- LEFT DESCRIPTION BOX -->
    <div class="description-box">
        <h4>About the Portfolio</h4>
        <p>
            This portfolio presents a structured overview of web development,
            data science, and artificial intelligence concepts. It highlights
            practical skills, academic learning, and hands-on project experience.
        </p>
    </div>

    <!-- PHOTO -->
    <img src="photo.jpeg" alt="My Photo" class="photo">

    <!-- AUTHOR -->
    <div class="author">by: Susmitha</div>

    <!-- FOOTER -->
    <div class="footer">
        Student Portfolio Project • Version 1.0 • 2026
    </div>

</div>

</body>
</html>

style.css
body{
    margin:0;
    padding:0;
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:#f0f0f0;
    font-family:'Georgia', serif;
}

.cover{
    width:400px;
    height:650px;
    background:linear-gradient(135deg, #1e3c72, #2a5298);
    border-radius:20px;
    box-shadow:0 15px 30px rgba(0,0,0,0.4);
    padding:35px 30px;
    color:white;
    text-align:center;
    position:relative;
}

.title{
    font-size:32px;
    font-weight:bold;
    background:rgba(255,255,255,0.95);
    color:#000;
    padding:16px;
    border-radius:12px;
}

.subtitle{
    font-size:16px;
    font-style:italic;
    background:rgba(255,255,255,0.85);
    color:#000;
    padding:10px;
    border-radius:8px;
    margin:18px auto 10px;
    width:90%;
}

.role{
    font-size:14px;
    margin-top:6px;
    opacity:0.95;
}

.divider{
    width:70%;
    height:2px;
    background:rgba(255,255,255,0.4);
    margin:16px auto;
}

.icons{
    font-size:34px;
    margin:10px 0;
}

.icons span{
    margin:0 8px;
}

.description-box{
    position:absolute;
    left:30px;
    bottom:200px;
    width:220px;
    background:rgba(255,255,255,0.18);
    padding:16px;
    border-radius:14px;
    text-align:left;
}

.description-box h4{
    margin:0 0 8px;
    font-size:15px;
}

.description-box p{
    margin:0;
    font-size:13px;
    line-height:1.5;
}

.photo{
    position:absolute;
    right:35px;
    bottom:130px;
    width:120px;
    height:140px;
    object-fit:cover;
    border-radius:12px;
    border:3px solid white;
    box-shadow:0 6px 15px rgba(0,0,0,0.35);
}

.author{
    position:absolute;
    bottom:70px;
    left:30px;
    background:rgba(255,255,255,0.9);
    color:#000;
    padding:8px 14px;
    border-radius:6px;
    font-style:italic;
    font-size:14px;
}

.footer{
    position:absolute;
    bottom:25px;
    width:100%;
    text-align:center;
    font-size:12px;
    opacity:0.85;
}
```
## OUTPUT:
![alt text](<Screenshot 2026-02-15 161602.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
