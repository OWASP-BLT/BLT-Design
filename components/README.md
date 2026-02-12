# BLT Components

Common UI components and patterns used in the BLT design system.

## Buttons

### Primary Button
```html
<button class="bg-primary-red hover:bg-red text-white font-medium px-6 py-3 rounded-lg transition-colors">
  Primary Action
</button>
```

### Secondary Button
```html
<button class="bg-primary hover:bg-opacity-90 text-white font-medium px-6 py-3 rounded-lg transition-colors">
  Secondary Action
</button>
```

### Outline Button
```html
<button class="border-2 border-primary-red text-primary-red hover:bg-primary-red hover:text-white font-medium px-6 py-3 rounded-lg transition-all">
  Outline Button
</button>
```

### Ghost Button
```html
<button class="text-primary-red hover:bg-red hover:bg-opacity-10 font-medium px-6 py-3 rounded-lg transition-colors">
  Ghost Button
</button>
```

### Button Sizes
```html
<!-- Small -->
<button class="px-4 py-2 text-sm">Small Button</button>

<!-- Medium (Default) -->
<button class="px-6 py-3 text-base">Medium Button</button>

<!-- Large -->
<button class="px-8 py-4 text-lg">Large Button</button>
```

### Disabled State
```html
<button class="bg-gray text-bodydark2 px-6 py-3 rounded-lg cursor-not-allowed opacity-65" disabled>
  Disabled Button
</button>
```

## Cards

### Basic Card
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

### Card with Header
```html
<div class="bg-white dark:bg-boxdark rounded-lg shadow-card border border-stroke dark:border-strokedark overflow-hidden">
  <div class="bg-gray-2 dark:bg-boxdark-2 px-6 py-4 border-b border-stroke dark:border-strokedark">
    <h3 class="font-satoshi text-title-sm font-medium text-black dark:text-white">
      Card Header
    </h3>
  </div>
  <div class="p-6">
    <p class="font-sans text-sm text-body dark:text-bodydark">
      Card content goes here.
    </p>
  </div>
</div>
```

### Card with Footer
```html
<div class="bg-white dark:bg-boxdark rounded-lg shadow-card border border-stroke dark:border-strokedark overflow-hidden">
  <div class="p-6">
    <h3 class="font-satoshi text-title-sm font-medium text-black dark:text-white mb-2">
      Card Title
    </h3>
    <p class="font-sans text-sm text-body dark:text-bodydark">
      Card content.
    </p>
  </div>
  <div class="bg-gray-2 dark:bg-boxdark-2 px-6 py-4 border-t border-stroke dark:border-strokedark">
    <button class="text-primary-red hover:underline text-sm font-medium">
      Action
    </button>
  </div>
</div>
```

## Forms

### Input Field
```html
<div class="space-y-2">
  <label class="font-sans text-sm font-medium text-black dark:text-white">
    Label
  </label>
  <input 
    type="text" 
    placeholder="Enter text..."
    class="w-full px-4 py-3 border border-stroke dark:border-form-strokedark bg-white dark:bg-form-input text-black dark:text-white rounded-lg focus:border-primary focus:ring-2 focus:ring-primary focus:ring-opacity-20 outline-none transition"
  >
</div>
```

### Textarea
```html
<div class="space-y-2">
  <label class="font-sans text-sm font-medium text-black dark:text-white">
    Description
  </label>
  <textarea 
    rows="4"
    placeholder="Enter description..."
    class="w-full px-4 py-3 border border-stroke dark:border-form-strokedark bg-white dark:bg-form-input text-black dark:text-white rounded-lg focus:border-primary focus:ring-2 focus:ring-primary focus:ring-opacity-20 outline-none transition resize-none"
  ></textarea>
</div>
```

### Select Dropdown
```html
<div class="space-y-2">
  <label class="font-sans text-sm font-medium text-black dark:text-white">
    Select Option
  </label>
  <select class="w-full px-4 py-3 border border-stroke dark:border-form-strokedark bg-white dark:bg-form-input text-black dark:text-white rounded-lg focus:border-primary focus:ring-2 focus:ring-primary focus:ring-opacity-20 outline-none transition">
    <option>Option 1</option>
    <option>Option 2</option>
    <option>Option 3</option>
  </select>
</div>
```

### Checkbox
```html
<label class="flex items-center space-x-3 cursor-pointer">
  <input 
    type="checkbox" 
    class="w-5 h-5 border-2 border-stroke dark:border-form-strokedark rounded text-primary-red focus:ring-2 focus:ring-primary focus:ring-opacity-20"
  >
  <span class="font-sans text-sm text-body dark:text-bodydark">
    Checkbox Label
  </span>
</label>
```

### Radio Button
```html
<label class="flex items-center space-x-3 cursor-pointer">
  <input 
    type="radio" 
    name="option"
    class="w-5 h-5 border-2 border-stroke dark:border-form-strokedark text-primary-red focus:ring-2 focus:ring-primary focus:ring-opacity-20"
  >
  <span class="font-sans text-sm text-body dark:text-bodydark">
    Radio Label
  </span>
</label>
```

