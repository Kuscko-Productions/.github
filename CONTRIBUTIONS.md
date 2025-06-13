# Contributing to Kuscko Productions Private Repositories
Thank you for your work on this project. Contributions to this repository are governed by internal agreements and policies maintained by Kuscko Productions LLC.

This repository is private and proprietary. All contributions are subject to our Proprietary Software License Agreement (PSLA) and Contributor License Agreement (CLA).

## 1. Contributor License Agreement (CLA)
**⚠️ Important**
All contributors must acknowledge and agree to the terms of our Contributor License Agreement (CLA) prior to submitting any work.

All contributions are considered work-for-hire and become the sole property of Kuscko Productions LLC.

No rights are granted to fork, reuse, distribute, or relicense any portion of this repository or its derivatives.

By contributing (committing, submitting pull requests, documentation, or any assets), you agree to be bound by the CLA and PSLA.

If you have not signed or reviewed the CLA, please contact your project manager or Kuscko Productions directly before proceeding.

## 2. Workflow and Branching
We use a fork-and-branch model even in private repositories to keep changes isolated and reviewable. Our standard branch progression is `main` > `staging` > `dev`.

Basic Workflow
Pull the latest `dev` branch
```
git checkout dev
git pull origin dev
```

Create a feature or fix branch
```
git checkout -b feature/short-description
```

Make and commit your changes
```
git add .
git commit -m "feat: Implement XYZ module"
```

Push to origin and open a pull request
```
git push origin feature/short-description
```

Submit PR for review, targeting the dev branch. Ensure your PR has a clear title and description. Reference relevant tickets or tasks if applicable (e.g., Jira or GitHub Issues).

## 3. Code Guidelines
Style: Follow project-specific formatting, naming, and comment conventions.

Documentation: Add or update inline comments and module-level documentation as needed.

Testing: Ensure all unit and integration tests pass before submission.

Security: Validate your changes for data integrity and confidentiality compliance.

## 4. Review and Approval
After submitting your pull request:

Automated Checks: CI pipelines will run code quality and test suites.

Manual Review: A senior team member will review your code.

Revisions: Address any requested changes promptly.

Merge: Once approved and verified, your code will be merged into the dev branch. From there, changes will progress to staging and then main through our standard deployment processes.

## 5. Questions or Issues
If you're unsure about how to proceed:

Contact your assigned technical lead or project manager.

Do not open public issues or discuss this repository in external channels.

## 🔒 Confidentiality Notice
This repository and its contents are confidential and proprietary. Unauthorized disclosure, reuse, or distribution is strictly prohibited and may result in legal action.

Thank you for contributing responsibly and professionally to Kuscko Productions LLC.
