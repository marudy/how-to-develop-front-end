# Learn Front End Development
Coding languages and tools for front end web/mobile development.
This guide will always contain the latest technologies that i personally use to my daily work.
Tools/technologies i deprecate over my work will also be removed from this guide.

## Table Of Contents

* [JavaScript](#javascript)
 * [Introduction](#introduction-to-javascript)
 * [Advanced](#advanced-javascript)
 * [ES2015 (ES6)](#es2015)
* [AngularJS v1](#angularjs-v1)
* [React Native](#react-native)
* [Flexbox](#flexbox)

## JavaScript

### Introduction-To-Javascript
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

### Advanced-JavaScript:
* [this](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this)
* [More Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
* [Strict Mode](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode)
* [Self-Executing Functions](http://markdalgleish.com/2011/03/self-executing-anonymous-functions/) - part of JavaScript closures!

### ES2015
* [Basics](https://www.martin-brennan.com/es6-basics/)
* [Babel tutorial](https://babeljs.io/docs/learn-es2015/) 
* [Video tutorial by egghead.io](https://egghead.io/courses/learn-es6-ecmascript-2015?utm_source=drip&utm_medium=email&utm_campaign=learn-es6)

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
import React, { Component } from 'react';
import { AppRegistry, Text } from 'react-native';

class HelloWorldApp extends Component {
  render() {
    return (
      <Text>Hello world!</Text>
    );
  }
}
```

```<Text>``` from above is a built-in component that just displays some text.

When you're building a React Native app, you'll be making new components a lot. Anything you see on the screen is some sort of component. A component reuires a render function which returns some JSX to render.

- Props.
Most components can be customized when they are created, with different parameters. These creation parameters are called props. This lets you make a single component that is used in many different places in your app, with slightly different properties in each place. Just refer to this.props in your render function.

- State.
There are two types of data that control a component: props and state. props are set by the parent and they are fixed throughout the lifetime of a component. For data that is going to change, we have to use state.


**React uses ES2015 syntax**

First of all, ES2015 (also known as ES6) is a set of improvements to JavaScript that is now part of the official standard, but not yet supported by all browsers, so often it isn't used yet in web development. React Native ships with ES2015 support and ES2015 compiler.

Before you proceed with React and React Native you need to have a look at ES2015. You don't need to read ES2015 extensively and all the changes it introduces but instead key changes and the ones that React uses. Check out this [article](https://www.martin-brennan.com/es6-basics/) for a simple and extensive but not comprehensive analysis. 

**Get started with React Native**

Have a look over [React Native website](https://facebook.github.io/react-native/docs/view.html) to gain access to information that include:
- installation
- tutorials
- guides
- components

## Flexbox
Flexbox as explained by [Scott Vandehey article](https://medium.com/@spaceninja/what-is-flexbox-6aed968555ef#.ullxjk8qp) is a layout method that has been introduced with CSS3 and serves as an alternative so that developers do not abuse floats. Floats / inline-block etc hacks are hard to remember. limited and usually also buggy. 

So far, there are three versions of the specification but only one matters but the one that matters is the final one:
* The [final 2012 spec](https://www.w3.org/TR/css-flexbox-1/) — display: flex — is the new hotness, with excellent browser support.

*Notes:*
1. Each spec used a different keyword for the display property, so if you see anything other than **display:flex** in the CSS code, it’s an older article and can be ignored.
1. Flexbox layout is most appropriate to the components of an application, and small-scale layouts, while the [Grid](http://css-tricks.com/snippets/css/complete-guide-grid/) layout is intended for larger scale layouts.

**Learn by playing**
* [Flexbox Defence](http://www.flexboxdefense.com/) - Very fun tower defense educational game
* [Flexbox Froggy](http://www.flexboxdefense.com/) - Interesting concept game with lots of levels

**Learn more about the Flexible Box Layout model**
* [Complete guide to flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [Using CSS Flexible Boxes](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes)

**Flexbox layout in React Native**
[Understanding React Native flexbox layout](https://medium.com/the-react-native-log/understanding-react-native-flexbox-layout-7a528200afd4)
