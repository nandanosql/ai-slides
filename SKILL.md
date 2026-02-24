---
name: AI Slides
description: Generate premium HTML slide decks with AI-powered content optimization, beautiful themes, and zero dependencies
icon: 🎯
version: 1.0.0
author: AI Slide Generator
tags: [presentation, slides, html, ai, design]
---

# AI Slides - Next-Generation Slide Generator

Generate stunning, self-contained HTML slide decks with AI-powered content optimization. No build tools, no dependencies, just beautiful presentations that work anywhere.

## Features

### 🎨 Premium Design System
- **5 Built-in Themes**: Minimal Corporate, Apple Keynote, Dark Futuristic, AI Startup Pitch, Data Storytelling
- **Responsive Layouts**: Perfect on desktop, tablet, and mobile
- **Smart Typography**: Hierarchy-based font scaling and spacing
- **Smooth Animations**: GPU-optimized transitions

### 🧠 AI Intelligence Layer
- **Content Optimization**: Rewrites for clarity and impact
- **Story Flow**: Structures narrative progression
- **Visual Suggestions**: Recommends icons, charts, and layouts
- **Auto-Summarization**: Converts long content into digestible bullets
- **Format Conversion**: LinkedIn posts → slides, blogs → presentations

### ⚡ Advanced Features
- **Keyboard Navigation**: Arrow keys, spacebar, ESC
- **Touch Gestures**: Swipe support for mobile
- **Speaker Notes**: Hidden notes for presenters
- **Progress Indicator**: Visual slide counter
- **Theme Switcher**: Live theme changes
- **Fullscreen Mode**: Distraction-free presenting
- **Light/Dark Mode**: Auto-detection and manual toggle

### 📊 Special Slide Types
- Title slides with hero text
- Content slides with bullets
- Quote slides with attribution
- Stats dashboard with animated counters
- Timeline slides with milestones
- Comparison slides (side-by-side)
- Chart slides (bar, pie, line)
- CTA slides with call-to-action
- Section dividers

## Usage

### Basic Usage

```
Generate a 5-slide pitch deck about AI automation with the Apple Keynote theme
```

### Advanced Usage

```
Create a presentation from this blog post [paste content] using the Dark Futuristic theme with animated charts
```

### Content Conversion

```
Turn this LinkedIn post into a slide deck:
[paste LinkedIn content]
```

### Custom Styling

```
Generate slides about product launch with:
- AI Startup Pitch theme
- Include timeline slide
- Add comparison slide (before/after)
- Include stats dashboard
```

## Prompt Patterns

### Pattern 1: Topic-Based Generation
```
Create a [number]-slide presentation about [topic] using [theme] theme
```

### Pattern 2: Content Conversion
```
Convert this [content type] into slides with [theme] theme:
[paste content]
```

### Pattern 3: Structured Request
```
Generate slides with:
- Topic: [topic]
- Theme: [theme name]
- Slides: [list of slide types]
- Special features: [animations, charts, etc.]
```

## Available Themes

1. **minimal-corporate** - Clean, professional, business-ready
2. **apple-keynote** - Bold typography, minimal design, high contrast
3. **dark-futuristic** - Dark mode, neon accents, tech-forward
4. **ai-startup** - Modern gradient, startup pitch style
5. **data-storytelling** - Chart-focused, data visualization emphasis

## Output Format

Every generated slide deck is:
- ✅ Single HTML file (self-contained)
- ✅ No external dependencies
- ✅ Works offline
- ✅ Production-ready
- ✅ Fully accessible (ARIA tags)
- ✅ Mobile responsive
- ✅ <150KB file size

## Architecture

### Core Components

1. **Slide Engine** (`base-engine.html`)
   - Navigation system
   - Keyboard/touch handlers
   - Progress tracking
   - Theme management
   - Animation engine

2. **Style Presets** (`STYLE_PRESETS.md`)
   - Theme definitions
   - Color palettes
   - Typography scales
   - Layout grids

3. **Prompt Templates** (`PROMPT_TEMPLATES.md`)
   - Content optimization patterns
   - Story structure templates
   - Visual suggestion logic

4. **Examples** (`EXAMPLES.md`)
   - Sample slide decks
   - Use case demonstrations
   - Best practices

## Installation

This skill is ready to use. Simply invoke it with your slide generation request.

## Extending the Skill

### Adding New Themes

1. Define color palette and typography in `STYLE_PRESETS.md`
2. Create CSS variables for the theme
3. Add theme to the theme switcher array
4. Test across all slide types

### Adding New Slide Types

1. Create HTML template structure
2. Define CSS styling for the layout
3. Add animation logic if needed
4. Document usage in `EXAMPLES.md`

### Customizing Animations

Edit the CSS animation definitions:
```css
@keyframes slideIn {
  from { transform: translateX(-100%); opacity: 0; }
  to { transform: translateX(0); opacity: 1; }
}
```

## Best Practices

### Content Guidelines
- **One idea per slide**: Keep it focused
- **6-8 words per line**: Easy to read
- **3-5 bullets max**: Avoid clutter
- **Large text**: Readable from distance
- **High contrast**: Ensure visibility

### Design Guidelines
- **Consistent spacing**: Use grid system
- **Visual hierarchy**: Size indicates importance
- **White space**: Let content breathe
- **Color purpose**: Use color meaningfully
- **Animation restraint**: Subtle, not distracting

### Technical Guidelines
- **Test in multiple browsers**: Chrome, Firefox, Safari
- **Check mobile view**: Responsive design
- **Validate accessibility**: Screen reader compatible
- **Optimize images**: Keep file size low
- **Test offline**: Ensure no external dependencies

## Keyboard Shortcuts

- `→` or `Space` - Next slide
- `←` - Previous slide
- `Home` - First slide
- `End` - Last slide
- `F` - Toggle fullscreen
- `S` - Toggle speaker notes
- `T` - Toggle theme
- `ESC` - Exit fullscreen

## Troubleshooting

### Slides not advancing
- Check JavaScript console for errors
- Ensure keyboard focus is on the presentation

### Theme not applying
- Verify theme name matches available themes
- Check CSS variable definitions

### Animations not smooth
- Enable hardware acceleration in browser
- Reduce animation complexity for older devices

### Mobile gestures not working
- Ensure touch event listeners are registered
- Check viewport meta tag is present

## Performance Optimization

- **Lazy load images**: Only load visible slides
- **CSS containment**: Isolate slide rendering
- **GPU acceleration**: Use transform and opacity
- **Debounce events**: Prevent excessive handlers
- **Minimize reflows**: Batch DOM updates

## Accessibility Features

- **ARIA landmarks**: Proper semantic structure
- **Keyboard navigation**: Full keyboard support
- **Screen reader support**: Descriptive labels
- **High contrast mode**: Readable in all modes
- **Focus indicators**: Clear focus states

## Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## File Size Targets

- Base engine: ~30KB
- With theme: ~50KB
- With content (10 slides): ~80-120KB
- With images: Varies (optimize to <150KB total)

## Security

- No external scripts
- No CDN dependencies
- No tracking code
- No cookies
- Safe to share and distribute

## License

This skill generates presentations that are yours to use, modify, and distribute freely.

## Support

For issues, feature requests, or questions about extending this skill, refer to the documentation files in this directory.

---

**Ready to create amazing presentations? Just ask!**
