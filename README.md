# Docker_compress_techniques
# Docker Image Optimization Techniques for Spring Boot Applications

This repository demonstrates different techniques to optimize Docker image size for a Spring Boot application. The goal is to build the same application using multiple Docker strategies and compare their resulting image sizes and benefits.

---

## 📌 Project Overview

We are using a simple Spring Boot application to explore the impact of different Dockerfile strategies on the final image size. This helps improve:

- **Startup time**
- **Security (smaller attack surface)**
- **Faster deployments**
- **Lower storage and transfer costs**

---

## 📊 Image Size Comparison

| Approach         | Image Size |
|------------------|------------|
| Default Dockerfile (fat JAR) | ~431 MB     |
| Distroless Image           | ~246 MB     |
| Multi-stage Build          | ~200 MB     |

---
