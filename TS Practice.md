## TS Practice:-


```
function users(data:any)
{
    return data
}

console.warn(users({name: "Jeet",age: 20}))
```


```
function myNum(){
    'stack load';
    let num:any=99;        //if we'll not use 'let' or 'var' then it'll show an error
    console.log(num);

}
myNum();
```



```
function add (a:any,b:any){
    console.log (a+b);
}
let add1=add (3,5);
let add2=add (13,5);
```

***Increment Operator***
```
class Counter {
    
    display(count:number) {
        for(let i=1; i<=count; i++){
            console.log(i);
        }
    }
}

let object1 = new Counter();
object1.display(25);
object1.display(9);
```
_Printing the even numbers upto the limit._


```
class Counter {
    
    display(count:number) {
        for(let i=1; i<=count; i++){
            while(i%2==0){
                console.log(i);
            }
        }
    }
}

let object1 = new Counter();
object1.display(25);
object1.display(9);
```
***Decrement Operator***


```
class Counter {
    
    display(count:number) {
        for(let i=count; i>=1; i--){
            console.log(i);
        }
    }
}

let object1 = new Counter();
object1.display(18);
object1.display(5);
```
