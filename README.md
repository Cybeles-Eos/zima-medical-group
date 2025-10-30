# 🎨 Static Web Design Template

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/your-repo/kingrg-version2)
[![License](https://img.shields.io/badge/license-ISC-green.svg)](LICENSE)
[![Sass](https://img.shields.io/badge/Sass-Modern%20%40use-ff69b4.svg)](https://sass-lang.com/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.x-purple.svg)](https://getbootstrap.com/)

> A modern, responsive static web design template crafted by **Guevara Web Graphics Studio** for custom web development projects. Built with modern Sass architecture, responsive design principles, and optimized for SEO and performance.

## 📋 Table of Contents

- [✨ Features](#-features)
- [🚀 Quick Start](#-quick-start)
- [📋 Prerequisites](#-prerequisites)
- [⚙️ Installation](#️-installation)
- [🛠️ Development](#️-development)
- [📁 Project Structure](#-project-structure)
- [📜 Available Scripts](#-available-scripts)
- [🎨 Customization](#-customization)
- [📱 Responsive Design](#-responsive-design)
- [🔧 Recent Updates](#-recent-updates)
- [🌐 Browser Support](#-browser-support)
- [❓ Troubleshooting](#-troubleshooting)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

## ✨ Features

### 🎯 Core Features
- **Modern Sass Architecture** - Uses latest Dart Sass with `@use` syntax
- **Responsive Design** - Mobile-first approach with Bootstrap 5
- **Component-Based Structure** - Modular Sass components for maintainability
- **SEO Optimized** - Meta tags, structured data, and performance optimizations
- **Cross-Browser Compatible** - Tested across modern browsers

### 🔧 Technical Stack
- **CSS Framework**: Bootstrap 5.x
- **Icons**: Font Awesome 5.8.1 (937+ solid, 427+ brand, 152+ regular icons)
- **Typography**: Poppins Google Font family
- **JavaScript**: jQuery 3.5.1, Slick Carousel, AOS Animations
- **Build Tools**: Dart Sass with modern `@use` imports
- **Development**: Hot-reload Sass compilation with watch mode

### 📦 Included Libraries
- **Bootstrap 5** - Responsive grid system and components
- **Font Awesome 5.8.1** - Complete icon library
- **Slick Carousel** - Touch-friendly carousel/slider
- **AOS (Animate On Scroll)** - Scroll animations
- **Modernizr** - Feature detection
- **Custom Reset CSS** - Consistent cross-browser styling

## 🚀 Quick Start

```bash
# Clone or download the project
git clone <your-repo-url>
cd static-template

# Install dependencies
npm install

# Start development with Sass watch mode
npm run sass-watch

# Or compile Sass once
npm run sass
```

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v14.0.0 or higher)
- **npm** (v6.0.0 or higher)
- A modern code editor (VS Code recommended)

### Recommended Tools
- **Live Server** extension for VS Code
- **Sass** extension for syntax highlighting
- **Auto Rename Tag** for HTML editing

## ⚙️ Installation

### 1. Download the Template
```bash
# Option 1: Clone repository
git clone <your-repo-url>
cd static-template

# Option 2: Download and extract ZIP file
```

### 2. Install Dependencies
```bash
npm install
```

This will install:
- **Dart Sass** (^1.92.1) - Modern Sass compiler

### 3. Verify Installation
```bash
# Test Sass compilation
npm run sass

# Check if style.css is generated
ls assets/css/style.css
```

## 🛠️ Development

### Starting Development

1. **Start Sass Watch Mode** (recommended for active development):
   ```bash
   npm run sass-watch
   ```
   This command will:
   - Monitor `assets/sass/` for changes
   - Automatically compile Sass to CSS
   - Generate source maps for debugging

2. **Open in Browser**:
   - Use Live Server extension in VS Code, or
   - Open `index.html` directly in your browser

### Development Workflow

```bash
# 1. Start Sass compilation in watch mode
npm run sass-watch

# 2. Edit Sass files in assets/sass/
# 3. Changes automatically compile to assets/css/style.css
# 4. Refresh browser to see changes (or use Live Server for auto-reload)
```

### File Editing Guidelines

- **Sass Files**: Edit only `.scss` files in `assets/sass/`
- **Compiled CSS**: Never edit `assets/css/style.css` directly
- **HTML**: Modify `index.html` for structure changes
- **JavaScript**: Custom scripts go in `assets/js/custom.js`

## 📁 Project Structure

```
static-template/
├── 📁 assets/
│   ├── 📁 css/                     # Compiled CSS files
│   │   ├── style.css              # Main compiled stylesheet
│   │   ├── style.css.map          # Sass source map
│   │   ├── bootstrap.min.css      # Bootstrap framework
│   │   ├── fontawesome-free-5.8.1-web/  # Font Awesome icons
│   │   └── ...                    # Other CSS libraries
│   ├── 📁 sass/                   # Source Sass files
│   │   ├── style.scss             # Main Sass entry point
│   │   ├── 📁 component/          # Sass components
│   │   │   ├── _global.scss       # Global styles
│   │   │   ├── _typography.scss   # Font definitions
│   │   │   ├── _color.scss        # Color variables
│   │   │   ├── _button.scss       # Button styles
│   │   │   ├── _header.scss       # Header component
│   │   │   ├── _footer.scss       # Footer component
│   │   │   ├── _mobile.scss       # Mobile navigation
│   │   │   └── _form.scss         # Form styles
│   │   └── 📁 pages/              # Page-specific styles
│   │       └── _home.scss         # Homepage styles
│   ├── 📁 js/                     # JavaScript files
│   │   ├── custom.js              # Custom JavaScript
│   │   ├── main.js                # Main JS functionality
│   │   ├── jquery-3.5.1.min.js   # jQuery library
│   │   ├── slick.min.js           # Carousel library
│   │   └── ...                    # Other JS libraries
│   └── 📁 fonts/                  # Font files
├── 📁 images/                     # Image assets
├── index.html                     # Main HTML file
├── package.json                   # Project dependencies
├── package-lock.json              # Dependency lock file
└── README.md                      # Project documentation
```

### Key Directories Explained

| Directory | Purpose | Notes |
|-----------|---------|-------|
| `assets/sass/` | Source Sass files | Edit these files only |
| `assets/css/` | Compiled CSS | Auto-generated, don't edit |
| `assets/sass/component/` | Reusable components | Modular Sass partials |
| `assets/sass/pages/` | Page-specific styles | Organized by page |

## 📜 Available Scripts

| Script | Command | Description |
|--------|---------|-------------|
| **Development** | `npm run sass-watch` | 🔄 Watch Sass files and auto-compile on changes |
| **Build** | `npm run sass` | 🏗️ Compile Sass to CSS once |

### Script Details

#### `npm run sass-watch`
- **Purpose**: Development mode with hot-reload
- **Action**: Monitors `assets/sass/style.scss` and dependencies
- **Output**: Compiles to `assets/css/style.css` with source maps
- **Usage**: Keep running during development

#### `npm run sass`
- **Purpose**: One-time compilation
- **Action**: Compiles Sass to CSS once
- **Output**: Production-ready CSS file
- **Usage**: Before deployment or testing

## 🎨 Customization

### Modifying Colors

Edit `assets/sass/component/_color.scss`:

```scss
// Primary brand color
$color-primary: #007bff; // Change this to your brand color

// Additional colors
.bg-yellow {
    background-color: #ffc107; // Custom yellow
}

.bg-red {
    background-color: #d70808; // Custom red
}
```

### Changing Typography

Edit `assets/sass/component/_typography.scss`:

```scss
// Primary font family
$font-primary: 'Poppins', sans-serif; // Change font here

// To use a different font:
// 1. Import the font in index.html
// 2. Update the variable above
// 3. Run npm run sass
```

### Adding New Components

1. Create a new file: `assets/sass/component/_newcomponent.scss`
2. Add your component styles
3. Import in `assets/sass/style.scss`:

```scss
@use "component/newcomponent" as *;
```

### Button Customization

Buttons are defined in `assets/sass/component/_button.scss`:

```scss
.btn {
    // Modify base button styles
    &--primary {
        background-color: $color-primary;
        // Primary button styles
    }
    
    &--secondary {
        color: $color-primary;
        // Secondary button styles
    }
}
```

## 📱 Responsive Design

### Breakpoints

The template uses Bootstrap's responsive breakpoints:

| Device | Breakpoint | Max Width |
|--------|------------|-----------|
| 📱 Mobile | `xs` | < 576px |
| 📱 Mobile Large | `sm` | 576px - 767px |
| 📱 Tablet | `md` | 768px - 991px |
| 💻 Desktop | `lg` | 992px - 1199px |
| 🖥️ Large Desktop | `xl` | 1200px+ |

### Mobile-First Approach

```scss
// Mobile first (default)
.element {
    font-size: 16px;
}

// Tablet and up
@media(min-width: 768px) {
    .element {
        font-size: 18px;
    }
}

// Desktop and up
@media(min-width: 992px) {
    .element {
        font-size: 20px;
    }
}
```

## 🔧 Recent Updates

### ✅ Sass Modernization (Latest)

We've recently upgraded the project to use modern Sass practices:

#### What Changed:
- ✅ **Migrated from `node-sass` to `dart-sass`**
- ✅ **Converted `@import` to `@use` syntax**
- ✅ **Eliminated deprecation warnings**
- ✅ **Improved compilation performance**
- ✅ **Future-proofed for Sass 3.0**

#### Before vs After:

**OLD (Deprecated):**
```scss
@import "component/global";
@import "component/typography";
```

**NEW (Modern):**
```scss
@use "component/global" as *;
@use "component/typography" as *;
```

#### Benefits:
- 🚫 **No more deprecation warnings**
- ⚡ **Faster compilation**
- 🔮 **Future-compatible with Sass 3.0**
- 🔧 **Better dependency management**

### Migration Notes

If you're updating from an older version:

1. **Dependencies**: Updated `package.json` to use `sass` instead of `node-sass`
2. **Syntax**: All `@import` statements converted to `@use`
3. **Components**: Each component now explicitly imports its dependencies
4. **Compatibility**: Maintains the same CSS output with modern tooling

## 🌐 Browser Support

### Supported Browsers

| Browser | Version | Notes |
|---------|---------|-------|
| Chrome | 90+ | ✅ Fully supported |
| Firefox | 88+ | ✅ Fully supported |
| Safari | 14+ | ✅ Fully supported |
| Edge | 90+ | ✅ Fully supported |
| Internet Explorer | ❌ | Not supported |

### Mobile Support

- ✅ iOS Safari 14+
- ✅ Chrome Mobile 90+
- ✅ Firefox Mobile 88+
- ✅ Samsung Internet 13+

### Features

- ✅ **CSS Grid & Flexbox** - Modern layout
- ✅ **CSS Custom Properties** - CSS variables
- ✅ **ES6+ JavaScript** - Modern JavaScript features
- ✅ **Responsive Images** - `srcset` and `sizes` attributes
- ✅ **Touch Events** - Mobile-friendly interactions

## ❓ Troubleshooting

### Common Issues & Solutions

#### 🚫 Sass Compilation Errors

**Problem**: `Error: Cannot find module 'sass'`

**Solution**:
```bash
# Delete node_modules and reinstall
rm -rf node_modules package-lock.json
npm install
```

**Problem**: `Error: Undefined variable $color-primary`

**Solution**: Ensure component files have proper `@use` statements:
```scss
@use "color" as *;  // Import color variables
```

#### 🚫 Watch Mode Not Working

**Problem**: `npm run sass-watch` doesn't detect changes

**Solutions**:
1. **Check file permissions**: Ensure Sass files are not read-only
2. **Restart watch mode**: Stop (Ctrl+C) and restart `npm run sass-watch`
3. **Check file paths**: Verify `assets/sass/style.scss` exists

#### 🚫 CSS Not Loading

**Problem**: Styles not appearing in browser

**Solutions**:
1. **Hard refresh**: Ctrl+F5 (Windows) or Cmd+Shift+R (Mac)
2. **Check file path**: Verify `assets/css/style.css` exists
3. **Compile manually**: Run `npm run sass`
4. **Check browser console** for 404 errors

#### 🚫 Bootstrap Conflicts

**Problem**: Bootstrap styles overriding custom styles

**Solution**: Increase CSS specificity or use `!important`:
```scss
.custom-button {
    background-color: $color-primary !important;
}
```

### Getting Help

1. **Check the console**: Browser DevTools → Console tab
2. **Verify file structure**: Ensure all files are in correct locations
3. **Test with simple changes**: Make a small CSS change to verify workflow
4. **Clear browser cache**: Hard refresh or incognito mode

### Performance Tips

- ✅ **Optimize images**: Use WebP format when possible
- ✅ **Minify CSS**: Use build tools for production
- ✅ **Enable gzip**: Configure server compression
- ✅ **Use CDN**: Consider CDN for libraries in production

## 🤝 Contributing

We welcome contributions to improve this template!

### Development Setup

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Make your changes**
4. **Test thoroughly**: Verify responsive design and cross-browser compatibility
5. **Commit**: `git commit -m 'Add amazing feature'`
6. **Push**: `git push origin feature/amazing-feature`
7. **Create Pull Request**

### Contribution Guidelines

- ✅ **Follow existing code style**
- ✅ **Test on multiple browsers**
- ✅ **Update documentation** if needed
- ✅ **Use modern Sass `@use` syntax**
- ✅ **Maintain responsive design**

### Reporting Issues

When reporting bugs, please include:

- 🔍 **Browser and version**
- 📱 **Device information** (for mobile issues)
- 📋 **Steps to reproduce**
- 📸 **Screenshots** (if applicable)
- 💻 **Console errors** (if any)

## 📄 License

This project is licensed under the **ISC License**.

```
Copyright (c) 2024 Guevara Web Graphics Studio

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.
```

---

## 📞 Support & Contact

**Created by**: Guevara Web Graphics Studio  
**Project**: kingrg-version2  
**Version**: 1.0.0  

### Professional Services

Guevara Web Graphics Studio offers:
- 🎨 **Custom Web Design**
- 🔍 **SEO Optimization**
- 🏢 **Brand Development**
- 📱 **Responsive Development**

---

<p align="center">
  <strong>Built with ❤️ by Guevara Web Graphics Studio</strong><br>
  <em>Crafting beautiful websites and personalized SEO services</em>
</p>

---

### Quick Reference

```bash
# Essential commands
npm install           # Install dependencies
npm run sass-watch   # Start development mode
npm run sass         # Compile Sass once

# File structure
assets/sass/         # Edit Sass here
assets/css/          # Compiled CSS (don't edit)
index.html           # Main HTML file
```

**Happy coding! 🚀**
