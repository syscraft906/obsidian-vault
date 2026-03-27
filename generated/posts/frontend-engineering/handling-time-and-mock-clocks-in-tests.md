---
uid: 323
source: "[[Angular Blog]]"
author: "[[Andrew Scott]]"
date: 2025-11-07
tags: [testing, asynchronous programming, javascript, mock clocks, test automation, jasmine, sinon, unit testing]
category: Frontend Engineering
url: https://blog.angular.dev/handling-time-and-mock-clocks-in-tests-5a393b32dd30?source=rss----447683c3d9a3---4
status: "\U0001F331 Seedling"
---

# Handling Time and Mock Clocks in Tests

## AI Summary
The blog discusses challenges with mock clocks in testing asynchronous code, such as fake date management, speed-up time for timeouts/debounces, and preventing timer leaks. It critiques pitfalls like manual time ticking leading to arbitrary delays and brittle tests. The author proposes auto-advancing mock clocks (available in Jasmine v5.7 and Sinon) to realistically simulate time progress without manual intervention, improving test reliability and reducing framework dependencies.

## Topics
- [[testing]]
- [[asynchronous programming]]
- [[javascript]]
- [[mock clocks]]
- [[test automation]]
- [[jasmine]]
- [[sinon]]
- [[unit testing]]

## Source
- Blog: [[Angular Blog]]
- Author: [[Andrew Scott]]
- Original: [Read Full Post](https://blog.angular.dev/handling-time-and-mock-clocks-in-tests-5a393b32dd30?source=rss----447683c3d9a3---4)
