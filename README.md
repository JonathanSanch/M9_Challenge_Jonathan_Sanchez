# OAuth-Security-Implementation-for-Java-Spring-API



## Module Challenge: Record Store API Secured

### Overview

Starter code: [./starter](./starter)

In this challenge, you willen force authentication of an API via OAuth.

### Goals

The goal of this challenge is to reinforce your knowledge of OAuth.

Specifically, you'll do the following:

1. Create an Authorization Server which will facilitate authentication via OAuth.

2. Refactor the provided Record Store API application to enforce authentication accordingly.

### Instructions


- Using the techniques described in class, create an Authorization Server which will facilitate OAuth authentication for the provided Record Store API application.

- For the Authorization server, create a few user accounts for testing purposes.

- Refactor the provided Record Store API starter project such that the controller enforces authentication via OAuth for all Record Store API routes.

---

- Using Insomnia, verify the following:

- An unauthenticated client is unable to access any of the API routes.

- An authenticated OAuth client is able to access all routes, including `GET`, `PUT` and `DELETE` operations.

© 2023 2U. All Rights Reserved.
