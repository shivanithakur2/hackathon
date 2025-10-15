# Prism Icons Reference

This document lists all available icons from your Prism Design System icon library.

## Available Icons (Partial List - Most Commonly Used)

### Navigation & Actions
- **16/add** (Component ID: 35104:53)
- **24/add** (Component ID: 290:591)
- **16/arrow-right** (Component ID: 35104:51)
- **24/arrow-right** (Component ID: 1:11190)
- **16/chevron-down** (Component ID: 1600:15624)
- **24/chevron-down** (Component ID: 1:11183)
- **24/chevron-left** (Component ID: 23:31133)
- **24/chevron-right** (Component ID: 23:37606)
- **16/chevron-right** (Component ID: 32:16328)
- **16/close** (Component ID: 1:26678)
- **24/close** (Component ID: 988:71430)
- **16/close-circle-fill** (Component ID: 23:71234)
- **24/edit-add-fill** (Component ID: 23:31406)

### Dashboard & Analytics
- **24/dashboard-line** (Component ID: 2008:547)
- **24/insight-line** (Component ID: 7830:517)
- **24/insight-fill** (Component ID: 1020:19446)
- **24/prism-line** (Component ID: 37881:52)

### Marketing & Campaigns
- **24/promo-bullhorn-line** (Component ID: 13700:47)
- **24/promo-line** (Component ID: 23:31645)
- **16/promo-fill** (Component ID: 1:26662)

### E-commerce
- **24/order-bag-line** (Component ID: 23:9043)
- **24/card-line** (Component ID: 1:23)
- **24/menu-edit-line** (Component ID: 23:9079)
- **24/reward-line** (Component ID: 23:9327)

### Money & Finance
- **24/money-circle-enabled-line** (Component ID: 23:9371)
- **16/money-circle-enabled-fill** (Component ID: 23:64324)
- **24/money-bank** (Component ID: 23:9073)

### Users & Social
- **24/person-profile-line** (Component ID: 23:9373)
- **24/people-group-line** (Component ID: 23:9047)

### System & Settings
- **24/settings-line** (Component ID: 23:9077)
- **24/help-circle-line** (Component ID: 23:9375)
- **24/logout-line** (Component ID: 23:9067)
- **24/signal-high** (Component ID: 23:9071)
- **24/locked-line** (Component ID: 23:30792)
- **16/locked-line** (Component ID: 23:41981)

### Location & Delivery
- **24/location-pin-enabled-line** (Component ID: 23:9045)
- **24/vehicle-car** (Component ID: 23:9075)
- **24/vehicle-car-fill** (Component ID: 23:70403)

### Time & Status
- **24/calendar-line** (Component ID: 1:26553)
- **16/time-line** (Component ID: 23:30868)
- **16/check** (Component ID: 1:30202)
- **16/check-circle-fill** (Component ID: 23:31650)
- **16/status-dot-open-color** (Component ID: 23:31994)

### UI Elements
- **24/search** (Component ID: 23:41972)
- **24/more-horizontal** (Component ID: 1:30439)
- **24/more-vertical** (Component ID: 23:41979)
- **24/favorite-fill** (Component ID: 23:32346)
- **24/list** (Component ID: 23:25022)
- **16/list** (Component ID: 23:32764)
- **16/sort-order** (Component ID: 23:70421)
- **16/merchant-fill** (Component ID: 23:34333)
- **16/arrow-up** (Component ID: 23:34351)
- **16/arrow-down** (Component ID: 23:34353)
- **16/info-fill** (Component ID: 1:26664)
- **24/pause-line** (Component ID: 23:41970)

### Logos
- **16/logo-dashpass-new** (Component ID: 23:70920)

## Currently Downloaded Icons

The following icons have been successfully downloaded to `/icons/`:

1. ✅ **chevron-down-16.svg** - Small down chevron for dropdowns
2. ✅ **add-24.svg** - Plus icon for adding items
3. ✅ **dashboard-line-24.svg** - Dashboard/home icon
4. ✅ **insight-line-24.svg** - Analytics/insights icon
5. ✅ **promo-bullhorn-line-24.svg** - Marketing/campaign icon

## How to Use Prism Icons

### Method 1: Direct SVG Import
```html
<img src="icons/dashboard-line-24.svg" alt="Dashboard" width="24" height="24">
```

### Method 2: Inline SVG (for color customization)
```html
<svg class="icon" width="24" height="24">
  <use href="icons/dashboard-line-24.svg#icon"></use>
</svg>
```

### Method 3: CSS Background
```css
.icon-dashboard {
  width: 24px;
  height: 24px;
  background: url('icons/dashboard-line-24.svg') no-repeat center;
  background-size: contain;
}
```

## Requesting More Icons

To download additional icons from the Prism library, you can request them by:
1. **Icon name** (e.g., "search", "close", "arrow-right")
2. **Size** (16px or 24px)
3. **Component ID** (from this reference list)

Example: "Please download the 24px search icon and the 16px close icon"

## Icon Naming Convention

Prism icons follow this pattern:
- **Size**: 16 or 24 (pixels)
- **Name**: Descriptive name (e.g., "chevron-down", "add", "dashboard")
- **Variant**: line (outline), fill (solid), or enabled

Format: `{size}/{name}[-{variant}]`

Examples:
- `16/add` - 16px add icon
- `24/dashboard-line` - 24px outlined dashboard icon
- `24/insight-fill` - 24px filled insight icon

