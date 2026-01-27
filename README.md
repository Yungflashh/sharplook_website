# Sharplook - Local Marketplace Website

A stunning, modern marketing website for Sharplook mobile app built with Next.js, TypeScript, and Tailwind CSS.

## 🎯 About Sharplook

Sharplook is a comprehensive local marketplace platform that connects users with trusted vendors for services and products. The app features:

- **Service Bookings** - Schedule appointments with local service providers
- **Product Marketplace** - Browse and purchase from local vendors
- **Secure Payments** - Escrow protection for all transactions
- **Real-Time Communication** - In-app messaging and voice recording
- **Smart Search** - Find vendors based on distance and ratings
- **Offer Bargaining** - Negotiate prices directly with vendors
- **And much more!**

## ✨ Website Features

- 🎨 Beautiful dark theme with vibrant pink (#D73870) brand color
- ⚡ Smooth animations powered by Framer Motion
- 📱 Fully responsive design
- 🚀 SEO optimized with proper metadata
- 🎯 Clear CTAs for iOS and Android downloads
- 💫 Interactive feature showcase with filtering
- 🔒 Security and trust indicators
- 📊 Statistics and social proof

## 🛠️ Tech Stack

- **Next.js 15** - React framework with App Router
- **TypeScript** - Type-safe development
- **Tailwind CSS 3** - Utility-first CSS framework
- **Framer Motion** - Animation library
- **Righteous & Outfit** - Modern Google Fonts

## 🚀 Getting Started

### Prerequisites

- Node.js 18 or higher
- npm or yarn

### Installation

1. Extract the zip file
2. Navigate to the project directory:
```bash
cd sharplook-website
```

3. Install dependencies:
```bash
npm install
```

### Development

Run the development server:
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the website.

### Build for Production

Generate the static website:
```bash
npm run build
```

The static files will be created in the `out` directory.

### Preview Production Build

```bash
npm run start
```

## 📁 Project Structure

```
sharplook-website/
├── app/
│   ├── globals.css       # Global styles, animations, and Tailwind
│   ├── layout.tsx        # Root layout with SEO metadata
│   └── page.tsx          # Main homepage with all sections
├── out/                  # Built static files (after build)
├── public/               # Static assets (add your images here)
├── next.config.js        # Next.js configuration (static export)
├── tailwind.config.js    # Tailwind CSS configuration
├── tsconfig.json         # TypeScript configuration
├── postcss.config.js     # PostCSS configuration
└── package.json          # Dependencies and scripts
```

## 🎨 Customization

### Brand Colors

The brand color (#D73870) is already set. To modify:

1. Update `tailwind.config.js`:
```javascript
colors: {
  primary: '#D73870',
  'primary-dark': '#B82D5C',
  'primary-light': '#FF5B96',
}
```

2. Update `app/globals.css`:
```css
:root {
  --primary: #D73870;
  --primary-dark: #B82D5C;
  --primary-light: #FF5B96;
}
```

### Content

Edit `app/page.tsx` to customize:
- App name and tagline
- Feature descriptions
- Statistics
- Download links
- Footer content
- Social media links

### Fonts

Change fonts in `app/layout.tsx`:
```html
<link href="https://fonts.googleapis.com/css2?family=YOUR_FONT&display=swap" rel="stylesheet" />
```

Then update `app/globals.css` to use your new fonts.

### Images

Add your app screenshots, logos, and other images to the `public` directory and reference them in your components.

## 📱 Features Showcased

The website highlights all operational Sharplook features:

✅ **Marketplace**
- Product ordering
- Vendor searching  
- Sponsored & featured products
- Service posting & approval

✅ **Booking System**
- Service bookings
- Late cancellation fees
- Distance calculations

✅ **Communication**
- In-app messaging
- Voice recording
- Email notifications
- Real-time updates

✅ **Security**
- Escrow payments
- User verification
- Secure registration flow
- Offer bargaining protection

## 🚀 Deployment

### Vercel (Recommended)

1. Push code to GitHub
2. Import project in Vercel
3. Deploy automatically

### Netlify

1. Drag and drop the `out` folder to Netlify
2. Or connect your Git repository

### Other Static Hosts

Upload the contents of the `out` directory to:
- AWS S3 + CloudFront
- GitHub Pages
- Cloudflare Pages
- Any static hosting service

## 📝 SEO

The website is optimized for search engines with:
- Semantic HTML structure
- Meta tags for title, description, keywords
- Open Graph tags for social sharing
- Fast loading times
- Mobile-first responsive design

To update SEO metadata, edit `app/layout.tsx`:
```typescript
export const metadata: Metadata = {
  title: 'Your Title',
  description: 'Your Description',
  // ...
}
```

## 🎯 Performance

The website is optimized for performance:
- Static generation (blazing fast)
- Optimized images (when added)
- Code splitting
- Minimal JavaScript bundle
- CSS optimizations

## 📄 License

This project is provided as-is for Sharplook's use.

## 🤝 Support

For questions about:
- **Next.js**: https://nextjs.org/docs
- **Tailwind CSS**: https://tailwindcss.com/docs
- **Framer Motion**: https://www.framer.com/motion/

## 📞 Contact

For Sharplook app support or inquiries, visit the website's contact section.

---

Built with ❤️ for Sharplook
