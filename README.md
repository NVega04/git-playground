# Git Playground

## Description
A practice repository used to learn and apply Git workflows, including branching strategies, commits, and pull requests, following a develop-based collaboration model.

## Getting Started

### Prerequisites
- Git installed
- Node.js (if applicable to this project)

### Installation
1. Clone the repository:
```bash
   git clone https://github.com/NVega04/git-playground.git
```
2. Navigate into the project folder:
```bash
   cd git-playground
```
3. Install dependencies (if any):
```bash
   npm install
```
## Branching Strategy
- `develop`: main integration branch where all features are merged
- `feature/*`: individual branches for each assigned functionality (e.g. `feature/login`, `feature/registro`, `feature/readme`)

## Contributing
1. Create your feature branch from `develop`:
```bash
   git checkout develop
   git pull origin develop
   git checkout -b feature/your-feature-name
```
2. Make your changes and commit them with clear, descriptive messages.
3. Push your branch and open a pull request targeting `develop`.

## License
See the [LICENCE](./LICENCE) file for details.

## Project Status
This project is part of a practice exercise to simulate a collaborative Git workflow using Gitflow and Conventional Commits.