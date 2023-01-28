# Ex-06-Book-Cover-Design
## AIM
### To design a book cover page using HTML and CSS
## Design Procedure
### Step 1: Clone the GitHub repository and create a Django admin interface.
### Step 2: Write HTML and CSS Code for desiging book cover page and excute them.
## Program
```
{% load static %}
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>
         @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Dancing+Script:wght@600&family=Nunito:wght@500;1000&family=Unbounded&display=swap');
         .bookpage{
            width: 400px;
            height: 600px;
            color: #FCFFE7;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-color: #301E67;
            background-size: cover;
        }
        .insight{
            font-family: 'Nunito', sans-serif;;
            color: #7286D3;
        }
        .hrstyle{
            color: #EB455F;
            width: 150px;
        }
        .author{
            font-family: 'Dancing Script', cursive;
            display: inline;
            position: absolute;
            color: #5B8FB9;
            top:185px;
            font-family:Georgia;
            font-size: medium;
            margin-top: 400px;
        }
        .booktitle{
            font-family: 'Unbounded', cursive;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        }
        .pub{
            font-family: 'Bebas Neue', cursive;
            font-size: 150%;
            position: absolute;
            top:145px;
            margin-top: 600px;
        }
        .ed{
            color: #E5E0FF;
            font-size: medium;
            font-family: 'Bebas Neue', cursive;
            position: absolute;
            top:75px;
            margin-top: 490px;
        }
        .subtitle{
            font-family: 'Bebas Neue', cursive;
            font-size: large;
            position: relative;
            top:30px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 310px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        .vect{
            margin: auto;
        }
        .webvector{
            margin-left: 210px;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                MyDOC Insight
            </div>
            <div class="hrstyle">
                <hr>
            </div>
            <div class="booktitle">
                <h1>Fundamentals of Web Application Development</h1></div>
            <div class="subtitle">
                >> HTML and CSS Combined with Django Architecture
            </div>
            <div class="mypic">
                <img src="{% static 'my.png' %}" width="110" height="125" alt="">
            </div>
            <div class="author">
               <p><b>Ronick Aakshath</b></p>
            </div>
            <div class="vect">
                <img src="{% static 'html.png' %}" width="80" height="80">
                <img src="{% static 'css.png' %}" width="80" height="80">
                <img src="{% static 'js.png' %}" width="80" height="80">
                <img src="{% static 'django.png' %}" width="80" height="80">
            </div>
            <div class="webvector">
                <img src="{% static 'web-development-image-01.png' %}" width="150" height="150">
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>
        </div>
    </body>
</html>
```
## Output
![](bcd_output.png)
## Result
### Thus we designed a book cover page using HTML and CSS is executed and the output is verified
