# docker-ci-cd-project
# Docker CI/CD Pipeline using GitHub Actions

## Project Overview

This project demonstrates a complete CI/CD pipeline using GitHub Actions.

Whenever code is pushed to the `main` branch, GitHub Actions automatically:

- Checks out the source code
- Sets up Docker Buildx
- Authenticates to GitHub Container Registry (GHCR)
- Builds a Docker image
- Pushes the image to GHCR using two tags:
  - latest
  - commit SHA

---

## Technologies

- GitHub Actions
- Docker
- GitHub Container Registry (GHCR)
- Node.js

---

## Workflow

Developer Push

↓

GitHub Actions

↓

Docker Build

↓

Push Image to GHCR

---

## Docker Image

ghcr.io/shreo1992/docker-ci-cd-project

---

## Tags

- latest
- Commit SHA

---

## Repository Structure

```text
docker-ci-cd-project/
├── app.js
├── package.json
├── Dockerfile
├── .dockerignore
└── .github/
    └── workflows/
        └── docker-ci-cd.yml
```

## Skills Demonstrated

- CI/CD
- GitHub Actions
- Docker Buildx
- Docker Registry Authentication
- GitHub Packages
- Docker Image Tagging
