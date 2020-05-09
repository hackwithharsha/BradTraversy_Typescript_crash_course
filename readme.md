# Getting started with Typescript

## Youtube Video

- [Crash Course](https://www.youtube.com/watch?v=rAy_3SIqT-E)

## What is TypeScript ?

- Superset of Javascript developed by Microsoft.
- Complies to plain javascript.
- Easily integrated into javascript projects.
- Designed for development of large applications.

## What does TypeScript Offers ?

- Static Type Checking
- Class Based Objects
- Modularity
- ES6 features
- Syntax closer to Java and other high level languages.

## Static Type Checking

- With Typescript, we can check and assign variable, parameter and function types.
- It is completely optional.
- Helps us find and prevent bugs and stop future issues from happening.
- Makes our code much more readable and descriptive.

## TypeScript Types

- String
- Number
- Boolean
- Array
- Any
- Void
- Null
- Tuple
- Enum
- Generics

## Class Based Objects

- Object Oriented Programming in JS !
- No Prototypes
- Encapsulation
- Inheritance
- Modifiers

## Typescript Compiler (tsc)

- Written in TypeScript itself.
- Compiles `.ts` files to `.js`
- Installed as an NPM Package (Node.js)
- Supports ES6 syntax.

## Installation

```bash
>>> npm install -g typescript
```

## Version

```bash
>>> tsc -v
```

## Compiling

```bash
>>> tsc app.ts

>>> tsc --out bundle.js app.ts

>>> tsc --watch --out bundle.js app.ts

>>> tsc --help

>>> tsc --init

# to compile all files.
>>> tsc

>>> tsc -w
```

## server

```bash
# never cache files
>>> http-server -c-1
```
