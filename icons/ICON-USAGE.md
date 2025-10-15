# Prism Icons - Usage Guide

## Available Icons

All icons are now integrated from the Prism Design System library.

### Navigation Icons (24px)
- `icons/home-24.svg` - Home icon
- `icons/dashboard-line-24.svg` - Dashboard icon
- `icons/insight-line-24.svg` - Insights/Analytics icon
- `icons/reports-24.svg` - Reports icon
- `icons/people-group-24.svg` - Customers icon
- `icons/order-bag-24.svg` - Orders icon
- `icons/promo-bullhorn-line-24.svg` - Marketing/Campaigns icon
- `icons/menu-24.svg` - Menu icon
- `icons/calendar-24.svg` - Calendar/Availability icon
- `icons/money-24.svg` - Financials icon
- `icons/settings-24.svg` - Settings icon
- `icons/info-circle-24.svg` - Info icon

### Action Icons
- `icons/add-24.svg` - Add/Plus icon (24px)
- `icons/chevron-down-16.svg` - Dropdown indicator (16px)

## How to Use

### In HTML
```html
<!-- Basic usage -->
<img src="icons/home-24.svg" alt="Home" width="24" height="24">

<!-- In navigation items -->
<div class="nav-menu-item">
    <img src="icons/dashboard-line-24.svg" alt="" width="24" height="24">
    <span>Dashboard</span>
</div>
```

### Styling
The CSS automatically applies color filters to match the DoorDash design system:
- Default: Gray (#606060)
- Hover/Selected: Dark gray (#191919)

```css
.nav-menu-item img {
    width: 24px;
    height: 24px;
    flex-shrink: 0;
    filter: brightness(0) saturate(100%) invert(40%);
}

.nav-menu-item:hover img,
.nav-menu-item.selected img {
    filter: brightness(0) saturate(100%) invert(11%);
}
```

## Icon Integration Status

✅ All navigation icons updated in `smart-campaign-reporting.html`
✅ Icons are sourced from Prism Design System
✅ CSS color filters applied for consistency
✅ Hover states working properly

## Need More Icons?

All icons are available in the Figma Prism Icons library:
https://www.figma.com/design/yXC84gSOgCe4tZ6U1AUtoj/Prism-Icons

To add more icons, just let me know which ones you need and I can export them from the library.

