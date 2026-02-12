# BLT Color Palette

The BLT design system uses a comprehensive color palette designed for accessibility and clarity in both light and dark modes.

## Brand Colors

### Primary Red
- **HEX:** `#E10101`
- **Usage:** Primary actions, CTAs, key UI elements, error states, important links
- **Tailwind:** `primary-red`

### Icon Red
- **HEX:** `#e74c3c`
- **Usage:** Interactive elements, icons, highlighted components
- **Tailwind:** `red`

## Core Colors

### Primary
- **HEX:** `#3C50E0`
- **Usage:** Primary buttons, links, interactive elements
- **Tailwind:** `primary`

### Secondary
- **HEX:** `#80CAEE`
- **Usage:** Secondary actions, hover states, accents
- **Tailwind:** `secondary`

## Neutral Colors

### Black Variants
- **Black:** `#1C2434` - Primary text
- **Black-2:** `#010101` - Deep black for dark mode
- **White:** `#FFFFFF` - Backgrounds, light text

### Gray Scale
- **Body:** `#64748B` - Body text (light mode)
- **Bodydark:** `#AEB7C0` - Body text (dark mode)
- **Bodydark1:** `#DEE4EE` - Light borders
- **Bodydark2:** `#8A99AF` - Muted text
- **Stroke:** `#E2E8F0` - Borders (light mode)
- **Gray:** `#EFF4FB` - Background gray
- **Graydark:** `#333A48` - Dark mode gray
- **Gray-2:** `#F7F9FC` - Light backgrounds
- **Gray-3:** `#FAFAFA` - Very light backgrounds
- **Whiten:** `#F1F5F9` - Off-white
- **Whiter:** `#F5F7FD` - Lighter off-white

### Dark Mode Colors
- **Boxdark:** `#24303F` - Container backgrounds (dark mode)
- **Boxdark-2:** `#1A222C` - Nested containers (dark mode)
- **Strokedark:** `#2E3A47` - Borders (dark mode)
- **Form-strokedark:** `#3d4d60` - Form borders (dark mode)
- **Form-input:** `#1d2a39` - Input backgrounds (dark mode)

## Semantic Colors

### Success
- **HEX:** `#10B981` (meta-3) / `#219653` (success)
- **Usage:** Success messages, completed states, positive actions

### Warning
- **HEX:** `#FFA70B` / `#FFBA00` (meta-6)
- **Usage:** Warning messages, caution states

### Danger/Error
- **HEX:** `#D34053` (danger) / `#DC3545` (meta-1)
- **Usage:** Error messages, destructive actions, critical alerts

### Info
- **HEX:** `#259AE6` (meta-5)
- **Usage:** Informational messages, neutral notifications

## Meta Colors

Additional utility colors for specific use cases:

- **Meta-1:** `#DC3545` - Red accent
- **Meta-2:** `#EFF2F7` - Light gray
- **Meta-3:** `#10B981` - Green
- **Meta-4:** `#313D4A` - Dark gray
- **Meta-5:** `#259AE6` - Blue
- **Meta-6:** `#FFBA00` - Yellow
- **Meta-7:** `#FF6766` - Light red
- **Meta-8:** `#F0950C` - Orange
- **Meta-9:** `#E5E7EB` - Border gray

## OWASP Brand Colors (Optional)

For alignment with broader OWASP branding:

- **Deep Blue:** `#142a3a`
- **Light Yellow:** `#f5f03e`
- **Slate Gray:** `#344851`

## Color Usage Guidelines

### Accessibility
- Ensure minimum contrast ratio of 4.5:1 for text
- Use high contrast for interactive elements
- Test color combinations in both light and dark modes

### Hierarchy
1. **Primary Red** - Main CTAs and critical actions
2. **Primary Blue** - Secondary actions and links
3. **Gray Scale** - Content hierarchy and structure
4. **Semantic Colors** - Status and feedback

### Dark Mode
- Use `boxdark` and `boxdark-2` for container backgrounds
- Use `strokedark` for borders
- Use `bodydark` for text
- Maintain contrast ratios in dark mode

## Examples

```css
/* Light Mode Button */
.btn-primary {
  background-color: #E10101;
  color: #FFFFFF;
  border: 1px solid #E10101;
}

/* Dark Mode Container */
.card-dark {
  background-color: #24303F;
  border: 1px solid #2E3A47;
  color: #AEB7C0;
}

/* Success State */
.alert-success {
  background-color: #10B981;
  color: #FFFFFF;
}
```
