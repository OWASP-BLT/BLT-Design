# BLT Spacing System

The BLT design system uses a comprehensive spacing scale for consistent layouts and component spacing.

## Spacing Scale

The spacing system extends Tailwind's default spacing with additional values for precise control.

### Base Units

All spacing values are based on rem units (1rem = 16px by default).

| Class | Value | Pixels | Usage |
|-------|-------|--------|-------|
| `0` | 0 | 0px | No spacing |
| `px` | 1px | 1px | Hairline borders |
| `0.5` | 0.125rem | 2px | Tiny spacing |
| `1` | 0.25rem | 4px | Extra small |
| `1.5` | 0.375rem | 6px | - |
| `2` | 0.5rem | 8px | Small |
| `2.5` | 0.625rem | 10px | - |
| `3` | 0.75rem | 12px | Default small |
| `3.5` | 0.875rem | 14px | - |
| `4` | 1rem | 16px | Base unit |

### Extended Spacing

BLT extends the standard scale with additional precise values:

| Class | Value | Pixels | Class | Value | Pixels |
|-------|-------|--------|-------|-------|--------|
| `4.5` | 1.125rem | 18px | `21` | 5.25rem | 84px |
| `5` | 1.25rem | 20px | `21.5` | 5.375rem | 86px |
| `5.5` | 1.375rem | 22px | `22` | 5.5rem | 88px |
| `6` | 1.5rem | 24px | `22.5` | 5.625rem | 90px |
| `6.5` | 1.625rem | 26px | `24` | 6rem | 96px |
| `7` | 1.75rem | 28px | `24.5` | 6.125rem | 98px |
| `7.5` | 1.875rem | 30px | `25` | 6.25rem | 100px |
| `8` | 2rem | 32px | `25.5` | 6.375rem | 102px |
| `8.5` | 2.125rem | 34px | `26` | 6.5rem | 104px |
| `9` | 2.25rem | 36px | `27` | 6.75rem | 108px |
| `9.5` | 2.375rem | 38px | `27.5` | 6.875rem | 110px |
| `10` | 2.5rem | 40px | `29` | 7.25rem | 116px |
| `10.5` | 2.625rem | 42px | `29.5` | 7.375rem | 118px |
| `11` | 2.75rem | 44px | `30` | 7.5rem | 120px |
| `11.5` | 2.875rem | 46px | `31` | 7.75rem | 124px |
| `12` | 3rem | 48px | `32` | 8rem | 128px |
| `12.5` | 3.125rem | 50px | `32.5` | 8.125rem | 130px |
| `13` | 3.25rem | 52px | `34` | 8.5rem | 136px |
| `13.5` | 3.375rem | 54px | `34.5` | 8.625rem | 138px |
| `14` | 3.5rem | 56px | `35` | 8.75rem | 140px |
| `14.5` | 3.625rem | 58px | `36` | 9rem | 144px |
| `15` | 3.75rem | 60px | `36.5` | 9.125rem | 146px |
| `15.5` | 3.875rem | 62px | `37.5` | 9.375rem | 150px |
| `16` | 4rem | 64px | `39` | 9.75rem | 156px |
| `16.5` | 4.125rem | 66px | `39.5` | 9.875rem | 158px |
| `17` | 4.25rem | 68px | `40` | 10rem | 160px |
| `17.5` | 4.375rem | 70px | `42.5` | 10.625rem | 170px |
| `18` | 4.5rem | 72px | `44` | 11rem | 176px |
| `18.5` | 4.625rem | 74px | `45` | 11.25rem | 180px |
| `19` | 4.75rem | 76px | `46` | 11.5rem | 184px |
| `19.5` | 4.875rem | 78px | `47.5` | 11.875rem | 190px |
| `20` | 5rem | 80px | `49` | 12.25rem | 196px |

### Large Spacing

For layouts and major sections:

| Class | Value | Pixels |
|-------|-------|--------|
| `50` | 12.5rem | 200px |
| `52` | 13rem | 208px |
| `52.5` | 13.125rem | 210px |
| `54` | 13.5rem | 216px |
| `54.5` | 13.625rem | 218px |
| `55` | 13.75rem | 220px |
| `55.5` | 13.875rem | 222px |
| `59` | 14.75rem | 236px |
| `60` | 15rem | 240px |
| `62.5` | 15.625rem | 250px |
| `65` | 16.25rem | 260px |
| `67` | 16.75rem | 268px |
| `67.5` | 16.875rem | 270px |
| `70` | 17.5rem | 280px |
| `72.5` | 18.125rem | 290px |
| `73` | 18.25rem | 292px |
| `75` | 18.75rem | 300px |
| `90` | 22.5rem | 360px |
| `94` | 23.5rem | 376px |
| `95` | 23.75rem | 380px |
| `100` | 25rem | 400px |
| `115` | 28.75rem | 460px |
| `125` | 31.25rem | 500px |
| `132.5` | 33.125rem | 530px |
| `150` | 37.5rem | 600px |
| `171.5` | 42.875rem | 686px |
| `180` | 45rem | 720px |
| `187.5` | 46.875rem | 750px |
| `203` | 50.75rem | 812px |
| `230` | 57.5rem | 920px |
| `242.5` | 60.625rem | 970px |

