# Contributing to AI Slides

Thank you for your interest in contributing to AI Slides! This document provides guidelines for contributing to the project.

## How to Contribute

### Reporting Issues

- Check if the issue already exists
- Provide a clear description of the problem
- Include steps to reproduce
- Share your browser/environment details

### Suggesting Features

- Open an issue with the "enhancement" label
- Describe the feature and its use case
- Explain why it would be valuable

### Contributing Code

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Test thoroughly
5. Commit with clear messages (`git commit -m 'Add amazing feature'`)
6. Push to your branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

## Adding New Themes

1. Define the theme in `STYLE_PRESETS.md`:
   - Color palette
   - Typography
   - Spacing
   - Animation preferences

2. Add CSS variables to `templates/base-engine.html`

3. Test across all slide types

4. Document in `EXAMPLES.md`

## Adding New Slide Types

1. Design the HTML structure
2. Add CSS styling
3. Include animation logic
4. Add examples to `EXAMPLES.md`
5. Update documentation

## Adding AI Patterns

1. Edit `PROMPT_TEMPLATES.md`
2. Add new optimization patterns
3. Include usage examples
4. Test with various content types

## Code Style

- Use clear, descriptive variable names
- Comment complex logic
- Keep functions focused and small
- Follow existing code patterns
- Ensure accessibility (ARIA labels, keyboard nav)

## Testing

Before submitting:

- [ ] Test in Chrome, Firefox, Safari
- [ ] Test on mobile devices
- [ ] Verify keyboard navigation
- [ ] Check accessibility with screen reader
- [ ] Validate HTML/CSS
- [ ] Test offline functionality
- [ ] Ensure file size stays under 150KB

## Documentation

- Update README.md if adding features
- Add examples to EXAMPLES.md
- Update SKILL.md for usage changes
- Keep ARCHITECTURE.md current

## Questions?

Open an issue with the "question" label or start a discussion.

## Code of Conduct

- Be respectful and inclusive
- Provide constructive feedback
- Focus on the code, not the person
- Help others learn and grow

Thank you for contributing! 🎉
