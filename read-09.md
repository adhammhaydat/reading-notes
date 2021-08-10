# FUNCTIONAL PROGRAMMING

### 1.What is functional programming?

A major goal of functional programming is to minimize side effects, which is accomplished by isolating them from the rest of the software code. Separating side effects from the rest of your logic can make a program easier to maintain, test, debug, extend and refactor.

### 2.What is a pure function and how do we know if something is a pure function?
A pure function is a function which: Given the same input, will always return the same output. Produces no side effects.

### 3.What are the benefits of a pure function?
Pure functions are much easier to read and reason about. All relevant inputs and dependencies are provided as parameters, so no effects are observed that alter variables outside of the set of inputs. This means that we can quickly understand a function and its dependencies, just by reading the function's declaration

### 4.What is immutability?
not capable of or susceptible to change.

### 5.What is Referential transparency?

In functional programming, referential transparency is generally defined as the fact that an expression, in a program, may be replaced by its value (or anything having the same value) without changing the result of the program.

----------------------------------------------------

### 1.What is a module?
Module in Node.js is a simple or complex functionality organized in single or multiple JavaScript files which can be reused throughout the Node.js application. Each module in Node.js has its own context, so it cannot interfere with other modules or pollute global scope.

### 2.What does the word ‘require’ do?
require are used to consume modules. It allows you to include modules in your programs. You can add built-in core Node. js modules, community-based modules ( node_modules ), and local modules.

### 3.How do we bring another module into the file the we are working in?
1. To import our own Node JS module. var arthmetic = require("arthmetic");
2. To import existing Node JS Module. Import Node JS “express” module; var arthmetic = require("express"); Import Node JS “mongoose” module; var mongoose = require("mongoose");

### 4.What do we have to do to make a module available?
1. Download & install Node. js. ...
2. Create a Node project. 
3. Create an empty project using the following commands: mkdir MyCoolModule. ...
4. Write your module. There should now be a package. ...
5. Publish the module to NPM (Node Package Manager) ...
6. Test your module.