## Usage with Utilities

### Margin
```html
<!-- All sides -->
<div class="m-4">Margin 16px on all sides</div>

<!-- Individual sides -->
<div class="mt-6 mr-4 mb-8 ml-4">Different margins</div>

<!-- Horizontal and Vertical -->
<div class="mx-auto my-8">Centered horizontally, 32px vertical margin</div>

<!-- Negative margins -->
<div class="-mt-4">Negative top margin</div>
```

### Padding
```html
<!-- All sides -->
<div class="p-6">Padding 24px on all sides</div>

<!-- Individual sides -->
<div class="pt-8 pr-6 pb-8 pl-6">Different paddings</div>

<!-- Horizontal and Vertical -->
<div class="px-4 py-6">Horizontal 16px, Vertical 24px</div>
```

### Gap (for Flexbox/Grid)
```html
<!-- Flex gap -->
<div class="flex gap-4">
  <div>Item 1</div>
  <div>Item 2</div>
</div>

<!-- Grid gap -->
<div class="grid grid-cols-3 gap-6">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>

<!-- Different horizontal and vertical gaps -->
<div class="grid grid-cols-2 gap-x-4 gap-y-6">
  <div>Item</div>
  <div>Item</div>
</div>
```

### Space Between
```html
<!-- Space between children -->
<div class="space-y-4">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>

<div class="flex space-x-6">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>
```

## Spacing Guidelines

### Component Spacing
- **Tight:** 0.5-1 (2-4px) - Within compact components
- **Normal:** 2-4 (8-16px) - Between related elements
- **Relaxed:** 6-8 (24-32px) - Between sections
- **Loose:** 12-16 (48-64px) - Between major sections

### Layout Spacing
- **Container padding:** 4-6 (16-24px) on mobile, 8-12 (32-48px) on desktop
- **Section spacing:** 12-24 (48-96px) between major sections
- **Card spacing:** 6 (24px) internal padding
- **Form spacing:** 4-6 (16-24px) between fields

### Responsive Spacing
```html
<!-- Mobile to Desktop -->
<div class="p-4 md:p-6 lg:p-8">
  Responsive padding
</div>

<div class="space-y-4 md:space-y-6 lg:space-y-8">
  <div>Item 1</div>
  <div>Item 2</div>
</div>

<section class="py-12 md:py-16 lg:py-24">
  Section with responsive vertical padding
</section>
```

## Common Patterns

### Card Component
```html
<div class="bg-white dark:bg-boxdark rounded-lg p-6 space-y-4">
  <h3 class="text-title-sm">Card Title</h3>
  <p class="text-sm">Card content</p>
  <button class="px-4 py-2">Action</button>
</div>
```

### Form Layout
```html
<form class="space-y-6">
  <div class="space-y-2">
    <label class="text-sm">Label</label>
    <input class="px-4 py-2">
  </div>
  <div class="space-y-2">
    <label class="text-sm">Label</label>
    <input class="px-4 py-2">
  </div>
  <button class="px-6 py-3 mt-4">Submit</button>
</form>
```

### Navigation
```html
<nav class="py-4 px-6">
  <ul class="flex space-x-6">
    <li><a href="#" class="px-3 py-2">Home</a></li>
    <li><a href="#" class="px-3 py-2">About</a></li>
    <li><a href="#" class="px-3 py-2">Contact</a></li>
  </ul>
</nav>
```

### Grid Layout
```html
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 p-6">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>
```

## Max Width Scale

Control content width for readability:

| Class | Value | Pixels |
|-------|-------|--------|
| `max-w-xs` | 20rem | 320px |
| `max-w-sm` | 24rem | 384px |
| `max-w-md` | 28rem | 448px |
| `max-w-lg` | 32rem | 512px |
| `max-w-xl` | 36rem | 576px |
| `max-w-2xl` | 42rem | 672px |
| `max-w-3xl` | 48rem | 768px |
| `max-w-4xl` | 56rem | 896px |
| `max-w-5xl` | 64rem | 1024px |
| `max-w-6xl` | 72rem | 1152px |
| `max-w-7xl` | 80rem | 1280px |

### Extended Max Widths

| Class | Value | Pixels |
|-------|-------|--------|
| `max-w-2.5` | 0.625rem | 10px |
| `max-w-22.5` | 5.625rem | 90px |
| `max-w-60` | 15rem | 240px |
| `max-w-70` | 17.5rem | 280px |
| `max-w-90` | 22.5rem | 360px |
| `max-w-125` | 31.25rem | 500px |
| `max-w-150` | 37.5rem | 600px |
| `max-w-180` | 45rem | 720px |
| `max-w-230` | 57.5rem | 920px |
| `max-w-270` | 67.5rem | 1080px |
| `max-w-280` | 70rem | 1120px |

## Accessibility

- Maintain minimum touch target size of 44x44px (11 units)
- Ensure adequate spacing between interactive elements
- Use consistent spacing throughout the interface
- Provide visual breathing room around content
