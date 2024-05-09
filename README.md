# Ex.07 Software Product Company Website
## Date:9/05/2024

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
//home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
    <style>
        *{
            margin:0;
            padding:0
        }
        #nav{
            background-color:rgb(125, 205, 151);
            color:#05512a;
            padding: 15px;
    
        }
        li,h1,ul{
            display:inline;
        }
        ul{
            margin-left:45%;
        }
        a{
            color:#007cb9;
            text-decoration: none;
        }
        a:hover{
            color:yellow;
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
            border-color: rgb(16, 18, 17);
            width: 400px;
            min-height: 300px;
            font-size: 20px;
            background-color:rgb(125, 205, 151);
        
        }
        .heading1{
            color:#05512a;
            text-align: center;
            padding-top: 20px;
        }
        .heading2{
            color:#05512a;
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
            color:#d4176c;
            text-align: center;
        }
    
        .bottomdiv{
 background-color:rgb(125, 205, 151);
            color:#007cb9;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 105px;

        }
        table{
            margin-left: 40px;
        }
    </style>
</head>
<body background="blue.png">
    <div class="header">
        <nav id="nav">
            <h1>
                ACCENTURE
            </h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="employee.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="Contact.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
        </nav>
    </div>
    <div class="searchbar">
    <input placeholder="search">
    </div>
        <div><pre class="heading2"><i><b>
" TOGETHER WE REIN>ENTED "         
Every day we embrace change and 
create value for all our stakeholders,
 in every part of the world.<b></i></pre></div>
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
                            <input type="submit" value="LOGIN" style="background-color: purple; color:white;">
                        </td>
                    </tr>
                </table>
                
            </form>
            </div>
        </div>
    <div class="bottomdiv">
        <p> Developed by SHAIK SAMREEN (212223110047)</p>
    </div>
</body>
<html>
```


//products.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>product</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:rgb(125, 205, 155);
            color:#05512a;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:#05512a;
        }
        li:hover{
            color:rgb(199, 215, 72);
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
            border-color:rgb(7, 58, 9);
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:rgb(125, 205, 155);
            cursor:pointer;
        }
        a{
            color:#05512a;
            text-decoration: none;
        }
        a:hover{
            color:rgb(199, 215, 72);
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:#05521a;
        }
      p{
            color:#05521a;
            text-align: center;
        }
   b{
            width: 300px;
            height: 200px;
        }
    h1{
            color:#05521a;
            text-align: center;
        }
        .bottomdiv{
 background-color:rgb(125, 205, 155);
            color:#05521a;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 230px;

        }
    </style>
</head>
<body background="blue.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">ACCENTURE</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="employee.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">PRODUCTS</h1>
        <br>
        <div class="product">
            <div class="box">
               <b><img src="1.png" ></b>
                <h1>CASE STUDY</h1>
                <p>Creating five-star associate experiences: Marriott International
                    Accenture and Marriot International created a new global HR hub that delivers employee experiences.</p>
            </div>
            <div class="box">
                <img src="2.png">
                <h1>RESEARCH REPORT</h1>
                <p>Reinvention in the age of generative AI
                    Five imperatives the C-suite must address to reinvent in the age of generative AI.</p>
            </div>
            <div class="box">
                <img src="3.png">
                <h1>CASE STUDY</h1>
                <p>Generative AI in the driver's seat: BMW
                    Accenture and BMW teamed up to create a new platform that uses generative AI to drive decisions.</p>
            </div>
        </div>
    </div>
    <div class="bottomdiv">
        <b> Developed by SHAIK SAMREEN (212223110047) </b>
    </div>
</body>
</html>
```

