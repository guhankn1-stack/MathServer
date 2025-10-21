# Ex.05 Design a Website for Server Side Processing
## Date:20.10.2025

## AIM:
 To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side. 


## FORMULA:
BMI = W/(H)<sup>2</sup>
<br> BMI =BODY MASS INDEX
<br> H =HEIGHT
<br> W =WEIGHT

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
    <head>
        <title>BMI Calculator</title>
        <style type="text/css">
            body{
                border: solid rgb(238, 241, 243) 10px;
                background-color: rgb(9, 16, 148);
            }
            .value{
                text-align: center;
                padding: 30px;
                width: 300px;
                height: 30px;
                font-size: 20px;
                background-color: rgb(222, 81, 189);
                margin:auto;

            }
            h1,h2,h3{
                text-align: center;
                font-size: 20px;
                padding: 20px;
            
            }
            button{
                padding: 10px;
                width: 250px;
                border-radius: 25px;
                border:solid rgb(250, 152, 152) 5px;
                background-color: rgb(132, 74, 148);
                font-size: 15px;
            } 
            h3{
                padding: 20px 50px;
                text-align: center;
                border: 10px solid rgb(121, 177, 9);
                background-color: rgb(181, 182, 206);
                width: 380px;
                margin: 20px auto;

            }
            input{
                padding: 10px;
            }
        </style>
    </head>
    <body>
    <h1>Guhan.K (25014479)</h1>
    <h2>Body Mass Index (BMI) Calculator</h2>
    <form method="post">
        {% csrf_token %}
        <div class="value">
        <label>Height (cm):</label>
        <input type="text" name="height" required>
        </div>
        <div class="value">
        <label>Weight (kg):</label>
        <input type="text" name="weight" required>
        </div>
        <div class="value">
        <button type="submit" >Calculate BMI</button>
        </div>
    <h3>Your BMI: {{bmi}}</h3>
    </form>
    </body>
</html>
```

## SERVER SIDE PROCESSING:
<img width="1919" height="1079" alt="serverside" src="https://github.com/user-attachments/assets/632d5179-103f-481a-b471-7afc5b550d17" />



## HOMEPAGE:
<img width="1920" height="1080" alt="output" src="https://github.com/user-attachments/assets/a9cf9620-6590-4505-ab6b-c5457f0c2f4b" />


## RESULT:
The program for performing server side processing is completed successfully.
