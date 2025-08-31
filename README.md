# kyros Website

A modern, responsive website for kyros - a UK-based automation agency that helps SMEs cut bottlenecks, save hours, and unlock growth with lightweight, bespoke automation.

## 🚀 Features

- **Modern Design**: Clean, professional layout inspired by high-end tech websites
- **Responsive**: Optimized for all screen sizes with fluid typography
- **Performance**: Fast-loading static site built with Astro
- **SEO Optimized**: Semantic HTML and proper meta tags
- **Accessibility**: ARIA labels and keyboard navigation support

## 🛠️ Tech Stack

- **Framework**: [Astro](https://astro.build/) - Static site generator
- **Styling**: CSS with custom properties and responsive design
- **Fonts**: Inter from Google Fonts
- **Icons**: Emoji-based icon system
- **Deployment**: Static hosting ready

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── Header.astro    # Navigation and hero section
│   ├── WhyUs.astro     # Value propositions
│   ├── Process.astro   # 3-step methodology
│   ├── CaseStudies.astro # Success stories
│   ├── Industries.astro # Industry focus areas
│   ├── FinalCTA.astro  # Call-to-action section
│   └── Footer.astro    # Site footer
├── layouts/            # Page layouts
│   └── Layout.astro   # Main HTML boilerplate
├── pages/              # Page components
│   ├── index.astro    # Homepage
│   └── discovery.astro # Discovery call landing page
└── styles/             # Global styles
    └── global.css     # CSS variables and base styles
```

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation
```bash
# Clone the repository
git clone https://github.com/tdawe1/kyros-website.git
cd kyros-website

# Install dependencies
npm install

# Start development server
npm run dev
```

### Build for Production
```bash
npm run build
```

### Preview Production Build
```bash
npm run preview
```

## 🌐 Deployment

### Local Development
```bash
npm run dev
# Site available at http://localhost:4321
```

### Production Hosting
```bash
npm run build
# Static files generated in dist/ folder
# Deploy dist/ contents to any static hosting service
```

### Self-Hosting
```bash
cd dist
python -m http.server 8080 --bind 0.0.0.0
# Site available at http://localhost:8080
```

## 🎨 Customization

### Colors
Update CSS variables in `src/styles/global.css`:
```css
:root {
  --bg-light: #F8F9FA;
  --text-dark: #212529;
  --accent-blue: #007BFF;
  --accent-orange: #FF6B35;
  --accent-purple: #8B5CF6;
}
```

### Content
- **Company Info**: Update `src/components/Header.astro` and `src/components/Footer.astro`
- **Process Steps**: Modify `src/components/Process.astro`
- **Case Studies**: Edit `src/components/CaseStudies.astro`
- **Value Props**: Update `src/components/WhyUs.astro`

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1920px  
- **Desktop**: > 1920px

## 🔧 Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run astro ...` - Run Astro CLI commands

## 📄 License

All rights reserved © 2024 kyros

## 🤝 Contributing

This is a private project for kyros. For questions or support, contact hello@kyros.com

---

Built with ❤️ using [Astro](https://astro.build/)
