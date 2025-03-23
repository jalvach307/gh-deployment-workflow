# -gh-deployment-workflow
 gh-deployment-workflow


https://roadmap.sh/projects/github-actions-deployment-workflow

Requirements
You are required to write a GitHub action that deploys any changes made to the index.html file to GitHub Pages. It should only deploy the file when the index.html file is changed.

Here are the steps to get you started:

Create a GitHub repository for the project called gh-deployment-workflow for example.
Repository should contain a simple index.html file saying “Hello, GitHub Actions!”
It should also have a README.md file explaining the project.
There should also be a deploy.yml file in the .github/workflows directory which contains the GitHub Actions workflow to deploy the website to GitHub Pages.
Every push to the main branch that changes the index.html file should trigger the workflow to run and deploy the website to GitHub Pages.
Website and any changes you make should be accessible at the GitHub pages URL for the repository e.g. https://<username>.github.io/gh-deployment-workflow/.
Stretch goal: You can also make this project more practical e.g. use some sort of a static site generator such as Hugo, Jekyll, Astro or similar generator to create a more complex website e.g. your own personal portfolio.



# GitHub Actions Deployment Workflow

This project demonstrates how to automatically deploy a website using GitHub Actions and GitHub Pages.

## Setup
1. Every push to the `main` branch that modifies `index.html` will trigger a deployment.
2. The website will be available at:

https://jalvach307.github.io/gh-deployment-workflow/

