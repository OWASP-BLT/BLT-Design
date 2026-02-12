# BLT Typography System

The BLT design system uses a modern, readable typography scale optimized for digital interfaces.

## Font Families

### Primary Font: Satoshi
- **Family:** `'Satoshi', sans-serif`
- **Usage:** Headings, display text, emphasis
- **Weights:** 400 (Regular), 500 (Medium), 600 (Semi-Bold), 700 (Bold)

### Secondary Font: Open Sans
- **Family:** `'Open Sans', sans-serif`
- **Usage:** Body text, UI components, general content
- **Weights:** 300 (Light), 400 (Regular), 600 (Semi-Bold), 700 (Bold)

## Font Size Scale

### Title Sizes

| Name | Size | Line Height | Usage |
|------|------|-------------|-------|
| `title-xxl` | 44px | 55px | Hero headings, landing pages |
| `title-xl` | 36px | 45px | Main page headings |
| `title-xl2` | 33px | 45px | Alternative large headings |
| `title-lg` | 28px | 35px | Section headings |
| `title-md` | 24px | 30px | Subsection headings |
| `title-md2` | 26px | 30px | Alternative medium headings |
| `title-sm` | 20px | 26px | Card headings, small sections |
| `title-xsm` | 18px | 24px | Smallest heading size |

### Body Sizes (Default Tailwind Scale)

| Name | Size | Usage |
|------|------|-------|
| `text-xs` | 12px | Captions, labels |
| `text-sm` | 14px | Small body text, metadata |
| `text-base` | 16px | Default body text |
| `text-lg` | 18px | Large body text, emphasis |
| `text-xl` | 20px | Prominent text |
| `text-2xl` | 24px | Large text |

## Typography Classes

### Headings

```html
<!-- Extra Extra Large Title -->
<h1 class="font-satoshi text-title-xxl font-bold text-black dark:text-white">
  Main Hero Heading
</h1>

<!-- Extra Large Title -->
<h1 class="font-satoshi text-title-xl font-bold text-black dark:text-white">
  Page Heading
</h1>

<!-- Large Title -->
<h2 class="font-satoshi text-title-lg font-semibold text-black dark:text-white">
  Section Heading
</h2>

<!-- Medium Title -->
<h3 class="font-satoshi text-title-md font-semibold text-black dark:text-white">
  Subsection Heading
</h3>

<!-- Small Title -->
<h4 class="font-satoshi text-title-sm font-medium text-black dark:text-white">
  Card Heading
</h4>
```

### Body Text

```html
<!-- Regular Body -->
<p class="font-sans text-base text-body dark:text-bodydark">
  Standard paragraph text for general content.
</p>

<!-- Large Body -->
<p class="font-sans text-lg text-body dark:text-bodydark">
  Emphasized or important paragraph text.
</p>

<!-- Small Body -->
<p class="font-sans text-sm text-bodydark2 dark:text-bodydark">
  Secondary information, metadata, captions.
</p>

<!-- Extra Small -->
<span class="font-sans text-xs text-bodydark2 dark:text-bodydark">
  Labels, timestamps, tiny details.
</span>
```

## Font Weights

- **Light (300):** Rarely used, only for very large display text
- **Regular (400):** Default body text weight
- **Medium (500):** Slightly emphasized text
- **Semi-Bold (600):** Subheadings, important labels
- **Bold (700):** Main headings, strong emphasis

## Line Height

- **Tight (1.2):** Headings and display text
- **Normal (1.5):** Default body text
- **Relaxed (1.75):** Long-form content, articles
- **Loose (2.0):** Very spacious layouts

## Letter Spacing

- **Tighter (-0.05em):** Large headings
- **Normal (0):** Default for most text
- **Wide (0.05em):** Uppercase text, labels
- **Wider (0.1em):** All-caps headings

## Text Colors

### Light Mode
- **Primary Text:** `text-black` (#1C2434)
- **Body Text:** `text-body` (#64748B)
- **Muted Text:** `text-bodydark2` (#8A99AF)

### Dark Mode
- **Primary Text:** `text-white` (#FFFFFF)
- **Body Text:** `text-bodydark` (#AEB7C0)
- **Muted Text:** `text-bodydark2` (#8A99AF)

## Usage Guidelines

### Hierarchy
1. Use larger, bolder fonts for more important content
2. Maintain consistent spacing between heading levels
3. Use font family to differentiate headings (Satoshi) from body (Open Sans)

### Readability
- Keep line length between 45-75 characters
- Use adequate line height for body text (1.5 minimum)
- Ensure sufficient contrast between text and background

### Responsive Typography
```html
<!-- Mobile to Desktop Responsive Heading -->
<h1 class="text-title-md md:text-title-lg lg:text-title-xl font-satoshi font-bold">
  Responsive Heading
</h1>

<!-- Responsive Body Text -->
<p class="text-sm md:text-base lg:text-lg font-sans">
  Responsive paragraph text.
</p>
```

### Accessibility
- Minimum font size: 14px (text-sm)
- Use proper semantic HTML tags (h1-h6, p, span)
- Ensure color contrast meets WCAG AA standards (4.5:1 for body, 3:1 for large text)
- Never rely solely on font size or color to convey meaning

## Examples

### Article Layout
```html
<article class="max-w-4xl mx-auto">
  <h1 class="font-satoshi text-title-xl font-bold text-black dark:text-white mb-4">
    Article Title
  </h1>
  <p class="font-sans text-sm text-bodydark2 dark:text-bodydark mb-6">
    Published on January 1, 2024
  </p>
  <p class="font-sans text-base text-body dark:text-bodydark leading-relaxed mb-4">
    First paragraph of the article with regular body text...
  </p>
  <h2 class="font-satoshi text-title-md font-semibold text-black dark:text-white mt-8 mb-4">
    Section Heading
  </h2>
  <p class="font-sans text-base text-body dark:text-bodydark leading-relaxed">
    More content here...
  </p>
</article>
```

### Card Component
```html
<div class="bg-white dark:bg-boxdark rounded-lg p-6">
  <h3 class="font-satoshi text-title-sm font-medium text-black dark:text-white mb-2">
    Card Title
  </h3>
  <p class="font-sans text-sm text-body dark:text-bodydark mb-4">
    Card description text goes here.
  </p>
  <span class="font-sans text-xs text-bodydark2 dark:text-bodydark">
    Last updated: 2 hours ago
  </span>
</div>
```
