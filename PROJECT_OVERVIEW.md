# Project Overview

## Core Purpose
The purpose of MiroFish is to provide an efficient and user-friendly platform for managing and visualizing data related to marine life and ecosystems. The platform aims to facilitate research, education, and conservation efforts by providing tools for data analysis and visualization.

## Vision
MiroFish envisions a world where data-driven insights lead to better understanding and protection of marine ecosystems. Through our platform, we aim to empower researchers, educational institutions, and conservation organizations with the tools they need to make informed decisions.

## Technology Stack
- **Frontend**: React.js, Redux, CSS, HTML
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Deployment**: Docker, AWS
- **Version Control**: Git, GitHub

## Project Structure
```
MiroFish/
├── client/            # Frontend code
│   ├── src/          # React components
│   ├── public/       # Static files
│   └── package.json   # Frontend dependencies
├── server/            # Backend code
│   ├── models/       # Database models
│   ├── routes/       # API routes
│   └── package.json   # Backend dependencies
└── README.md          # Project documentation
```

## Workflow
1. **Development**: Developers work on separate branches and use pull requests to integrate changes.
2. **Testing**: Each pull request triggers automated tests to ensure code quality.
3. **Deployment**: Successfully merged branches are deployed to the production environment.

## Deployment Instructions
1. Clone the repository: `git clone https://github.com/hatthoclangta/MiroFish.git`
2. Navigate to the server directory: `cd MiroFish/server`
3. Install dependencies: `npm install`
4. Start the server: `node index.js`
5. Navigate to the client directory: `cd ../client`
6. Install dependencies: `npm install`
7. Start the client: `npm start`

## Background Information
MiroFish is developed in response to the growing need for effective marine data management tools. With the increasing pressures on marine ecosystems, there's a critical need for easy access to data and insights that can drive better policies and conservation strategies. We believe that MiroFish will contribute significantly to this goal by bringing state-of-the-art tools to a diverse user base.