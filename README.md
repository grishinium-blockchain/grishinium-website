# Grishinium Landing Page

A standalone HTML landing page for the Grishinium AI-powered blockchain platform.

## Features

- **Interactive Pie Chart** - Tokenomics visualization with hover tooltips
- **Project Cards** - Ecosystem project showcase
- **Responsive Design** - Works on all devices
- **Modern UI** - Clean, gradient-based design with animations
- **AI/Web4 Branding** - Focused on AI and machine-to-machine themes

## Structure

```
Landing/
├── index.html          # Main HTML file
├── css/               # Stylesheets
│   ├── style.css      # Main styles
│   ├── mq.css         # Media queries
│   ├── icons.css      # Icon fonts
│   └── fonts/         # Font files
├── js/                # JavaScript files
│   ├── Grishinium.js    # Main functionality
│   └── *.min.js       # Animation libraries
├── img/               # Images and assets
│   ├── global/        # Global UI elements
│   └── home/          # Homepage specific images
├── favicon/           # Favicon files
├── package.json       # Project configuration
└── README.md          # This file
```

## Running the Site

### Option 1: Python HTTP Server (Recommended)
```bash
npm start
# or
python3 -m http.server 8000
```

### Option 2: Any HTTP Server
Since this is a static HTML site, you can use any web server:
- Live Server (VS Code extension)
- Node.js `http-server`
- Apache/Nginx
- Netlify/Vercel for deployment

## Customizations Made

1. **Tokenomics Section**: Replaced bar chart with interactive pie chart
2. **Project Section**: Restored project cards (previously had ticker)
3. **Discord Button**: Removed distracting "Ask a question" button
4. **Branding**: Updated content to reflect Grishinium/AI themes
5. **Design**: Modern gradient-based color scheme with glow effects

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients and animations
- **JavaScript** - Interactive elements and animations
- **GSAP** - Animation library
- **jQuery** - DOM manipulation

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers

## Development

This is a self-contained static website. All assets are included and paths are relative, making it easy to:

1. Deploy to any static hosting service
2. Run locally without build tools
3. Customize without complex tooling
4. Convert to React/Vue/other frameworks later

## Next Steps

To convert this to a React application:
1. Break HTML into React components
2. Convert CSS to CSS modules or styled-components
3. Replace jQuery with React hooks
4. Add state management if needed
