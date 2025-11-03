# Set Up CI/CD Pipeline using GitHub Actions

## Objective
Automate testing and deployment using GitHub Actions on every push to the main branch.

## Steps
1. Create `.github/workflows/main.yml` in your repository.
2. Push code to the `main` branch to trigger the workflow.
3. The pipeline will:
   - Install dependencies
   - Run tests
   - Build the project
   - Deploy to GitHub Pages (if configured)

## Expected Output
Automatic workflow execution  
Tests and builds on each push  
Deployment shown under the **Actions** tab
