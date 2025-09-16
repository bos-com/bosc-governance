# Contributing to Bugema Open Source Community (BOSC)

Thank you for your interest in contributing to BOSC! This guide will help you understand how to contribute effectively to our community and projects.

## Table of Contents

- [Getting Started](#getting-started)
- [Contribution Workflow](#contribution-workflow)
- [Quality Standards](#quality-standards)
- [Types of Contributions](#types-of-contributions)
- [Project-Specific Guidelines](#project-specific-guidelines)
- [Review Process](#review-process)
- [Recognition and Rewards](#recognition-and-rewards)
- [Getting Help](#getting-help)

## Getting Started

### Prerequisites

Before contributing, ensure you have:

1. **Git installed** on your local machine
2. **GitHub account** (for code contributions)
3. **Basic understanding** of the project you want to contribute to
4. **Read and understood** our [Code of Conduct](CODE_OF_CONDUCT.md)

### Joining the Community

1. **Register**: Join through the official BOSC portal, GitHub, or community sign-up form
2. **Introduce yourself**: Post in our welcome channel or mailing list
3. **Attend events**: Join our weekly/monthly meetups to meet other contributors
4. **Choose a project**: Browse our projects and find one that interests you

## Contribution Workflow

### 1. Fork and Clone

```bash
# Fork the repository on GitHub, then clone your fork
git clone https://github.com/YOUR_USERNAME/PROJECT_NAME.git
cd PROJECT_NAME

# Add the original repository as upstream
git remote add upstream https://github.com/BOSC/PROJECT_NAME.git
```

### 2. Create a Branch

```bash
# Create a new branch for your contribution
git checkout -b feature/your-feature-name
# or
git checkout -b fix/issue-number
```

### 3. Make Changes

- Write clean, well-documented code
- Follow the project's coding standards
- Add tests for new functionality
- Update documentation as needed

### 4. Test Your Changes

```bash
# Run existing tests
npm test  # or pytest, cargo test, etc.

# Run linting
npm run lint  # or similar

# Test your specific changes
# Add your own test cases
```

### 5. Commit Your Changes

```bash
# Stage your changes
git add .

# Commit with a descriptive message
git commit -m "Add feature: brief description of changes

- Detailed description of what was changed
- Why the change was made
- Any relevant context

Fixes #123"  # if applicable
```

### 6. Push and Create Pull Request

```bash
# Push your branch
git push origin feature/your-feature-name

# Create a Pull Request on GitHub
```

## Quality Standards

### Code Quality

- **Documentation**: All code must be well-documented with clear comments
- **Testing**: Include tests for new functionality and bug fixes
- **Style**: Follow the project's coding style guidelines
- **Performance**: Consider performance implications of your changes
- **Security**: Ensure your code doesn't introduce security vulnerabilities

### Documentation

- **README Updates**: Update README files when adding new features
- **API Documentation**: Document new APIs and functions
- **Code Comments**: Write clear, concise comments explaining complex logic
- **Commit Messages**: Use clear, descriptive commit messages

### Testing Requirements

- **Unit Tests**: Write unit tests for new functions and methods
- **Integration Tests**: Test how your changes interact with existing code
- **Edge Cases**: Consider and test edge cases
- **Regression Tests**: Ensure existing functionality still works

## Types of Contributions

### Code Contributions

- **Bug Fixes**: Fix existing issues and bugs
- **New Features**: Add new functionality to projects
- **Performance Improvements**: Optimize existing code
- **Refactoring**: Improve code structure without changing functionality

### Documentation

- **README Files**: Improve project documentation
- **API Documentation**: Document functions and classes
- **Tutorials**: Create guides for new users
- **Translation**: Translate documentation to other languages

### Design and UI/UX

- **User Interface**: Improve user interfaces
- **User Experience**: Enhance user experience
- **Graphics**: Create logos, icons, and visual assets
- **Wireframes**: Design application layouts

### Research and Analysis

- **Market Research**: Research relevant technologies and trends
- **Performance Analysis**: Analyze and optimize performance
- **Security Audits**: Review code for security issues
- **Academic Papers**: Collaborate on research publications

### Community Building

- **Mentoring**: Help new contributors learn
- **Event Organization**: Help organize meetups and workshops
- **Content Creation**: Create blog posts, videos, or tutorials
- **Outreach**: Help promote BOSC in the community

## Project-Specific Guidelines

### GreenCode Project

- Focus on environmental sustainability
- Follow green coding practices
- Document environmental impact of changes
- Include sustainability metrics in tests

### LifeLine-ICT Project

- Prioritize accessibility and usability
- Follow healthcare data privacy standards
- Include accessibility testing
- Document user impact

### OpenCare-Africa Project

- Consider African context and needs
- Follow international healthcare standards
- Include localization considerations
- Document cultural sensitivity

## Review Process

### Pull Request Guidelines

1. **Clear Description**: Provide a clear description of your changes
2. **Reference Issues**: Link to relevant issues or discussions
3. **Screenshots**: Include screenshots for UI changes
4. **Testing**: Describe how you tested your changes
5. **Breaking Changes**: Clearly mark any breaking changes

### Review Criteria

Maintainers will review your contribution based on:

- **Code Quality**: Is the code clean, well-documented, and tested?
- **Functionality**: Does it work as intended?
- **Compatibility**: Does it work with existing code?
- **Performance**: Are there any performance implications?
- **Security**: Are there any security concerns?
- **Documentation**: Is the documentation updated appropriately?

### Review Timeline

- **Initial Review**: Within 3-5 business days
- **Feedback**: Constructive feedback provided within 1 week
- **Final Decision**: Usually within 2 weeks of submission

## Recognition and Rewards

### Contributor Recognition

- **Badges**: Earn badges for different types of contributions
- **Certificates**: Receive certificates for significant contributions
- **Showcase**: Your work will be showcased at BOSC events
- **Leadership Opportunities**: Active contributors can become maintainers

### Contribution Levels

- **Newcomer**: First-time contributors
- **Regular Contributor**: Consistent monthly contributions
- **Core Contributor**: Significant ongoing contributions
- **Maintainer**: Project leadership role
- **Steering Committee**: Community governance role

## Getting Help

### Resources

- **Documentation**: Check project README files and wikis
- **Issues**: Search existing GitHub issues for similar problems
- **Discussions**: Use GitHub Discussions for questions
- **Mailing List**: Join our mailing list for announcements
- **Slack/Discord**: Join our chat channels for real-time help

### Mentorship

- **Mentor Program**: Request a mentor for guidance
- **Office Hours**: Attend maintainer office hours
- **Workshops**: Join our regular workshops and training sessions
- **Pair Programming**: Find a pair programming partner

### Contact Information

- **General Questions**: [BOSC Mailing List]
- **Technical Issues**: [GitHub Issues]
- **Community Support**: [Slack/Discord Channels]
- **Direct Contact**: Muwanga Kosea (BOSC BDFL) - [Email]

## Code of Conduct

Please note that all contributors are expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md). We are committed to providing a welcoming and inclusive environment for everyone.

## License

By contributing to BOSC projects, you agree that your contributions will be licensed under the same license as the project you're contributing to.

---

*Thank you for contributing to BOSC! Your contributions help us build a better open-source community.*

*Copyright BOSC 2025*
