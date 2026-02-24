# AI Slides

An AI-powered skill for creating stunning HTML presentations with intelligent content optimization, premium themes, and zero dependencies.

## What This Does

AI Slides transforms your ideas, blog posts, or LinkedIn content into professional slide decks. Unlike traditional tools, it doesn't just template your content — it analyzes, optimizes, and structures it for maximum impact. Think of it as having a presentation designer and content strategist working together.

## Key Features

**AI-Powered Content Optimization** — Rewrites for clarity, structures story flow, suggests visuals, and converts formats (blog → slides, LinkedIn → deck).

**Zero Dependencies** — Single HTML files with inline CSS/JS. No npm, no build tools, no frameworks. Works offline forever.

**5 Premium Themes** — Professional designs that rival PowerPoint and Keynote. Switch themes live during presentation.

**Smart Slide Types** — Title, stats dashboards, timelines, comparisons, quotes, charts, CTAs — all with smooth animations.

**Production Quality** — Accessible (ARIA), responsive, <150KB, GPU-optimized, works everywhere.

## Installation

### For Claude Code Users

Copy the skill files to your Claude Code skills directory:

```bash
# Create the skill directory
mkdir -p ~/.claude/skills/ai-slides

# Copy the files
cp SKILL.md ~/.claude/skills/ai-slides/
cp STYLE_PRESETS.md ~/.claude/skills/ai-slides/
cp PROMPT_TEMPLATES.md ~/.claude/skills/ai-slides/
cp EXAMPLES.md ~/.claude/skills/ai-slides/
```

Then use it by typing `/ai-slides` in Claude Code.

### Manual Download

1. Download all `.md` files from this repo
2. Place them in `~/.claude/skills/ai-slides/`
3. Restart Claude Code

## Usage

### Create a New Presentation

```
/ai-slides

> "Create a 5-slide pitch deck about AI automation"
```

The skill will:
1. Analyze your topic and structure the narrative
2. Optimize content for slide format
3. Suggest appropriate theme and layouts
4. Generate a self-contained HTML file
5. Open it in your browser

### Convert Content to Slides

```
/ai-slides

> "Turn this blog post into slides:
[paste your content]"
```

The skill will:
1. Extract key messages and main points
2. Rewrite for clarity and impact
3. Structure into logical slide flow
4. Add visual elements (stats, quotes, charts)
5. Generate production-ready presentation

### Advanced Usage

```
/ai-slides

> "Generate slides with:
- Topic: Q4 Performance Review
- Theme: Data Storytelling
- Slides: Title, Summary, Revenue chart, Customer metrics, Timeline, Action items
- Include animated stats and comparison slide"
```

## Included Themes

### Professional
**Minimal Corporate** — Clean, business-ready, trustworthy
**Apple Keynote** — Bold typography, high contrast, minimal

### Tech-Forward
**Dark Futuristic** — Dark mode, neon accents, particle effects
**AI Startup** — Modern gradients, vibrant, pitch-ready

### Data-Focused
**Data Storytelling** — Chart-optimized, grid layouts, analytics-ready

## Output Example

Each presentation is a single, self-contained HTML file:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Your Presentation</title>
    <style>
        /* All CSS inline - themes, animations, responsive */
        :root {
            --primary: #2563eb;
            --text: #0f172a;
            /* ... */
        }
    </style>
</head>
<body>
    <div id="presentation">
        <div class="slide slide-title active">
            <h1>Your Title</h1>
            <p class="subtitle">Compelling subtitle</p>
        </div>

        <div class="slide">
            <h2>Key Points</h2>
            <ul>
                <li>First insight</li>
                <li>Second insight</li>
            </ul>
        </div>

        <!-- More slides... -->
    </div>

    <script>
        // Navigation, animations, theme switching - all inline
    </script>
