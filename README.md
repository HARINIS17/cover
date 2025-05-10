# Ex.06 Book Front Cover Page Design
## Date:10-05-2025

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
<html>
<head>
<meta name="veiwport"
content="width=device-width,initial-sacale=1.0">
<style>
.bookpage{
width:400px;
height:600px;
color: white;
margin-left: auto;
margin-right: auto;
padding: 20px;
font-family: 'Franklin Gothic Medium','Arial Narrow',Arial,sans-serief;
background-image: url(bg1.jpeg);
background-size: cover;
}

.insight{
color:plum;
}

.hrstyle{
width: 100px;
}

.author{
display: inline;
position: relative;
color:violet;
top: 190px;
font-family: Georgia;
font-size: medium;
}


.booktitle h1 {
      font-family: 'Courier New', Courier, monospace;
      color: gold;
      font-size: 22px;
      text-align: center;
      line-height: 1.5;
      margin-top: 60px;
    }

.id{
width:400px;
position: relative;
top:180px;
}

.pub{
font-size:medium;
position: relative;
color:goldenrod;
top:155px;
left:330px;
}

.ed{
color:goldenrod;
font-size: medium;
font-family: Verdana;
position:relative;
top:85px;
}

.subtitle{
font-family:Tahoma;
font-size:large;
position: relative;
top: 40px;
}


.mypic{
position:relative;
top:135px;
left:260px;
width:100px;
height:100px;
background-size:cover;
}

</style>
<title>Book Cover Page</title>
</head>
<body>
<div class="bookpage">
<div class="insight">
  SEC INSIGHT
</div>
<div class="booktitle">
    <h1>Progressive Web Exploration:<br> A Practical Approach to<br> Modern Development</h1>
<div class="subtitle">
From Zero to Master
</div>
<div class="mypic">
<img src="WhatsApp Image 2025-05-10 at 16.50.51_e0cbeec2.jpg" width="130" height="135" alt="">
</div>

<div class="id">
<hr style="color:rgb(20, 15, 13);">
</div>
<div class="author">
<p><b>HARINI S</b></p>
</div>
<div class="pub">
    SEC
</div>
<div class="ed">
<b>First Edition</b>
</div>
</div>
</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot 2025-05-10 172228.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
