# js-documentation1

###functions
function without parametrs
function addition(){
    var a=10;
    var b=20;
    return a+b;
} 

addition ()

30

```
Functions with parameters  

```javascript
function addition(a,b){
   return (a+b)
}
addition(2,3)
```
anonymous function

```javascrip
var subraction=function (a,b){
     return (a-b) 
 }    
undefined
subraction(4,3)
```

Arrow fuction 
```javascrip
var mul=(a,b)=>{
  return (a*b)
}
mul(2,3)
6
```
### higher order function(hof)
* a function accepts another function as an argument.*

```javascipt
arr.map((item,index )=>{
    console.log( item+" is having index of:"+index)
})
