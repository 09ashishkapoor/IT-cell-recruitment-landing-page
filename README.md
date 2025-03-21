# IT Cell Recruitment Landing Page

A responsive landing page built with Astro for recruiting tech volunteers. The page features a spiritual theme with Ma Adya Kali background and modern design elements.

## Features

- 🎨 Responsive design that works on all devices
- 🖼️ Beautiful background image of Ma Adya Kali
- 🌈 Custom color scheme with spiritual significance
- 📱 Mobile-friendly layout
- 🎯 Clear sections for different aspects of recruitment
- ✨ Modern, semi-transparent UI elements

## Project Structure

```text
/
├── public/
│   ├── MaaAdyaKali_5.png    # Background image
│   └── sdfsdfsdf.png        # Favicon
├── src/
│   ├── components/
│   │   └── Card.astro       # Reusable card component
│   ├── layouts/
│   │   └── Layout.astro     # Main layout template
│   └── pages/
│       └── index.astro      # Main landing page
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

## 🎨 Customization

The page uses a carefully chosen color scheme:
- Headers: Saffron (#ff9933)
- Emphasis Text: Golden (#ffd700)
- Main Text: White (#ffffff)
- Background Overlay: Semi-transparent black (rgba(0, 0, 0, 0.75))

To modify the design:
1. Edit `src/pages/index.astro` for content and component-specific styles
2. Edit `styles.css` for global styles
3. Update images in the `public/` directory

## 🔧 Technologies Used

- [Astro](https://astro.build) - Static Site Generator
- Modern CSS with custom properties
- Responsive Design principles
- CSS Grid and Flexbox for layouts

## 📝 License

All rights reserved. This project and its contents are not available for reuse.
