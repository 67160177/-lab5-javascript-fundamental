# ข้อที่ 1

=== Variables & Data Types Practice ===

Constants:
MAX_USERS: 100
PI: 3.14159

Variable (let):
count after increment: 2

=== Primitive Data Types ===
Numbers: 25 5.9 -10
Strings: John Doe
Booleans: isStudent: true isTeacher: false
null: null
undefined: undefined

=== Object Data Types ===
Array: [ 'apple', 'banana', 'orange' ]
First fruit: apple
Array length: 3
Object: { name: 'John', age: 25, city: 'Bangkok', isStudent: true }
Person name: John
Person age: 25

=== typeof Operator ===
typeof 25: number
typeof 'hello': string
typeof true: boolean
typeof undefined: undefined
typeof []: object
typeof {}: object
typeof (() => {}): function

=== Type Coercion ===
'5' + 2: 52
'5' - 2: 3
'5' \* 2: 10
true + 1: 2

Explicit coercion:
String(25): 25
Number('25'): 25
Boolean(1): true
Boolean(0): false
Boolean(''): false
Boolean('hello'): true

=== Challenge: Person Object ===
Student object:
{
firstName: 'Alice',
lastName: 'Smith',
age: 20,
gpa: 3.8,
courses: [ 'HTML', 'CSS', 'JavaScript' ],
isActive: true,
getFullName: [Function: getFullName],
getInfo: [Function: getInfo]
}
Full name: Alice Smith
Info: Alice Smith, Age: 20, GPA: 3.8
Courses: HTML, CSS, JavaScript

=== Truthy vs Falsy ===
Falsy values:
0: false
"": false
null: false
undefined: false
false: false
NaN: false

Truthy values:
1: true
hello: true
true: true
[]: true
{}: true
() => {}: true

✅ Activity 1 completed!
