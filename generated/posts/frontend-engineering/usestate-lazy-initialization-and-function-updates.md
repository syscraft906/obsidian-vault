---
uid: 405
source: "[[Kent C Dodds]]"
author: "[[Unknown]]"
date: 2020-08-03
tags: [react, state management, useState, functional components, hooks, performance optimization]
category: Frontend Engineering
url: https://kentcdodds.com/blog/use-state-lazy-initialization-and-function-updates
status: "\U0001F331 Seedling"
---

# useState lazy initialization and function updates

## AI Summary
The blog explains two techniques for optimizing React's useState hook: lazy initialization to defer expensive computations until first render and function updates for setState to handle relative state changes. It details how passing a function to useState avoids recalculating initial values on every render, while using functions in setState ensures reliable access to the most recent state during updates. These patterns are crucial for managing performance and state consistency in React functional components.

## Topics
- [[react]]
- [[state management]]
- [[useState]]
- [[functional components]]
- [[hooks]]
- [[performance optimization]]

## Source
- Blog: [[Kent C Dodds]]
- Author: [[Unknown]]
- Original: [Read Full Post](https://kentcdodds.com/blog/use-state-lazy-initialization-and-function-updates)
