# Frontend Interview Preperation Guide
I created this repo to help engineers with their preparation for frontend interviews. Feel free to star/fork it for future reference.

# Call for Help/Contribution
Feel free to raise PRs to enrich this repo with more questions (Don't forget to add placeholder for answer as well). Also most of the answers are yet to be added. Feel free to add them as well.


# Questions

| No. | Questions |
|---- | ---------
|1  | [What is CORS? How does it work in browsers? What is preflight request](#What-is-CORS-How-does-it-work-in-browsers-What-is-preflight-request) |
|2  | [Why do we need Redux? Why can't same thing be done by a global state?](#Why-do-we-need-Redux-Why-cant-same-thing-be-done-by-a-global-state) |
|3  | [Explain how does virtual DOM works exactly?](#Explain-how-does-virtual-DOM-works-exactly) |
|4  | [What happens when you enter a URL in the browser?](#What-happens-when-you-enter-a-URL-in-the-browser) |
|5  | [Apart from the task queue, what other queues are there in browser?](#Apart-from-the-task-queue-what-other-queues-are-there-in-browser) |
|6  | [If we define a class in JS using arrow functions and without using class keyword, would it work?](#If-we-define-a-class-in-JS-using-arrow-functions-and-without-using-class-keyword-would-it-work) |
|7  | [Describe ES6 features and properties](#Describe-ES6-features-and-properties) |
|8  | [How does virtual DOM works in React? Talk about React Fibre, the reconciliation algorithm of react.](#How-does-virtual-DOM-works-in-React-Talk-about-React-Fibre-the-reconciliation-algorithm-of-react) |
|9  | [What is event loop and how does it work?](#What-is-event-loop-and-how-does-it-work) |
|10  | [Difference between state and props](#Difference-between-state-and-props) |
|11  | [Why we need key in react lists? What happens if we provide the index as the key ?](#Why-we-need-key-in-react-lists-What-happens-if-we-provide-the-index-as-the-key-) |
|12  | [How to improve performance of a web app](#How-to-improve-performance-of-a-web-app) |
|13  | [What are controlled and uncontrolled inputs in React ?](#What-are-controlled-and-uncontrolled-inputs-in-React-) |
|14  | [What is a closure? How can it be used ?](#What-is-a-closure-How-can-it-be-used-) |
|15  | [Why do we need redux? Why can't we just use a global state?](#Why-do-we-need-redux-Why-cant-we-just-use-a-global-state) |
|16  | [Event Propogation and Event bubbling?](#Event-Propogation-and-Event-bubbling) |
|17  | [Difference between debouncing and throttling?](#Difference-between-debouncing-and-throttling) |
|18  | [Difference between call, apply and bind?](#Difference-between-call-apply-and-bind) |
|19  | [What is async and await. What does a async function return?](#What-is-async-and-await-What-does-a-async-function-return) |
|20  | [What is a Higher Order Component ? Give example and explain the use cases where it should be used.](#What-is-a-Higher-Order-Component--Give-example-and-explain-the-use-cases-where-it-should-be-used) |
|21  | [How to deep clone a object in javascript ?](#How-to-deep-clone-a-object-in-javascript-) |
|22  | [Implement a singleton class in Javascript.](#Implement-a-singleton-class-in-Javascript) |
|23  | [Lifecycle hooks of react with use of each hook?](#Lifecycle-hooks-of-react-with-use-of-each-hook) |
|24  | [Does react component only update on state change or also on prop change ?](#Does-react-component-only-update-on-state-change-or-also-on-prop-change-) |
|25  | [How to start a new Angular project from cli ?](#How-to-start-a-new-Angular-project-from-cli-) |


1. ### What is CORS? How does it work in browsers? What is preflight request
     Answer To be added
2. ### Why do we need Redux? Why can't same thing be done by a global state?
     Answer To be added
3. ### Explain how does virtual DOM works exactly
     Answer To be added
4. ### What happens when you enter a URL in the browser?
    1. You enter a URL into a web browser.<br>
    2. The browser looks up the IP address for the domain name via DNS.<br>
    3. The browser sends a HTTP request to the server.<br>
    4. The server sends back a HTTP response.<br>
    5. The browser begins rendering the HTML.<br>
    6. The browser sends requests for additional objects embedded in HTML (images, css, JavaScript) and repeats steps 3-5.
Once the page is loaded, the browser sends further async requests as needed.
5. ### Apart from the task queue, what other queues are there in browser? 
     Render queue and microtask queue - for resolving promises.They do have a priority as well.
6. ### If we define a class in JS using arrow functions and without using class keyword, would it work?
     This wouldn't work. because it will not only throw a syntax SyntaxError(" `${name}` is not a constructor"). but semantically, a class
     need to set its 'this' context to all functions and variables inside it. Arrow functions this context is set to its parent (surrounding code) and not its children/itself.
7. ### Describe ES6 features and properties.
     Answer To be added
8. ### How does virtual DOM works in React? Talk about React Fibre, the reconciliation algorithm of react.
     Answer To be added
9. ### What is event loop and how does it work?
   > For solution, refer to below links.

    [![loop](http://img.youtube.com/vi/cCOL7MC4Pl0/0.jpg)](http://www.youtube.com/watch?v=cCOL7MC4Pl0 "Jake Archibald: In The Loop - JSConf.Asia")
    [![event loop](http://img.youtube.com/vi/8aGhZQkoFbQ/0.jpg)](http://www.youtube.com/watch?v=8aGhZQkoFbQ "What is event loop?")
10. ### Difference between state and props
     Answer To be added
11. ### Why we need key in react lists? What happens if we provide the index as the key ?
     Answer To be added
12. ### How to improve performance of a web app
     Answer To be added
13. ### What are controlled and uncontrolled inputs in React ?
     Answer To be added
14. ### What is a closure? How can it be used ?
     closures gives access to an outer function's scope from an inner function.
     it is a mechanism used to enable data privacy
15. ### Why do we need redux? Why can't we just use a global state?
     Answer To be added
16. ### Event Propogation and Event bubbling?
     Event propagation is a mechanism that defines how events propagate or travel through the DOM tree to arrives at its target and what happens to it afterward.
     Event bubbling is a type of event propagation where the event first triggers on the deepest target element. It causes all events in the child nodes to be automatically passed to its parent nodes. The advantage of this method is speed because the code only requires to traverse the DOM tree once.
17. ### Difference between debouncing and throttling?
     Answer To be added
18. ### Difference between call, apply and bind?
     Call/apply call the function immediately, whereas bind returns a function that, when later executed.
     Use .bind() when you want that function to later be called with a certain context, useful in events. Use .call() or .apply() when you want to invoke the function immediately, and modify the context.
19. ### What is async and await. What does a async function return?
     Async and Await are extensions of promises.
     Async functions enable us to write promise based code as if it were synchronous, 
     but without blocking the execution thread by operating asynchronously via the event-loop.
     Await makes JavaScript wait until the promise returns a result.
20. ### What is a Higher Order Component ? Give example and explain the use cases where it should be used.
     Answer To be added
21. ### How to deep clone a object in javascript ?
     Answer To be added
22. ### Implement a singleton class in Javascript.
     Answer To be added
23. ### Lifecycle hooks of react with use of each hook?
     Answer To be added
24. ### Does react component only update on state change or also on prop change ?
     Answer To be added
25. ### How to start a new Angular project from cli ?
     Answer To be added




Video tutorial links
- [Software Interview Preparation Guide - Strategies and Resources on How to - By Gaurav Sen](https://www.youtube.com/watch?time_continue=768&v=bBPHpH8aKjw)
- [Coding Made Simple - By Tushar Roy](https://www.youtube.com/user/tusharroy2525/)

Programming Questions
- [Programming Inteview Questions - By Arden Dertat](http://www.ardendertat.com/2012/01/09/programming-interview-questions/)
