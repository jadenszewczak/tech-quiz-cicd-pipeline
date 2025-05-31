# Tech Quiz CI/CD Pipeline

## Description

A full-stack MERN quiz application demonstrating modern CI/CD practices with automated testing and deployment pipelines using GitHub Actions.

## Features

- 🧪 Automated Cypress component testing on pull requests
- 🚀 Continuous deployment to Render on merge to main
- 📝 MongoDB integration for question storage
- ⚛️ React-based interactive quiz interface
- 🔄 Automated CI/CD pipeline with GitHub Actions

## Technologies Used

- **Frontend**: React, TypeScript, Vite
- **Backend**: Node.js, Express, MongoDB
- **Testing**: Cypress
- **CI/CD**: GitHub Actions
- **Deployment**: Render
- **Database**: MongoDB Atlas

## Live Application

[View Live App](https://tech-quiz-cicd-pipeline.onrender.com)

## Installation

```bash
git clone https://github.com/jadenszewczak/tech-quiz-cicd-pipeline.git
cd tech-quiz-cicd-pipeline
npm install
```

## Environment Variables

Create a `.env` file in the server directory:

```bash
MONGODB_URI=mongodb+srv://cicdPipelineUser:NrNwKLYyxuWj5gdj@cluster0.apnc6yx.mongodb.net/techquiz?retryWrites=true&w=majority&appName=Cluster0
```

## Usage

```bash
# Development
npm run develop

# Build
npm run build

# Seed database
npm run seed

# Run tests
npm run test-component
```

## CI/CD Pipeline

- **Pull Request to develop**: Triggers automated Cypress component tests
- **Merge to main**: Triggers automatic deployment to Render

## Screenshots

![GitHub Actions Tests](./screenshots/github-actions-tests.png)
![GitHub Actions Deploy](./screenshots/github-actions-deploy.png)
![Live Application](./screenshots/live-app.png)

## Contributing

1. Create a feature branch from `develop`
2. Make your changes
3. Submit a pull request to `develop`
4. Tests will run automatically
5. After approval and merge to `develop`, create PR to `main` for deployment

## License

MIT
