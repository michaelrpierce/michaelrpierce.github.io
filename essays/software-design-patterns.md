---
layout: essay
type: essay
title: Software Design Patterns
date: 2021-04-29
labels:
  - Software Engineering
  - Software Design Patterns
  - Meteor
---

## The Wheel

There is a very good chance that you are familiar with or have heard the expression "don't reinvent the wheel." This 
expression has been passed from one to another to warn others about wasting time and effort to create a solution to a
task when that solution already exists. Why spend uneccessary time and effort attempting to drag your cart full of 
goods down the road when the wheel already exists. This piece of advice hold true when considering software design.
Since the many decades that it has been around, software developers have noticed many reoccurring problems that present
themselves when designing software. Thankfully these developers came up with design solutions that could be reused when
these problems resurfaced again in the future and shared these solutions with the rest of us. They gave us our software
design wheels.

## The Ocean

Just like the wheel, however, it is important to understand when it is appropriate to use a software design pattern and
when it is applicable. A wheel isn't going to help you if you need to carry your goods accross the ocean, and a boat 
isn't going to get you to the top of Everest. Just like how a wheel is designed to travel along a road, it is important
to realize that software design patterns are intended to solve specific problems, and there are benefits and trade-offs
to each. 

While I will not going to list all of the specific design patterns here (the [Wikipedia](https://en.wikipedia.org/wiki/Software_design_pattern) page on software design patterns 
is a good start for further research on specific patterns), I will provide a brief example of a few software design 
patterns. The consensus is that the many software design patterns fall into one of three archetypes: creational, 
behavioural, and structural.

### Many Different Fish in the Sea

#### Creational

The creational design pattern can be described as how to create objects. One example is the singleton design pattern.
This is a very straightforward design that allows only one instance of a class to be created. Over this past semester
I have been utilizing this design pattern when using MongoDB collections with Bowfolios, which implements this design
pattern by constructing a single collection instance to provide the rest of the application with information from the
database. 


#### Behavioural

The structural design pattern can be described as how to manage interactions between objects. One example is the 
publish/subscribe design pattern. This design pattern is fundamental to the way in which data is shared within the 
Meteor API. The MongoDB collections are published and pages can subscribe to individual publications as necessary to 
load relevant information to create the web page.

#### Structural

The structural design pattern can be described as how to represent a collection of objects. With Meteor I have been 
using a Front Controller design (specifically the FlowRouter package) with Bowfolios to handle and process requests.
The Front Controller design can process tasks such as authentication, authorization, and logging before passing the
request to the appropriate handlers. 

## Training Wheels

Over the course of and prior to this last semester I have been encountering a variety of these design problems and 
appropriate design patterns used to solve them. They have served as excellent tools to guide me throughout the 
learning process and in many problem solving scenarios without even fully realizing it. Looking forward, I am excited
to experience and implement more of these design patterns to better grow as a more solid and well-rounded software 
developer.
