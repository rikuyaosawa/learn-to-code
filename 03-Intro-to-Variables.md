# Intro to Variables

Table of Contents

- [Intro to Variables](#intro-to-variables)
  - [Overview](#overview)
  - [Variables](#variables)
    - [Variable in JavaScript](#variable-in-javascript)
  - [Hands On: Your First Variables](#hands-on-your-first-variables)
  - [Recap](#recap)

## Overview

So far we have discussed about what program is, what it can do, and also the types of data there are.

What is a program? It's a set of instruction. For who? Computers. To do what? So that computers can perform a given task.

We got our hands on practice on printing to the console using `console.log`, and played with data types such as `string` and `number`.

## Variables

This time, we are introducing **variables**.

Let's look at the formal definition:

> [!IMPORTANT]
>
> **A variable in programming is a named storage location in memory that holds a value that can change during program execution.**

Computer memory being the storage inside the computer.

One analogy we can use is that a variable is like a labeled box where you can store something, replace it with something else, and retrieve it whenever needed.

---

![Variable as box: analogy](https://miro.medium.com/v2/resize:fit:1400/1*Px7h03Ih7B5QZu4KQpSEoQ.png)

---

As the name suggests, you can also write an instruction to change the content or the `value` of the box.

Variables are powerful because **they let you persist whatever data you want persist.** Imagine you have to throw away all the things you ever bought, instead of storing them somewhere for later use.

### Variable in JavaScript

In JavaScript, there are special **keywords** we write to tell the computer whatever is after the keywords, it is a variable.

- `var` variable keyword - short for variable
- `let` variable keyword
- `const` variable keyword - creates an immutable variable - short for constant

This is essentially **declaring** a variable. Declaring the existence of a variable.

**const keyword**

Sometimes, you want the value of a variable not messed by others or even yourself. We could then use the `const` keyword to make the variable immune to change, or immutable.

**Variable Name**

What follows these keywords is **the name for the variable**, which is decided by the programmer. There are some restrictions though:

- a variable name cannot be already existing special keywords, such as `var`.
- a variable name cannot contain space, so you can't name a variable `my name`. You would instead remove space, and capitalize the second word, like so: `myName`, or `uniformNumber`. This capitalizing of the second word is not a rule, but a convention, meaning it's what everyone uses, called **camel casing**.

> [!NOTE] Other Naming Conventions
>
> Other programming languages have different conventions, such as Python uses **snake casing** that looks like this: `my_name`.

Here's the syntax for creating a variable:

```
[keyword (var | let | const)] [variableName] = [data we want the variable to store]
```

> [!NOTE] The Equal Sign in Programming
>
> The equal sign `=` in programming does not mean `a equals (=) b`. It simply means you are storing the right hand side into the left hand side. Kind of like this:
> `A <= B`. The term for it is called **assignment**. In the example of `A = B`, you are assigning `B` to `A`.

## Hands On: Your First Variables

Let's assign the string `"Hello, World"`, to a variable named `greeting`, using `var` keyword:

```js
var greeting = "Hello, World";
```

You just created your very first variable!

Remember, **a variable is a box that contains some kind of data, or value, we call it.**

Let's create another variable. This variable will store a person's name. What variable name would be appropriate?

name? personName?

Both are alright. Here, we will simply call it `name`.

```js
var name = "Rikuya Osawa";
```

#### Challenge

How about making a variable that stores your favorite number? Like your uniform number.

Don't forget to console log the variables you made to check what they are storing!

## Recap

You did it. The first introduction to the variables.

Let's recap what we learned today:

- a variable is a box where you can store data, or value. The data you store inside a variable persist for it to be used in some way later.
- In JavaScript (the programming language we have been writing code in), variable is created using special keywords, such as:

  - `var`
  - `let`
  - `const`

  We haven't used `let`, and `const` yet.

- The variable name is decided by us, the coder, and they follow a convention called **camel casing** that looks like: `myNumber`, `tastyBanana` where the second word is capitalized.
- The equal sign `=` assigns the right hand side value to the left hand side variable, like: `var myNumber = 10`, where `10` gets stored inside `myNumber`.

<br />

When I started coding, I had a hard time wrapping my head around the concept of variables.

Here, I tried to explain it in the way I wish I was taught. It is still a lot to take in though, so we will learn one step at a time.
