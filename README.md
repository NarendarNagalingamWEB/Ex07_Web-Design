# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE

```
<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="red">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>

```


## OUTPUT
![2023-05-27 (20)](https://github.com/NarendarNagalingamWEB/Ex07_Web-Design/assets/128288529/b0234c84-a421-4e38-b76f-3f29e99bf9c5)
![2023-05-27 (19)](https://github.com/NarendarNagalingamWEB/Ex07_Web-Design/assets/128288529/5d1cc592-9330-4f2f-a128-ebc78626534e)


## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
