# Ex.No:06 JavaScript Calculator
## Date:24-11-2026
## AIM

To design and develop a simple calculator using HTML, CSS, and JavaScript to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

## ALGORITHM

1. Create an HTML page to design the calculator interface.
2. Create a display field to show the numbers and calculation results.
3. Create buttons for digits from 0 to 9 and arithmetic operators.
4. Use CSS to arrange and style the calculator buttons and display.
5. Write JavaScript functions to handle button clicks.
6. Store the entered numbers and operators in the calculator display.
7. Use JavaScript to evaluate the arithmetic expression.
8. Display the calculated result on the calculator screen.
9. Provide a clear button to reset the calculator.
10. Test the calculator with different arithmetic operations.

## PROGRAM
```
<!DOCTYPE html>
<html>
    <head>
        <title>JavaScript Calculator</title>
        <style>
            body
            {
                background-color:#FFF0F5;
            }
            .calc
            {
                margin:85px auto auto auto;
                height:560px;
                width:400px;
                border:5px soliD #79569C;
                border-radius:15px;
                background-color:#E6D6F5;
            }
            h1
            {
                color:#59366F;
                text-align:center;
                font-size:35px;
                font-family:monospace;
            }
            .rows
            {
                display:flex;
                justify-content:center;
            }
            input
            {
                font-family:monospace;
                font-size:30px;
                border-radius:10px;
                background-color:#F3E8FA;
                color:#59366F;
                border:3px solid #79569C;
            }
            input[type='text']
            {
                margin:5px auto 25px auto;
                height:65px;
                width:320px;
                text-align:right;
                background-color:#FBF7FF;
            }
            input[type='button']
            {
                height:75px;
                width:75px;
                margin:5px;
            }
            input[type='button'][value='=']
            {
                background-color:#A8DDB5;
            }
            input[type='button'][value='C']
            {
                background-color:#F3A6B8;
            }
        </style>
    </head>
    <body>
        <div class="calc">
            <h1>Simple Calculator</h1>
            <div style="text-align: center;">
                <input type="text" id="cal">
            </div>
            <div class="rows">
                <input type="button" value="1" onclick="cal.value+='1'">
                <input type="button" value="2" onclick="cal.value+='2'">
                <input type="button" value="3" onclick="cal.value+='3'">
                <input type="button" value="+" onclick="cal.value+='+'">
            </div>
            <div class="rows">
                <input type="button" value="4" onclick="cal.value+='4'">
                <input type="button" value="5" onclick="cal.value+='5'">
                <input type="button" value="6" onclick="cal.value+='6'">
                <input type="button" value="-" onclick="cal.value+='-'">
            </div>
            <div class="rows">
                <input type="button" value="7" onclick="cal.value+='7'">
                <input type="button" value="8" onclick="cal.value+='8'">
                <input type="button" value="9" onclick="cal.value+='9'">
                <input type="button" value="*" onclick="cal.value+='*'">
            </div>
            <div class="rows">
                <input type="button" value="0" onclick="cal.value+='0'">
                <input type="button" value="=" onclick="cal.value=eval(cal.value)">
                <input type="button" value="C" onclick="cal.value=''">
                <input type="button" value="/" onclick="cal.value+='/'">
            </div>
        </div>
    </body>
</html>
```

## OUTPUT


## RESULT

Thus, a JavaScript-based calculator was successfully designed and developed to perform basic arithmetic operations using HTML, CSS, and JavaScript.

## RESULT

Thus, a JavaScript-based calculator was successfully designed and developed to perform basic arithmetic operations using HTML, CSS, and JavaScript.
