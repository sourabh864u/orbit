Project description
---
Create a web app for an issue tracking system. An issue consists of the following basic properties:

1. Title
2. Status
3. Description
4. Severity
5. Assignee
6. DueDate

A user can create a new issue and view it afterwards.

All issues should be persisted somewhere for retrieval.

An issue can be retrieved via a unique URL (e.g. http://www.myissues.com/issue/12345)

Feel free to spend more time on your areas of strengths (UI, Data Model or Server-Side Architecture)

Documentations
---
How to compile and run this project

1) The Project is using .mdf database to store the issues.
2) Please check DBIssueTracing.mdf in App_Data folder.
3) Also make sure the connection string in AccountViewModels.cs    is pointed to right path.
4) Run the project.


Concerns and area of improvement:

1) Validation in not done specially for Date.
2) After submitting the issue the return message show be properly displayed.