</body>
</html>
```

Features included:
- Keyboard navigation (arrows, space, home, end)
- Touch/swipe support (mobile)
- Live theme switching (press T)
- Speaker notes (press S)
- Fullscreen mode (press F)
- Progress indicator
- Smooth GPU-accelerated animations
- Responsive design
- Accessibility (ARIA, keyboard nav)

## Philosophy

This skill was built on these beliefs:

**AI should enhance, not replace.** The AI optimizes your content and suggests improvements, but you stay in control.

**Dependencies are debt.** A single HTML file will work in 10 years. A React project from 2019? Good luck.

**Design matters.** Every presentation should look custom-crafted, not template-generated.

**Accessibility is essential.** Beautiful slides that everyone can use and navigate.

**Comments are kindness.** Generated code explains itself to future-you.

## What Makes This Different

### vs. PowerPoint/Keynote
- ✅ Single HTML file (no proprietary format)
- ✅ Works on any device with a browser
- ✅ AI content optimization built-in
- ✅ Version control friendly (plain text)
- ✅ No software license required

### vs. Reveal.js
- ✅ Zero dependencies (no npm, no build)
- ✅ AI-powered content structuring
- ✅ Smaller file size (<150KB vs 500KB+)
- ✅ Live theme switching
- ✅ Simpler to customize

### vs. Google Slides
- ✅ Works offline forever
- ✅ No account required
- ✅ Complete privacy (no tracking)
- ✅ AI content optimization
- ✅ Professional themes out of the box

## Files

| File | Purpose |
|------|---------|
| `SKILL.md` | Main skill instructions for Claude Code |
| `STYLE_PRESETS.md` | 5 curated theme definitions with color palettes |
| `PROMPT_TEMPLATES.md` | AI patterns for content optimization |
| `EXAMPLES.md` | Real-world examples and best practices |
| `templates/base-engine.html` | Core slide engine (reference) |
| `templates/presets/*.html` | Sample presentations |

## Real-World Examples

### Startup Pitch (8 slides)
```
/ai-slides

> "Create an investor pitch with problem, solution, traction,
timeline, team, and CTA. Use AI Startup theme."
```

**Output**: `sample-startup-pitch.html`
- Gradient hero slide
- Stats dashboard with animated counters
- Timeline with milestones
- Before/After comparison
- Customer testimonial quote
- Strong CTA

### Product Launch (6 slides)
```
/ai-slides

> "Create a product launch keynote with hero feature,
features grid, performance stats, and pricing.
Use Apple Keynote theme."
```

**Output**: `sample-product-launch.html`
- Dramatic title slide
- Large hero number (10×)
- Feature grid (2×2)
- Performance metrics
- Pricing table
- Download CTA

### Data Report (7 slides)
```
/ai-slides

> "Generate Q4 performance review with summary,
revenue chart, customer metrics, and action items.
Use Data Storytelling theme."
```

**Output**: Professional quarterly report
- Executive summary
- Revenue trend visualization
- Customer acquisition metrics
- Market analysis
- Challenges and opportunities
- Q1 priorities

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `→` or `Space` | Next slide |
| `←` | Previous slide |
| `Home` | First slide |
| `End` | Last slide |
| `F` | Toggle fullscreen |
| `S` | Toggle speaker notes |
| `T` | Cycle themes |
| `ESC` | Exit fullscreen |

## Customization

### Add Your Own Theme

1. Edit `STYLE_PRESETS.md` with your color palette
2. Add CSS variables to generated HTML:
```css
:root[data-theme="your-theme"] {
  --primary: #your-color;
  --background: #your-bg;
  /* ... */
}
```
3. Add theme name to switcher array in JavaScript

### Embed Images

```html
<img src="your-image.jpg" alt="Description">
```

### Embed Videos

```html
<video src="demo.mp4" controls></video>
```

### Add Custom Animations

```css
@keyframes yourAnimation {
  from { opacity: 0; transform: scale(0.8); }
  to { opacity: 1; transform: scale(1); }
}
```

## Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

| Metric | Target | Achieved |
|--------|--------|----------|
| File size (10 slides) | <150KB | ~90KB |
| Initial load | <100ms | ~50ms |
| Slide transition | <300ms | ~250ms |
| Animation FPS | 60fps | 60fps |

## Privacy & Security

- ✅ No external scripts or CDN dependencies
- ✅ No tracking, analytics, or cookies
- ✅ No data sent to external servers
- ✅ Safe to share and distribute
- ✅ Works completely offline

## Common Use Cases

- **Investor Pitches** — Problem, solution, traction, team, ask
- **Product Launches** — Features, benefits, pricing, CTA
- **Conference Talks** — Title, problem, approach, results, demo
- **Training Sessions** — Agenda, principles, examples, practice
- **Sales Presentations** — Pain points, solution, case studies, pricing
- **Data Reports** — Summary, metrics, trends, insights, actions

## Troubleshooting

**Slides not advancing?**
Check JavaScript console for errors. Ensure keyboard focus is on the presentation.

**Theme not changing?**
Press `T` to cycle themes. Verify theme name in HTML matches available themes.

**Animations choppy?**
Enable hardware acceleration in browser settings. Close other tabs.

**Mobile gestures not working?**
Swipe directly on the slide area. Refresh the page if needed.

## Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Claude Code (for skill usage)
- No other dependencies

## Credits

Built with Claude Code for creators who value quality, speed, and simplicity.

Inspired by the philosophy that beautiful presentations shouldn't require design expertise — just good content and smart AI.

## License

MIT — Use it, modify it, share it. Generated presentations are yours to use freely.

---

**Ready to create stunning presentations?** Just ask, and watch your ideas transform into beautiful slides.
