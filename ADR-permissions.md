# Architectural Decision Record: Permissions

**Status**

Accepted

**Context**

To gain access to device features and data, the team must specify the permissions that the mobile app requires.


**Decision**

We'll set up a permission system that only asks users for the permissions the app requires in order for the app to work. For example, to give accurate restaurant suggestions and delivery times, we'll ask for access to the device's location and to keep user info safe, we'll follow the rules for getting and managing permissions set by each platform.

**Consequences**

We ensure users' privacy and security first by implementing a thorough permission system, which contributes to customer trust. However, in order to gain users' consent, we also need to make sure that we make it apparent to them why we require each permission. Furthermore, we must properly manage permissions and allow users to modify their preferences at any time.
