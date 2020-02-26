Functions

default values should be in end of the parameters(REST Parameters)
overloading is nopossible in javascript
overriding can be done in JS


anonymous funtion  name less funtion
value can be passed to variable

var sq=funtion(num){return num*num}
sq(4)
console.log(sq)

onload() is an anonymous function 

immediatly invoke function  expresion(IIFE)

(function(number){return number*number})(4)
can be used in loops

passing function to another function 
lisp javascript python scheme programing languages are functional program ing laguages which treat variables  and fucntion are first class citizens


var sq=funtion(num){return num*num}

function newf(a){
a();
}

newf(square);

observer pattern read?

arrow function

lambdas in other languages

we can skip the curly bracesss even 

var sq=(num)=>num*num

in ES 6 we use arrow function mostly except in constructors and can be used any where



8 javascript methods  used for  arrrays?


const filtereditems=items.filter((item)=>{return item.price <= 100})

const filtereditems=items.map((item))=>{return item.price <= 100}

const filtereditems=items.find((item))=>{return item.price === 100}


items.forEach(item)=>
{
console.log(item.price)
}

returns true or false
const iitems=items.some((item)+>
{
retrun item.price <=100}
)

const iitems=items.every((item)+>
{
retrun item.price <=100}
)


const iitems=items.reduce((currenctotal,item)+>
{
retrun item.price +currentTotal},0
)

include function

const in=items.include(2)

returns true are false


slice and splice



Es6 Features

Spread syntax  used for dereferencing the objects
...
reference is  broken 
let b=[...a];
let d=[...a,b,...c]
for objects
var obj1={id:101,name:'arun'}
const employee={...obj1,..obj2}


REST paramenters we can send any number of paremeters as we wish but this can be done only at the last


funtion myfun(a,b,..manyMoreArgs)
manyMoreArgs is an array ie objects

object destructuring assignment we are destructuring the objects and assigning the variable

let 1,b1,r
[a1,b1]

a=1,b=2
[a,b]=[b,a]



Tasks of Day:

anonimous funtions

Create an Html Element using Javascript

Filter=>Length of the capital less than 5 letters
Map=> Country name to capital letters
Find=>Detials of india

Reduce=>sum of odd numbers and sum of numbers of an arrray

splice,slice?


