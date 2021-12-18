
WAP = Write A Program
-----------------------

WAP that calculates the Simple Interest and Compound Interest. The Principal, Amount, Rate of Interest and Time are entered through the keyboard.
-------------------------------------------------------


```
let pr = 1000, rt = 6.7, tm = 4;
let SI = (pr * tm * rt)/ 100;
let A = pr *(Math.pow((1 + rt / 100), tm));
let CI = A - pr;
alert ( "Simple interest is " +SI);
console.log("Compound interest is " + CI);
```

_________________________________________
WAP that accepts the marks of 5 subjects and finds the sum and percentage marks obtained by the student.
-------------------------------------------------------------------------------------


```
let sb1 = 67, sb2 = 51, sb3 = 49, sb4 = 80, sb5 = 32;
let total = (sb1 + sb2 + sb3 + sb4 + sb5);
let percentage = ((sb1 + sb2 + sb3 + sb4 + sb5)/500) * 100;
alert ( "Total marks obtained is " + total);
console.log("He obtained " + percentage " % of marks.");
```

 ----------------------------------------------------------------------------------------------
WAP to calculate the area and circumference of a circle.
-----------------------------------------------------------------------------------------------


```
const pi = 3.14 ;
let rad = 6;
let crm = 2 * pi * rad;
let area = pi * rad * rad;  // let area = pi* rad**2;
alert ( "Circumference of the circle is " + crm);
console.log("Area of the circle is  " + area );
```

------------------------------------------------------------------------------
WAP that swaps values of two variables using a third variable.
------------------------------------------------------------------------------


```
var x = 2, y= 5 ;
var z = x ;
var x = y ;
var y = z ;
alert ( "Value of X is " + x);
console.log("Value of y is " + y );
```
--------------------------------------------------------------------------------
WAP that checks whether the two numbers entered by the user are equal or not.
----------------------------------------------------------------------------------------


```
let x= 11, y = 11;
if (x == y){
    alert ('x and y, both are same.'); // We can use both Single (' ') and Double Quotes (" "); but, it is better to follow any one of them throughout the program.
}
else {
    console.log (x+ " and " +y " both are not the same.")
}
```
 --------------------------------------------------------------------------------------
WAP to find the greatest of three numbers.
--------------------------------------------------------------------------------


```
var a= 24, b= 38, c= 16;
if (a > b){
    if (a>c){
        alert(a + " is greatest");
    }
    else {
        alert(c+ " is greatest");
    }
}
else{
    if (b>c){
        alert(b + " is greatest");
    }
    else {
        alert(c+ " is greatest");
    }
}
```
----------------------------------------------------------------------------------
WAP that tells whether a given year is a leap year or not.
-------------------------------------------------------------------------------------


```
var year: number = 2006;
if ((year%4==0||year%400==0) && year%100!=0){
    alert( year + " is a leap year.");
	}
else {
		alert( year +" is not a leap year.");
	}

```
