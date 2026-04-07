# 7swazy ui
# html structure
```html
<div class="glass-card">
    <div class="header">...</div>
    <div class="tabs">...</div>
    <div class="tab-content">YOUR CONTENT HERE</div>
    <footer>...</footer>
</div>
```
# adding a tab
```html
<button class="tab-btn" data-tab="mytab">My Tab</button>
<div id="mytabTab" class="tab-content">Content here</div>
```
# add to javascript
```html
const mytabTab = document.getElementById('mytabTab');
// Add to switchTab function
```

# css clases you can use
| Class | Purpose |
| :--- | :--- |
| `.btn-primary` | Blue gradient button |
| `.btn-secondary` | Dark outline button |
| `.card-grid` | Grid layout for cards |
| `.card` | Individual card |
| `.input-group` | Form field wrapper |
| `.flex` | Flex container with gap |

# Save this as a template and just replace:
# The header title and subtitle
# The tab content areas
# The footer text
# Add your own JavaScript functions
# The UI will stay consistent across all your projects.
