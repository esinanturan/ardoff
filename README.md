# 🏔️ Ardoff Offroad Kulübü

A modern, responsive web application for viewing the Ardoff Offroad Club's rules and regulations PDF document.

## 🌟 Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **PDF Viewer**: Embedded PDF viewing with fallback options
- **Modern UI**: Blue, green, and white themed design with smooth animations
- **Cross-browser Compatible**: Works on all modern browsers
- **Accessibility**: Proper contrast ratios and semantic HTML
- **Progressive Enhancement**: Graceful fallbacks for older browsers

## 🚀 Quick Start

This is a static website that can be viewed by simply opening `index.html` in any web browser.

## 📦 Deployment on Render.com

This project is ready for deployment on Render.com as a static site.

### Automatic Deployment

1. **Fork or Clone** this repository to your GitHub account
2. **Connect to Render**:
   - Go to [Render.com](https://render.com)
   - Click "New +" → "Static Site"
   - Connect your GitHub repository
3. **Configuration** (auto-detected from `render.yaml`):
   - **Build Command**: `npm run build`
   - **Publish Directory**: `./`
4. **Deploy**: Click "Create Static Site"

### Manual Configuration

If you prefer manual setup:

- **Name**: `ardoff-offroad-club`
- **Build Command**: `npm run build`
- **Publish Directory**: `./`
- **Auto-Deploy**: Yes

## 🛠️ Technical Details

### Files Structure
```
ardoff/
├── index.html          # Main HTML file
├── kurallar.pdf        # Club rules PDF document
├── package.json        # Node.js configuration
├── render.yaml         # Render.com deployment config
└── README.md          # This file
```

### Technologies Used
- **HTML5**: Semantic markup and accessibility
- **CSS3**: Modern styling with gradients, animations, and responsive design
- **JavaScript**: PDF viewing controls and responsive behavior
- **No external dependencies**: Pure vanilla web technologies

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🎨 Customization

### Color Scheme
The current theme uses:
- **Primary**: Blue tones (`#2196F3`, `#1e3a5f`)
- **Secondary**: Green tones (`#4CAF50`, `#2d5a4a`)
- **Accent**: White with transparency

### Fonts
- Primary font: Arial (system font for maximum compatibility)
- Fallback: system sans-serif fonts

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px

## 🔒 Security Features

- **Content Security**: X-Frame-Options and X-Content-Type-Options headers
- **PDF Security**: Proper Content-Type headers for PDF files
- **XSS Protection**: No external scripts or inline JavaScript vulnerabilities

## 📄 License

MIT License - feel free to use this template for your own projects.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Support

For questions about the Ardoff Offroad Club, please contact the club administrators.

---

**🚙💨 Macera bizi bekliyor!** - *Adventure awaits us!* 