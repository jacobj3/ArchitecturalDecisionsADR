# Architectural Decision Record: Native, Web, or Hybrid App

**Status**


Accepted

**Context**


Considering the requirements of the food ordering app, such as location-based services, real-time order tracking, and a seamless user experience, the team must choose between native, web, or hybrid app development.

**Decision**


For the food ordering service, we've made the decision to create a native mobile app as it offers the best user experience, performance, and device feature integration. Through the use of platform-specific APIs, we can guarantee the best possible usability and functionality for location tracking, real-time updates, and push notifications.

**Consequences**


Creating native apps may result in longer development times and higher development costs since separate codebases are needed for the iOS and Android platforms. Concurrently, we can achieve a better user experience, smoother integration with device features, and increased performance. We can also offer offline support with a native app, which is essential for users who are in places with limited connectivity.







