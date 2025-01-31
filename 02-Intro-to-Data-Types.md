# Intro to Data Types

Table of Contents

- [Intro to Data Types](#intro-to-data-types)
  - [Overview](#overview)
  - [Data Types](#data-types)
  - [Hands On: Playing with String and Number](#hands-on-playing-with-string-and-number)
    - [What happens for strings without quotations?](#what-happens-for-strings-without-quotations)
  - [Recap](#recap)

## Overview

A computer program is a set of instructions that a computer executes to perform a specific task

And with program, you can do things like basic calculations and printing words to the console.

We have also learned that in order to print out words such as:

```
Hello, World!
```

we needed to wrap them with quotations, like so:

```
"Hello, World!"
```

But why do we need the quotations? and why don't the numbers need them?

Introducing the data types.

## Data Types

In order for the computer to **perform a task**, they need to know what kind of data they are dealing with. And that's why there are data types.

Let's formally state what data types are:

**Data types refer to the type of data a programming language can handle within the program.**

So far, we have used two types already:

- one with the quotations, like `"Hello!"`
- one without the quotations, and are numbers, like `"123"`

And their data types are called **string** and **number**.

| Data Type | Definition               | Example            |                               |
| --------- | ------------------------ | ------------------ | ----------------------------- |
| string    | a sequence of characters | "Hello, World!"    | Wrapped in quotation (' or ") |
| number    | floating point numbers   | 3.14, 100, 100,000 | Does not require quotation    |

There are other data types, but for now, we are going to use string and number.

## Hands On: Playing with String and Number

Alright, it's time for hands on practice.

It's when we put in the effort to practice that we learn the most.

Let's print out your name to the console. Your name is a sequence of characters, so we are going to use **string** as our data type.

Once that's done, let's do some math. This time, multiplication. JavaScript uses the asterisk `*` for the multiplication operator.

Ok, following are the code we could write:

```js
console.log("Rikuya Osawa");
```

```js
console.log(10 * 10);
```

Each will output the data corresponding to their data types.

If you forget what `console.log` does, it just prints out the output data to the place called console, in order for programmers to debug (finding and fixing bugs), log (leave record for processes), and sometimes to test things out.

### What happens for strings without quotations?

What happens if you forget to wrap the words with quotations?

```js
console.log(hello);
```

You will most likely encounter this error message:

```
Uncaught ReferenceError: ... is not defined
```

Computer is complaining that it has not reference to whatever we wrote without the quotations.

This is because the computer thinks they are dealing with something called a **variable**. It is a box where you can store pretty much any kind of data.

It is the next topic we shall look at next.

## Recap

Congrats! You've done it.

There are a lot of new concepts to understand when starting out on any new endeavor. It is completely normal.

What we have been discussing is at the core and foundation of almost every modern programming languages, so you will encounter these very often.

Let's review the data type we looked at today.

| Data Type | Definition               | Example            |                               |
| --------- | ------------------------ | ------------------ | ----------------------------- |
| string    | a sequence of characters | "Hello, World!"    | Wrapped in quotation (' or ") |
| number    | floating point numbers   | 3.14, 100, 100,000 | Does not require quotation    |

There are other data types such as `boolean` and `object`, both of which are very important, and we shall talk about them later on.
