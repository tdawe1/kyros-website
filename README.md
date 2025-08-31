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

## 🤔 Why Astro?

This project was built using **Astro** as a learning experience and exploration of modern web development tools. As my first time using Astro, I chose it for several compelling reasons:

- **Performance First**: Astro's "zero JavaScript by default" approach ensures lightning-fast page loads
- **Component Islands**: The ability to selectively add interactivity only where needed
- **Framework Agnostic**: Can use React, Vue, Svelte components alongside vanilla HTML/CSS
- **Static Site Generation**: Perfect for content-heavy websites that don't need complex client-side state
- **Modern Developer Experience**: Built-in TypeScript support, hot reloading, and excellent tooling
- **Learning Opportunity**: A chance to explore a framework that's gaining significant traction in the static site space

**Note**: This is my first Astro project, so the codebase represents a learning journey. While functional and well-structured, it may not follow all Astro best practices yet.

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

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1920px  
- **Desktop**: > 1920px

## 📄 License

All rights reserved © 2024 kyros

## 🤝 Support

For questions or support, contact hello@kyros.com

---

Built with ❤️ using [Astro](https://astro.build/)
