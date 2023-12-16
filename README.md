# Ex.07 Software Product Company Website
## Date:16.12.2023

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home1.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Home</title>
    <style>
        *{
            margin:0;
            padding:0
        }
        #nav{
            background-color:yellow;
            color:black;
            padding: 15px;
    
        }
        li,h1,ul{
            display:inline;
        }
        ul{
            margin-left:45%;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:plum;
            cursor:pointer;
 }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
      
        .box {
            display:inline-block;
            border-style:dotted ;
            border-radius: 10px;
            border-color: pink;
            width: 400px;
            min-height: 300px;
            font-size: 20px;
            background-color:pink;
        
        }
        .heading1{
            color:black;
            text-align: center;
            padding-top: 20px;
        }
        .heading2{
            color:black;
            text-align: justify;
            font-size: 30px;
            margin-left: 30px;
        }
        .edge{
            padding-left: 900px;
        }
        .box{
            text-align: center;
        }
 p{
            color:black;
            text-align: center;
        }
    
        .bottomdiv{
 background-color:yellow;
            color:black;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 75px;

        }
        table{
            margin-left: 40px;
        }
        body{
            background-repeat: no-repeat;
            background-size: cover;
        }
    </style>
</head>
<body background="bg.jpg">
    <div class="header">
        <nav id="nav">
            <h1>
                HI-TECH SOFTWARE SOLUTIONS
            </h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
        </nav>
    </div>
    <div class="searchbar">
    <input placeholder="search">
    </div>
        <div><pre class="heading2"><i><b>
"Hi-Tech has been providing specialized 
 products and engineering services to
 India's power and process industries "<b></i></pre></div>
        <div class="edge">
            <div class="box">
            <h1 class="heading1">LOGIN HERE</h1>
            <br>
            <br>
            <form>
                <table cellpadding="15px" cellspacing="15px">
                    <tr>
                        <td>
                           <p> Username:</p>
                        </td>
                        <td>
                            <input type="email" name="name" placeholder="Enter a Email">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <p> Password:</p>
                        </td>
                        <td>
                            <input type="password" name="pwd" placeholder="Enter a Password">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" value="LOGIN" style="background-color: yellow; color:black;">
                        </td>
                    </tr>
                </table>
                
            </form>
            </div>
        </div>
    <div class="bottomdiv">
        <p>Designed and Developed by Swathi (23013673)</p>
    </div>
</body>
<html>

products.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Products</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:yellow;
            color:black;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:black;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
 input{
            width: 18%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:purple;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:yellow;
            cursor:pointer;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:plum;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:black;
        }
      p{
            color:black;
            text-align: center;
        }
   b{
            width: 300px;
            height: 200px;
        }
    h1{
            color:black;
            text-align: center;
        }
        .bottomdiv{
 background-color:yellow;
            color:black;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 179px;

        }
        body{
            background-repeat: no-repeat;
            background-size: cover;
        }
    </style>
</head>
<body background="bg.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">HI-TECH SOFTWARE SOLUTIONS</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">PRODUCTS</h1>
        <br>
        <div class="product">
            <div class="box">
               <b><img src="webapp.jpg" ></b>
                <h1>WEB APP</h1>
<p>FileX is a web application where users can upload the files and can send mail intimation to the target user. An automated random user name and password is generated and sent along with the mail.</p>
            </div>
            <div class="box">
                <img src="autocad.png">
                <h1>AutoCAD</h1>
                <p>Convert To Polyline command is used to convert the closed loop into a single polyline entity. Supported closed loop entities are line, arc, spline, poly line, elliptical arc.This command will be useful while cutting the Metal plates using AutoCAD drawing.</p>
            </div>
            <div class="box">
                <img src="revit.png">
                <h1>REVIT</h1>
                <p>The purpose of this tool is to directly load families from one Autodesk® Revit® project to another tool enables the users to easily look in to the views, types, parameters of the families in a Revit project file and directly load the selected families in to the current Revit project. </p>
            </div>
        </div>
    </div>
    <div class="bottomdiv">
        <b>Designed and Developed by Swathi (23013673)</b>
    </div>
</body>
</html>

person.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Employees</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:yellow;
            color:black;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:black;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
        a{
            color:black;
text-decoration: none;
        }
        a:hover{
            color:plum;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:black;
        }
        .bottomdiv{
            background-color:yellow;
            color:purple;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 156px;

        }
        img{
            border-radius: 50%;
            width: 200px;
            display: inline;
            padding:3px;
            
        }
        .person{
            margin:100px;
            text-align: center;
        }
        b,p{
            color:black;
            text-align: center;
        }
        body{
            background-repeat: no-repeat;
            background-size: cover;
        }
      
