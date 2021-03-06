---
title: "Implementing a Voice Memo Application"
slug: implementing-a-voice-memo-application
---

Before we jump into creating our app, lets flesh out the components of our voice memo app.

We will need the following models:

- Memo
  - title
  - time
  - voice_file
  - text_body
  - belongs to a user (Relationship)

- User
  - name
  - email
  - password
  - has many memos (Relationship)

## The Entity Relation Diagram

![User Memo ERD](assets/user-memo-erd.png)
