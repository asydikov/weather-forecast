# Internal Development Portals
## The Hype:
Right now, Internal Development Portals (IDPs) are the hotness. They are garnering more hype than NFTs. They've been called the next Kubernetes. Like Kubernetes, IDP's value isn't immediatly obvious, but like Kubernetes, theres a likelyhood this can change.
## What is an IDP?
From devops.com:
"_An internal developer portal is a self-service application and data store that lets developers and managers track and organize everything their engineering teams build and operate._"
from configure8.com:
"_An Internal Developer Portal is a self-service application and data store that lets developers and managers track and organize everything their engineering teams build and operate._"
from humanitec.com:
"_An Internal Developer Platform, or IDP, is a self-service layer that allows developers to interact independently with their organization’s delivery setup, enabling them to self-serve environments, deployments, databases, logs and anything else they need to run their applications._"
from [medium.com](https://medium.com/nationwide-technology/api-developer-portal-the-what-the-why-and-the-how-3222a5c7a824):
"_In simple terms, a developer portal is an interface that bridges the gap between the consumers and the provider of a set of APIs. It usually consists of a website that enables developers to discover and explore the APIs, find out how to use them, get access to help and support, and potentially also test out the APIs in a sandbox environment._"
## ELI5?
An IDP is a hub for all the things that a dev needs, be it CI/CD info, service status, API Documentation, metrics, provisioning etc.
## Doesn't RedGate already have all that?
In most teams, we do! Not quite in the consistent and discoverable manner that an IDP would give us, but we should still be very proud.
## What options are there?
### [backstage](https://backstage.io/)
Backstage was created at Spotify for internal use and then opensourced and has quickly become the defacto standard. Many vendors (such as [roadie](https://roadie.io/)) offering IDP packages are built upon backstage. Due to its prevelance, most resources on the web talking about IDPs are talking about backstage. Backstage strong points are microservice management and infrastructure orchestration with some interesting documentation tooling.
### [humanitec](https://humanitec.com/)
Humanitec seems to be more devops orientated than backstage calling itself an "Internal Developer Platform", mostly concentrating on RBACs and infrastructure orchestration. Info is more limited but hopefully our call with them on Wednesday will give more clarity.
## What are the benefits of Backstage?
### Software Catalog
"for managing all your software (microservices, libraries, data pipelines, websites, ML models, etc.)"
### Backstage Software Templates
"for quickly spinning up new projects and standardizing your tooling with your organization’s best practices"
### TechDocs
"for making it easy to create, maintain, find, and use technical documentation, using a "docs like code" approach"