# Personal Portfolio Website

A modern, responsive portfolio and blog website built with 11ty (Eleventy) and Tailwind CSS.

## Features

- 🚀 Fast and lightweight static site generation with 11ty
- 🎨 Modern design with Tailwind CSS
- 📱 Fully responsive layout
- 🌙 Dark mode support
- 📝 Blog functionality
- 🎯 Project showcase
- 🔍 SEO optimized

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn

## Getting Started

1. Clone the repository:
```bash
git clone <repository-url>
cd portfolio
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Build for production:
```bash
npm run build
```

## Project Structure

```
.
├── src/
│   ├── _includes/     # Reusable components
│   ├── _layouts/      # Layout templates
│   ├── assets/        # Static assets
│   ├── css/          # CSS files
│   └── index.njk     # Home page
├── _site/            # Generated site (gitignored)
├── .eleventy.js      # 11ty configuration
├── tailwind.config.js # Tailwind CSS configuration
└── package.json
```

## Customization

1. Update personal information in the templates
2. Modify the color scheme in `tailwind.config.js`
3. Add your projects and blog posts
4. Customize the layout in `src/_includes/base.njk`

## License

MIT License - feel free to use this template for your own portfolio! 