</style>
</head>
<body background="bg.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">HI-TECH SOFTWARE SOLUTIONS</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">EMPLOYEES</h1>
        <table class="person">
            <tr>
                <td>
                    <img src="mypic.jpg" class="MyPic">
                </td>
                <td>
                    <img src="thalapathy.jpg" class="Vijay">
                </td>
                <td>
                   <img src="ashwin.jpg" class="Ashwin">
                </td>
                <td>
                    <img src="sivangii.jpg" class="Sivaangi">
                </td>
                <td>
                    <img src="balaji.jpeg" class="Balaji">
                </td>
                <td>
                    <img src="keerthy.jpg"class="keerthy"
                </td>
            </tr>
            <tr>
                <td>
                    <b>Swathi</b>
                    <p>CEO</p>
                </td>
                <td>
                    <b>Jospesh Vijay</b>
                    <p>CEO,Co-Founder</p>
                </td>
                <td>
                    <b>Ashwin kumar</b>
                    <p>CTO,Co-Founder</p>
                </td>
                <td>
                    <b>Sivaangi Krishankumar</b>
                    <p>CEODirector</p>
                </td>
                <td>
                    <b>Balaji Murugadoss</b>
                    <p>Asst.Director</p>
                </td>
                <td>
                    <b>Keerthy Suresh</b>
                    <p>Dy.Director</p>
                </td>
              
            </tr>
        </table>
    </div>
    <div class="bottomdiv">
<p>Designed and Developed by Swathi (23013673)</p>
    </div>
</body>
</html>

contactus.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Contactus</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:yellow;
            color:black;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:black;
  }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:black;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:yellow;
            cursor:pointer;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
color:black;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color: black;
        }
        .table1{
            color:blue;
            font-size: large;
        }
        .contactus{
            margin-left:400px;
        }
        .heading3{
            padding-top: 30px;
            padding-bottom: 10px;
            text-align: center;
            color: purple;
        }
        .table2{
            color:black;
            font-size: large;
            background-color:yellow;
            border-radius: 5px;
            border-style:dotted;
            border-color: black;

        }
        .queries{
            margin-left:570px;
        }
        .bottomdiv{
            background-color:yellow;
            color:black;
            text-align: center;
            position:relative;
display:block;
            margin-top: 27px;

        }
        body{
            background-repeat: no-repeat;
            background-size: cover;
        }
    </style>
</head>
<body background="bg.jpg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">HI-TECH SOFTWARE SOLUTIONS</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">CONTACT US</h1>
        <div class="contactus">
            <table cellpadding="15px" cellspacing="15px" class="table1">
                <tr>
                    <td>
                        ADDRESS :
                    </td>
                    <td>
                        No. 4, Bharathi Nagar, 4th Street,Off North Usman Road,T. Nagar, Chennai - 600 017.

</td>
                </tr>
                <tr>
                    <td>
                        LANDMARK :
                    </td>
                    <td>
                        near t nagar chennai.
                    </td>
                </tr>
                <tr>
                    <td>
                        Email :
                    </td>
                    <td>
                        Hitechsoftsolutions@gmail.com
                    </td>
                </tr>
                <tr>
                    <td>
                        PHONE :
                    </td>
                    <td>
                        6369795268
                    </td>
                </tr>
            </table>
        </div>
        <div>
            <h3 class="heading3">QUERIES</h3>
            <div class="queries">
                <table cellpadding="15px" cellspacing="15px" class="table2">
                    <tr>
                        <td>
 NAME :
                        </td>
                        <td>
                            <input type="name" placeholder="Enter your name"> 
                        </td>
                    </tr>
                    <tr>
                        <td>
                            EMAIL :
                        </td>
                        <td>
                            <input type="email" placeholder="Enter your E-mail">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            MESSAGE :
                        </td>
                        <td>
                            <input type="text" placeholder="Enter your text">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" style="background-color: white; color: purple;">
                        </td>
                    </tr>
            </table>
        </div>
        <div class="bottomdiv">
            <p>Designed and Developed by Swathi (23013673)</p>
        </div>
    </div>
</body>
</html>
```

## OUTPUT:
![Alt text](<Screenshot (48).png>)
![Alt text](<Screenshot (49).png>)
![Alt text](<Screenshot (50).png>)
![Alt text](<Screenshot (51).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
