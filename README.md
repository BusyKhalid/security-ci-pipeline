# Security CI Pipeline

A streamlined GitHub Actions pipeline for comprehensive security checks, including scans for vulnerabilities in container images, code dependencies, source code, and detection of exposed secrets.

## Usage

1. Download the workflow file from [here](https://github.com/BusyKhalid/security-ci-pipeline/tree/main/.github/workflows) and add it to `.github/workflows/security.yml`.
2. The pipeline triggers automatically on:
   - Pushes to `main`
   - Pull requests targeting `main`
   - A scheduled run every Sunday at 10:00 AM UTC
3. Review detailed scan results in the repository's **Security** tab.

## License

This project is licensed under the MIT License.

---

**Developed by [Khalid Alraddady](https://www.linkedin.com/in/your-linkedin-profile)**

Feel free to reach out with any questions, suggestions, or feedback!
