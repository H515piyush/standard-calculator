# Design of a Standard Calculator

## AIM:

To design a web application for a standard calculator.

## DESIGN STEPS:

### Step 1:
clone the github respository and create a new django project

### Step 2:

make change in setting.py
### Step 3:

create a new html file and use a css for colours
### Step 4:

write javascripts for implementing operation
### Step 5:
validate the html and css code

### Step 6:

Publish the website in the given URL.

## PROGRAM :
<!DOCTYPE html>
<html>
    <head>
        <title>AR Calculator</title>
        <style type="text/css">
        table{
            border: 1px solid black;
            margin-left: auto;
            margin-right: auto;
        }
        input[type="text"]{
            border: 1px solid black;
            padding: 20px 45px;
            font-size: 24px;
            font-weight: bold;
            border-radius: 2px;
        }


        input[type="button"]{
            width: 100%;
            padding: 20px 40px;
            background-color:rgb(238, 130, 184);
            border-radius: 2px;
        }
        </style>
    </head>
    <body>
        <form name="form1" onload="result.value=''">
            <h1 style="text-align: center;color:blue;">Simple Calculator</h1>
        <table id="calc">
            <tr>
                <td colspan="4">
                    <input type="text" id="result">
                </td>
            </tr>
            <tr>
                <td><input type="button" value="+" onclick="result.value+='+'"/></td>
                <td><input type="button" value="1" onclick="result.value+='1'"/></td>
                <td><input type="button" value="2" onclick="result.value+='2'"/></td>
                <td><input type="button" value="3" onclick="result.value+='3'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="-" onclick="result.value+='-'"/></td>
                <td><input type="button" value="4" onclick="result.value+='4'"/></td>
                <td><input type="button" value="5" onclick="result.value+='5'"/></td>
                <td><input type="button" value="6" onclick="result.value+='6'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="*" onclick="result.value+='*'"/></td>
                <td><input type="button" value="7" onclick="result.value+='7'"/></td>
                <td><input type="button" value="8" onclick="result.value+='8'"/></td>
                <td><input type="button" value="9" onclick="result.value+='9'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="/" onclick="result.value+='/'"/></td>
                <td><input type="button" value="." onclick="result.value+='.'"/></td>
                <td><input type="button" value="0" onclick="result.value+='0'"/></td>
                <td><input type="button" value="=" onclick="result.value=eval(result.value)"/></td>
            </tr>
            <tr>
                <td colspan="4">
                    <input type="button" value="Clear All" id="clear" onclick="result.value=''">
                </td>
            </tr>
        </table>
        </form>
    </body>
</html>
## OUTPUT:
![Screenshot 2023-12-30 110511](https://github.com/H515piyush/standard-calculator/assets/147472999/a2b36f39-c420-44d9-a564-77f3f2240d48)

## Result:
THE WEB CALCULATOR IS READY TO USE

