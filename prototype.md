Meteor.js
- Suitable for prototypes and applications with a limited amount of concurrent users, such as in KMUs.

Advantages:
- Social auth integration
- Minimongo to save data on client --> easy to implement PWAs
- Realtime synchronisation between clients by default
- Easy to define database schema with little boilerplate code
- Easy dockerised deployment to a VPS with meteor-up


Disadvantages:
- Slow build times in hot reload especially with many packages
- Relatively complex to switch framework due to code-sharing
- Hard to separate frontend and backend development due to code-sharing
- Difficulty to deploy frontend to a CDN since integrated with code-sharing
- Scaling could be complex with many concurrent users (untested)
- Only supports mongodb
- Many community packages not supported anymore


Vulcan.js 
- based on Meteor.js
