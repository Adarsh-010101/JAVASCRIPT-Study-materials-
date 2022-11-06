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

    Supp0se we have a file named - person.js

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

## Properties 

## Methods 

## The Spread & Rest Operator 

## Destructuring 

## Reference & Primitive

## Wrap Up 

## Array Functions in Javascirpt :

   
   
