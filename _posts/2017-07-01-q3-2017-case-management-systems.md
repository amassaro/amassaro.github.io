---
layout: post
title: "Q3 2017: Case Management Systems"
tags: [csharp case-management quarterly-recap]
comments: false
---

Summer brings a new project area: case management.

## Case Management

I've started work on a case management system. These systems are all about tracking workflows - items move through stages, require approvals, have associated documents, and need audit trails. It's a common pattern in business software but getting the details right requires careful thought.

## Workflow Complexity

The interesting challenge with case management is handling the edge cases (pun intended). What happens when a case needs to go backwards? What about parallel approvals? How do you handle exceptions to the normal flow? The happy path is easy; it's everything else that makes it interesting.

## Go Project Updates

On the side, the Go-based fish reporting project continues to receive occasional updates. It's become a reliable little tool for its intended purpose.
