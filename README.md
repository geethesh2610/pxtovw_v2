# PX to VW Converter 🎨

A powerful, feature-rich tool for converting CSS pixel values to viewport width (vw) units for truly responsive web design. Built with a modern dark theme interface and comprehensive CSS property support.

![Version](https://img.shields.io/badge/version-2.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Build](https://img.shields.io/badge/build-passing-brightgreen)

## ✨ Features

### 🎯 Core Functionality

-   **Instant Conversion**: Real-time conversion from pixels to viewport width units
-   **Multi-Breakpoint Support**: Separate calculations for mobile, desktop, and large screens
-   **25+ CSS Properties**: Support for fonts, padding, margin, borders, and more
-   **Visual Side Selection**: Interactive box model for selecting specific sides (top, right, bottom, left)
-   **Smart Combinations**: Automatically handles x/y axis combinations for properties like padding and margin

### 🎨 Design

-   **Modern Dark Theme**: Easy on the eyes with a sleek slate color palette
-   **Fully Responsive**: Works seamlessly on mobile, tablet, and desktop
-   **Smooth Animations**: Polished transitions and interactive feedback
-   **Copy to Clipboard**: One-click copying for all generated values

### 🛠️ Supported CSS Properties

#### Sizing

-   Width, Height
-   Min/Max Width, Min/Max Height

#### Spacing

-   Padding (all sides, x/y axis, individual)
-   Margin (all sides, x/y axis, individual)
-   Gap, Space

#### Positioning

-   Top, Right, Bottom, Left
-   Inset (x/y axis)
-   Translate (x/y axis)

#### Borders & Effects

-   Border Width (all sides, individual)
-   Rounded (corners, individual)
-   Outline Width
-   Ring Width
-   Stroke Width
-   Divide Width

#### Typography

-   Font Size (with custom CSS class generation)

#### Scrolling

-   Scroll Margin, Scroll Padding

## 🚀 Getting Started

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/pxtovw_v2.git
cd pxtovw_v2
```

2. **Open in browser**
   Simply open `index.html` in your web browser. No build process required!

### Usage

1. **Enter your pixel value** in the "Value (px)" input
2. **Set viewport widths** for desktop (default: 1728px) and mobile (default: 430px)
3. **Select a CSS property** from the dropdown menu
4. **Choose sides** (if applicable) using the visual box model
5. **Copy the generated values** - Choose from:
    - Mobile VW value
    - Desktop VW value
    - Large Screen VW value (if enabled)
    - Complete Tailwind class (ready to paste)
    - CSS classes (for fonts)

### Example

**Input:**

-   Value: `24px`
-   Desktop Width: `1728px`
-   Mobile Width: `430px`
-   Property: Font Size

**Output:**

-   Mobile VW: `5.581vw`
-   Desktop VW: `1.389vw`
-   Complete Tailwind Class: `text-[5.581vw] md:text-[1.389vw]`

## 🎛️ Advanced Features

### Large Screen Adjustment

Enable the **Large Screen Adjustment** toggle to add a size multiplier for screens 1920px and wider. This helps maintain proper proportions on ultra-wide displays.

**Default multiplier:** 0.9 (90% of desktop size)

### Quick Presets

Use the quick value buttons (4px, 8px, 12px, 16px, 20px, 24px, 32px, 48px) for common spacing values.

### Visual Side Selection

For properties like padding, margin, and borders, use the interactive box model to visually select which sides to apply values to:

-   Click individual sides (Top, Right, Bottom, Left)
-   Select multiple sides for combined classes
-   Automatic detection of x/y axis combinations

## 🎨 Customization

### Viewport Widths

Adjust the desktop and mobile viewport widths to match your design system:

-   **Desktop**: Typically 1440px, 1728px, or 1920px
-   **Mobile**: Common values are 375px, 390px, or 430px

### Large Screen Multiplier

Fine-tune the size reduction for large screens:

-   Range: 0.5 to 1.0
-   Default: 0.9
-   Lower values = smaller text/spacing on large screens

## 📱 Responsive Design

The converter itself is fully responsive with breakpoints at:

-   Mobile: < 640px
-   Tablet: 640px - 1024px
-   Desktop: 1024px - 1280px
-   Large Desktop: > 1280px
