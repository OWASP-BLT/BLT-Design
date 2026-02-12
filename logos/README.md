# BLT Logo and Brand Guidelines

## Logo Usage

The BLT (Bug Logging Tool) logo is a critical part of the brand identity. Please follow these guidelines when using the logo.

## Logo Specifications

### Primary Logo
The primary BLT logo should be used in most contexts. It consists of:
- **BLT** wordmark in the brand's signature style
- Primary red color (#E10101)

### Logo Variations

1. **Full Color Logo** - For use on light backgrounds
2. **White Logo** - For use on dark backgrounds
3. **Black Logo** - For use in monochrome contexts
4. **Icon Only** - For use in small spaces (favicons, app icons)

## Color Specifications

### Primary Logo Colors
- **Primary Red:** #E10101
- **Alternative Red:** #e74c3c
- **Black:** #1C2434
- **White:** #FFFFFF

## Logo Placement

### Clear Space
Always maintain clear space around the logo equal to the height of the "B" in BLT. This ensures the logo has breathing room and remains visually distinct.

### Minimum Size
- **Digital:** 120px wide minimum
- **Print:** 1 inch (2.54 cm) wide minimum
- **Favicon/Icon:** 32x32px minimum

## Usage Guidelines

### DO:
✅ Use the logo in its original proportions  
✅ Use approved color variations  
✅ Ensure sufficient contrast with background  
✅ Maintain clear space around the logo  
✅ Use high-resolution files for print  
✅ Place on appropriate backgrounds  

### DON'T:
❌ Distort or stretch the logo  
❌ Change the logo colors  
❌ Add effects (shadows, gradients, outlines)  
❌ Rotate the logo  
❌ Place on busy backgrounds  
❌ Use low-resolution images  
❌ Alter the spacing between letters  

## Background Usage

### Light Backgrounds
Use the full-color logo on:
- White (#FFFFFF)
- Light gray (#F7F9FC, #EFF4FB)
- Very light colors with sufficient contrast

### Dark Backgrounds
Use the white logo on:
- Black (#1C2434, #010101)
- Dark gray (#24303F, #1A222C)
- Dark colors with sufficient contrast

### Colored Backgrounds
Ensure the logo maintains high contrast:
- Use white logo on dark primary colors
- Use full-color logo on light secondary colors
- Test contrast ratio (minimum 4.5:1)

## File Formats

### Digital Use
- **SVG** - Preferred for web (scalable, small file size)
- **PNG** - For raster images with transparency
- **WebP** - For optimized web images

### Print Use
- **PDF** - Vector format for print
- **EPS** - For professional printing
- **High-res PNG** - 300 DPI minimum

## Logo with Tagline

When using the logo with a tagline or descriptor:
- Place tagline below the logo
- Use Open Sans font, regular weight
- Size should be 25-30% of logo width
- Maintain appropriate spacing

Example:
```
      BLT
Bug Logging Tool
```

## Accessibility

Ensure logo placement considers:
- Screen reader compatibility (provide alt text)
- High contrast for visibility
- Appropriate sizing for readability
- Touch target size for interactive logos (minimum 44x44px)

## Co-Branding

When using the BLT logo with partner logos:
1. Maintain equal visual weight
2. Use a divider or separator
3. Follow partner's brand guidelines
4. Ensure both logos are clearly visible
5. Maintain individual clear spaces

## OWASP Branding

As part of the OWASP Foundation:
- The OWASP logo may be used alongside the BLT logo
- Follow OWASP's branding guidelines
- Maintain clear distinction between OWASP and BLT branding
- Link to OWASP Foundation when appropriate

## Logo Assets Location

Logo files should be organized as:
```
logos/
├── svg/
│   ├── blt-logo-full-color.svg
│   ├── blt-logo-white.svg
│   ├── blt-logo-black.svg
│   └── blt-icon.svg
├── png/
│   ├── blt-logo-full-color.png
│   ├── blt-logo-white.png
│   ├── blt-logo-black.png
│   └── blt-icon.png
└── favicon/
    ├── favicon.ico
    ├── favicon-16x16.png
    ├── favicon-32x32.png
    └── favicon-96x96.png
```

## Examples

### Website Header
```html
<header class="bg-white border-b border-stroke">
  <div class="container mx-auto px-6 py-4">
    <img 
      src="/logos/svg/blt-logo-full-color.svg" 
      alt="BLT - Bug Logging Tool"
      class="h-10"
    >
  </div>
</header>
```

### Dark Mode Header
```html
<header class="bg-boxdark border-b border-strokedark">
  <div class="container mx-auto px-6 py-4">
    <img 
      src="/logos/svg/blt-logo-white.svg" 
      alt="BLT - Bug Logging Tool"
      class="h-10"
    >
  </div>
</header>
```

### Favicon
```html
<link rel="icon" type="image/x-icon" href="/logos/favicon/favicon.ico">
<link rel="icon" type="image/png" sizes="16x16" href="/logos/favicon/favicon-16x16.png">
<link rel="icon" type="image/png" sizes="32x32" href="/logos/favicon/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="96x96" href="/logos/favicon/favicon-96x96.png">
```

## Questions or Issues

For questions about logo usage or to request custom logo variations:
- Open an issue: https://github.com/OWASP-BLT/BLT-Design/issues
- Contact the BLT team: https://github.com/OWASP-BLT/BLT

## License

The BLT logo and brand assets are property of the OWASP Foundation and the BLT project. 
Usage must comply with the OWASP Foundation trademark policy and these brand guidelines.
