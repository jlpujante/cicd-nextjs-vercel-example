# cicd-nextjs-vercel-example

This repository contains a skeleton code and configuration files necessary for deploying a basic Next.js application using an automated CI/CD pipeline in Vercel.

## Folder Structure
- `.github/workflows/:` This directory houses the GitHub Actions workflow files defining the CI/CD pipeline.
- `my-app/:` Contains the main code files for the Next.js application.

  
## Pipeline Overview
The pipeline is triggered by events like code pushes or pull requests. It automatically builds, tests, and deploys the FastAPI application to an instance in Render site. The process includes infrastructure configuration, code deployment, and automated testing.

## Get Started
1. Run locally the server:
```bash
  npm run dev
```
   
Feel free to explore the repository for more details on the pipeline setup and configuration.

