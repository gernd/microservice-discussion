## Microservice Architecture Discussion
---
## Pros
---
### Technology Heterogeneity
- best tool for the job can be picked (e.g. different programming language or persistence
  technology)
- service with smallest impact can be chosen for trying out a new technology
---
### Resilience
- monolith: if the backend fails, the result is total system outage
- if one service in the system fails, the error should not cascade
- several instances of a service can be run -> if one fails, the other one takes over
---
### Scaling
- monolith: all or nothing can be scaled
- ms architecture: dedicated services can be scaled depending on their workload
---
## Cons
TODO
---
## Sources 
- TODO Newman Microservice book
- TODO Fowler Blogpost
--- 
## Thanks for discussing!
- https://www.github.com/gernd/microservice-discussion
