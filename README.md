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

## Key Concepts

- Ingress vs Service
- Layer 7 HTTP routing
- Host-based routing
- Path-based routing
- TLS termination
- Kubernetes service discovery
- Controller-based reconciliation

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
