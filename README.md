# Sky Website - DevOps Deployment Pipeline 🚀

[[Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](https://veeraputradorababu2004-ops.github.io/sky-website/)
[[Docker Image](https://img.shields.io/badge/ghcr.io-sky--website-blue?style=for-the-badge&logo=docker)](https://github.com/veeraputradorababu2004-ops/sky-website/pkgs/container/sky-website)
[[CI/CD Status](https://img.shields.io/badge/GitHub_Actions-Passing-success?style=for-the-badge&logo=githubactions)](https://github.com/veeraputradorababu2004-ops/sky-website/actions)

Containerized a static website using Docker + Nginx, automated builds with GitHub Actions CI/CD, and deployed to GitHub Pages + Render.

*🔗 Live Demo*: https://veeraputradorababu2004-ops.github.io/sky-website/

## 🛠️ Tech Stack
- *Containerization*: Docker, Nginx:alpine
- *CI/CD*: GitHub Actions 
- *Registry*: GitHub Container Registry (GHCR)
- *Deployment*: GitHub Pages, Render
- *Version Control*: Git, GitHub

## ⚙️ How CI/CD Works
git push → GitHub Actions triggers → Docker image builds → Push to GHCR.io → Auto-deploy ready

## 📦 Run with Docker
```bash
docker pull ghcr.io/veeraputradorababu2004-ops/sky-website:latest
docker run -d -p 8080:80 ghcr.io/veeraputradorababu2004-ops/sky-website:latest
# Open http://localhost:8080
