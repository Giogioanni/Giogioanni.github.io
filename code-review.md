---
layout: default
title: "Code Review"
---
<h2>
  <a href="https://youtu.be/0wX5Hiijl7Q" target="_blank" rel="noopener noreferrer">
    Informal Code Review Video
  </a>
</h2>


A code review is a structured walkthrough of some code to confirm it meets a certain set of requirements and quality standards; such as readability, correctness, maintainability, security, and test coverage. It is super important for computer science professionals like myself because it helps us catch defects early, reduce future maintenance costs, improve the consistency of the codebase, and supports knowledge-sharing among the team. Some best practices include using a checklist approach, reviewing small and focused changes when I can, verifying tests that cover the key behaviors and even edge cases, and checking for security issues. Code reviews should happen before merging into the main branch; this makes sure the review is efficient and focuses on clarity, design, and risk rather than any basic build features. Even in my own capstone artifact (Appointment Service), my approach is practical because the project already has passing unit tests which allows for my code review to focus on quality findings and on the enhancement plan rather than troubleshooting.
I am using Clipchamp for recording my screen and narration. My complete approach to this review is to make a clear, rubric-aligned structure for each category. 1 being describing the existing functionality, 2 being to analyze weaknesses/limitations/vulnerabilities using the criteria of structure, logic, efficiency, security, testing, and documentation. 3 is being able to explain the practical enhancements that can be made that are tied to the course outcomes. In the SD&E part I will walk through the Appointment record validation and the service layer’s add/get/delete workflow, then talk about the design and security-related improvements. In the Algorithms and Data structures  section I will talk about the HashMap and how it supports efficient ID-based operations and bring forth enhancements that add support for date-based queries and sorting while talking about the trade-offs. In the databases section I will talk about the current solution right now is in-memory only and outline a plan to add persistence using a database, repository layer, and secure query practices. I will also update the status checkpoints table to reflect that my baseline unit tests base and my detailed outline for the code review there is complete.




References that I used to help me in my code review plan.

Farah, D. (2025, June 17). The code review checklist that actually helps. Appfire.
https://appfire.com/resources/blog/code-review-checklist

Atlassian. (n.d.). What are code reviews and how they actually save time.
https://www.atlassian.com/agile/software-development/code-reviews


