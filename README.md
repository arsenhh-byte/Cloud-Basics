
# DevOps Bootcamp Exercise: NodeJS Deployment on DigitalOcean

## Overview
This document outlines the steps for setting up, deploying, and managing a NodeJS application on a DigitalOcean droplet.

## Steps
1. **Clone Git Repository:** Cloned the provided Git repository and created a new personal project repository from it.
2. **Package NodeJS App:** Used `npm pack` to package the Node app into a single tar file.
3. **Create a New Server:** I set up a new droplet server on DigitalOcean.
4. **Prepare Server:** Installed Node.js and npm on the new droplet to prepare it for running the Node app.
5. **Copy App:** Transfered the packaged NodeJS app to the prepared droplet.
6. **Run Node App:** Started the Node application in detached mode using `npm install` followed by `node server.js`.
7. **Configure Firewall:** Opened the necessary port on the droplet to make the application accessible through a web browser.

## Conclusion
This exercise covers the end-to-end process of deploying a NodeJS application on a cloud server, ensuring each step is documented for smooth setup and execution.

--- 

