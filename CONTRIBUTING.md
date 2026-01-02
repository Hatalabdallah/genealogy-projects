# Contributing to Genealogy Projects Portfolio

First off, thank you for considering contributing to the Genealogy Projects Portfolio! It's people like you that make this collection of genealogy applications such a great resource for family history researchers and developers alike.

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report. Following these guidelines helps maintainers and the community understand your report, reproduce the behavior, and find related reports.

**Before Submitting A Bug Report**
* Check the [existing issues](https://github.com/abdallahddumbakato/genealogy-projects/issues) to see if the problem has already been reported.
* Perform a [cursory search](https://github.com/abdallahddumbakato/genealogy-projects/issues) to see if the problem has already been reported.

**How Do I Submit A (Good) Bug Report?**
Bugs are tracked as [GitHub issues](https://github.com/abdallahddumbakato/genealogy-projects/issues). Create an issue and provide the following information:

- **Use a clear and descriptive title** for the issue to identify the problem.
- **Describe the exact steps which reproduce the problem** in as many details as possible.
- **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples.
- **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
- **Explain which behavior you expected to see instead and why.**
- **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem.
- **If the problem is related to performance or memory**, include a CPU profile capture with your report.

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion, including completely new features and minor improvements to existing functionality.

**Before Submitting An Enhancement Suggestion**
* Check if there's already a package which provides that enhancement.
* Determine which repository the enhancement should be suggested in.

**How Do I Submit A (Good) Enhancement Suggestion?**
Enhancement suggestions are tracked as [GitHub issues](https://github.com/abdallahddumbakato/genealogy-projects/issues). Create an issue and provide the following information:

- **Use a clear and descriptive title** for the issue to identify the suggestion.
- **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
- **Provide specific examples to demonstrate the steps**. Include copy/pasteable snippets which you use in those examples.
- **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
- **Explain why this enhancement would be useful** to most users of these genealogy projects.

### Your First Code Contribution

Unsure where to begin contributing to Genealogy Projects? You can start by looking through these `good first issue` and `help wanted` issues:

* [Good first issues](https://github.com/abdallahddumbakato/genealogy-projects/labels/good%20first%20issue) - issues which should only require a few lines of code, and a test or two.
* [Help wanted issues](https://github.com/abdallahddumbakato/genealogy-projects/labels/help%20wanted) - issues which should be a bit more involved than `good first issue` issues.

## Development Setup

### Prerequisites
- Node.js 18+
- Git
- Your preferred package manager (npm, yarn, pnpm, or bun)

### Setup Steps
1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
```bash
git clone https://github.com/YOUR_USERNAME/genealogy-projects.git
cd genealogy-projects
```

3. **Choose a project to work on**:
```bash
cd family-story-ui-main  # or family-weaver-ui-main or heritage-hub-ui-main
```

4. **Add upstream remote**:
```bash
git remote add upstream https://github.com/abdallahddumbakato/genealogy-projects.git
```

5. **Install dependencies**:
```bash
npm install
```

6. **Create a new branch**:
```bash
git checkout -b feature/your-feature-name
```

7. **Make your changes**
8. **Run tests** to ensure your changes don't break existing functionality:
```bash
npm test
```

9. **Commit your changes** using conventional commit format:
```bash
git add .
git commit -m "feat: add new feature"
```

10. **Push to your fork**:
```bash
git push origin feature/your-feature-name
```

11. **Create a Pull Request** on GitHub

## Pull Request Process

1. Ensure any install or build dependencies are removed before the end of the layer when doing a build.
2. Update the README.md with details of changes to the interface, if applicable.
3. Increase the version numbers in any examples files and the README.md to the new version that this Pull Request would represent. The versioning scheme we use is [SemVer](http://semver.org/).
4. You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

## Style Guides

### Git Commit Messages
* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* Use [Conventional Commits](https://www.conventionalcommits.org/) format:
  - `feat:` for new features
  - `fix:` for bug fixes
  - `docs:` for documentation changes
  - `style:` for formatting changes
  - `refactor:` for code refactoring
  - `test:` for test changes
  - `chore:` for maintenance tasks

### JavaScript/TypeScript Style Guide
* Use TypeScript for all new code
* Follow the existing code style
* Use meaningful variable names
* Add JSDoc comments for complex functions
* Keep functions small and focused

### CSS/Tailwind Style Guide
* Use Tailwind CSS utility classes
* Follow the existing design system
* Use CSS variables for theming
* Keep styles responsive and accessible

### Testing
* Write tests for all new features
* Update tests when modifying existing features
* Aim for high test coverage
* Use React Testing Library for component tests

## Project Structure

```
genealogy-projects/
├── family-story-ui-main/     # Modern genealogy platform
│   └── src/
│       ├── components/       # Reusable UI components
│       │   ├── ui/          # ShadCN components
│       │   ├── layout/      # Layout components
│       │   └── home/        # Home page sections
│       ├── pages/           # Page components
│       ├── hooks/           # Custom React hooks
│       ├── lib/             # Utility functions
│       ├── assets/          # Static assets
│       ├── types/           # TypeScript type definitions
│       └── tests/           # Test files
├── family-weaver-ui-main/    # Family tapestry creator
├── heritage-hub-ui-main/     # Heritage management system
└── .github/                  # GitHub workflows and templates
```

## Recognition

Contributors who have their pull requests accepted will be:
1. Added to the contributors list in the README
2. Mentioned in release notes
3. Given credit in the project documentation

## Questions?

If you have any questions about contributing, feel free to:
* Open an issue with the "question" label
* Contact the maintainer at **a.ddumba@kyakabi.com**
* Join our community discussions

Thank you for contributing to Genealogy Projects! 🎉

---

**Maintainer**: Ddumba Abdallah Kato  
**Email**: a.ddumba@kyakabi.com  
**Portfolio**: https://ddumba.kyakabi.com  
**GitHub**: https://github.com/abdallahddumbakato 
**LinkedIn**: https://www.linkedin.com/in/ddumba-abdallah-kato-a356392a5/