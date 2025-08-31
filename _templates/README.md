# Global Components System

## Overview
This folder contains global components to ensure consistent navigation and footer across all pages.

## Components

### 1. `/includes/navbar.html`
- Global navigation bar
- Mobile-responsive with hamburger menu
- Consistent branding and links
- Copy this exact HTML into all pages

### 2. `/includes/footer.html`
- Global footer with company info
- Service links and areas served
- Consistent contact information
- Copy this exact HTML into all pages

### 3. `/includes/global-scripts.html`
- Mobile navigation functionality
- Smooth scrolling for internal links
- Common JavaScript for all pages
- Include before closing `</body>` tag

## Usage Instructions

### For New Pages:
1. Start with `/templates/page-template.html`
2. Copy navbar content from `/includes/navbar.html`
3. Copy footer content from `/includes/footer.html`
4. Copy scripts from `/includes/global-scripts.html`
5. Customize page-specific content only

### For Existing Pages:
1. Replace navigation section with content from `/includes/navbar.html`
2. Replace footer section with content from `/includes/footer.html`
3. Update scripts with content from `/includes/global-scripts.html`

## Updating Global Components

### To Update Navigation:
1. Edit `/includes/navbar.html`
2. Copy the updated HTML to all existing pages
3. Test mobile navigation on all pages

### To Update Footer:
1. Edit `/includes/footer.html`
2. Copy the updated HTML to all existing pages
3. Verify all footer links work correctly

## File Structure
```
/
├── _includes/
│   ├── navbar.html      (Global navigation)
│   ├── footer.html      (Global footer)
│   └── global-scripts.html (Global JavaScript)
├── _templates/
│   ├── page-template.html (Master template)
│   └── README.md        (This file)
├── index.html
├── about-us-katy-seal-coating.html
├── faq-katy-seal-coating.html
├── seal-coating-richmond-tx.html
└── blog/
    ├── index.html
    └── best-time-seal-coat-driveway-texas-2024.html
```

## Benefits
- ✅ Consistent navigation across all pages
- ✅ Easy to update site-wide changes
- ✅ Mobile navigation works everywhere
- ✅ Professional, uniform appearance
- ✅ SEO-friendly internal linking