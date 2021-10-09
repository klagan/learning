## Introduction

The Kubernetes cluster hosts, manages and orchestrates the REST microservices eg. self healing, scaling, rolling updates.

This can be replaced with a traditional and lower cost web application with application service plan depending on requirements.

## Security

The cluster is exposed to the public internet through an ingress controller. To prevent direct access from consumers and bypassing both Front door and the APIM we must protect it with a mutual TLS certificate against the APIM.