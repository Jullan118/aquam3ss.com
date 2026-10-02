# HAZE — Parametric Sunglasses

A project showcase website demonstrating computational design and parametric modeling concepts for an adaptive sunglasses product line.

## Overview

HAZE is an interactive showcase of parametric design principles applied to product development. The site features smooth animations that represent the continuous variation and adaptation inherent in computational design systems.

## Project Structure

```
haze/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet with animations
├── README.md           # Project documentation
└── assets/
    ├── head-model.png  # 3D head model for rotation animation
    └── wave.png        # Wave pattern for continuous animation
```

## Features

- **Rotating Head Model**: 3D parametric head model with continuous 360° rotation animation (25s cycle)
- **Wave Animation**: Dynamic wave pattern demonstrating flow and continuous variation (12s cycle)
- **Dark Aesthetic**: Professional dark theme with neon accent lighting
- **Responsive Design**: Optimized for desktop, tablet, and mobile displays
- **Performance Optimized**: CSS-based animations for smooth 60fps performance

## Setup

1. Clone or download this repository
2. Add your parametric model images to the `assets/` folder:
   - `head-model.png` — 3D head model (square dimensions recommended)
   - `wave.png` — Wave pattern (horizontal dimensions recommended)
3. Open `index.html` in a modern web browser

## Styling

The site uses **Archivo** as the primary font family, imported from Google Fonts. Colors are optimized for a dark computational design aesthetic:

- Background: Dark charcoal gradient (#1a1819 to #221f20)
- Accent: Neon blue drop shadows (rgba(65, 105, 225, 0.3))

## Animations

### Rotate Animation
- Duration: 25 seconds
- Effect: Full 360° Y-axis rotation
- Loop: Infinite, linear

### Wave Animation
- Duration: 12 seconds
- Effect: Horizontal translation at -50%
- Loop: Infinite, linear

## Browser Support

Optimized for modern browsers supporting:
- CSS 3D transforms (`rotateY`)
- CSS animations and keyframes
- CSS gradients and filters
- CSS Grid and Flexbox

Recommended: Chrome, Firefox, Safari, Edge (latest versions)

## Integration

This project is designed to integrate seamlessly into the aquam3ss.com portfolio website. Copy the entire project folder into your portfolio projects directory and link to `index.html` from your portfolio index.

## Notes

- Images in the `assets/` folder are placeholders. Replace with your own parametric design visualizations.
- All text content has been removed to keep the focus on visual animation and interaction.
- The site is fully responsive and will adapt to different screen sizes.
