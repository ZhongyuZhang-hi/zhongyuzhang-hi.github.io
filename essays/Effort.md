---
layout: essay
type: essay
title: "Effort Estimation"
# All dates must be YYYY-MM-DD format!
date: 2025-05-08
published: true
labels:
  - Programming
  - Team Project
  - Github
---
<img src="../img/essays/puzzle.jpg">

*"Don't write a new program if one already does more or less what you want."* ― Richard Hill

## The Factory Floor of Code
Imagine walking into a bustling factory in the early 20th century. Workers assemble machines not by handcrafting every bolt and gear, but by slotting in standardized, interchangeable parts. A piston from one engine fits perfectly into another. A gear from a textile machine can be repurposed for a locomotive. This revolution in manufacturing didn’t just speed up production, it made systems more reliable, maintainable, and scalable.

Software design patterns are the interchangeable parts of programming. Just like a factory worker doesn't craft a new wheel for every car, a programmer doesn't rewrite code for problems that already have proven solutions. Whether it’s sorting data or managing object creation, these patterns provide reliable, tested components we can plug into place.

## The Power of Interchangeability
The beauty of design patterns lies in their universality and flexibility. Just like factory parts designed to solve a specific mechanical task, each design pattern is crafted to address a common software problem in a reusable way. Because these patterns focus on solving one problem well, they can often be swapped out or repurposed for slightly different use cases with minimal changes. This is especially helpful when maintaining or extending code in larger projects.

In ICS 314, I experienced this firsthand with Next.js-based applications. The layout, form submission, and database interaction components followed patterns that I could reuse and slightly modify across different pages or features. For instance, the code for adding a new record to database through a form used a consistent design: form validation, submission handling, and backend route calling. Once I understood the pattern, creating a component for another type of record is much easier than starting from scratch, I was just adapting a known mechanism to a new task.

This interchangeability also made collaboration smoother. When working on team projects or code reviews, we could quickly understand each other’s contributions because the structure and logic followed familiar patterns. Instead of puzzling through custom logic each time, we were all speaking the same architectural language.

## Conclusion
Software design patterns are the industrial revolution of programming. They turn the craft of coding into scalable engineering. By standing on the shoulders of these reusable solutions, we can spend less time solving solved problems and instead push for further changes and better solutions.

- ChatGPT is used to assist in writing this essay only in word choice, spelling, and grammar.

