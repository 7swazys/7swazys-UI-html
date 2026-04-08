# 7swazy

## themes

| theme | primary color | best for |
| :--- | :--- | :--- |
| blue | `#3b82f6` | Default, professional |
| red  | `#f63b3b` | Bold, attention-grabbing |
| purple | `#8b38f8` | Creative, modern |

## html structure

```html
<div class="glass-card">
    <div class="header">...</div>
    <div class="tabs">...</div>
    <div class="tab-content">YOUR CONTENT HERE</div>
    <footer>...</footer>
</div>
```

## adding a tab

```html
<button class="tab-btn" data-tab="mytab">My Tab</button>
<div id="mytabTab" class="tab-content">Content here</div>
```

## add to javascript

```html
const mytabTab = document.getElementById('mytabTab');
// Add to switchTab function
```

## css classes you can use

| class | purpose |
| :--- | :--- |
| `.btn-primary` | Gradient button |
| `.btn-secondary` | Dark outline button |
| `.card-grid` | Grid layout for cards |
| `.card` | Individual card |
| `.input-group` | Form field wrapper |
| `.flex` | Flex container with gap |

## Utility Classes

| Class | Purpose |
| :--- | :--- |
| `.text-center` | Center text alignment |
| `.mt-2` | Margin top 1rem |
| `.mb-2` | Margin bottom 1rem |
| `.gap-2` | Gap 1rem between flex items |

## Theme Color References

### Blue Theme
- Primary: `#3b82f6`
- Gradient: `#2563eb` → `#1e40af`
- Text light: `#c0e0ff`
- Text muted: `#9ab3d5`

### Red Theme
- Primary: `#f63b3b`
- Gradient: `#eb2525` → `#af1e1e`
- Text light: `#ffc0c0`
- Text muted: `#d59b9b`

### Purple Theme
- Primary: `#8b38f8`
- Gradient: `#7c25eb` → `#541eaf`
- Text light: `#dcc0ff`
- Text muted: `#b89bd5`

## Quick Start

1. Copy the template code for your chosen theme
2. Replace the header title and subtitle
3. Modify tab content areas
4. Update the footer text
5. Add your own JavaScript functions

## Responsive Breakpoints

- Desktop: Full layout with grid cards
- Tablet: Adjusts spacing and padding
- Mobile (max-width: 700px): Stacked layout, smaller padding

## Customization Tips

- Change theme colors by updating the CSS variables in the style block
- Add more tabs by copying the tab button and content div pattern
- Modify the gradient directions in `.btn-primary` and `.header-left h1`
- Adjust blur intensity with `backdrop-filter: blur()` value

## Template Notes

- The UI stays consistent across all your projects
- All themes maintain the same glass morphic effect
- Tab switching logic is pre-configured
- Fully responsive out of the box
