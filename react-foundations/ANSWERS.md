# Check Your Understanding – React Foundations

## What is the DOM?
The **Document Object Model (DOM)** is a tree-like structure created by the browser from HTML. It represents every element on the page as an object, so JavaScript can select, add, update, or delete parts of the UI dynamically.

## What is the difference between Imperative vs Declarative Programming?
- **Imperative**: Step-by-step instructions on *how* to do something (e.g., manual DOM manipulation with `createElement`).  
- **Declarative**: Describe *what* you want, and let the tool figure out *how* (e.g., `<h1>Text</h1>` in React).  
*Pizza analogy*: Imperative = recipe steps; Declarative = ordering a pizza.

## What is JSX – the syntax extension for JavaScript?
**JSX** is a syntax extension that lets you write HTML-like code inside JavaScript. Example: `const element = <h1>Hello</h1>;`  
It makes UI code readable but needs to be transpiled to plain JS.

## What is the Babel interpreter?
**Babel** is a JavaScript compiler/transpiler that converts JSX and modern JS features (like arrow functions) into plain JavaScript that browsers can run.  
In the tutorial: `<script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>`

## What is the difference between props and state?
**Props**: Read-only data passed *into* a component from a parent (like function arguments).  
**State**: Internal, mutable data *inside* a component that can change over time (managed with `useState`).