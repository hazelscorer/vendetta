# VENDETTA - Artist Portfolio Website

A bold, contemporary portfolio website for Vendetta, a visual artist based in Derry City, Northern Ireland.

## About the Artist

Vendetta is a 19-year-old visual artist creating raw, unfiltered work that explores the human condition through bold colors, stark contrasts, and unflinching emotion. Trained part-time in art at Foyle College, their portfolio spans portraiture, abstract expressionism, and experimental compositions in oil on canvas.

## Features

- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Animated Interactions**: Smooth scroll effects, hover states, and entrance animations
- **Bold Aesthetic**: Dark theme with striking red accents and distinctive typography
- **Gallery Showcase**: Grid layout displaying selected works with overlay information
- **About Section**: Artist biography and background details
- **Contact Information**: Direct email link for inquiries and collaborations

## Hosting on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in (or create an account)
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository: `vendetta-portfolio` (or `your-username.github.io` for a user site)
4. Make it public
5. Don't initialize with README (we already have one)
6. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**
1. In your new repository, click "uploading an existing file"
2. Drag and drop all files from this folder (index.html, README.md, and the images folder)
3. Commit the changes

**Option B: Using Git Command Line**
```bash
# Navigate to the vendetta-portfolio folder
cd vendetta-portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit the files
git commit -m "Initial commit - Vendetta portfolio website"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR-USERNAME/vendetta-portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" (top menu)
3. Scroll down and click "Pages" (left sidebar)
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait a few minutes for deployment

Your site will be live at: `https://YOUR-USERNAME.github.io/vendetta-portfolio/`

(Or if you named it `your-username.github.io`, it will be at `https://your-username.github.io/`)

## Customization

### Updating Contact Email
In `index.html`, find and replace:
```html
<a href="mailto:vendetta.art@example.com" class="contact-email">vendetta.art@example.com</a>
```
Replace with your actual email address.

### Adding More Artworks
1. Add your image to the `images/` folder
2. In `index.html`, copy an existing artwork card and update:
   - Image source: `src="images/your-image.jpg"`
   - Title: `<h3 class="artwork-title">Your Title</h3>`
   - Details: `<p class="artwork-year">2024 | Oil on Canvas | Dimensions</p>`

Note: Large canvases (like the portrait pieces) are 150 × 80 cm, smaller works are 40 × 60 cm

### Changing Colors
Edit the CSS variables in `index.html` (around line 13):
```css
:root {
    --primary-bg: #0a0a0a;        /* Main background */
    --accent-red: #ff0033;         /* Accent color */
    --accent-yellow: #ffcc00;      /* Secondary accent */
}
```

## File Structure

```
vendetta-portfolio/
│
├── index.html              # Main website file
├── README.md              # This file
└── images/                # Artwork images folder
    ├── suit-portrait.jpg
    ├── silhouette.jpg
    ├── reggae-spirit.jpg
    ├── abstract-weave.jpg
    ├── neon-face.jpg
    ├── sunset-silhouette.jpg
    └── alive-portrait.jpg
```

## Technologies Used

- HTML5
- CSS3 (with animations and transitions)
- Vanilla JavaScript
- Google Fonts (Bebas Neue, Oswald, Work Sans)

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

All artwork © 2025 Vendetta. All rights reserved.
Website design and code may be modified for personal use.

---

**Created with bold vision and artistic integrity.**
