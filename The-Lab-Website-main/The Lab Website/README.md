# The Lab - Student-Led Program Landing Page

A modern, responsive landing page for "The Lab" - a student-led program that empowers students to launch tennis, coding, and leadership programs. Built with Tailwind CSS and inspired by modern design principles.

## 🌟 Features

### Visual Design
- **Warm Color Palette**: Soft warm white background (#FFF9F5) with red → orange → yellow gradients
- **Glowing Lab Flask Logo**: Custom SVG logo with animated glow effects
- **Smooth Gradients**: Beautiful gradient text fills and border effects
- **Radial Glow Background**: Subtle radial gradient glow behind content
- **Hover Animations**: Soft glow and scale effects on interactive elements

### Layout & Structure
- **Responsive Design**: Fully responsive across all device sizes
- **Sticky Navigation**: Transparent navbar that fades to white on scroll
- **Hero Section**: Large, impactful headline with gradient text effects
- **Program Cards**: Showcase for tennis, coding, and leadership programs
- **Smooth Scrolling**: Elegant navigation between sections

### Technical Features
- **Tailwind CSS**: Modern utility-first CSS framework
- **Inter Font**: Clean, modern typography
- **Custom Animations**: CSS keyframes for glow and float effects
- **Mobile-First**: Optimized for mobile devices
- **Performance Optimized**: Lightweight and fast loading

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- No build tools required - uses CDN for Tailwind CSS

### Installation & Running

1. **Clone or download** the project files
2. **Open `index.html`** in your web browser
3. **That's it!** The page should load immediately

Alternatively, you can serve it locally:

```bash
# Using Python (if installed)
python -m http.server 8000

# Using Node.js (if installed)
npx serve .

# Using PHP (if installed)
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 🎨 Design System

### Color Palette
- **Background**: `#FFF9F5` (Warm White)
- **Primary Gradient**: Red (`#FF4444`) → Orange (`#FF8C42`) → Yellow (`#FFD93D`)
- **Text**: Dark gray (`#1F2937`) for readability
- **Accents**: Orange (`#F97316`) for hover states

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700, 800
- **Hierarchy**: Clear size progression from 5xl to 2xl

### Components
- **Buttons**: Gradient borders with hover effects
- **Cards**: Semi-transparent backgrounds with backdrop blur
- **Logo**: Custom SVG with animated glow
- **Navigation**: Sticky with scroll-based transparency

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px  
- **Desktop**: > 1024px

## 🔧 Customization

### Colors
Edit the Tailwind config in the `<script>` tag to modify colors:

```javascript
colors: {
    'warm-white': '#FFF9F5',
    'glow-red': '#FF4444',
    'glow-orange': '#FF8C42',
    'glow-yellow': '#FFD93D',
}
```

### Content
- Update text content directly in the HTML
- Modify the logo SVG in the navigation section
- Add new sections by following the existing structure

### Animations
Customize animations in the CSS keyframes section:

```css
@keyframes glow {
    '0%': { boxShadow: '0 0 20px rgba(255, 68, 68, 0.3)' },
    '100%': { boxShadow: '0 0 30px rgba(255, 140, 66, 0.5)' },
}
```

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test across different devices and browsers
5. Submit a pull request

## 📞 Contact

For questions or support, please reach out to the development team.

---

**Built with ❤️ for The Lab program** 