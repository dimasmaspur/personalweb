# Personal Website - Dimas Purwanto

Sebuah personal website modern dan outstanding yang dibuat dengan Astro dan Tailwind CSS, menampilkan portfolio, experience, dan blog.

## ✨ Features

- **Modern Design**: Desain yang clean dan professional terinspirasi dari website modern
- **Responsive**: Fully responsive untuk semua device
- **Fast Performance**: Dibangun dengan Astro untuk optimal performance
- **Dark Mode Ready**: Siap untuk implementasi dark mode
- **SEO Optimized**: Meta tags dan struktur HTML yang SEO-friendly
- **Smooth Animations**: Micro-interactions dan animasi yang smooth
- **Mobile-First**: Didesain dengan pendekatan mobile-first

## 🛠️ Tech Stack

- **Framework**: [Astro](https://astro.build)
- **Styling**: [Tailwind CSS](https://tailwindcss.com)
- **Typography**: [Inter Font](https://fonts.google.com/specimen/Inter)
- **Icons**: Custom SVG icons
- **Deployment**: Ready for Netlify, Vercel, atau platform hosting lainnya

## 📁 Project Structure

```text
/
├── public/
│   └── favicon.svg              # Custom favicon dengan inisial DP
├── src/
│   ├── components/
│   │   ├── Layout.astro         # Base layout component
│   │   ├── Navigation.astro     # Navigation dengan mobile menu
│   │   └── ProjectCard.astro    # Reusable project card component
│   ├── pages/
│   │   ├── index.astro          # Homepage dengan semua sections
│   │   ├── projects.astro       # Halaman daftar semua projects
│   │   └── blog.astro           # Halaman blog
│   └── styles/
│       └── global.css           # Global styles dan custom animations
└── package.json
```

## 🎨 Design Features

### Homepage Sections:
1. **Hero Section** - Introduction dengan gradient text dan CTA buttons
2. **About Section** - Profile dan skills showcase
3. **Experience Section** - Work experience dengan timeline
4. **Projects Section** - Featured projects dengan tech stack
5. **Contact Section** - Contact form dan social links

### Additional Pages:
- **Projects Page** - Complete portfolio showcase
- **Blog Page** - Articles dan insights tentang development

### Custom Animations:
- Floating animations
- Gradient text effects
- Hover glows
- Smooth scrolling
- Fade-in effects

## 🚀 Getting Started

1. **Install dependencies**
   ```bash
   npm install
   ```

2. **Start development server**
   ```bash
   npm run dev
   ```

3. **Open browser**
   Navigate to `http://localhost:4321`

## 🛠️ Available Commands

| Command | Action |
|---------|--------|
| `npm run dev` | Start local dev server |
| `npm run build` | Build production site |
| `npm run preview` | Preview build locally |

## 📝 Customization

### Personal Information
Update data dalam file `src/pages/index.astro`:
- `experiences` array - Work experience
- `projects` array - Portfolio projects  
- `skills` array - Technical skills

### Styling
Modifikasi `src/styles/global.css` untuk:
- Custom animations
- Color schemes
- Typography adjustments

### Content
- Edit component files di `src/components/`
- Update page content di `src/pages/`
- Replace favicon di `public/favicon.svg`

## 🎯 Performance Features

- Static site generation dengan Astro
- Optimized fonts loading
- Minimal JavaScript bundle
- CSS optimizations dengan Tailwind
- Image optimization ready

## 📱 Responsive Design

- Mobile-first approach
- Responsive navigation dengan hamburger menu
- Adaptive typography
- Touch-friendly interactions
- Optimized for all screen sizes

## 🔗 Deployment

Website ini siap untuk di-deploy ke:
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- [GitHub Pages](https://pages.github.com/)
- [Cloudflare Pages](https://pages.cloudflare.com/)

Build command: `npm run build`
Output directory: `dist/`

## 📄 License

MIT License - Silakan gunakan dan modifikasi sesuai kebutuhan.

---

Dibuat dengan ❤️ menggunakan Astro & Tailwind CSS