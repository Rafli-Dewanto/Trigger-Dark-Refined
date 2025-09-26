# Contributing to Trigger Dark Refined

Thank you for your interest in contributing to Trigger Dark Refined! This document provides guidelines for contributing to this VS Code theme extension.

## How to Contribute

### Reporting Issues

If you find a bug or have a suggestion for improvement:

1. **Check existing issues** to avoid duplicates
2. **Create a new issue** with a clear title and description
3. **Include screenshots** if relevant
4. **Specify your environment** (VS Code version, OS, etc.)

### Suggesting Enhancements

We welcome suggestions for new features or improvements:

1. **Open an issue** with the label "enhancement"
2. **Describe the enhancement** in detail
3. **Explain why it would be useful** to other users

### Code Contributions

#### Setting up the Development Environment

1. **Fork the repository**
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/yourusername/trigger-dark-refined.git
   cd trigger-dark-refined
   ```
3. **Install dependencies**:
   ```bash
   npm install
   ```

#### Making Changes

1. **Create a new branch** for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. **Make your changes** to the theme files
3. **Test your changes** by loading the extension in VS Code:
   - Press `F5` to open a new Extension Development Host window
   - Test your theme with different file types

#### Theme Modification Guidelines

When modifying `themes/trigger-dark.json`:

- **Maintain consistency** with the existing color palette
- **Test with multiple languages** (JavaScript, Python, HTML, etc.)
- **Ensure good contrast ratios** for accessibility
- **Follow semantic color usage** (e.g., errors should be red-ish)

#### Submitting Changes

1. **Commit your changes** with clear commit messages:
   ```bash
   git add .
   git commit -m "Add: Enhanced syntax highlighting for Python"
   ```
2. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
3. **Create a Pull Request** with:
   - Clear title and description
   - Screenshots of before/after (if visual changes)
   - List of changes made

### Code Style

- Use consistent indentation (2 spaces for JSON files)
- Follow semantic color naming
- Add comments for complex color choices
- Keep the theme file organized by sections

### Testing

Before submitting your changes:

1. **Test the theme** with multiple file types
2. **Check for accessibility** (good contrast ratios)
3. **Verify no syntax errors** in JSON files
4. **Test in both light and dark environments**

### Color Palette Guidelines

When adding or modifying colors:

- **Maintain the dark theme aesthetic**
- **Use colors that complement each other**
- **Ensure sufficient contrast** for readability
- **Test with colorblind-friendly tools**
- **Document new colors** in the README if significant

## Community

- Be respectful and inclusive
- Help others learn and grow
- Share knowledge and best practices
- Follow the [Code of Conduct](CODE_OF_CONDUCT.md)

## Questions?

If you have questions about contributing, feel free to:

- Open an issue with the "question" label
- Check existing discussions
- Reach out to the maintainers

Thank you for helping make Trigger Dark Refined better! 🎨✨
