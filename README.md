# Storm Website v3

A super polished, professional, and uber-modern website for Storm - the SWPPP writing app.

## Features

- 🎨 Modern, responsive design with Tailwind CSS
- ⚡ Smooth animations powered by Framer Motion
- 📱 Fully responsive across all devices
- 🖼️ High-quality images from Unsplash
- 🚀 Built with Next.js 14 and React 18
- ✨ Professional UI/UX with gradient accents and smooth transitions

## Getting Started

### Prerequisites

- Node.js 18+ installed
- npm or yarn package manager

### Installation

1. Install dependencies:
```bash
npm install
# or
yarn install
```

2. Run the development server:
```bash
npm run dev
# or
yarn dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## Project Structure

```
├── app/
│   ├── layout.tsx          # Root layout with metadata
│   ├── page.tsx            # Main page component
│   └── globals.css         # Global styles and Tailwind directives
├── components/
│   ├── Navbar.tsx          # Navigation bar with mobile menu
│   ├── Hero.tsx            # Hero section with CTA
│   ├── Features.tsx        # Features showcase
│   ├── HowItWorks.tsx      # Step-by-step process
│   ├── Testimonials.tsx    # Customer testimonials
│   ├── CTA.tsx             # Call-to-action section
│   └── Footer.tsx          # Footer with links
├── package.json
├── tailwind.config.js      # Tailwind configuration
└── next.config.js          # Next.js configuration
```

## Build for Production

```bash
npm run build
npm start
```

## Technologies Used

- **Next.js 14** - React framework with App Router
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first CSS framework
- **Framer Motion** - Animation library
- **Unsplash** - High-quality stock images

## Customization

### Colors

Edit the color scheme in `tailwind.config.js` under the `storm` theme:

```js
colors: {
  storm: {
    primary: '#0066FF',
    secondary: '#00D4FF',
    dark: '#001F3F',
    light: '#F0F9FF',
  },
}
```

### Content

Update the content in each component file:
- `components/Hero.tsx` - Hero section text
- `components/Features.tsx` - Feature descriptions
- `components/Testimonials.tsx` - Customer testimonials

## License

All rights reserved.


