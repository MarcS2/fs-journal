# JavaScript.



to break console.logs into sections you can use console.group('group name')
console.log(exm)
console.log(exm)
console.log(exm)

console.groupEnd()
-with this you can collapse console.logs in the consoles

Camel case is written with the first word un-capitalized and words after are capitalized ie clockStop
-for js
Kabob case is written with hyphens ie clock-stop
-for css

= Details
-1 = is for value assignment or reassignment 
-2 == is for  comparing 
-3 === is for strict comparison that compares not only the value but also the type of data

for string's 
-``

-""

-''

Boolean
- boolean values are true or false


script tag goes in the bottom of the body for js



Numbers 

-math in js works with P.E.M.D.A.S: ()^*/+-

Objects{} & Arrays[]

-objects store things in key value pairs

-you can pull out key-pairs in an object by using brackets and quotes ie person['name'] ie person.name

const person = {
  name = 'Jeremy'

  key^   value^
  exmpArray: [0,1,2,3]
  arrays use index to store 
}


? are a ternary operator they can be used to determine true or false and return a resault based on if its T/F
console.log(`hello I am $[person.name ? 'true input' : 'false input']`)
                    object ^  key  ^

- you can dump key pairs from objects to new values ie 
const copyPerson = {...person}
copyPerson.name 
-with this you can access info from the original array


Array

- const arrayOfNums = [1, 2, 3, 4]
-const strings = ['hello', 'what']