# Kubernetes NGINX Ingress Controller

A hands-on Kubernetes implementation demonstrating how the NGINX Ingress Controller manages external application traffic and routes requests to Kubernetes services.

## What this project demonstrates

- NGINX Ingress Controller deployment
- Kubernetes Ingress resources
- HTTP/HTTPS routing
- Host- and path-based routing
- Service exposure through Ingress
- External-to-internal application traffic flow
- Kubernetes networking concepts

## Traffic Flow

Client
  ↓
NGINX Ingress Controller
  ↓
Ingress Rules
  ↓
Kubernetes Service
  ↓
Application Pods
