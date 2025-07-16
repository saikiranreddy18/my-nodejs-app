
# My Node.js CI/CD Project
A simple Node.js Express app with a Jenkins CI/CD pipeline.

## Setup
1. Clone the repo: \`git clone https://github.com/<your-username>/my-nodejs-app.git\`
2. Install dependencies: \`npm install\`
3. Run locally: \`npm start\`
4. Run tests: \`npm test\`

## Jenkins Pipeline
- Checks out code from Git.
- Installs dependencies, runs tests, builds, and pushes a Docker image.
- Requires Docker Hub credentials in Jenkins.

## Run Docker Image
\`\`\`bash
docker run -p 3000:3000 <your-dockerhub-username>/my-nodejs-app:<tag>
\`\`\`
EOT
