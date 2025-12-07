# ABC Pvt Ltd - Service-Based Company Website

A modern, animated, and responsive website built with Next.js 14, TypeScript, and Tailwind CSS.

## 🎨 Color Theme

The website features a fresh **Teal/Emerald/Cyan** color scheme:

- **Primary (Teal)**: `#14B8A6` - Main brand color
- **Accent (Emerald)**: `#10B981` - Secondary highlights
- **Secondary (Cyan)**: `#06B6D4` - Additional accents

## 🚀 Features

- ✨ Modern and clean design
- 🎭 Smooth animations with Framer Motion
- 📱 Fully responsive (mobile, tablet, desktop)
- 🖼️ Open-source images from Unsplash
- 🎠 Client carousel with Swiper
- 💬 Interactive chatbot
- 🎯 Optimized performance

## 📦 Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Carousel**: Swiper
- **Icons**: React Icons
- **Images**: Unsplash (open-source)

## 🛠️ Getting Started

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Run development server:**
   ```bash
   npm run dev
   ```

3. **Open browser:**
   Navigate to [http://localhost:2020](http://localhost:2020)

## 📁 Project Structure

```
servbas/
├── app/
│   ├── layout.tsx       # Root layout with metadata
│   ├── page.tsx         # Home page
│   └── globals.css      # Global styles
├── components/
│   ├── Navbar.tsx       # Navigation bar
│   ├── Hero.tsx         # Hero section
│   ├── Services.tsx     # Services showcase
│   ├── ClientsCarousel.tsx  # Client projects
│   ├── About.tsx        # About section
│   ├── Contact.tsx      # Contact form
│   ├── Footer.tsx       # Footer
│   └── Chatbot.tsx      # Chatbot widget
├── public/
│   └── images/          # Local images (if any)
└── package.json
```

## 🎨 Customization

### Change Colors

Edit `tailwind.config.ts`:

```typescript
colors: {
  primary: {
    DEFAULT: '#14B8A6',  // Your color
    dark: '#0F766E',
    light: '#5EEAD4',
  },
  // ...
}
```

### Update Images

Replace image URLs in components with your own Unsplash or local images.

### Modify Content

Edit the respective component files in the `components/` folder.

## 📸 Image Sources

All images are from [Unsplash](https://unsplash.com/) - free to use under the Unsplash License.

## 🌐 Deployment

Build for production:

```bash
npm run build
npm start
```

Or deploy to Vercel with one click.

## 📝 License

MIT License - Feel free to use this for your projects!

---

Built with ❤️ using Next.js and TypeScript
