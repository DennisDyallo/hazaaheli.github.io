# Haza Aheli - EPK Website

🌟 **Official Electronic Press Kit for Haza Aheli & The Hazayana Collective**

A modern, interactive EPK showcasing fusion dance performances, sacred bass music, and immersive workshop offerings for festival bookings worldwide.

## 🎭 About

This single-page website serves as a professional press kit for **Haza Aheli**, an international performer blending:
- Tribal Fusion dance
- Sacred Bass music
- Fire performance art
- Immersive workshops
- Live percussion & didgeridoo

Featured at major festivals including Boom Festival, Burning Man, and Envision.

## ✨ Features

### 🎨 Interactive Elements
- **Dynamic Biography Tabs**: Switch between elevator pitch, full bio, and collective information
- **Performance Offerings**: Modular packages for stages, workshops, and dancefloors
- **Interactive Vibe Charts**: Visual energy profiles using Chart.js radar charts
- **AI Vision Generator**: Powered by Gemini API to create custom performance visions

### 📱 Technical Highlights
- Fully responsive design with mobile-first approach
- Smooth scroll navigation
- Custom color palette (sand, gold, charcoal, clay tones)
- Animated elements with fade-in effects
- Tailwind CSS for styling
- FontAwesome icons
- Custom Google Fonts (Cormorant Garamond, Montserrat)

### 🧠 AI Integration
The **Vision Alchemist** tool uses the Gemini API to generate personalized performance descriptions based on:
- Event name and theme
- Festival vibe and setting
- Helps organizers visualize how the performance fits their specific atmosphere

## 🚀 Live Site

Visit: [https://hazaaheli.github.io](https://hazaaheli.github.io)

## 🛠️ Technologies Used

- HTML5
- CSS3 (Custom properties, animations)
- JavaScript (ES6+)
- [Tailwind CSS](https://tailwindcss.com/) (CDN)
- [Chart.js](https://www.chartjs.org/) - Data visualization
- [FontAwesome 6](https://fontawesome.com/) - Icons
- [Google Fonts](https://fonts.google.com/) - Typography
- **Gemini API** - AI-powered content generation

## 📂 Structure

```
.
├── index.html          # Main EPK page (single-page application)
└── README.md          # This file
```

## 🎨 Color Palette

```css
--color-sand: #f5f2eb;      /* Background */
--color-stone: #e6e2d3;     /* Borders */
--color-charcoal: #2c2a29;  /* Primary text */
--color-gold: #c5a059;      /* Accent/highlights */
--color-clay: #8c6a5d;      /* Secondary accent */
```

## 📋 Sections

1. **Hero** - Sacred Movement introduction with CTA buttons
2. **About** - Artist & collective biographies with tabbed navigation
3. **Offerings** - Three performance packages with interactive charts
4. **Vision Alchemist** - AI-powered custom vision generator
5. **Past Performances** - Historical engagement data
6. **Media Gallery** - Embedded video and press links
7. **Booking** - Contact form and logistics information

## 🔧 Local Development

Simply open `index.html` in a modern web browser:

```bash
# Using Python's built-in server
python3 -m http.server 8000

# Or using Node's http-server
npx http-server
```

Then navigate to `http://localhost:8000`

## 📝 Customization

To customize the content:
1. Edit biography content in the `updateBio()` JavaScript function
2. Modify performance offerings in the `selectOffering()` function  
3. Update chart data in the Chart.js configuration
4. Adjust color scheme in CSS custom properties

## 🤖 API Configuration

The Gemini AI integration requires an API key. The current implementation includes:
- Event name and theme input
- AI-generated performance vision descriptions
- Error handling for API calls

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

All content and branding © Haza Aheli Management. Website design and code may be used for reference with attribution.

## 📞 Contact

For booking inquiries and performance requests, use the contact form on the website or reach out via the social media links provided.

---

**Built with ✨ for the global festival community**
