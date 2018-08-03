# Section 04 - HTML Level two

[Back to Readme.md](README.md)

## Content

- [Introduction](#introduction)
- [Part One - Tables](#part-one-tables)
- [Part Two - Tables Quiz](#part-two-tables-quiz)
- [Part Four - Form Basics](#part-four-form-basics)
- [Part Five - Forms and Labels](#part-five-forms-and-labels)
- [Part Six - Forms and Selections](#part-six-forms-and-selections)
- [Assessment](#assessment)

## Introduction

[Video: HTML Level two Introduction](https://www.udemy.com/python-and-django-full-stack-web-developer-bootcamp/learn/v4/t/lecture/6550302?start=0)

## Part One - Tables

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Part One - Tables</title>
</head>

<body>

    <table border="1">
        <thead>
            <th>#</th>
            <th>Color</th>
            <th>Country</th>
        </thead>
        <tr>
            <td>1</td>
            <td>Red</td>
            <td>Russia</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Blue</td>
            <td>USA</td>
        </tr>
    </table>
</body>

</html>
```

[Video: HTML Level two - Part One](https://www.udemy.com/python-and-django-full-stack-web-developer-bootcamp/learn/v4/t/lecture/6550140?start=0)

## Part Two - Tables Quiz

```console
Pop Quiz!


Use the following information to make a
table about Country GDP.

Source for data below:
https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)

Make a table with HTML consisting of 3 columns:
Country Name
Country Flag
GDP (millions of USD)

Your table will have 3 rows.
Use the information below to attribute the cells correctly:

United States
US Flag: "https://upload.wikimedia.org/wikipedia/en/thumb/a/a4/Flag_of_the_United_States.svg/190px-Flag_of_the_United_States.svg.png"
GDP: 18,561,930

India
Indian Flag: "https://upload.wikimedia.org/wikipedia/en/thumb/4/41/Flag_of_India.svg/150px-Flag_of_India.svg.png"
GDP: 2,250,990

United Kingdom
UK Flag: "https://upload.wikimedia.org/wikipedia/en/thumb/a/ae/Flag_of_the_United_Kingdom.svg/200px-Flag_of_the_United_Kingdom.svg.png"
GDP: 2,649,890
```

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Part Two - Tables Quiz</title>
</head>

<body>

    <table border="1">
        <thead>
            <th>Country Name</th>
            <th>Country Flag</th>
            <th>GDP (millons of USD)</th>
        </thead>
        <tr>
            <td>United States</td>
            <td>
                <img src="https://upload.wikimedia.org/wikipedia/en/thumb/a/a4/Flag_of_the_United_States.svg/190px-Flag_of_the_United_States.svg.png"
                    alt="US Flag">
            </td>
            <td>18,561,930</td>
        </tr>
        <tr>
            <td>India</td>
            <td>
                <img src="https://upload.wikimedia.org/wikipedia/en/thumb/4/41/Flag_of_India.svg/150px-Flag_of_India.svg.png" alt="India Flag">
            </td>
            <td>2,250,990</td>
        </tr>
        <tr>
            <td>United Kingdom</td>
            <td>
                <img src="https://upload.wikimedia.org/wikipedia/en/thumb/a/ae/Flag_of_the_United_Kingdom.svg/200px-Flag_of_the_United_Kingdom.svg.png"
                    alt="UK Flag">
            </td>
            <td>2,649,890</td>
        </tr>

    </table>
</body>
</html>
```

[Video: HTML Level two - Part Two Quiz](https://www.udemy.com/python-and-django-full-stack-web-developer-bootcamp/learn/v4/t/lecture/6550190?start=0)  
[Video: HTML Level two - Part Two Quiz Solution](https://www.udemy.com/python-and-django-full-stack-web-developer-bootcamp/learn/v4/t/lecture/6550240?start=0)

## Part Four - Form Basics

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Part Four - Form basics</title>
</head>

<body>

    <form>
        <h1>Log In</h1>
        <h2>Please Input your Email and Password</h2>
        <input type="email" name="useremail" id="" value="" placeholder="Email">
        <input type="password" name="password" placeholder="Password">
        <input type="submit" name="" value="Submit">
    </form>

    <form>
        <h1>Choose Color!</h1>
        <h2>Click on Button!</h2>
        <input type="color" name="" id="">

        <h2>Enter some text</h2>
        <input type="text" name="" id="" value="Text goes here">

    </form>

</body>

</html>
```

[W3school: Form information](https://www.w3schools.com/html/html_forms.asp)

[Video: Part Four](https://www.udemy.com/python-and-django-full-stack-web-developer-bootcamp/learn/v4/t/lecture/6550202?start=0)

## Part Five - Forms and Labels

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Part Five - Forms Actions and Labels</title>
</head>

<body>
    <form action="https://wwww.facebook.com" method="GET">
        <label for="email">Enter Email:</label>
        <input type="email" name="useremail" id="email" placeholder="Email" required/>

        <label for="input">Enter Input:</label>
        <input type="text" name="userinput" id="input" placeholder="Input" />
        <input type="submit" value="Submit" />

    </form>

</body>

</html>
```

[Video: Part Five](https://www.udemy.com/python-and-django-full-stack-web-developer-bootcamp/learn/v4/t/lecture/6550280?start=0)

## Part Six - Forms and Selections

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Part Six - Form and selections</title>
</head>

<body>
    <h1>Hotel Feedback Form</h1>
    <form method="GET">
        <h2>Are you from inside the US? or Outside the US?</h2>
        <label for="inusa">Inside:</label>
        <input type="radio" name="loc" id="inusa" value="inside">

        <label for="outusa">Outside:</label>
        <input type="radio" name="loc" id="outusa" value="outside">

        <h2>How was your service?</h2>
        <select name="stars" id="">
            <option value="Great">3</option>
            <option value="Okay">2</option>
            <option value="Bad">1</option>
        </select>

        <p>Any other feedback?</p>
        <textarea name="feedback" id="" cols="30" rows="10"></textarea>
        <br>
        <input type="submit" value="SUBMIT">


    </form>

</body>

</html>
```

[Video: Part Six](https://www.udemy.com/python-and-django-full-stack-web-developer-bootcamp/learn/v4/t/lecture/6550212?start=0)

## Assessment

[Video: Assessment](https://www.udemy.com/python-and-django-full-stack-web-developer-bootcamp/learn/v4/t/lecture/6550136?start=0)

[Video: Assessment Solution](https://www.udemy.com/python-and-django-full-stack-web-developer-bootcamp/learn/v4/t/lecture/6550134?start=0)