//employee.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>employees</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:rgb(125, 205, 155);
            color:#00521a;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:#00521a;
        }
        li:hover{
            color:#00521a;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
        a{
            color:#00521a;
text-decoration: none;
        }
        a:hover{
            color:#00521a;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:#00521a;
        }
        .bottomdiv{
            background-color:rgb(125, 205, 155);
            color:#00521a;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 0.7px;

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
            color:#e3f3ea;
            text-align: center;
        }
      
</style>
</head>
<body background="blue.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">ACCENTURE</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="employee.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">EMPLOYEES</h1>
        <table class="person">
            <tr>
                <td>
                    <img src="ceo.png" class="MyPic">
                </td>
		

                <td>
                    <img src="cofounder.png" class="cofoundar">
                </td>
		
                <td>
                   <img src="cofounder2.png" class="cofoundar">
                </td>
                <td>
                    <img src="director.png" class="PV Sindhu">
                </td>
                <td>
                    <img src="adirector.png" class="Sania Nehwal">
                </td>
            </tr>
            <tr>
                <td>
                    <b>Virat Kohli</b>
                    <p>CEO</p>
                </td>
                <td>
                    <b>MS Dhoni</b>
                    <p>Co-Founder</p>
                </td>
                <td>
                    <b>Dinesh Karthik</b>
                    <p>CTO,Co-Founder</p>
                </td>
                <td>
                    <b>Shreyas Iyer</b>
                    <p>Director</p>
                </td>
                <td>
                    <b>Rohit Sharma</b>
                    <p>Asst.Director</p>
                </td>
              
            </tr>
        </table>
    </div>
    <div class="bottomdiv">
<p> Developed by SHAIK SAMREEN (212223110047)</p>
    </div>
</body>
</html>
```

//contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contact</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:rgb(125, 205, 155);
            color:#05521a;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:#05521a;
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
            border-color:rgb(246, 238, 238);
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:rgb(125, 205, 155);
            cursor:pointer;
        }
        a{
            color:b#05512a;
            text-decoration: none;
        }
        a:hover{
color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:#05512a;
        }
        .table1{
            color:black;
            font-size: large;
        }
        .contactus{
            margin-left:400px;
        }
        .heading3{
            padding-top: 30px;
            padding-bottom: 10px;
            text-align: center;
            color:#05512a;
        }
        .table2{
            color:#05512a;
            font-size: large;
            background-color:rgb(125, 205, 155);
            border-radius: 5px;
            border-style:dotted;
            border-color: rgb(125, 205, 155);

        }
        .queries{
            margin-left:600px;
        }
        .bottomdiv{
            background-color:rgb(125, 205, 155);
            color:#05512a;
            text-align: center;
            position:relative;
display:block;
            margin-top: 24px;

        }
    </style>
</head>
<body background="blue.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">ACCENTURE</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="products.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="employee.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contact.html" target="_blank">Contact Us</a>
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
                        K.K.Nagar, Anna main road, chennai-600078
</td>
                </tr>
                <tr>
                    <td>
                        LANDMARK :
                    </td>
                    <td>
                        chennai
                    </td>
                </tr>
                <tr>
                    <td>
                        Email :
                    </td>
                    <td>
                        accentureweb@gamil.com
                    </td>
                </tr>
                <tr>
                    <td>
                        PHONE :
                    </td>
                    <td>
                        8428454444
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
                            <input type="submit" style="background-color: white; color:#007cb9;">
                        </td>
                    </tr>
            </table>
        </div>
        <div class="bottomdiv">
            <p> Developed by SHAIK SAMREEN (212223110047) </p>
        </div>
    </div>
</body>
</html>
```


## OUTPUT:
![Screenshot 2024-05-09 110801](https://github.com/ManojKumarShankar/softweb/assets/122000959/d14fe24f-f727-4383-b6a4-95eadc9bb4fa)
![Screenshot 2024-05-09 110833](https://github.com/ManojKumarShankar/softweb/assets/122000959/42afd3e6-2109-4708-8701-faf61686afc6)
![Screenshot 2024-05-09 110848](https://github.com/ManojKumarShankar/softweb/assets/122000959/ac0bf656-a7f2-4b0e-98b8-c8730209c936)
![Screenshot 2024-05-09 110904](https://github.com/ManojKumarShankar/softweb/assets/122000959/f0903a93-7b5f-4009-904c-9ed27cea0040)






## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
