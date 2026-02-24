# Installation Guide

Quick guide to installing and using the AI Slides skill.

## Installation

### Option 1: Direct Use (Recommended)
The skill is ready to use immediately. No installation required.

Simply invoke the skill with your slide generation request:
```
Generate a 5-slide pitch deck about AI automation
```

### Option 2: Manual Setup
If you want to customize or extend the skill:

1. **Copy the skill folder** to your skills directory:
   ```bash
   cp -r ai-slides ~/.craft-agent/skills/
   ```

2. **Verify installation**:
   ```bash
   ls ~/.craft-agent/skills/ai-slides
   ```

3. **Test the skill**:
   Open one of the sample decks in your browser:
   ```bash
   open ai-slides/templates/presets/sample-startup-pitch.html
   ```

## Quick Start

### 1. Basic Slide Generation

**Request**:
```
Create a 5-slide presentation about remote work
```

**What you get**:
- Title slide
- Problem slide
- Solution slide
- Benefits slide
- CTA slide

### 2. Theme Selection

**Request**:
```
Generate slides about product launch with Apple Keynote theme
```

**Available themes**:
- `minimal-corporate` (default)
- `apple-keynote`
- `dark-futuristic`
- `ai-startup`
- `data-storytelling`

### 3. Content Conversion

**Request**:
```
Convert this blog post into slides:
[paste your content]
```

**Supported formats**:
- Blog posts
- LinkedIn posts
- Meeting notes
- Articles
- Reports

### 4. Custom Slide Types

**Request**:
```
Generate slides with:
- Title slide
- Stats dashboard (show 4 metrics)
- Timeline (show 5 milestones)
- Comparison (before/after)
- CTA slide
```

**Available slide types**:
- Title
- Content (bullets)
- Quote
- Stats dashboard
- Timeline
- Comparison
- Chart
- CTA
- Section divider

## Using Generated Slides

### Opening Slides
1. Save the generated HTML to a file (e.g., `presentation.html`)
2. Open in any modern browser
3. Press `F` for fullscreen
4. Use arrow keys to navigate

### Keyboard Controls
- `→` or `Space` - Next slide
- `←` - Previous slide
- `Home` - First slide
- `End` - Last slide
- `F` - Fullscreen
- `S` - Speaker notes
- `T` - Change theme
- `ESC` - Exit fullscreen

### Mobile Usage
- Swipe left/right to navigate
- Tap controls at bottom
- Works in portrait and landscape

### Sharing
1. **Direct sharing**: Send the HTML file
2. **Web hosting**: Upload to any web server
3. **PDF export**: Print to PDF from browser
4. **Screenshots**: Export individual slides as images

## Customization

### Changing Themes
Themes can be switched live during presentation:
- Press `T` to cycle through themes
- Or edit the HTML to set default theme

### Adding Content
Edit the HTML file to:
- Add more slides
- Modify text
- Change colors
- Add images
- Embed videos

### Creating Custom Themes
1. Open `STYLE_PRESETS.md`
2. Copy an existing theme
3. Modify colors and typography
4. Add to `base-engine.html`

## Examples

### Example 1: Startup Pitch
```
Generate an 8-slide investor pitch with:
- Title
- Problem
- Solution
- Market size
- Traction (stats)
- Timeline
- Team
- CTA

Use AI Startup theme
```

### Example 2: Product Demo
```
Create a product demo presentation with:
- Hero slide with large number
- Feature grid (4 features)
- Performance stats
- Pricing table
- CTA

Use Apple Keynote theme
```

### Example 3: Data Report
```
Generate a quarterly report with:
- Executive summary
- Revenue chart
- Customer metrics (stats dashboard)
- Market analysis
- Action items

Use Data Storytelling theme
```

## Troubleshooting

### Issue: Slides don't load
**Solution**: Ensure JavaScript is enabled in your browser

### Issue: Animations are choppy
**Solution**:
- Close other browser tabs
- Enable hardware acceleration
- Use a modern browser (Chrome, Firefox, Safari)

### Issue: Theme not changing
**Solution**:
- Press `T` to cycle themes
- Check browser console for errors
- Verify theme name in HTML

### Issue: Mobile gestures not working
**Solution**:
- Ensure you're swiping on the slide area
- Check that touch events aren't blocked
- Try refreshing the page

## Best Practices

### Content
- Keep slides focused (one idea per slide)
- Use large, readable text
- Limit bullets to 3-5 per slide
- Include visual breaks

### Design
- Choose theme appropriate for audience
- Maintain consistent spacing
- Use high contrast colors
- Add speaker notes for context

### Technical
- Test in target browser before presenting
- Have a backup (PDF export)
- Check mobile view if presenting on tablet
- Ensure offline functionality

## Advanced Usage

### Batch Generation
Generate multiple presentations:
```
Create 3 different versions of this pitch:
1. 5-minute version (5 slides)
2. 15-minute version (12 slides)
3. 30-minute version (20 slides)
```

### Multi-Language
Request slides in different languages:
```
Generate slides in Spanish about...
```

### Custom Layouts
Request specific layouts:
```
Create a slide with:
- Left: Large image
- Right: 3 bullet points
```

## Resources

- **Documentation**: See `SKILL.md` for complete reference
- **Themes**: See `STYLE_PRESETS.md` for all theme options
- **Examples**: See `EXAMPLES.md` for real-world use cases
- **AI Patterns**: See `PROMPT_TEMPLATES.md` for content optimization

## Support

### Common Questions

**Q: Can I use custom fonts?**
A: Yes, add `@import` or embed fonts in the HTML

**Q: Can I add my logo?**
A: Yes, add an `<img>` tag to any slide

**Q: Can I embed videos?**
A: Yes, use `<video>` or `<iframe>` tags

**Q: Can I export to PowerPoint?**
A: Not directly, but you can print to PDF

**Q: Can I use this commercially?**
A: Yes, generated presentations are yours to use freely

### Getting Help

1. Check the documentation files
2. Review the sample decks
3. Examine the base engine HTML
4. Experiment with different prompts

## Next Steps

1. **Try the samples**: Open the example decks
2. **Generate your first deck**: Start with a simple request
3. **Customize**: Modify themes and layouts
4. **Share**: Present your slides and get feedback
5. **Extend**: Add new themes and features

---

**You're ready to create amazing presentations!**

Start by asking for what you need, and the AI will generate beautiful, production-ready slides.
