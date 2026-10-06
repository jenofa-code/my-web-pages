# CI/CD Pipeline with GitHub Actions

This project demonstrates a Continuous Integration and Continuous Deployment (CI/CD) pipeline implemented using GitHub Actions.

## Project Structure
- `.github/workflows/main.yml` - Contains the CI/CD pipeline workflow configuration.
- `app.py` - Main application entry point.
- `requirements.txt` - Project dependencies list.

## CI/CD Pipeline Steps
1. **Checkout Code:** Pulls the repository code into the runner.
2. **Set up Python:** Configures Python 3.9 environment.
3. **Install Dependencies:** Installs required packages listed in `requirements.txt`.
4. **Run Tests:** Runs unit/integration tests to ensure code quality.
5. **Deploy:** Simulates deployment execution upon successful tests.

## How to Trigger
Any code commit or pull request pushed to the `main` branch automatically triggers the pipeline workflow.
