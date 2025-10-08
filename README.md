# Ex.06 Book Front Cover Page Design
## Date:08/10/2025

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
cover.html

<html>
<head>
    <title>Book Cover</title>
    <link rel="stylesheet" href="cover.css">
</head>
<body>
    <div class="cover">
        <div class="border">
                <div class="header">
                <p>SEC Insights</p><hr class="underline">
            </div>
            <div class="title">
                BECOMING THE <br>
                UNSEEN FIRE <br>
            </div>
            <div class="subtitle">
                Even the Quietest Spark can start a Storm <br>
                Top seller of 2026
            </div>
            <div class="bottom">
                <div class="left">
                    <div class="edition"><b>LIMITED EDITION</b></div>
                </div>
                <div class="right">
                    <img src="admin5.jpg" alt="Author Photo" class="img">
                </div>
            </div>
            <hr class="bottom-hr">
            <div class="names">
                <div class="author"><b>S.Visaniya<br>25017540</b></div>
                <div class="sec-name">SEC</div>
            </div>
        </div>
    </div>
</body>
</html>

cover.css

cover.css

body {
    margin: 0;
    padding: 0;
    font-family: Georgia, serif;
}

.cover {
    width: 618px;
    height: 889px;
    margin: 20px auto;
    background-image: url('cutebg.jpg');
    background-size: cover;
    background-position: center;
    box-sizing: border-box;
    padding: 8px;
}
.border {
    width: 100%;
    height: 100%;
    border: 5px solid rgb(131, 65, 120);
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
}
.header {
    display: flex;
    flex-direction: column;
    font-size: 18px;
    color: black;
    font-style: italic;
}

.underline {
    width: 130px;
    height: 1.5px;
    background-color: purple;
    border: none;
    margin-right: 90%;
    margin-top: 1.5px;
    margin-bottom: 20px;
}
.title {
    text-align: center;
    font-size: 50px;
    font-weight: bold;
    color: purple;
    margin-top: 40px;
}
.subtitle {
    font-size: 30px;
    color: black;
    margin-top: 30px;
}
.bottom {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    margin-top: auto;
}
.left{
    font-size: 25px;
    font-weight: bold;
    color: purple;
    margin-bottom: 15px;
}
.right {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.img {
    width: 120px;
    height: 140px;
    margin: 20px;
    border: 2px black;
    background-color: white;
}
.bottom-hr {
    width: 100%;
    height: 1.5px;
    background-color: white;
    border: none;
}
.names {
    display: flex;
    justify-content: space-between;
    margin-top: 5px;
}
.author {
    font-size: 25px;
    font-weight: bold;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    color: black;
    margin-top: 10px;
    margin-bottom: 20px;
}
.sec-name {
    font-size: 20px;
    color: rgb(7, 7, 7);
    margin-right: 60px;
}
```


## OUTPUT:
![alt text](<Screenshot (39).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
