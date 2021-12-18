## Basic Arithmetic Function Using FUNCTION :-


```
let x: number = 10 , y:number=20 ;
let sum:number = x + y;
var mul = x * y;
alert ('The Sum is ' +sum);
alert ('The Mul is ' +mul);


```


```
function  mulNums(a:number, b:number){
    return a * b ;
    
}
var mul:number = mulNums(10,9)
console.log( 'multiplication is ' + mul ); 

```


-------------------------------------------------------------------------
Variable and its Scoping (Local, Global)
-------------------------------------------------------------------------

```
let num1:number = 1; 
    num1++;
    console.log(num1);
function letDeclaration() { 
    let num2:number = 14;
    console.log(num2);
    num2++
    console.log(num2);


    if (num2 > num1) { 
        let num3: number = 3;
        num3++;
        console.log(num3);
        console.log(num1); 
    } 
    
    while(num1 < num2) { 
        let num4: number = 4;
        num1++;
        console.log(num4 = num4 * 2);
        console.log(num4);
        num4++;
        console.log(num4);
    }

    console.log(num1); 
    console.log(num2);  
    console.log(num3); 
    console.log(num4); 
}

letDeclaration();
```



```
const playerCodes: any = { 
    player1 : 'wer', 
    player2 : 12, 
    player3 : 'aki', 
    player4 : 258
}; 
console.log (playerCodes);
playerCodes.player3++;          // Here we have to write ObjectName.SubPropoerty to access its value.
player3++;                      // It will show ERROR bcz, there is no ObjectName attached to it.
playerCodes.player2 = 21; 
console.log (playerCodes);

const playerCode: string = 'Ram'     
    console.log (playerCode);
```

------------------------------
Data-Types          * Number
------------------------------

```
let first:number = 457; // number 
let second: number = 0x37CF;  // hexadecimal
let third:number=0o377 ;      // octal
let thirdX:number=0o377 * 10000 ;
let fourth: number = 0b111001;// binary  

console.log(thirdX);
console.log(first);  // 123 
console.log(second); // 14287
second++
console.log(second);
console.log(third);  // 255
console.log(fourth); // 57 
```


-----------------------------
Data-Types          * Array
-----------------------------

```
let fruits: string[] = ['Apple', 'Orange', 'Banana'];
let vegs: Array<string> = ['Beans', 'Potato', 'onion'];
let arr = [1, 3, 5 + 6, 'Apple' + ' Juice', 'Orange', 'Banana', 0x37CF, 0x89BA, true, false];

let fruit: Array<string>;
fruit = ['Apple', 'Orange', 'Banana']; 

let ids: Array<number>;
ids = [23, 34, 100, 124, 44]; 

console.log(fruits);
console.log(fruits[1]);
console.log(vegs);
console.log(arr);
console.log(fruit);
console.log(ids);
console.log('------------------------------------------------');
```


------------
Function
------------


```
function display() {
    console.log("Hello TypeScript!");
    console.log("Hello World!");
}

display();
```


```
let a:number = 5, b:number = 8;
function  addNums(a:number = 2, b:number){
    return a * b ;
       
}
let sum: number = a + b;
var mul:number = addNums(10,9)
console.log( 'multiplication is ' + mul ); 
alert ('The Sum is ' +sum);
```


```
let a:number = 5, b:number = 7;
function  addNums(){
    return a * b ;
      
}
let sum: number = a + b;
var mul:number = addNums(10,9)  //This values will not get executed
console.log( 'multiplication is ' + mul ); 
alert ('The Sum is ' +sum);
```


```
function  addNums(a:number, b:number){
    return a * b ;
    
}
var mul:number = addNums(10,8);
console.log(mul);
var mul:number = addNums(20,10);
console.log( 'multiplication is ' + mul );
```