## Alerts

### Success Alert
```html
<div class="bg-meta-3 bg-opacity-10 border-l-4 border-meta-3 px-6 py-4 rounded-lg">
  <div class="flex items-start space-x-3">
    <svg class="w-6 h-6 text-meta-3 flex-shrink-0" fill="currentColor" viewBox="0 0 20 20">
      <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/>
    </svg>
    <div>
      <h4 class="font-satoshi text-sm font-semibold text-meta-3 mb-1">Success!</h4>
      <p class="font-sans text-sm text-body dark:text-bodydark">Your action was completed successfully.</p>
    </div>
  </div>
</div>
```

### Error Alert
```html
<div class="bg-danger bg-opacity-10 border-l-4 border-danger px-6 py-4 rounded-lg">
  <div class="flex items-start space-x-3">
    <svg class="w-6 h-6 text-danger flex-shrink-0" fill="currentColor" viewBox="0 0 20 20">
      <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zM8.707 7.293a1 1 0 00-1.414 1.414L8.586 10l-1.293 1.293a1 1 0 101.414 1.414L10 11.414l1.293 1.293a1 1 0 001.414-1.414L11.414 10l1.293-1.293a1 1 0 00-1.414-1.414L10 8.586 8.707 7.293z" clip-rule="evenodd"/>
    </svg>
    <div>
      <h4 class="font-satoshi text-sm font-semibold text-danger mb-1">Error!</h4>
      <p class="font-sans text-sm text-body dark:text-bodydark">Something went wrong. Please try again.</p>
    </div>
  </div>
</div>
```

### Warning Alert
```html
<div class="bg-warning bg-opacity-10 border-l-4 border-warning px-6 py-4 rounded-lg">
  <div class="flex items-start space-x-3">
    <svg class="w-6 h-6 text-warning flex-shrink-0" fill="currentColor" viewBox="0 0 20 20">
      <path fill-rule="evenodd" d="M8.257 3.099c.765-1.36 2.722-1.36 3.486 0l5.58 9.92c.75 1.334-.213 2.98-1.742 2.98H4.42c-1.53 0-2.493-1.646-1.743-2.98l5.58-9.92zM11 13a1 1 0 11-2 0 1 1 0 012 0zm-1-8a1 1 0 00-1 1v3a1 1 0 002 0V6a1 1 0 00-1-1z" clip-rule="evenodd"/>
    </svg>
    <div>
      <h4 class="font-satoshi text-sm font-semibold text-warning mb-1">Warning!</h4>
      <p class="font-sans text-sm text-body dark:text-bodydark">Please review your input before proceeding.</p>
    </div>
  </div>
</div>
```

### Info Alert
```html
<div class="bg-meta-5 bg-opacity-10 border-l-4 border-meta-5 px-6 py-4 rounded-lg">
  <div class="flex items-start space-x-3">
    <svg class="w-6 h-6 text-meta-5 flex-shrink-0" fill="currentColor" viewBox="0 0 20 20">
      <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z" clip-rule="evenodd"/>
    </svg>
    <div>
      <h4 class="font-satoshi text-sm font-semibold text-meta-5 mb-1">Info</h4>
      <p class="font-sans text-sm text-body dark:text-bodydark">Here's some useful information for you.</p>
    </div>
  </div>
</div>
```

## Badges

```html
<!-- Default Badge -->
<span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-medium bg-gray text-black">
  Default
</span>

<!-- Primary Badge -->
<span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-medium bg-primary-red text-white">
  Primary
</span>

<!-- Success Badge -->
<span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-medium bg-meta-3 text-white">
  Success
</span>

<!-- Warning Badge -->
<span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-medium bg-warning text-white">
  Warning
</span>

<!-- Danger Badge -->
<span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-medium bg-danger text-white">
  Danger
</span>

<!-- Outline Badge -->
<span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-medium border-2 border-primary-red text-primary-red">
  Outline
</span>
```

## Navigation

### Navbar
```html
<nav class="bg-white dark:bg-boxdark border-b border-stroke dark:border-strokedark">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-center h-16">
      <div class="flex items-center space-x-8">
        <a href="#" class="font-satoshi text-title-xsm font-bold text-primary-red">
          BLT
        </a>
        <div class="hidden md:flex space-x-6">
          <a href="#" class="text-sm font-medium text-black dark:text-white hover:text-primary-red transition">
            Home
          </a>
          <a href="#" class="text-sm font-medium text-body dark:text-bodydark hover:text-primary-red transition">
            About
          </a>
          <a href="#" class="text-sm font-medium text-body dark:text-bodydark hover:text-primary-red transition">
            Features
          </a>
        </div>
      </div>
      <button class="bg-primary-red text-white px-6 py-2 rounded-lg hover:bg-red transition">
        Get Started
      </button>
    </div>
  </div>
</nav>
```

