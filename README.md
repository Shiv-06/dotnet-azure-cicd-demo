# .NET + Azure CI/CD Demo

This repo demonstrates a basic CI/CD workflow for a .NET Core application using **GitHub Actions** and **Docker**.

## 🧠 Tech Stack

- C#, .NET Core
- Docker
- GitHub Actions
- (Conceptually) Azure App Service / Azure Container Registry

## ✨ What It Shows

- Dockerfile for building a .NET Core app image  
- GitHub Actions workflow that:
  - Restores dependencies  
  - Builds the project  
  - Runs tests (if added)  

## Future Enhancements

- Push container image to Azure Container Registry  
- Deploy automatically to Azure Web App or AKS
