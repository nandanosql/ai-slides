# Style Presets

Complete theme definitions for the AI Slides system. Each theme includes color palette, typography, spacing, and animation preferences.

---

## 1. Minimal Corporate

**Use Case**: Business presentations, corporate meetings, professional pitches

**Color Palette**
```css
--primary: #2563eb;      /* Blue 600 */
--secondary: #64748b;    /* Slate 500 */
--accent: #0ea5e9;       /* Sky 500 */
--background: #ffffff;   /* White */
--surface: #f8fafc;      /* Slate 50 */
--text: #0f172a;         /* Slate 900 */
--text-muted: #64748b;   /* Slate 500 */
--border: #e2e8f0;       /* Slate 200 */
```

**Typography**
```css
--font-primary: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
--font-heading: 'Inter', sans-serif;
--font-mono: 'JetBrains Mono', monospace;

--text-xs: 0.75rem;      /* 12px */
--text-sm: 0.875rem;     /* 14px */
--text-base: 1rem;       /* 16px */
--text-lg: 1.125rem;     /* 18px */
--text-xl: 1.25rem;      /* 20px */
--text-2xl: 1.5rem;      /* 24px */
--text-3xl: 1.875rem;    /* 30px */
--text-4xl: 2.25rem;     /* 36px */
--text-5xl: 3rem;        /* 48px */
--text-6xl: 3.75rem;     /* 60px */
```

**Spacing**
```css
--spacing-unit: 8px;
--slide-padding: 80px;
--content-max-width: 1200px;
```

**Animations**
```css
--transition-speed: 0.3s;
--animation-easing: cubic-bezier(0.4, 0, 0.2, 1);
```

---

## 2. Apple Keynote Style

**Use Case**: Product launches, design showcases, bold statements

**Color Palette**
```css
--primary: #000000;      /* Pure Black */
--secondary: #86868b;    /* Gray */
--accent: #0071e3;       /* Apple Blue */
--background: #ffffff;   /* White */
--surface: #f5f5f7;      /* Light Gray */
--text: #1d1d1f;         /* Near Black */
--text-muted: #86868b;   /* Gray */
--border: #d2d2d7;       /* Border Gray */
```

**Typography**
```css
--font-primary: 'SF Pro Display', -apple-system, BlinkMacSystemFont, sans-serif;
--font-heading: 'SF Pro Display', sans-serif;
--font-mono: 'SF Mono', monospace;

--text-xs: 0.875rem;     /* 14px */
--text-sm: 1rem;         /* 16px */
--text-base: 1.125rem;   /* 18px */
--text-lg: 1.25rem;      /* 20px */
--text-xl: 1.5rem;       /* 24px */
--text-2xl: 2rem;        /* 32px */
--text-3xl: 2.5rem;      /* 40px */
--text-4xl: 3.5rem;      /* 56px */
--text-5xl: 4.5rem;      /* 72px */
--text-6xl: 6rem;        /* 96px */
```

**Spacing**
```css
--spacing-unit: 8px;
--slide-padding: 100px;
--content-max-width: 1400px;
```

**Animations**
```css
--transition-speed: 0.4s;
--animation-easing: cubic-bezier(0.28, 0.11, 0.32, 1);
```

**Special Features**
- Extra bold headings (font-weight: 700)
- Generous white space
- Large hero text
- Minimal borders

---

## 3. Dark Futuristic

**Use Case**: Tech presentations, developer talks, AI/ML topics

**Color Palette**
```css
--primary: #8b5cf6;      /* Violet 500 */
--secondary: #6366f1;    /* Indigo 500 */
--accent: #06b6d4;       /* Cyan 500 */
--background: #0f172a;   /* Slate 900 */
--surface: #1e293b;      /* Slate 800 */
--text: #f1f5f9;         /* Slate 100 */
--text-muted: #94a3b8;   /* Slate 400 */
--border: #334155;       /* Slate 700 */
--glow: rgba(139, 92, 246, 0.5);
```

**Typography**
```css
--font-primary: 'Space Grotesk', sans-serif;
--font-heading: 'Space Grotesk', sans-serif;
--font-mono: 'Fira Code', monospace;

--text-xs: 0.75rem;
--text-sm: 0.875rem;
--text-base: 1rem;
--text-lg: 1.125rem;
--text-xl: 1.25rem;
--text-2xl: 1.5rem;
--text-3xl: 2rem;
--text-4xl: 2.5rem;
--text-5xl: 3.5rem;
--text-6xl: 4.5rem;
```

**Spacing**
```css
--spacing-unit: 8px;
--slide-padding: 80px;
--content-max-width: 1200px;
```

**Animations**
```css
--transition-speed: 0.35s;
--animation-easing: cubic-bezier(0.34, 1.56, 0.64, 1);
```

**Special Features**
- Neon glow effects
- Gradient text
- Animated borders
- Code syntax highlighting

---

## 4. AI Startup Pitch

**Use Case**: Investor pitches, startup demos, growth stories

