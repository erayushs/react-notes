## What is React?

React is a JavaScript library developed by Facebook for building user interfaces, especially single-page applications. It allows developers to create reusable UI components and manage the application's state efficiently.

## Why React is known as ‘React’?

The name ‘React’ was chosen because the library was designed to allow developers to react to changes in state and data within an application, and to update the user interface in a declarative and efficient manner.

## How to start your React Project using parcel?

Step 1. npm init -y

Step 2. npm i -D parcel

Step 3. npm i react react-dom

Step 4. touch index.html index.js index.css

Step 5. "main": "index.js", (remove this from package.json) and write type="module" in index.html in script tage

Step 6. npx parcel index.html

## How JSX is converted and is rendered?

JSX is transpiled to React.createElement()

JSX => React.createElement => ReactElement (which is a JS object/ JS code) => ReactDOM converts it to HTML Element (when it renders)
