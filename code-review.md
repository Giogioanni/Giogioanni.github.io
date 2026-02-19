---
layout: default
title: "Code Review"
---

## Informal Code Review Video
[Watch the video on YouTube](https://youtu.be/0wX5Hiijl7Q){:target="_blank" rel="noopener noreferrer"}

## Summary
A code review is a structured walkthrough of code to confirm it meets quality standards such as readability, correctness, maintainability, security, and test coverage. It is important because it helps catch defects early, reduces future maintenance costs, improves consistency across the codebase, and supports knowledge-sharing.

## Best Practices I Used
Some key best practices I followed include using a checklist, reviewing against requirements, verifying test coverage for key behaviors and edge cases, and checking for security risks. Code reviews should happen before merging into the main branch so the review focuses on clarity, design decisions, and risk.

## My Approach for This Artifact (Appointment Service)
I recorded the walkthrough using Clipchamp and organized the review around the CS499 rubric categories:

- **Software Design & Engineering:** I explain the Appointment validation and the service layer workflow (add/get/delete), then identify design, documentation, and security-related improvements.
- **Algorithms & Data Structures:** I discuss the HashMap approach for efficient ID-based operations and propose enhancements for date-based queries and sorting, including trade-offs.
- **Databases:** I explain that the baseline version is in-memory and outline the plan to add persistence using SQLite, a repository layer, and safe data access practices.

## References
Farah, D. (2025, June 17). *The code review checklist that actually helps*. Appfire. https://appfire.com/resources/blog/code-review-checklist

Atlassian. (n.d.). *What are code reviews and how they actually save time*. https://www.atlassian.com/agile/software-development/code-reviews
