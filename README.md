# TypeScript Introduction

TypeScript is Javascript with added syntax for types.

## What is TypeScript?

TypeScript is a syntactic superset of JavaScript which adds static typing. This basically means that TypeScript adds syntax on top of JavaScript, allowing developers to add types.

`TypeScript being a "Syntactic Superset" means that it shares the same base syntax as JavaScript, but adds something to it.`

## Why should I use TypeScript?

JavaScript is a loosely typed language. It can be difficult to understand what types of data are being passed around in JavaScript. In JavaScript, function parameters and variables don't have any information! So developers need to look at documentation, or guess based on the implementation. TypeScript allows specifying the types of data being passed around within the code, and has the ability to report errors when the types don't match. For example, TypeScript will report an error when passing a string into a function that expexts a number. JavaScript will not.

`TypeScript uses compile time type checking. Which means it checks if the specified types match before running the code, not while running the code.`

## How do I use TypeScript?

A common way to use TypeScript is to use the official TypeScript compiler, which transpiles TypeScript code into JavaScript. We will see soon how to get the compiler setup for a local project. Some popular code editors, such as Visual Studio Code, have built-in TypeScript support and can show errors as you write code!

## TypeScript Compiler

TypeScript is transpiled into JavaScript using a compiler.

`TypeScript being converted into JavaScript means it runs anywhere that JavaScript runs!`

## Installing the Compiler

TypeScript has an official compiler which can be installed through npm. Within your project, run the following command to install the compiler:

> npm install typescript --save-dev

Which should give you an output similar to:

> added 1 package, and audited 2 packages in 2s
> found 0 vulnerabilities

The compiler is installed in the `node_modules` directory and can be run with: `npx tsc`.

> npx tsc

Wich should give you an output similar to:

> Version 4.5.5
> tsc: The TypeScript Compiler - Version 4.5.5

Followed by a list of all the Common Commands.

## Configuring the Compiler