### Sidebar
```html
<aside class="w-64 bg-white dark:bg-boxdark border-r border-stroke dark:border-strokedark h-screen p-6">
  <div class="space-y-2">
    <a href="#" class="flex items-center space-x-3 px-4 py-3 rounded-lg bg-primary-red bg-opacity-10 text-primary-red font-medium">
      <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20">
        <path d="M10.707 2.293a1 1 0 00-1.414 0l-7 7a1 1 0 001.414 1.414L4 10.414V17a1 1 0 001 1h2a1 1 0 001-1v-2a1 1 0 011-1h2a1 1 0 011 1v2a1 1 0 001 1h2a1 1 0 001-1v-6.586l.293.293a1 1 0 001.414-1.414l-7-7z"/>
      </svg>
      <span>Dashboard</span>
    </a>
    <a href="#" class="flex items-center space-x-3 px-4 py-3 rounded-lg text-body dark:text-bodydark hover:bg-gray dark:hover:bg-boxdark-2 transition">
      <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20">
        <path d="M9 2a1 1 0 000 2h2a1 1 0 100-2H9z"/>
        <path fill-rule="evenodd" d="M4 5a2 2 0 012-2 3 3 0 003 3h2a3 3 0 003-3 2 2 0 012 2v11a2 2 0 01-2 2H6a2 2 0 01-2-2V5zm3 4a1 1 0 000 2h.01a1 1 0 100-2H7zm3 0a1 1 0 000 2h3a1 1 0 100-2h-3zm-3 4a1 1 0 100 2h.01a1 1 0 100-2H7zm3 0a1 1 0 100 2h3a1 1 0 100-2h-3z" clip-rule="evenodd"/>
      </svg>
      <span>Reports</span>
    </a>
  </div>
</aside>
```

## Tables

```html
<div class="bg-white dark:bg-boxdark rounded-lg shadow-card border border-stroke dark:border-strokedark overflow-hidden">
  <table class="w-full">
    <thead class="bg-gray-2 dark:bg-boxdark-2">
      <tr>
        <th class="px-6 py-4 text-left text-sm font-semibold text-black dark:text-white">Name</th>
        <th class="px-6 py-4 text-left text-sm font-semibold text-black dark:text-white">Status</th>
        <th class="px-6 py-4 text-left text-sm font-semibold text-black dark:text-white">Date</th>
        <th class="px-6 py-4 text-left text-sm font-semibold text-black dark:text-white">Action</th>
      </tr>
    </thead>
    <tbody class="divide-y divide-stroke dark:divide-strokedark">
      <tr class="hover:bg-gray dark:hover:bg-boxdark-2 transition">
        <td class="px-6 py-4 text-sm text-body dark:text-bodydark">John Doe</td>
        <td class="px-6 py-4">
          <span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-medium bg-meta-3 text-white">
            Active
          </span>
        </td>
        <td class="px-6 py-4 text-sm text-body dark:text-bodydark">2024-01-15</td>
        <td class="px-6 py-4">
          <button class="text-primary-red hover:underline text-sm font-medium">View</button>
        </td>
      </tr>
    </tbody>
  </table>
</div>
```

## Loading Spinners

```html
<!-- Simple Spinner -->
<div class="animate-spin rounded-full h-8 w-8 border-4 border-gray border-t-primary-red"></div>

<!-- Button with Spinner -->
<button class="bg-primary-red text-white px-6 py-3 rounded-lg flex items-center space-x-2">
  <div class="animate-spin rounded-full h-4 w-4 border-2 border-white border-t-transparent"></div>
  <span>Loading...</span>
</button>
```

## Modals

```html
<!-- Modal Overlay -->
<div class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-999999 p-4">
  <!-- Modal Content -->
  <div class="bg-white dark:bg-boxdark rounded-lg shadow-6 max-w-md w-full">
    <!-- Modal Header -->
    <div class="flex items-center justify-between px-6 py-4 border-b border-stroke dark:border-strokedark">
      <h3 class="font-satoshi text-title-sm font-medium text-black dark:text-white">
        Modal Title
      </h3>
      <button class="text-bodydark2 hover:text-black dark:hover:text-white transition">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/>
        </svg>
      </button>
    </div>
    <!-- Modal Body -->
    <div class="px-6 py-4">
      <p class="text-sm text-body dark:text-bodydark">
        Modal content goes here.
      </p>
    </div>
    <!-- Modal Footer -->
    <div class="flex items-center justify-end space-x-3 px-6 py-4 border-t border-stroke dark:border-strokedark">
      <button class="px-6 py-2 border border-stroke dark:border-strokedark text-body dark:text-bodydark rounded-lg hover:bg-gray dark:hover:bg-boxdark-2 transition">
        Cancel
      </button>
      <button class="px-6 py-2 bg-primary-red text-white rounded-lg hover:bg-red transition">
        Confirm
      </button>
    </div>
  </div>
</div>
```
