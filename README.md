# GentleGithubWorkflows
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

This repository serves as a centralized hub for a variety of GitHub Actions workflows tailored to streamline your continuous integration (CI) processes.

## Features:

- **Diverse Integration**: Seamlessly integrate workflows into your GitHub projects to automate CI tasks.
- **Enhanced Productivity**: Save time and effort by automating repetitive tasks, allowing you to focus on development.
- **Code Quality Assurance**: Ensure code quality with automated testing and validation processes integrated into your CI pipeline.

## Installation

Add jobs (f.e dart_quality_check) to your workflow at `.github/workflows/your_workflow.yaml` and provide the desired version of the dart SDK:

```yaml
    jobs:
    dart_quality_check:
        uses: GentleTechTeam/GentleGithubWorkflows/.github/workflows/dart_quality_check.yml@main
        with:
        DART_SDK_VERSION: "3.0.0"
```


## License

This project is licensed under the [MIT License](LICENSE).

## Contact

- Author: Gentle Tech Team
- Email: gentletechteam@gmail.com
- Website: [gentletech.net](gentletech.net)






