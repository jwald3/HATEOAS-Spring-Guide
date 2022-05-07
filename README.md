# HATEOAS Spring Guide
Work-through of the HATEOAS fully-RESTful tutorial found on the official Spring website at https://spring.io/guides/tutorials/rest/

This repository is based on the Building REST services with Spring tutorial. The repository includes a pair of fully RESTful API resources with HATEOAS principles applied where each endpoint hosts links for easy navigation, reference, and interactions with individual or all resources.

Most notably, the Order resource leverages HATEOAS structure to provide links to endpoints that allow the order details to be modified through HTTP requests. Orders with the status "IN_PROGRESS" include links to cancel or complete the order while orders that are "CANCELLED" or "COMPLETED" only reference themselves and the resource root.
