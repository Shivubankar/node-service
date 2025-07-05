# node-service
A basic Node.js microservice with Docker and Kubernetes support
# Node.js Microservice (Kubernetes + AWS + CI/CD)

This is a basic Node.js Express microservice with a `/health` endpoint.  
The app is containerized with Docker and deployed using Kubernetes on AWS EKS.  
CI/CD is configured via GitHub Actions to build and deploy automatically.

---

## 🚀 Endpoint

- `GET /health` → Returns `{"status": "OK"}`

---

## 🧪 Run Locally

```bash
# Install dependencies
npm install

# Run the app
node index.js

# Access in browser or curl:
curl http://localhost:3000/health
