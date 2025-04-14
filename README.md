# AI Tools Directory 🤖

> The ultimate curated collection of AI tools and resources in a sleek, searchable directory.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Netlify Status](https://api.netlify.com/api/v1/badges/your-badge-id/deploy-status)](https://app.netlify.com/sites/your-site/deploys)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Customization Guide](#customization-guide)
- [Deployment](#deployment)
- [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Support & Resources](#support--resources)

## Overview

AI Tools Directory is a responsive, modern directory website showcasing artificial intelligence tools and resources in a clean, three-column grid layout. Built with HTML, CSS, and JavaScript, it offers fast loading times and excellent search capabilities.

## Features

- 🔍 Real-time search functionality
- 📱 Responsive 3-column grid layout
- 🏷️ Category filtering
- 🎨 Customizable styling
- 🚀 Fast loading times
- 📊 SEO optimized
- 💻 Mobile-friendly design

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- Git
- Text editor (VS Code recommended)

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/ai-tools-directory.git

# Navigate to project directory
cd ai-tools-directory

# Install dependencies
npm install

# Start development server
npm run dev
```

## Directory Structure

```
ai-tools-directory/
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── data/
│   └── directory-items.json
├── index.html
├── README.md
└── package.json
```

## Customization Guide

### Adding Directory Items

Edit `data/directory-items.json`:

```json
{
  "items": [
    {
      "name": "Tool Name",
      "description": "Tool description",
      "category": "Category",
      "url": "https://toolurl.com",
      "image": "tool-image.jpg"
    }
  ]
}
```

### Modifying Categories

Update the categories array in `assets/js/main.js`:

```javascript
const categories = [
  "AI Writing",
  "Image Generation",
  "Chat Bots",
  "Code Assistance"
];
```

### Updating Hero Section

Modify the hero section in `index.html`:

```html
<section class="hero">
  <h1>Your New Title</h1>
  <p>Your new description text</p>
</section>
```

### Customizing Colors

Edit `assets/css/style.css`:

```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --text-color: #your-color;
  --background-color: #your-color;
}
```

## Deployment

### Netlify Deployment

1. Fork this repository
2. Create a new site in Netlify
3. Connect to your GitHub repository
4. Deploy with these settings:
   - Build command: `npm run build`
   - Publish directory: `dist`

### Vercel Deployment

1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow the prompts

## Custom Domain Setup

1. Purchase domain from your preferred registrar
2. Add domain in deployment platform:
   ```
   Domain: yourdomain.com
   WWW Domain: www.yourdomain.com
   ```
3. Update DNS records:
   ```
   A Record: @ → Your deployment IP
   CNAME: www → yourdomain.netlify.app
   ```

## Troubleshooting

### Common Issues

1. **Images Not Loading**
   - Check file paths
   - Verify image formats (JPG/PNG/WebP)
   - Ensure proper permissions

2. **Search Not Working**
   - Clear browser cache
   - Check console for errors
   - Verify data structure in JSON

3. **Layout Issues**
   - Validate HTML
   - Check CSS media queries
   - Test different screen sizes

## Support & Resources

- 📚 [Documentation Wiki](https://github.com/yourusername/ai-tools-directory/wiki)
- 🐛 [Issue Tracker](https://github.com/yourusername/ai-tools-directory/issues)
- 💬 [Community Discord](https://discord.gg/yourinvite)
- 📧 [Support Email](mailto:support@aitools.com)

### Useful Links

- [Contributing Guidelines](CONTRIBUTING.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [License](LICENSE.md)

---

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

Made with ❤️ by [Your Name](https://github.com/yourusername)