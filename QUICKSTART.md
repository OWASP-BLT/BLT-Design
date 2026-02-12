# BLT Design System - Quick Reference

## 🚀 Quick Start

### Installation
```bash
npm install @owasp-blt/design-system
```

### Basic Setup
```javascript
// tailwind.config.js
module.exports = require('@owasp-blt/design-system/tailwind.config.js')
```

## 🎨 Color Tokens

```html
<!-- Brand Colors -->
<div class="bg-primary-red">Primary Brand Red (#E10101)</div>
<div class="bg-red">Icon Red (#e74c3c)</div>

<!-- Core Colors -->
<div class="bg-primary">Primary (#3C50E0)</div>
<div class="bg-secondary">Secondary (#80CAEE)</div>

<!-- Semantic Colors -->
<div class="bg-success">Success (#219653)</div>
<div class="bg-danger">Danger (#D34053)</div>
<div class="bg-warning">Warning (#FFA70B)</div>

<!-- Text Colors -->
<p class="text-black dark:text-white">Primary Text</p>
<p class="text-body dark:text-bodydark">Body Text</p>
```

## 📝 Typography

```html
<!-- Headings -->
<h1 class="font-satoshi text-title-xl font-bold">Main Heading (36px)</h1>
<h2 class="font-satoshi text-title-lg font-semibold">Section (28px)</h2>
<h3 class="font-satoshi text-title-md font-medium">Subsection (24px)</h3>

<!-- Body Text -->
<p class="font-sans text-base text-body dark:text-bodydark">
  Regular body text (16px)
</p>
```

## 🔘 Buttons

```html
<!-- Primary -->
<button class="bg-primary-red hover:bg-red text-white px-6 py-3 rounded-lg">
  Primary
</button>

<!-- Secondary -->
<button class="bg-primary hover:bg-opacity-90 text-white px-6 py-3 rounded-lg">
  Secondary
</button>

<!-- Outline -->
<button class="border-2 border-primary-red text-primary-red hover:bg-primary-red hover:text-white px-6 py-3 rounded-lg">
  Outline
</button>
```

## 🎴 Cards

```html
<div class="bg-white dark:bg-boxdark rounded-lg shadow-card p-6 border border-stroke dark:border-strokedark">
  <h3 class="font-satoshi text-title-sm font-medium text-black dark:text-white mb-2">
    Card Title
  </h3>
  <p class="text-sm text-body dark:text-bodydark">
    Card content here
  </p>
</div>
```

## 📝 Forms

```html
<input 
  type="text"
  class="w-full px-4 py-3 border border-stroke dark:border-form-strokedark bg-white dark:bg-form-input text-black dark:text-white rounded-lg focus:border-primary focus:ring-2 focus:ring-primary focus:ring-opacity-20 outline-none"
>
```

## ⚠️ Alerts

```html
<!-- Success -->
<div class="bg-meta-3 bg-opacity-10 border-l-4 border-meta-3 px-6 py-4 rounded-lg">
  <h4 class="font-semibold text-meta-3">Success!</h4>
  <p class="text-body dark:text-bodydark">Message here</p>
</div>

<!-- Error -->
<div class="bg-danger bg-opacity-10 border-l-4 border-danger px-6 py-4 rounded-lg">
  <h4 class="font-semibold text-danger">Error!</h4>
  <p class="text-body dark:text-bodydark">Message here</p>
</div>
```

## 🏷️ Badges

```html
<span class="inline-flex px-3 py-1 rounded-full text-xs font-medium bg-primary-red text-white">
  Badge
</span>
```

## 📏 Spacing

```html
<!-- Padding -->
<div class="p-4">16px all sides</div>
<div class="px-6 py-4">24px horizontal, 16px vertical</div>

<!-- Margin -->
<div class="m-4">16px margin</div>
<div class="mb-6">24px bottom margin</div>

<!-- Gap (Flexbox/Grid) -->
<div class="flex gap-4">16px gap between items</div>
```

## 🌓 Dark Mode

```html
<!-- Enable dark mode -->
<html class="dark">
  <!-- Content automatically adapts -->
</html>

<!-- Toggle with JavaScript -->
<script>
  document.documentElement.classList.toggle('dark')
</script>
```

## 📱 Responsive Design

```html
<!-- Mobile to Desktop -->
<div class="text-sm md:text-base lg:text-lg">
  Responsive text size
</div>

<div class="p-4 md:p-6 lg:p-8">
  Responsive padding
</div>

<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
  <!-- Responsive grid -->
</div>
```

## 🎯 Common Patterns

### Page Layout
```html
<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
  <!-- Content -->
</div>
```

### Container
```html
<div class="bg-white dark:bg-boxdark rounded-lg shadow-card p-6">
  <!-- Content -->
</div>
```

### Section Spacing
```html
<section class="py-12 md:py-16 lg:py-24">
  <!-- Content -->
</section>
```

## 📚 Full Documentation

- [Colors](./colors/README.md) - Complete color palette
- [Typography](./typography/README.md) - Font system
- [Spacing](./spacing/README.md) - Spacing utilities
- [Components](./components/README.md) - All components
- [Logos](./logos/README.md) - Brand guidelines

## 🔗 Resources

- [Main BLT Repo](https://github.com/OWASP-BLT/BLT)
- [BLT Documentation](https://owasp-blt.github.io/documentation/)
- [Tailwind CSS Docs](https://tailwindcss.com/docs)

## 💡 Tips

1. **Always use design tokens** - Don't hardcode colors or spacing
2. **Support dark mode** - Use `dark:` prefix for dark mode styles
3. **Be responsive** - Use responsive breakpoints (sm, md, lg, xl)
4. **Maintain accessibility** - Ensure proper contrast and semantic HTML
5. **Use the example** - Check `examples/index.html` for patterns

---

*For detailed documentation, see the individual README files in each directory.*
