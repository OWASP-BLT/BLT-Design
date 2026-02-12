# BLT Design System

The official design system for OWASP BLT (Bug Logging Tool) - a comprehensive collection of design tokens, components, and guidelines for building consistent and accessible user interfaces.

## 📚 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Design Tokens](#design-tokens)
- [Components](#components)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## 🎨 Overview

The BLT Design System provides a complete set of design resources including:

- **Colors** - Comprehensive color palette for light and dark modes
- **Typography** - Font families, sizes, and text styles
- **Spacing** - Consistent spacing and layout scales
- **Components** - Reusable UI components and patterns
- **Logos** - Brand assets and usage guidelines
- **Design Tokens** - CSS variables and Tailwind configuration

## ✨ Features

- 🌓 **Dark Mode Support** - Full light and dark theme support
- 🎨 **Comprehensive Color System** - Primary, semantic, and meta colors
- 📝 **Typography Scale** - Custom font sizes and type hierarchy
- 📏 **Extended Spacing** - Fine-grained spacing control
- 🧩 **UI Components** - Pre-built components with examples
- ⚡ **Tailwind CSS** - Full Tailwind configuration included
- 🎯 **Accessibility** - WCAG AA compliant color contrasts
- 📱 **Responsive** - Mobile-first responsive breakpoints

## 🚀 Getting Started

### Installation

#### Using NPM

```bash
npm install @owasp-blt/design-system
```

#### Using as a Git Submodule

```bash
git submodule add https://github.com/OWASP-BLT/BLT-Design.git
```

### Quick Start with Tailwind CSS

1. Install the design system and Tailwind CSS:

```bash
npm install @owasp-blt/design-system tailwindcss
```

2. Create or update your `tailwind.config.js`:

```javascript
module.exports = require('@owasp-blt/design-system/tailwind.config.js')
```

Or extend it with your custom configuration:

```javascript
const bltConfig = require('@owasp-blt/design-system/tailwind.config.js')

module.exports = {
  ...bltConfig,
  content: [
    ...bltConfig.content,
    './src/**/*.{html,js,jsx,ts,tsx}',
  ],
  theme: {
    ...bltConfig.theme,
    extend: {
      ...bltConfig.theme.extend,
      // Your custom extensions
    },
  },
}
```

3. Import the CSS variables (optional):

```css
@import '@owasp-blt/design-system/tokens/variables.css';
```

### Using CSS Variables Only

If you're not using Tailwind CSS, you can use the CSS variables directly:

```html
<link rel="stylesheet" href="node_modules/@owasp-blt/design-system/tokens/variables.css">
```

```css
.my-button {
  background-color: var(--color-primary-red);
  color: var(--color-white);
  padding: var(--spacing-md) var(--spacing-lg);
  border-radius: var(--radius-lg);
  font-family: var(--font-family-sans);
}
```

## 🎨 Design Tokens

### Colors

The BLT design system uses a comprehensive color palette designed for both light and dark modes.

#### Brand Colors
- **Primary Red:** `#E10101` - Main brand color, used for primary actions
- **Icon Red:** `#e74c3c` - Interactive elements and icons

#### Core Colors
- **Primary:** `#3C50E0` - Primary interactive elements
- **Secondary:** `#80CAEE` - Secondary actions and accents

#### Semantic Colors
- **Success:** `#10B981` / `#219653` - Success states
- **Warning:** `#FFA70B` / `#FFBA00` - Warning messages
- **Danger:** `#D34053` / `#DC3545` - Error states and destructive actions

[View complete color documentation →](./colors/README.md)

### Typography

Two font families power the BLT design system:

- **Satoshi** - Display and heading font
- **Open Sans** - Body text and UI elements

Custom typography scale from `title-xxl` (44px) to `title-xsm` (18px).

[View complete typography documentation →](./typography/README.md)

### Spacing

Extended spacing scale from `0.5` (2px) to `242.5` (970px) for precise layout control.

[View complete spacing documentation →](./spacing/README.md)

## 🧩 Components

Pre-built, accessible components ready to use:

- **Buttons** - Primary, secondary, outline, and ghost variants
- **Cards** - Basic cards, cards with headers and footers
- **Forms** - Inputs, textareas, selects, checkboxes, radio buttons
- **Alerts** - Success, error, warning, and info alerts
- **Badges** - Status indicators and labels
- **Navigation** - Navbar and sidebar components
- **Tables** - Data tables with sorting and actions
- **Modals** - Dialog boxes and overlays
- **Loading** - Spinners and loading states

[View complete component library →](./components/README.md)

## 💻 Usage

### Example: Button Component

```html
<!-- Primary Button -->
<button class="bg-primary-red hover:bg-red text-white font-medium px-6 py-3 rounded-lg transition-colors">
  Primary Action
</button>

<!-- Secondary Button -->
<button class="bg-primary hover:bg-opacity-90 text-white font-medium px-6 py-3 rounded-lg transition-colors">
  Secondary Action
</button>
```

### Example: Card Component

```html
<div class="bg-white dark:bg-boxdark rounded-lg shadow-card p-6 border border-stroke dark:border-strokedark">
  <h3 class="font-satoshi text-title-sm font-medium text-black dark:text-white mb-2">
    Card Title
  </h3>
  <p class="font-sans text-sm text-body dark:text-bodydark">
    Card description and content goes here.
  </p>
</div>
```

### Example: Form Input

```html
<div class="space-y-2">
  <label class="font-sans text-sm font-medium text-black dark:text-white">
    Email Address
  </label>
  <input 
    type="email" 
    placeholder="Enter your email..."
    class="w-full px-4 py-3 border border-stroke dark:border-form-strokedark bg-white dark:bg-form-input text-black dark:text-white rounded-lg focus:border-primary focus:ring-2 focus:ring-primary focus:ring-opacity-20 outline-none transition"
  >
</div>
```

### Dark Mode

Enable dark mode by adding the `dark` class to your HTML or body element:

```html
<html class="dark">
  <!-- Your content -->
</html>
```

Or toggle it dynamically with JavaScript:

```javascript
// Enable dark mode
document.documentElement.classList.add('dark')

// Disable dark mode
document.documentElement.classList.remove('dark')

// Toggle dark mode
document.documentElement.classList.toggle('dark')
```

## 📖 Documentation

Each section of the design system has detailed documentation:

- [Colors](./colors/README.md) - Complete color palette and usage guidelines
- [Typography](./typography/README.md) - Font families, sizes, and text styles
- [Spacing](./spacing/README.md) - Spacing scale and layout utilities
- [Components](./components/README.md) - UI component library with examples
- [Logos](./logos/README.md) - Brand assets and logo usage guidelines
- [Tokens](./tokens/variables.css) - CSS variables for non-Tailwind projects

## 🤝 Contributing

We welcome contributions to the BLT Design System! Here's how you can help:

1. **Report Issues** - Found a bug or have a suggestion? [Open an issue](https://github.com/OWASP-BLT/BLT-Design/issues)
2. **Submit Pull Requests** - Have a fix or improvement? Submit a PR!
3. **Improve Documentation** - Help us make the docs better
4. **Share Feedback** - Tell us how you're using the design system

### Development Setup

```bash
# Clone the repository
git clone https://github.com/OWASP-BLT/BLT-Design.git

# Navigate to the directory
cd BLT-Design

# Install dependencies
npm install
```

## 🔗 Related Projects

- [OWASP BLT](https://github.com/OWASP-BLT/BLT) - Main BLT application
- [BLT Documentation](https://owasp-blt.github.io/documentation/) - User guide and docs

## 📄 License

This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0) - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- OWASP Foundation for supporting the BLT project
- The BLT community for their contributions and feedback
- All contributors who have helped build and improve this design system

## 📞 Support

- **Documentation:** [https://owasp-blt.github.io/documentation/](https://owasp-blt.github.io/documentation/)
- **Issues:** [https://github.com/OWASP-BLT/BLT-Design/issues](https://github.com/OWASP-BLT/BLT-Design/issues)
- **Main BLT Repo:** [https://github.com/OWASP-BLT/BLT](https://github.com/OWASP-BLT/BLT)

---

Made with ❤️ by the OWASP BLT Team 
