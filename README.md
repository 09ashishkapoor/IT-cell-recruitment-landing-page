# IT Cell Recruitment Landing Page

A responsive landing page built with Astro for recruiting tech volunteers. The page features a spiritual theme with Ma Adya Kali background, modern design elements, and an integrated application form.

## Features

- 🎨 Responsive design optimized for all devices
- 🖼️ Beautiful background image of Ma Adya Kali
- 🌈 Custom color scheme with spiritual significance
- 📝 Integrated JotForm application system
- 📱 Mobile-friendly layout
- 🎯 Clear sections highlighting volunteer opportunities
- ✨ Modern, semi-transparent UI elements
- 🔒 Secure form submission handling

## Project Structure

```text
/
├── public/
│   ├── MaaAdyaKali_5.png    # Background image
│   └── new-favicon.png      # Site favicon
├── src/
│   ├── components/
│   │   └── Card.astro       # Reusable card component
│   ├── layouts/
│   │   └── Layout.astro     # Main layout template
│   └── pages/
│       └── index.astro      # Main landing page with form integration
├── styles.css               # Global styles
└── package.json            # Project dependencies
```

## 🚀 Getting Started

1. Clone this repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open your browser and visit: `http://localhost:4321`

## 🛠️ Commands

| Command                | Action                                     |
| :-------------------- | :----------------------------------------- |
| `npm install`         | Install dependencies                       |
| `npm run dev`         | Start dev server at `localhost:4321`       |
| `npm run build`       | Build for production to `./dist/`          |
| `npm run preview`     | Preview production build locally           |

## 🎨 Design & Customization

The page uses a carefully chosen color scheme with spiritual significance:
- Headers: Saffron (#ff9933) - Representing energy and spirituality
- Emphasis Text: Golden (#ffd700) - Symbolizing divine wisdom
- Main Text: White (#ffffff) - For clarity and purity
- Background Overlay: Semi-transparent black (rgba(0, 0, 0, 0.75)) - For readability

Components and sections:
- Hero section with welcoming message
- Skills and requirements sections
- Values and opportunities overview
- Embedded JotForm application form
- Responsive footer

To modify the design:
1. Edit `src/pages/index.astro` for content and component-specific styles
2. Update the JotForm iframe ID in index.astro for a different form
3. Edit background image in public/MaaAdyaKali_5.png
4. Modify color scheme in the style section of index.astro

## 🔧 Technologies Used

- [Astro](https://astro.build) v4.15.11 - Static Site Generator
- Modern CSS with custom properties
- JotForm for secure form handling
- Responsive Design principles
- CSS Grid and Flexbox for layouts

## 📝 License

All rights reserved. This project and its contents are not available for reuse.
