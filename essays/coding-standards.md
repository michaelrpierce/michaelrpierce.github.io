---
layout: essay
type: essay
title: Coding Standards
date: 2021-02-11
labels:
  - Coding Standards
  - Programming
  - Research
---

## There is No Right Way to Program, but There Are Many Wrong Ways

One of the first things I was ever told when I began to learn programming techniques was that there was no *one* right
to right a program. There are many ways to implement or complete a task when writing a program and this leads to a wide
variety of outcomes. Whether you are implementing a Stack via a linked list or an array, or printing a tree iteratively
or recursively, each technique has its own merit and can prove useful under different circumstances. However, there is
definitely a wrong way to write a program.

Coding standards should be just like the name describes: standard. Have you ever opened a project only to find
indentation and curly braces to be inconsistently scattered throughout the file? The answer is likely no (unless you
are dealing with beginner programmers or teaching an introduction course). With many modern IDE's having a built-in
option to reformat code, there should be no reason for code to be disorganized.

## Consistency is Key

> Implementing the proper coding standards within the same group/organization can lend to improved readability and efficiency.

> Implementing the proper   coding   standards   withinTheSame   group  /organization   can   lend   to improved   readabilityand   efficiency.

Which of the above sentences was easier to read? What about the following?

```
foo(var) {};
foo(var) { };
foo( var ) {};
foo (var) {};
foo(var) {};
```

Spacing is an example of the importance of coding standards when it comes to the readability of code. Reading is an
integral part of the modern world, and we all learn to grow accustomed to a standard way in which things are written.
Sentences have a single space separating words and end with a period. This allows you to absorb a segment of 
information and relate it to what was previously written. Breaking this standard can lead to issues with readability
and can lend to a lot of wasted time as you scour thousands of lines of code. It doesn't really matter if you write
your functions as **foo(var)** or **foo (var)** as long as you are consistent throughout projects within your group
or organization (at the very least be consistent in the same file). Using tools such as ESLint with the IntelliJ IDE 
has allowed me to personally ensure that the code I am writing is consistent and readable, with almost no effort 
exerted by me at all. Utilize the resources that are available to you to produce more readable code and save time.

 
