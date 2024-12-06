# Ex.06 Book Front Cover Page Design
# Date:29-11-2024
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```<!DOCTYPE html>
<html>
<head>
    <title>book cover</title>
    <style>
        .bookpage{
            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url(book.jpg);
            background-size: cover;
        }
        .insight{
            color:darkturquoise;
        }
        .hrstyle{
            width:100px;
        }
        .author{
            display: inline;
            position: relative;
            color:darkturquoise;;
            top:190px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:darkturquoise;;
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 10px;
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
        }
        .pub{
            color:darkturquoise;
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:darkturquoise;
                        font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        }
        .subtitle{
            color:darkturquoise;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:200px;
        }
        .mypic{
            position: relative;
            top: 105px;
            left: 280px;
            width: 80px;
            height: 80px;
            background-size:contain;
            shape-rendering: crispEdges;
        }
        </style>
        <title>Book Cover Page</title>
</head>
        <body>
        <div class="bookpage" >
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color:red">
            </div>
            <div class="booktitle">
                <h1>Responsive Web     <br>
                    Design with        <br>
                    HTML and CSS  </h1> </div>
            <div class="subtitle">
                    Develop futuer-proof responsive  <br>
                    websites using the latest <br>
                    HTML and CSS techniques
            </div>        
            <div class="mypic">
                <img src="myphoto.jpg" width="120" height="145" >
            </div>
            <div class="id">
                <hr style="color:red">
            </div>
            <div class="author">
               <p><b>cherry</b></p>
            </div>
            <div class="ed">
                <b>Third Edition</b>
            </div>
        </div>
        </body>
</html>
```
# OUTPUT:
![Screenshot (62)](https://github.com/user-attachments/assets/56f2b0d1-d131-451f-8e77-8da47c59b8bd)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
