# GitHub Actions CI/CD Pipeline – Tech Quiz App

## Description

This project demonstrates a full-stack web application integrated with a GitHub Actions CI/CD pipeline. It was developed as part of the University of Denver Coding Bootcamp and showcases the use of continuous integration and deployment practices for modern application development.

The application is a multiple-choice quiz platform built using React, TypeScript, Node.js, Express, and MongoDB. GitHub Actions is configured to automatically run Cypress component tests when a pull request is opened to the `develop` branch, and to automatically deploy the latest version to Render when the code is merged into `main`.

This project is for educational purposes and is not intended for further development. As such, contributions will not be reviewed.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [CI/CD Workflow](#cicd-workflow)
- [Deployment](#deployment)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## Installation

To run this application locally:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/lisaj5472/GitHubActions-CICD-Setup.git
   ```

2. **Navigate into the project directory:**

   ```bash
   cd GitHubActions-CICD-Setup
   ```

3. **Install dependencies:**

   ```bash
   npm run install
   ```

4. **Seed the database (optional for local use):**

   ```bash
   npm run build
   npm run seed
   ```

5. **Start the development servers:**

   ```bash
   npm run develop
   ```

## Usage

Once the app is running:

- Navigate to `http://localhost:5173` in your browser.
- Click **Start Quiz** to begin.
- Select answers to multiple-choice questions and view your score upon completion.

## Technologies Used

- React
- TypeScript
- Node.js
- Express
- MongoDB Atlas
- Vite
- Cypress
- GitHub Actions

## Features

- Full-stack quiz application with real-time scoring
- Modular React components with hooks
- Cypress component testing
- GitHub Actions CI/CD integration
- Auto-deploy to Render on production merge

## CI/CD Workflow

- A GitHub Action runs Cypress component tests automatically whenever a pull request is made to the `develop` branch.
- When code is merged from `develop` to `main`, a GitHub Action triggers a deploy hook to Render to publish the updated application.

## Deployment

The live application is deployed via Render and is continuously updated through GitHub Actions.

**Live URL:** [https://githubactions-cicd-setup.onrender.com](https://githubactions-cicd-setup.onrender.com)

## Acknowledgements

This project was created using starter files and instruction provided by the **University of Denver Coding Bootcamp**. It follows the requirements of the “19 CI/CD: GitHub Actions CI/CD Setup” challenge.

## Contact

For any questions or feedback, please contact:

- **GitHub**: [lisaj5472](https://github.com/lisaj5472)
- **Email**: lisaj5472@gmail.com
