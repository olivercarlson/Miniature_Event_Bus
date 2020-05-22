# Miniature Event Bus

### Purpose:

The purpose of this project is to demonstrate and understand the process of event based communication between microservices.

Project consists two distinct parts: a tiny create-react-app client and a microservices backend of 5 NodeJS servers
with simple I/O routes that all create and respond to events. Posts are stored in memory (must refresh the page to load new content, AJAX on client is only done on mount)


Current version allows starting of Kubernetes clusters with skaffold. Pull images from docker hub, configure skaffold and 
```skaffold dev```
