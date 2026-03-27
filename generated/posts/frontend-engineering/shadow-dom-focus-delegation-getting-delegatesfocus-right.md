---
uid: 308
source: "[[Frontend Masters]]"
author: "[[Rob Levin]]"
date: 2026-03-24
tags: [shadow dom, web components, focus management, lit, accessibility, javascript, css]
category: Frontend Engineering
url: https://frontendmasters.com/blog/shadow-dom-focus-delegation-getting-delegatesfocus-right/
status: "\U0001F331 Seedling"
---

# Shadow DOM Focus Delegation: Getting delegatesFocus Right

## AI Summary
This post explains how to use the `delegatesFocus` feature in Shadow DOM to simplify focus management for web components. It details three key benefits: automatic focus delegation to internal elements on host clicks, consistent `:focus` styling via CSS, and preventing 'stranded focus' for accessibility. The article includes practical examples using LitElement, guidelines for when to enable `delegatesFocus` (simple wrappers like buttons/inputs) versus when to avoid it (complex components with custom focus logic), and implementation tips for AgnosticUI components. It also highlights common pitfalls like avoiding `tabindex` on the host element.

## Topics
- [[shadow dom]]
- [[web components]]
- [[focus management]]
- [[lit]]
- [[accessibility]]
- [[javascript]]
- [[css]]

## Source
- Blog: [[Frontend Masters]]
- Author: [[Rob Levin]]
- Original: [Read Full Post](https://frontendmasters.com/blog/shadow-dom-focus-delegation-getting-delegatesfocus-right/)
