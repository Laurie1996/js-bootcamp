
* Functies


1. Je kan ze hergebruiken
2. dynamisch


*function
#Function sum (a,b) {
  return a+bb
}

sum (1,2)

(1,2) = het Argument

***


Het woord function is een Keyword
(a,b) parameters eigenlijk ook een Variable

*NaN (Not a number)**

#Verschil Null en Undefined
Null is een variable met een lege waarde en Undefined is de absentie van een waarde


* Conditionals

If / Else  

=
== Gelijk aan
==== Gelijk aan en aan het datatype
< Groter dan
> Kleiner dan


* Loops

 *for ( var index=0; index <10;  index++)*** ]

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

## Index <10 ; = Loop moet starten als index kleiner is dan 10 (nu gelijk aan 0) en doet
 dan +1 (Hij stopt bij 9 door de index<10;)
 index++ = Index +1

* Object en Array


#Object

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



var = cyclists 
*cyclists.reduce(function(fastestTime , currentTime){
  if (fastestTime > currentTime.time) {
    return currentTime.time
  } else {
    return fastestTime
  }
}, Infinity)**


Return (geeft de mogelijkheid om iets bij een functie te returnen)
