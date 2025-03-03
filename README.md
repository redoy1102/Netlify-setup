# Netlify Setup Guide
This repository contains a Tailwind CSS project configured for Netlify deployment.
## Deployment Configuration
Use the following settings when deploying this project on Netlify:
### Base directory
Leave this blank (root directory of the repository)
### Build command
npx tailwindcss -i ./src/input.css -o ./src/output.css
### Publish directory
src
