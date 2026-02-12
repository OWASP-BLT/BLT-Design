# Contributing to BLT Design System

Thank you for your interest in contributing to the BLT Design System! This document provides guidelines and instructions for contributing.

## 🤝 How to Contribute

There are many ways to contribute to the BLT Design System:

- 🐛 **Report bugs** - Found an issue? Let us know!
- 💡 **Suggest enhancements** - Have ideas for improvements?
- 📝 **Improve documentation** - Help make our docs better
- 🎨 **Design contributions** - Propose new components or patterns
- 💻 **Code contributions** - Submit pull requests with fixes or features

## 📋 Before You Start

1. **Check existing issues** - Search [existing issues](https://github.com/OWASP-BLT/BLT-Design/issues) to avoid duplicates
2. **Read the documentation** - Familiarize yourself with the design system
3. **Discuss major changes** - For significant changes, open an issue first to discuss

## 🐛 Reporting Bugs

When reporting bugs, please include:

- **Description** - Clear description of the issue
- **Steps to reproduce** - How to reproduce the bug
- **Expected behavior** - What should happen
- **Actual behavior** - What actually happens
- **Screenshots** - If applicable
- **Environment** - Browser, OS, etc.

### Bug Report Template

```markdown
**Describe the bug**
A clear description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '...'
3. See error

**Expected behavior**
What you expected to happen.

**Screenshots**
Add screenshots if applicable.

**Environment:**
- Browser: [e.g., Chrome 120]
- OS: [e.g., macOS 14]
- Design System Version: [e.g., 1.0.0]
```

## 💡 Suggesting Enhancements

When suggesting enhancements:

- **Use a clear title** - Describe the enhancement concisely
- **Provide context** - Explain why this would be useful
- **Include examples** - Show how it would work
- **Consider alternatives** - Discuss other approaches

### Enhancement Template

```markdown
**Enhancement description**
Clear description of the proposed enhancement.

**Use case**
Explain the problem this solves or the value it adds.

**Proposed solution**
Describe how you envision this working.

**Examples**
Provide code examples or mockups if applicable.

**Alternatives considered**
What other approaches did you consider?
```

## 📝 Contributing Documentation

Documentation improvements are always welcome!

### Documentation Guidelines

- Use clear, concise language
- Include code examples where appropriate
- Follow the existing documentation structure
- Test examples to ensure they work
- Check for typos and grammar

## 🎨 Design Contributions

### Adding New Components

When proposing new components:

1. **Check existing patterns** - Ensure it doesn't duplicate existing components
2. **Follow design principles** - Maintain consistency with existing components
3. **Consider accessibility** - Ensure WCAG AA compliance
4. **Include dark mode** - All components must support dark mode
5. **Provide examples** - Show various use cases

### Component Checklist

- [ ] Component follows existing patterns
- [ ] Supports light and dark modes
- [ ] Accessible (keyboard navigation, screen readers)
- [ ] Responsive design
- [ ] Documented with examples
- [ ] Consistent with design tokens

## 💻 Code Contributions

### Development Setup

```bash
# Fork and clone the repository
git clone https://github.com/YOUR_USERNAME/BLT-Design.git
cd BLT-Design

# Install dependencies
npm install

# Create a branch for your changes
git checkout -b feature/your-feature-name
```

### Coding Standards

- **Follow existing patterns** - Match the style of existing code
- **Use design tokens** - Don't hardcode colors, spacing, etc.
- **Write clear code** - Use descriptive names and comments where needed
- **Keep it simple** - Avoid over-engineering
- **Test your changes** - Ensure everything works as expected

### Commit Messages

Write clear, descriptive commit messages:

```
<type>: <subject>

<body>

<footer>
```

Types:
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Formatting, missing semi-colons, etc.
- `refactor`: Code restructuring
- `test`: Adding tests
- `chore`: Maintenance tasks

Examples:
```
feat: add dropdown component with dark mode support

- Created dropdown component
- Added open/close animations
- Included keyboard navigation
- Supports light and dark themes

Closes #123
```

### Pull Request Process

1. **Update documentation** - Include relevant docs updates
2. **Test your changes** - Verify everything works
3. **Update examples** - Add examples if applicable
4. **Write clear PR description** - Explain what and why
5. **Link related issues** - Reference issue numbers

### Pull Request Template

```markdown
## Description
Brief description of changes.

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Design improvement

## Changes Made
- Change 1
- Change 2
- Change 3

## Screenshots (if applicable)
Add screenshots for visual changes.

## Checklist
- [ ] Code follows existing patterns
- [ ] Documentation updated
- [ ] Examples added/updated
- [ ] Tested in light and dark modes
- [ ] Accessible (keyboard + screen reader)
- [ ] Responsive design tested

## Related Issues
Closes #(issue number)
```

## 🔍 Review Process

All contributions go through review:

1. **Automated checks** - Code style, tests, etc.
2. **Manual review** - Maintainers review the changes
3. **Feedback** - Reviewers may request changes
4. **Approval** - Once approved, changes are merged

## 🎯 Design Principles

When contributing, keep these principles in mind:

### Consistency
- Follow established patterns
- Use design tokens
- Maintain visual hierarchy

### Accessibility
- WCAG AA compliance minimum
- Keyboard navigation support
- Screen reader compatibility
- Sufficient color contrast

### Performance
- Minimize file sizes
- Optimize images
- Use efficient CSS

### Simplicity
- Keep components simple
- Avoid over-abstraction
- Clear documentation

## 📚 Resources

- [Main BLT Repository](https://github.com/OWASP-BLT/BLT)
- [BLT Documentation](https://owasp-blt.github.io/documentation/)
- [Tailwind CSS Docs](https://tailwindcss.com/docs)
- [WCAG Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)

## 🙋 Questions?

- **General questions**: Open a [discussion](https://github.com/OWASP-BLT/BLT-Design/discussions)
- **Bug reports**: Open an [issue](https://github.com/OWASP-BLT/BLT-Design/issues)
- **Security issues**: See [SECURITY.md](SECURITY.md)

## 📜 License

By contributing, you agree that your contributions will be licensed under the same license as the project (AGPL-3.0).

## 🌟 Recognition

Contributors are recognized in:
- Project README
- Release notes
- Contributors page

Thank you for making the BLT Design System better! 🎉
