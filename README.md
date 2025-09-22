# Day 1: CI/CD Pipeline Demo

This is a simple Node.js web application demonstrating **CI/CD automation using GitHub Actions and DockerHub**.  

---

## **Project Overview**

- **App**: Minimal Node.js + Express app
- **Dockerized**: Using a Dockerfile
- **CI/CD**: GitHub Actions automatically builds and pushes the Docker image on every push to `main`
- **DockerHub Repository**: `nmiyani/devopsday1`
- **GitHub Repository**: `nmiyani/day1`

---

## **Application Details**

- **Server File**: `server.js`
- **Dependencies**: Express
- **Development Tool**: nodemon (hot reload)
- **Port**: 3000
- **Docker CMD**: `npx nodemon server.js` (runs server inside container)
