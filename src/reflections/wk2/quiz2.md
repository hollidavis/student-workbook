# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var, let, & const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a reusable set of statements to perform a task or calculate a value. Functions can be passed one or more values and can return a value at the end of their execution.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
- S - Single Responsibility a class should be having one and only one responsibility
- O - Open / Closed classes should be open for extension but closed for modification
- L - Liskov Substitution parent classes should be easily substituted with their child classes without blowing up the application
- I - Interface Segregation many client specific interfaces are better than one general interface
- D - Dependency Inversion classes should depend on abstraction but not on concretion
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
The pineapple's current position is index 2. We know this because all indexes start their count at 0.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
How would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
Examples of conditional statements are if/else statements and switches. 
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
That section of the for loop is called an final-expression. To increase i I would add "i++" to increment the variable each loop.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM stands for Document Object Model. The file first accessed when rendering the DOM is the index.html
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
- Undefined
- Boolean
- Number
- String
- BigInt
- Symbol
- Object
- Function
- Null
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
The difference between a parameter and an argument is that parameters are what you tell the function to expect to receive while arguments are the actual values it receives when run.

```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive values are data that are stored on the stack. Reference values are objects that are stored in the heap. 
```