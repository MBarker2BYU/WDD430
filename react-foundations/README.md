This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.




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

# React Foundations – MBarker2BYU

## Progress
- [x] Chapter 1: About React and Next.js
- [x] Chapter 2: Rendering User Interfaces (UI)
- [x] Chapter 3: Updating UI with JavaScript
- [x] Chapter 4: Getting Started with React
- [x] Chapter 5: Building UI with Components
- [x] Chapter 6: Displaying Data with Props
- [x] Chapter 7: Adding Interactivity with State

## Files
- `app/page.tsx`: Next.js home page (Chapter 1 edit)
- `index.html`: React tutorial progress (Chapters 3–7)

## Repo
https://github.com/MBarker2BYU/WDD430/tree/main/react-foundations