# Frontend Interview Questions

Common question for Frontend Interviews, most by Boris Cherny found [here](https://performancejs.com/post/hde6d32/The-Best-Frontend-JavaScript-Interview-Questions-(Written-by-a-Frontend-Engineer)) and the _Master the JavaScript Interview_ series and [_10 Interview Questions Every JavaScript Developer Should Know_](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95) by [Eric Elliot](https://medium.com/@_ericelliott).
Practical Javascript training tasks can be found [here](https://github.com/anszu/javascript-training).

## General

1. What is Big O notation?  
_A method to describe the performance or complexity of an algorithm._    
[Full article to answer question.](https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation/)

2. What is the DOM?  
_The Document Object Model is an object based hierarchical model of a pages HTML structure. The DOM is represented by a node tree that can be used by eg. Javascript programms for reading or modifications._     
[Full article to answer question.](https://bitsofco.de/what-exactly-is-the-dom/)

3. What are the pros and cons of monolithic vs microservice architectures?  
_Monolith = one unit of code with tight coupling between the components_      
_Microservice = several independent components not relying on each other_    
_Pro Monolith: easy to hook up components to cross-cutting concerns like logging or security featueres_      
_Con Monolith: scaling and maintainance is hard due to tight coupling, harder to understand_    
_Pro Microservice: easy to scale and maintain, easier to understand_    
_Con Mircoservice: possible code duplication, problem of how to implement shared logic, often harder to set up_    
_Result: in the long-run Microservices are usually the better choice._  
[Full article to answer question.](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)

4. What is asynchronous programming, and why is it important in JavaScript?  
_An event loop is listening for operations, which when requested don't block the rest of the code. User interfaces are asynchronous by nature waiting for user inputs to fire an event handler._  
[Full article to answer question.](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)

5. Describe a few ways to communicate between a server and a client. Describe how a few network protocols work at a high level (IP, TCP, HTTP/S/2, UDP, RTC, DNS, etc.)  
_insert answer here_  
[Full article to answer question.](https://www.lifewire.com/definition-of-protocol-network-817949)

6. What is REST, and why do people use it?  
_insert answer here_  
[Full article to answer question.](https://www.codecademy.com/articles/what-is-rest)

7. How does DNS Lookup work?  
_insert answer here_  
[Full article to answer question.](https://royal.pingdom.com/a-visual-explanation-of-how-dns-lookups-work/)

## Javascript

1. What is the event loop?  
_insert answer here_   
[Full article to answer question.](https://flaviocopes.com/javascript-event-loop/)

2. What is a closure?  
_insert answer here_   
[Full article to answer question.](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-closure-b2f0d2152b36)

3. How does prototypal inheritance work, and how is it different from class inheritance?  

_Class inheritance:_   
- _Instances inherit from classes (like a blueprint — a description of the class), and create sub-class relationships: hierarchical class taxonomies._
- _Instances are typically instantiated via constructor functions with the `new` keyword. Class inheritance may or may not use the `class` keyword from ES6._

_Prototypal Inheritance:_  
- _A prototype is a working object instance. Objects inherit directly from other objects. Instances may be composed from many different objects, allowing for easy selective inheritance._ 
- _Instances are typically instantiated via factory functions (function that return an object), object literals (comma-separated list of name-value pairs wrapped in curly braces), `[Object.create()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/create)` or inheriting features directly from one object to another by copying the source objects properties (Concatenative inheritance) with [`Object.assign()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign) (formely done eg. by jQueries $.extend())_  

_In JavaScript, prototypal inheritance is simpler & more flexible than class inheritance._  
[Full article to answer question.](https://medium.com/javascript-scene/master-the-javascript-interview-what-s-the-difference-between-class-prototypal-inheritance-e4cd0a7562e9)

4. How does this work?  
_insert answer here_   
[Full article to answer question.](https://medium.com/quick-code/understanding-the-this-keyword-in-javascript-cb76d4c7c5e8)

5. What is event bubbling and how does it work?  
_insert answer here_   
[Full article to answer question.](https://javascript.info/bubbling-and-capturing)

6. What is Function Composition?  
_insert answer here_  
[Full article to answer question.](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-function-composition-20dfb109a1a0)

7. What ist a Pure Function?  
_insert answer here_  
[Full article to answer question.](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-pure-function-d1c076bec976)

8. What is Functional Programming?  
_insert answer here_  
[Full article to answer question.](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0)

9. What are the pros and cons of functional programming vs object-oriented programming?  
_insert answer here_  
[Full article to answer question.](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)

10. What is a Promise?  
_insert answer here_  
[Full article to answer question.](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-promise-27fc71e77261)

11. Can you name two programming paradigms important for JavaScript app developers?  
_insert answer here_  
[Full article to answer question.](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)

12. What does “favor object composition over class inheritance” mean?  
_insert answer here_  
[Full article to answer question.](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)

13. What are two-way data binding and one-way data flow, and how are they different?  
_insert answer here_  
[Full article to answer question.](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)

## React

1. What are React Hooks and why are the useful?  
_insert answer here_  
[Full article to answer question.](https://reactjs.org/docs/hooks-intro.html)

2. Explain the Rendering Prop pattern.  
_insert answer here_  
[Full article to answer question.](https://reactjs.org/docs/render-props.html)

3. Explain the HOC pattern.  
_insert answer here_  
[Full article to answer question.](https://reactjs.org/docs/higher-order-components.html)

4. What is a pure compoment?  
_insert answer here_  
[Full article to answer question.](https://medium.com/front-end-weekly/using-a-purecomponent-in-reacts-262972f9f1e0)

5. When should you use a functional component and when a class component?  
_insert answer here_  
[Full article to answer question.](https://programmingwithmosh.com/react/react-functional-components/)

6. What is the difference between a presentational and a container component?  
_insert answer here_  
[Full article to answer question.](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0)

6. Explain JSX attribute spreading.  
_insert answer here_  
[Full article to answer question.](https://codeburst.io/react-anti-pattern-jsx-spread-attributes-59d1dd53677f)

7. How do you render content conditionally in JSX?  
_insert answer here_  
[Full article to answer question.](https://reactjs.org/docs/conditional-rendering.html)

8. What is the difference between component composition and component inheritance and which one should be prefered?  
_insert answer here_  
[Full article to answer question.](https://reactjs.org/docs/composition-vs-inheritance.html)

## Others

1. What do you know about Machine Learning?  
_insert answer here_  
[Full article to answer question.](https://towardsdatascience.com/machine-learning-an-introduction-23b84d51e6d0)

## Further reading on interviews

[Soft Skills](https://medium.com/javascript-scene/master-the-javascript-interview-soft-skills-a8a5fb02c466)   
[Star Interview Method](https://www.themuse.com/advice/star-interview-method)

