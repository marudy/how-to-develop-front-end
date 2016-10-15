# Learn Front End Development
Coding languages and tools for front end web/mobile development.
This guide will always contain the latest technologies that i personally use to my daily work.
Tools/technologies i deprecate over my work will also be removed from this guide.

## Table Of Contents

* [JavaScript](#javascript)
* [AngularJS v1](#angularjs-v1)
* [React Native](#react-native)

## JavaScript
JavaScript is a programming language that adds interactivity to your website (for example: games, dynamic styling, animation). Alongside with HTML and CSS, it is one of the three core technologies of World Wide Web content production. 

You need to know that JavaScript is:

* [dynamic](https://en.wikipedia.org/wiki/Dynamic_programming_language) - meaning it's a loosely type language!
* [prototype-based](https://en.wikipedia.org/wiki/Prototype-based_programming) - pay attention here!
* with [first-class functions](https://en.wikipedia.org/wiki/First-class_function) - functions are treated as first class citizens!

JavaScript is a multi-paradigm language, supporting object-oriented, imperative and functional programming styles.
Created by Mozilla (back then it was called Netscape) engineers, there is no better place for documentation than the [JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide) in Mozilla Developer Network. Don't forget to experiment with interactive tutorials such as [JavaScript.com](https://www.javascript.com/) from Codecademy

**Basics & Object Oriented JavaScript:**
* [Basics](https://developer.mozilla.org/en-US/Learn/Getting_started_with_the_web/JavaScript_basics)
* Scoping
 * [Variable Scope](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_types#Variable_scope)
 * [Function Scope](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions#Function_scope)
 * [Block Scope](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let) - introduced in ES2015!
* [Data Types & Structures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures)
* [JavaScript Hoisting Explained](http://code.tutsplus.com/tutorials/javascript-hoisting-explained--net-15092)
* [Promises](https://www.promisejs.org/)
* [Re-introduction to JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript)
* [Object Oriented JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Introduction_to_Object-Oriented_JavaScript)
* [ES2015 basics (also called ES6)](https://www.martin-brennan.com/es6-basics/)

**Advanced Javascript:**
* [this](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this)
* [More Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
* [Strict Mode](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode)
* [Self-Executing Functions](http://markdalgleish.com/2011/03/self-executing-anonymous-functions/) - part of JavaScript closures!


## AngularJS-v1
AngularJS is an MV* framework for use when building client-side single-page apps ([SPA](https://en.wikipedia.org/wiki/Single-page_application)). It is not a library, but a framework for building dynamic web pages. It focuses on *extending HTML* and providing dynamic data binding. Instead of manipulating the DOM “directly,” you annotate your DOM with metadata (directives), and Angular manipulates the DOM for you.

Using dependency injection, Angular brings traditionally server-side services, such as view-dependent controllers, to client-side web applications. Consequently, much of the burden on the server can be reduced. Get in speed with AngularJS by starting with the links below:

* [Conceptual Overview](https://docs.angularjs.org/guide/concepts)
* [How to get started](http://www.ng-newsletter.com/posts/beginner2expert-how_to_start.html)
* [How 2 way data bidning works: $digest & $apply](https://www.sitepoint.com/understanding-angulars-apply-digest/)
* Directives
  * [Introduction](http://www.ng-newsletter.com/posts/beginner2expert-directives.html)
  * [Scoping](https://github.com/angular/angular.js/wiki/Understanding-Scopes)
  * [Build Custom Directives](http://www.ng-newsletter.com/posts/directives.html)
  * [Cheat Sheet](https://d2eip9sf3oo6c2.cloudfront.net/pdf/egghead-io-directive-definition-object-cheat-sheet.pdf?__s=n5ryciokbigwwwkvvwhc)


## React-Native
React Native, is an open-source JavaScript library, which enables native iOS and Android development with React. To understand the basic structure of a React Native app, you need to understand some of the basic React concepts, like JSX, components, state, and props.

**Notable React Features**
- The use of a "virtual DOM."
React creates an in-memory data structure cache, computes the resulting differences, and then updates the browser's displayed DOM efficiently. This allows the programmer to write code as if the entire page is rendered on each change while the React libraries only render subcomponents that actually change.

- JSX
React components are typically written in JSX, a *JavaScript extension syntax allowing quoting of HTML and using HTML tag syntax to render subcomponents.* Many frameworks use a special templating language which lets you embed code inside HTML (i.e. Angular). In React, this is reversed. JSX lets you write your HTML inside JavaScript code. 

- Components
JavaScript code written in classes(ES2015) and using JSX mentioned above. I.e.
```html
<pre>
class HelloWorldApp extends Component {
  render() {
    return (
      <Text>Hello world!</Text>
    );
  }
}
</pre>
```

```<Text>``` from above is a built-in component that just displays some text.


**React uses ES2015 syntax**

First of all, ES2015 (also known as ES6) is a set of improvements to JavaScript that is now part of the official standard, but not yet supported by all browsers, so often it isn't used yet in web development. React Native ships with ES2015 support and ES2015 compiler.

Before you proceed with React and React Native you need to have a look at ES2015. You don't need to read ES2015 extensively and all the changes it introduces but instead key changes and the ones that React uses. Check out this [article](https://www.martin-brennan.com/es6-basics/) for a simple and extensive but not comprehensive analysis. 


