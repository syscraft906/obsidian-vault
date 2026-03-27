---
uid: 416
source: "[[Kent C Dodds]]"
author: "[[Unknown]]"
date: 2020-06-03
tags: [testing, api, javascript, software development, mocking, test reliability, api testing]
category: Frontend Engineering
url: https://kentcdodds.com/blog/stop-mocking-fetch
status: "\U0001F331 Seedling"
---

# Stop mocking fetch

## AI Summary
This post argues against mocking HTTP requests like fetch in tests, highlighting how it leads to fragile tests, technical debt, and false confidence. It explains that mocking APIs creates artificial isolation that breaks real-world dependencies. The article advocates for using real HTTP calls with controlled environments or API mocking libraries like MSW (Mock Service Worker) to maintain test accuracy while improving maintainability and developer experience.

## Topics
- [[testing]]
- [[api]]
- [[javascript]]
- [[software development]]
- [[mocking]]
- [[test reliability]]
- [[api testing]]

## Source
- Blog: [[Kent C Dodds]]
- Author: [[Unknown]]
- Original: [Read Full Post](https://kentcdodds.com/blog/stop-mocking-fetch)
