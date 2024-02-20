# Architectural Decision Record: Data Storage

**Status**

Accepted

**Context**

The data storage solution for storing user information, order histories, restaurant menus, and app settings must be chosen by the team.

**Decision**

We decided to use both relational databases like PostgreSQL and NoSQL databases like MongoDB together for the food ordering app. Relational databases will store organized data like user accounts and orders because they're reliable and can handle complex questions. NoSQL databases will handle flexible data like user reviews and menus, giving us more freedom and room to grow.

**Conesequences**

We may leverage the greatest features of both NoSQL and relational databases to meet various app requirements by combining them. To maintain consistency and security, we must ensure that the data is properly synchronized and organized. To protect consumers' private information and adhere to privacy rules, we also need to encrypt data and restrict who can view it.

