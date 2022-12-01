---
layout: essay
type: essay
title: "Haven't I Seen You Somewhere Before?"
# All dates must be YYYY-MM-DD format!
date: 2022-12-1
published: true
labels:
- Software Engineering
- Design Patterns
- Meteor
---

## Déjà Vu

As you continue doing coding problems and projects, you’ll start to notice recurring techniques that you use. The issues covered may not be related in any way, but the code you implement tends to look similar in structure. These are called design patterns.

Design patterns are reusable solutions on how to solve a common problem when designing an application. It is a template or description on how to approach the problem. These patterns are meant to save time and improve efficiency.

## Application of Design Patterns

The final project for my software engineering class required us to create a working application using Meteor. We started with a basic meteor template and implemented our own changes from there. My group was able to make use of design patterns when designing our web application, [No More Ramen](https://no-more-ramen.github.io/).

#### Observer Design Pattern

This is a behavioral design pattern that defines how to notify objects of changes to other object(s). The pattern consists of two actors: the observer (interested in the updates) and the subject (generates the updates). In the case of our project, this was through the use of subscribers and publishers, which took on the roles of observer and subject respectively. We could subscribe to publications that retrieved data from the MongoDB collections, these also updated the data whenever changes were made. For example, if a student wants to see the recipes available, we would publish the Recipe collection on the server side and then subscribe on the client side so the data can be displayed to the student.

#### Singleton Design Pattern

This is a creational design pattern that restricts object creation for a class to only one instance. In our project, one instance of this pattern comes in the form of recipe table components. Each recipe component is then exported to the Search Recipe page which lists out all the recipes in a table. 

## Design Patterns to the Rescue

Thus, by recognizing these design patterns, we were able to save a lot of time and energy when creating our application. Understanding when and how to apply these patterns is important in software development.

<div class="text-center p-4">
    <img width="300px" img class="img-fluid" src="../img/design-patterns/spongebob.jfif">
</div>