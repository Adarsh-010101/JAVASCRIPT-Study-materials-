## JAVASCRIPT 
   * JavaScript is a dynamic programming language that's used for web development in web applications,game development etc.
    It allows you to implement dynamic features on web pages that cannot be done with only HTML and CSS.
   - JavaScript is the Programming Language for the Web.
   - JavaScript can update and change both HTML and CSS. 
   - JavaScript can calculate, manipulate and validate .
   
##  Javascript Key Features <>
   -Scripting Language (JavaScript is a lightweight scripting language made for client-side execution on the browser)
   -Interpreter Based  -Light Weight    -Case Sensitive     -Control Statements    -Objects as first-class citizens     -Event Handling
   -Functions as First-class citizens(supports functional programming)
   
## Let & const 
   ### LET ( Using 'LET' , while declaring a variable and assigning it with some values that can be updated later .
   
   EXAMPLE ->   
   
    let myclass = 'class'; 
    console.log(myclass);  // Output - class                                                                                              
    ....

    myclass = 'A';         
    console.log(myclass);  // Output -   A                                                                                           

    myclass = 'B';         
    console.log(myclass);  // Output -   B                                                                               

    myclass = 'C';        
    console.log(myclass);  // Output -   C                                                                              

    myclass = 'D';        
    console.log(myclass);   // Output -   D                                                                           

    myclass = 'E';        
    console.log(myclass);   // Output -   E , in this case - Value of variable 'myclass' gets updated every time we declare a new value to it .

   ### CONST ( Using 'CONST' , at the time of variable declaration , the value assigned to the variable remains constant and  can not be changed )
   Example ->
   
    const status = 'Qualified';
    console.log(status);


    status = 'Disqualified';
    console.log(status);    
   
    // Output - ' Qualified ' & will show type error as for the assignment to constant variable (in this case - Value assigned once to the variable 'status'  will    always be the same , as it says the  "const var" will be constant always.)
   
## Arrow functions :

  - These functions were introduced in ES6.
  - These functions allow us to write shorter function syntax:

       let myFunction = (a, b) => a * b;
       
  ### Example : 
    let myFunction = (a, b) => a * b;
    document.getElementById("demo").innerHTML = myFunction(4, 5); 
    // it will return 20 
       
 ### WITHOOUT Arrow :
     
    hello = function() {
    return "Hello World!"; }
  Example :
     
      let hello ="";

      hello = function() {
      return "Hello World!";
    } 

    document.getElementById("demo").innerHTML = hello(); // it will return Hello World 
 
 ### WITH   Arrow 
 
    const multiply = (number) => {
    return number * 2; }
    console.log(multiply(2)); // will return num * 2 , i.e; 2*2 = 4 
    
## Exports and Imports 
  - Exports and Imports Statements are also reffered to as so called  'modules' 
  - Using these 'Import &export modules, we can import content from anothern file & 
  - It helps javascript files to know about their dependencies
      
   ### DEFAULT EXPORT 

    - Supp0se we have a file named - person.js

     where ,

       const person = {

        name: 'Max'                                                    

     }      

      export  default person   

        ||           app.js              ||

        import person from './person.js'

        import prs from './person.js' //

  // note*  ( In the above file , it shows us the example of default export &  In default export you just have to choose the name )

                                                   

   ### NAMED EXPORT 

   2) Supp0se we have another  file named - utility.js

    export const clean = () = > { ... }  

    export const basedata = 10 ; // name is defined by export 

     ||               app.js              ||

    import  { basedata } from './utility.js' 

    import  {  clean }   from './utility.js' 

    this can also be written as -  import  { basedata , clean } from './utility.js' 

        import  { smth} from './utility.js' 

        import  { smth as Smth }  from './utility.js' 
 
        import  * as bundled from './utility.js' // for bundled export of items.

 
     
    
## Classes 
          - A blueprint for  js objects.
          - contains Methods & Properties 
          -  uses a constructor() to add properties.
          - Suppports inheritence 
          
   Example :
          
          class React {    
          
             name = 'JS Library' // Property 
             call = () = > {..}  // Method 
             
            } 
            
          
   Methods :  fn's attached to classes 
     - Example : 
     
              constructor() {
                ... .. ....
              } 
              
        
   Properties : var's attached to classes 
            

## OPERATORS 
   - Spread : 
              -The JavaScript spread operator ( ... ) allows us to quickly copy all or part of an existing array or object into another array or object.  
              -The Spread operator expands elements of an iterable .
   
   - Rest :    
              -The Rest Operator compresses elements of an iterable .
              -The rest operator ( ... ) instructs the computer to add whatever otherInfo (arguments) supplied by the user into an array
              -The rest operator (…) allows us to call a function with any number of arguments and then access those excess arguments as an array.
              -The rest operator also allows us in destructuring array or objects .
              
              
## Destructuring 
   - Destructuring is a simple property that is used to make code much clear and readable, mainly when we pass props in React.
   - It is a characteristic of JavaScript.
   - It is used to take out sections of data from an array or objects.
   - It makes the code more clear. When we access the props using this keyword, we have to use this/ this.props throughout the program, 
       but by the use of restructuring, we can discard this/ this.props by assigning them in new variables.

## Why do we use destructuring ?
    - It makes developer’s life easy, by assigning their own variables. 
    - Nested data is more complex, it takes time to access, but by the use of destructuring, we can access faster of nested data.
    - It improves the sustainability, readability of code.
    - It helps to cut the amount of code used in an application.
    - It trims the number of steps taken to access data properties.
    - It provides components with the exact data properties.
    - It saves time from iterate over an array of objects multiple times.
    - In ReactJS We use multiple times ternary operators inside the render function, without destructuring it looks complex and hard to access them, but by       - the use of destructuring, we can improve the readability of ternary operators.

           
## Reference & Primitive 
        - Objects & Arrays are reference types , if we reassign these objects or arrays , we are copying the pointer not the value .
        - If you want to do this in a real copy way, we need to create new object
        
    =-Primitive : 
       - Primitive values are atomic pieces of data while reference values are objects that might consist of multiple values.
       = 
## Wrap Up 

## Array Functions in Javascirpt :

   
   
