# Architectural Decision Record: Backend Language

**Status**

Accepted

**Context**

In order to implement the server-side logic and APIs needed for the food ordering app, the team must choose a backend language.

**Decision**

We have decided to build the food ordering app's backend using Node.js, its features make it ideal for managing asynchronous tasks like push notifications and real-time updates. It offers a vast ecosystem of frameworks and libraries, promoting scalability and quick development.

**Consequences**

By selecting Node.js, we can leverage JavaScript on the client and server sides, which speeds up development and guarantees consistency. In situations with high traffic, we need to manage the number of simultaneous tasks and resource usage to prevent performance bottlenecks. Furthermore, the event-driven architecture of Node.js fits in nicely with the asynchronous nature of our app's real-time features.

