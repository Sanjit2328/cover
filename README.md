# Ex.06 Book Front Cover Page Design
## Date:

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
<html>

<head>
    <title>BOOK COVER</title>
    <style>
        .bookcover {
            width: 400px;
            height: 600px;
            color: black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: Arial, sans-serif; /* corrected font-family declaration */
            background-image: url(robot.jpg);
            background-size: cover;
        }

        .head {
            color: rgb(18, 210, 221);

        }

        .style {
            width: 100px;
        }

        .authorname {
            display: inline;
            position: relative;
            color: rgb(17, 2, 46);
            top: 190px;
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
            font-size: x-large;
        }

        .title {
            color: rgb(0, 0, 0);
            font-family: Arial, sans-serif; /* fallback font */
            font-size: x-large;
            text-align: center;
            position: relative;
            top: 2px;

        }

        .line {
            width: 330px;
            color: black;
            position: relative;
            top: 180px;
        }

        .end {
            color: rgba(7, 7, 7, 0.94);
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 85px;

        }

        .subtitle {
            color: rgb(0, 0, 0);
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; /* fallback font */
            font-size: large;
            position: relative;
            top: 50px;
        }

        .photo {
            position: relative;
            top: 300px;
            left: 300px;
            width: 90px; /* Adjust the size here */
            height: 100px; /* Adjust the size here */
        }
    </style>
</head>

<body>
    <div class="bookcover">
        <div class="head">
            WEB DESIGNING
        </div>
        <div class="style">
            <hr style="color:rgb(209, 96, 237)">
        </div>
        <div class="title">
            <h1>ROBOTICS</h1>
        </div>
        <div class="subtitle">
           IMPACT OF ROBOTICS IN FUTURE
        </div>
        <div class="subtitle">
            Best seller of 2024
        </div>

        <div class="photo">
            <img src="ID PIC.jpg" width="90" height="90" style="border-radius: 50%;">
        </div>
        <div class="line">
            <hr style="color:rgba(81, 13, 13, 0.555)">
        </div>
        <div class="authorname">
            <p><b>SANJIT P</b></p>
        </div>
        
        <div class="end">
            <b>NEW EDITION</b>
        </div>
    </div>
</body>

</html>

```

## OUTPUT:
NAME:SANJIT P

REGISTER NO:212223230190
![Screenshot 2024-04-27 082553](https://github.com/Sanjit2328/cover/assets/139331694/5c7b7320-c9c9-4403-b350-acac22b9a606)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