**Color Palette**
```css
--primary: #6366f1;      /* Indigo 500 */
--secondary: #8b5cf6;    /* Violet 500 */
--accent: #ec4899;       /* Pink 500 */
--background: #ffffff;   /* White */
--surface: #fafafa;      /* Neutral 50 */
--text: #171717;         /* Neutral 900 */
--text-muted: #737373;   /* Neutral 500 */
--border: #e5e5e5;       /* Neutral 200 */
--gradient-start: #6366f1;
--gradient-end: #ec4899;
```

**Typography**
```css
--font-primary: 'Outfit', sans-serif;
--font-heading: 'Outfit', sans-serif;
--font-mono: 'IBM Plex Mono', monospace;

--text-xs: 0.75rem;
--text-sm: 0.875rem;
--text-base: 1rem;
--text-lg: 1.125rem;
--text-xl: 1.375rem;
--text-2xl: 1.75rem;
--text-3xl: 2.25rem;
--text-4xl: 3rem;
--text-5xl: 4rem;
--text-6xl: 5rem;
```

**Spacing**
```css
--spacing-unit: 8px;
--slide-padding: 80px;
--content-max-width: 1100px;
```

**Animations**
```css
--transition-speed: 0.4s;
--animation-easing: cubic-bezier(0.16, 1, 0.3, 1);
```

**Special Features**
- Gradient backgrounds
- Rounded corners
- Animated metrics
- Bold CTAs

---

## 5. Data Storytelling

**Use Case**: Analytics presentations, research findings, data reports

**Color Palette**
```css
--primary: #0891b2;      /* Cyan 600 */
--secondary: #0ea5e9;    /* Sky 500 */
--accent: #f59e0b;       /* Amber 500 */
--background: #ffffff;   /* White */
--surface: #f0f9ff;      /* Sky 50 */
--text: #0c4a6e;         /* Sky 900 */
--text-muted: #0369a1;   /* Sky 700 */
--border: #bae6fd;       /* Sky 200 */
--chart-1: #0891b2;      /* Cyan 600 */
--chart-2: #0ea5e9;      /* Sky 500 */
--chart-3: #f59e0b;      /* Amber 500 */
--chart-4: #8b5cf6;      /* Violet 500 */
--chart-5: #ec4899;      /* Pink 500 */
```

**Typography**
```css
--font-primary: 'IBM Plex Sans', sans-serif;
--font-heading: 'IBM Plex Sans', sans-serif;
--font-mono: 'IBM Plex Mono', monospace;

--text-xs: 0.75rem;
--text-sm: 0.875rem;
--text-base: 1rem;
--text-lg: 1.125rem;
--text-xl: 1.25rem;
--text-2xl: 1.5rem;
--text-3xl: 1.875rem;
--text-4xl: 2.25rem;
--text-5xl: 3rem;
--text-6xl: 3.75rem;
```

**Spacing**
```css
--spacing-unit: 8px;
--slide-padding: 80px;
--content-max-width: 1300px;
```

**Animations**
```css
--transition-speed: 0.3s;
--animation-easing: cubic-bezier(0.4, 0, 0.2, 1);
```

**Special Features**
- Chart-optimized colors
- Grid backgrounds
- Number animations
- Data visualization focus

---

## Theme Implementation Guide

### CSS Variable Structure

Each theme is implemented using CSS custom properties:

```css
:root[data-theme="theme-name"] {
  /* Colors */
  --primary: value;
  --secondary: value;
  /* ... */

  /* Typography */
  --font-primary: value;
  /* ... */

  /* Spacing */
  --spacing-unit: value;
  /* ... */

  /* Animations */
  --transition-speed: value;
  /* ... */
}
```

### Theme Switching

Themes are switched by changing the `data-theme` attribute on the root element:

```javascript
document.documentElement.setAttribute('data-theme', 'apple-keynote');
```

### Creating Custom Themes

1. Copy an existing theme definition
2. Modify color palette and typography
3. Test across all slide types
4. Add to theme switcher array
5. Document in this file

### Font Loading

Themes use system fonts as fallbacks. For custom fonts:

```css
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');
```

Or embed fonts directly in the HTML for offline use.

### Responsive Adjustments

All themes include responsive breakpoints:

```css
@media (max-width: 768px) {
  :root {
    --text-6xl: 3rem;
    --slide-padding: 40px;
  }
}
```

---

## Color Psychology Guide

**Blue (Corporate, Keynote)**: Trust, professionalism, stability
**Purple/Violet (Futuristic, Startup)**: Innovation, creativity, luxury
**Cyan/Teal (Data)**: Clarity, precision, intelligence
**Pink/Magenta (Startup)**: Energy, passion, boldness
**Dark (Futuristic)**: Sophistication, focus, modernity

---

## Accessibility Considerations

All themes maintain:
- **Contrast ratio**: Minimum 4.5:1 for text
- **Focus indicators**: Visible keyboard focus
- **Color independence**: Information not conveyed by color alone
- **Readable fonts**: Minimum 16px base size
- **Clear hierarchy**: Size and weight differentiation
