
**Functies**

Functie aanroepen altijd met de haakjes ()

#bijvoorbeeld
helloObject.greeting ()

1. Je kan ze hergebruiken
2. dynamisch


*function
#Function sum (a,b) {
  return a+bb
}

sum (1,2)

(1,2) = het Argument

***


**Het woord function is een Keyword
(a,b) parameters eigenlijk ook een Variable

NaN (Not a number)**

#Verschil Null en Undefined
Null is een variable met een lege waarde en Undefined is de absentie van een waarde


**Conditionals**

*If / Else  

=
== Gelijk aan
==== Gelijk aan en aan het datatype
< Groter dan
> Kleiner dan


 #Loops

 for ( var index=0; index <10;  index++) ]

 Console.log geeft :

0
1
2
3
4
5
6
7
8
9
**

## Index <10 ; = Loop moet starten als index kleiner is dan 10 (nu gelijk aan 0) en doet
 dan +1 (Hij stopt bij 9 door de index<10;)
 index++ = Index +1



#Object

* mutable data type

object combineren met const
wijzig de waarde van het object kan, maar niet het object zelf.

Object bestaat uit *[key]:Value** Pairs
Key is de manier waarop je het opvraagt je Variable
value kan elk datatype zijn

datatypes of meerdere data scheiden door een ,
zorgt voor nettere, makkelijkere, kortere java

*Var student {
  name:"henk",
  grade: 10

}

student.name
"henk"

student.grade
10
**


var object = {
  key1: 'this is text'
  key2: 12
  key 3: [{
    key= "some text here"}]
}


#boolean

var boolean = true;



#Array

Verzameling van variabelen
var = [datatypes]
Var.students  = [ 1, "1", True]


*WINDOW**


#High order function

*students.forEach (function (student){
  console.log(student)
})**


3 types of functions met arrays

students.push({name:'piet'})

functional programming principals
.shift
.push
.length

High order functions
Map ----> returned een new array  met hetgene wat je returned per item.
Filter ------> Returned new array met wat als true
Reduce  ----- > returned wat je wilt  (bijvoorbeeld snelste tijd etc.)



*var = cyclists [

]
cyclists.reduce(function(fastestTime , currentTime){
  if (fastestTime > currentTime.time) {
    return currentTime.time
  } else {
    return fastestTime
  }
}, Infinity)**


Return (geeft de mogelijkheid om iets bij een functie te returnen)

#methods

functie die is gedeclareerd in een object


**Voorbeeld**

*console(object).(punt =1 trap lager) log(name.length)**



**Scopes**


#Global Scope ==== hoogste niveau, niet genest, niet in een functie (ik kan er altijd bij)
    const name= 'Danny'; //global

#Local Scope // function Scope ==== function binnen de gatekeepers []
function greeting () {
  const name = 'Danny'; // Local
}

#FunctionScope {
  Console.log moet in de functie staan anders undefined.
  je moet de functie callen met de haakjes()
}


#Block scope eigenlijk hetzelfde als een function scope maar minder streng
we geven alleen var toestemming om deze buiten de gatekeepers te gebruiken

- herkennen aan de if statement vergelijkbaar aan de funtion scope

  if (true) {
    let y =5;
  }

console.log (Y)

   Undefined want console niet in de if statement


**Hoisting**

Hoisting suggests that variable and function declarations are physically moved to the top
of your code

#Hoisting
num=6;
console.log(num);
var num;

#Hoisting is gewoon iets unieks aan java maar kut niet gebruiken
myJob= 'Developer'
console.log('my job is' + myJob);
var myJob;

#De gewoonlijke manier is netter
var myJob= 'developer'
console.log('my job is' + myJob);
