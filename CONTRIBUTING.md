# Contributing to Gold Store Skincare Website

Thank you for your interest in contributing to the Gold Store Skincare Website! We welcome contributions to help improve this responsive landing page.

To maintain high code quality and professional standards, please follow these guidelines.

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

## How Can I Contribute?

### Reporting Bugs
If you find a broken link, layout misalignment, or image loading error:
- Open a GitHub Issue describing the bug.
- Include browser details, steps to reproduce, and screen layouts if applicable.

### Submitting Pull Requests (PRs)
1. Fork the repository and create your branch from `main`.
2. Format your HTML and CSS code to follow standard web conventions.
3. Commit your changes using **Conventional Commits** (see below).
4. Submit your PR with a clear description of the changes.

---

## Coding Standards

### HTML Relative Links
- **Always use relative paths** (e.g. `./index.html`, `./aboutus.html`) for link elements, image tags, and script sources.
- Never use absolute file paths (starting with `/`) as they break navigation when pages are run locally or hosted in project subfolders.

### CSS Styling
- Place custom style rules inside `css/style.css`.
- Ensure styles are responsive across phone, tablet, and desktop viewports.
- Optimize images under the `img/` folder (keep file sizes compressed for web loading speeds).

---

## Commit Messages

We use the [Conventional Commits](https://www.conventionalcommits.org/) format:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

### Common Types:
- `feat`: A new layout section or page template.
- `fix`: A bug fix (e.g. broken navbar links, responsive flex wraps).
- `docs`: Documentation-only changes.
- `style`: Formatting, spacing, CSS adjustments.
- `refactor`: Restructuring CSS overrides.

### Examples:
- `feat(aboutus): add team members grid layout`
- `fix(navbar): resolve absolute link pathing on index page`
- `docs(readme): add project installation screenshots`
