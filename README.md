# AppCanopy Website

A modern, responsive website for AppCanopy - showcasing mobile applications.

## 🚀 Quick Start

This is a static website designed for GitHub Pages. Simply push to your repository and enable GitHub Pages in your repository settings.

## 📁 File Structure

```
appcanopy.github.io/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # JavaScript for interactions
└── README.md       # This file
```

## ✏️ Customization Guide

### 1. Update Your App Information

In `index.html`, find the **Apps Section** and update the app card with your actual app details:

```html
<!-- Look for this section and update: -->
<div class="app-card featured">
    <!-- Replace placeholder-icon with your app icon -->
    <div class="app-icon">
        <img src="your-app-icon.png" alt="Your App Name">
    </div>
    <h3 class="app-name">Your App Name</h3>
    <p class="app-tagline">Your App Tagline</p>
    <p class="app-description">Your app description...</p>
    <!-- Update Play Store link -->
    <a href="https://play.google.com/store/apps/details?id=your.app.id" class="app-link">
```

### 2. Update Contact Information

Find the **Contact Section** and update:
- Email address
- Play Store developer page link
- GitHub profile link

### 3. Add Your App Icon

1. Add your app icon image to the repository (e.g., `app-icon.png`)
2. Update the img src in the app card:
   ```html
   <div class="app-icon">
       <img src="app-icon.png" alt="Your App Name">
   </div>
   ```
3. Remove the `<span class="placeholder-icon">📱</span>` line

### 4. Adding More Apps

When you publish more apps, duplicate the app card structure:

```html
<div class="app-card">
    <div class="app-card-glow"></div>
    <div class="app-card-content">
        <div class="app-header">
            <div class="app-icon">
                <img src="new-app-icon.png" alt="New App">
            </div>
        </div>
        <h3 class="app-name">New App Name</h3>
        <p class="app-tagline">App Tagline</p>
        <p class="app-description">App description...</p>
        <div class="app-stats">
            <div class="app-stat">
                <span class="app-stat-value">⭐ 4.5</span>
                <span class="app-stat-label">Rating</span>
            </div>
            <div class="app-stat">
                <span class="app-stat-value">10K+</span>
                <span class="app-stat-label">Downloads</span>
            </div>
        </div>
        <a href="#" class="app-link" target="_blank">
            <!-- Play Store icon SVG -->
            <span>Get on Play Store</span>
        </a>
    </div>
</div>
```

### 5. Update Stats (When You Grow)

Update the hero stats to reflect your actual numbers:

```html
<div class="hero-stats">
    <div class="stat-item">
        <span class="stat-number">5</span>
        <span class="stat-label">Apps Published</span>
    </div>
    <!-- etc. -->
</div>
```

## 🎨 Customizing Colors

The color scheme uses CSS variables in `styles.css`. To change colors, update these variables at the top:

```css
:root {
    --accent-primary: #22c55e;      /* Main green accent */
    --accent-secondary: #10b981;    /* Secondary green */
    --bg-primary: #0a0f0d;          /* Dark background */
    /* etc. */
}
```

## 📱 Features

- ✅ Fully responsive design
- ✅ Smooth scroll animations
- ✅ Mobile-friendly navigation
- ✅ Modern dark theme
- ✅ Optimized for GitHub Pages
- ✅ No build tools required

## 🌐 Deploying to GitHub Pages

1. Push all files to your `appcanopy.github.io` repository
2. Go to **Settings** > **Pages**
3. Under "Source", select **main** branch
4. Save and wait a few minutes
5. Your site will be live at `https://appcanopy.github.io`

## 📝 License

Feel free to customize and use this template for your developer portfolio.
