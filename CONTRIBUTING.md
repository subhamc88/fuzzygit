# Contributing to Fuzzygit

Thank you for your interest in contributing to **Fuzzygit**!  
We appreciate your help in improving this project.  
Please take a moment to review these guidelines before getting started.

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).  
Please ensure you’ve read it before contributing.

## How Can You Contribute?

We welcome contributions in various forms:

- **Reporting Bugs**: Find and submit detailed reports of bugs.
- **Feature Requests**: Suggest new features or enhancements.
- **Code Contributions**: Fix bugs or add new functionality.
- **Improving Documentation**: Help keep our documentation accurate and up-to-date.

## Getting Started

1. **Fork the Repository**: Click the fork button at the top-right of the
repository page to create a copy of the repository in your own account.
2. **Clone Your Fork**: Clone your fork to your local machine using the command:

   ```bash
   git clone https://github.com/subhamc88/Fuzzygit.git
   ```

3. **Create a New Branch**: Create a new branch for your feature or fix,
ensuring you branch off of the `develop` branch.
Please use the following naming convention for your branch:

   ```txt
   feature/<description>      # for new features
   fix/<description>          # for bug fixes
   docs/<description>         # for documentation changes
   chore/<description>        # for other changes that don't modify src or test
   refactor/<description>     # for code changes that neither fix a bug nor add a feature
   test/<description>         # for adding or modifying tests
   style/<description>        # for formatting changes, like linting or styling
   perf/<description>         # for performance improvements
   build/<description>        # for changes that affect the build system or external dependencies
   ci/<description>           # for changes related to continuous integration or deployment
   release/<version>          # for version release branches
   hotfix/<description>       # for critical bug fixes that need to be addressed immediately
   experimental/<description> # for experimental features or changes being tested
   ```

   Example:

   ```bash
   git checkout -b feature/add-new-feature
   ```

4. **Make Your Changes**: Implement your changes locally.
5. **Commit Your Changes**: Commit your changes with a clear and concise message,
following the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
format:

    Example:

   ```bash
   git commit -m "feat: add a new feature"
   ```

6. **Push to Your Fork**: Push your changes back to your fork:

   ```bash
   git push origin add-new-feature
   ```

7. **Open a Pull Request**: Navigate to the original repository and
click on the "New Pull Request" button.
Ensure your PR targets the `develop` branch.

## Coding Standards

- Follow the existing coding style in the project.
- Write clear and concise commit messages.
- Ensure your code is free of warnings and errors.

## Testing

Please include tests for your changes.
Ensure that all existing tests pass before submitting your pull request.

## Questions?

If you have any questions or need help, feel free to open an issue or
reach out to the maintainers.

Thank you for contributing to **Fuzzygit**!
