# YOUWARE.md

## Project Overview

This is a playful interactive "forgiveness" website featuring cute kitten images. The site uses a multi-screen flow with animated interactions to create a sweet and humorous experience.

## Architecture

- **Single HTML file**: `index.html` serves as the main entry point
- **Embedded CSS**: All styles are inline in the HTML head for simplicity
- **Vanilla JavaScript**: Interactive functionality is handled by embedded scripts
- **Static Assets**: Multiple kitten images (JPG/PNG) are used across different screens

## Key Features

- **Three-screen flow**: Initial screen → Interactive screen → Thank you screen
- **Button animations**: "Yes" button scales on hover, "No" button escapes mouse interaction
- **Visual effects**: Heart decorations, shadows, rounded corners for a cute aesthetic
- **Responsive design**: Flexible container sizing with mobile-friendly viewport

## File Structure

```
/
├── index.html          # Main HTML file with embedded CSS/JS
├── css/
│   └── style.css      # External CSS (currently unused, styles are inline)
├── *.jpg, *.png       # Kitten images for different screens
```

## Development Notes

- The project uses inline styles and scripts for simplicity
- No build process or package management required
- All functionality is self-contained in `index.html`
- Images are directly referenced without a CDN or image optimization

## Color Scheme

- Primary background: `#ffd1dc` (light pink)
- Container background: `#fff5f7` (soft pink-white)
- Accent colors: `#ff69b4` (hot pink), `#ffb6c1` (light pink)
- Border color: `#ffb6c1` (light pink)

## Interactive Elements

- **Screen 1**: Single "No" button that leads to Screen 2
- **Screen 2**: "Yes" button (leads to Screen 3) and escaping "No" button
- **Screen 3**: Final thank you message with happy kitten

## Translation Status

All text content has been translated from Spanish to English:
- Page title: "Will You Forgive Me?"
- Main question: "Will you forgive me?"
- Final message: "I knew you would forgive me! 💗"
