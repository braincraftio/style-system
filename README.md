# 🦄 Aurora Design System

> Where enterprise meets whimsy - A modern design system that brings joy to professional software through thoughtful color, subtle animation, and accessible components.

## 🎨 Overview

Aurora Design System is a cotton-candy-serious approach to enterprise UI design. Professional enough for the boardroom, whimsical enough for the ice cream parlor.

### Key Features

- **🍭 Lavender-Grey Color Palette**: Warm, inviting neutrals with subtle lavender influence
- **🌙 Cozy Dark Mode**: Dark surfaces mixed with lavender warmth for comfortable night viewing
- **✨ Modern CSS Architecture**: Built with CSS layers, custom properties, and container queries
- **♿ Accessibility First**: WCAG AAA compliant with APCA contrast calculations
- **📱 Fully Responsive**: Fluid typography and flexible layouts
- **🎪 Whimsical Interactions**: Subtle animations that delight without distraction

## 🚀 Quick Start

### View Live Demo

Visit the live demo at: `https://[your-username].github.io/style-system/`

### Local Development

1. Clone the repository
2. Open `index.html` in your browser
3. Or run a local server:
   ```bash
   python3 -m http.server 8080
   # Visit http://localhost:8080
   ```

## 🎨 Color System

### Primary Palette
- **Lavender Dream**: Soft purple for primary actions
- **Mint Whisper**: Fresh green for success states
- **Peach Bloom**: Warm orange for accents
- **Sky Mist**: Cool blue for information

### Neutral Foundation
- **Warm Cream**: Light backgrounds with subtle warmth
- **Soft Cream**: Secondary surfaces
- **Lavender Slate**: Text and UI elements with lavender influence
- **Twilight Slate**: Deep purple-grey for strong contrast

## 🛠️ Components

### Interactive Elements
- **Buttons**: Primary, secondary, and ghost variants with multiple sizes
- **Forms**: Inputs, textareas, selects, toggles with validation states
- **Cards**: Basic, interactive, and gradient border variants
- **Modals**: Accessible dialogs with focus management
- **Toasts**: Non-intrusive notifications

### Visual Components
- **Alerts**: Success, warning, danger, and info styles
- **Badges & Chips**: For tags and removable items
- **Progress Bars**: Animated gradient indicators
- **Avatars**: With status indicators
- **Tooltips**: Contextual help text
- **Skeleton Loaders**: For loading states

## 📦 Deployment

This repository includes a GitHub Actions workflow that automatically deploys to GitHub Pages when you push to the main branch.

### Setup GitHub Pages

1. Go to Settings → Pages in your GitHub repository
2. Under "Source", select "GitHub Actions"
3. Push to main branch to trigger deployment
4. Your site will be available at `https://[your-username].github.io/style-system/`

## 💻 JavaScript API

```javascript
// Theme management
window.AuroraDS.theme.toggle()
window.AuroraDS.theme.set('dark')

// Modal control
window.AuroraDS.modal.show('modal-id')
window.AuroraDS.modal.hide('modal-id')

// Toast notifications
window.AuroraDS.showToast('Message', 'success')
```

## 🎯 Design Tokens

The system uses CSS custom properties for all design decisions:

```css
/* Colors */
var(--color-primary)     /* Lavender */
var(--color-secondary)   /* Mint */
var(--color-accent)      /* Peach */

/* Spacing (8px grid) */
var(--space-4)   /* 16px */
var(--space-6)   /* 24px */
var(--space-8)   /* 32px */

/* Typography */
var(--text-base)
var(--font-sans)
var(--leading-relaxed)

/* Effects */
var(--shadow-sm)
var(--radius-lg)
var(--duration-normal)
```

## ♿ Accessibility Features

- Semantic HTML structure
- ARIA labels and descriptions
- Keyboard navigation support
- Focus management for modals
- Screen reader announcements
- Reduced motion support
- High contrast mode support
- Touch target optimization

## 🚀 Browser Support

- Chrome 105+ (Full support)
- Firefox 103+ (Full support)
- Safari 15.4+ (Full support)
- Edge 105+ (Full support)

For older browsers, the system includes fallbacks:
- Hex color fallbacks for OKLCH
- Media query fallbacks for container queries
- Graceful degradation for modern CSS features

## 🤝 Contributing

We welcome contributions that maintain the whimsical-yet-professional aesthetic of Aurora Design System. This is a demonstration of the BrainCraft.io style system.

For contributions or questions, please visit [github.com/braincraftio/style-system](https://github.com/braincraftio/style-system).

## 📄 License

MIT License - Feel free to use Aurora Design System in your projects!

---

Made with 🦄✨ and a love for beautiful, accessible design.