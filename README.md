# Netflix Landing Page

<div align="center">

![Netflix Logo](./Assets/logo.png)

A modern, responsive Netflix landing page recreation built with HTML, CSS, and vanilla JavaScript. This project demonstrates professional web design principles with an engaging user interface inspired by Netflix's official platform.

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)]()

[Live Demo](#) • [Features](#features) • [Getting Started](#getting-started) • [Technologies](#technologies)

</div>

---

## 📋 Overview

This is a pixel-perfect recreation of the Netflix landing page for the Indian market. The project showcases a full-featured streaming service homepage with a hero section, feature highlights, FAQ section, and footer navigation. It's fully responsive and optimized for all device sizes.

## ✨ Features

### Hero Section

- **Eye-catching Header** - Gradient overlay with engaging call-to-action
- **Language Selector** - Multi-language support interface
- **Sign In Button** - Authentication entry point
- **Email Signup Form** - Newsletter subscription with validation
- **Dynamic Background** - High-quality header image with dark overlay

### Content Sections

- **Feature Showcase** - 4 distinct feature panels highlighting Netflix capabilities:
  - Enjoy on your TV
  - Download shows to watch offline
  - Watch everywhere
  - Create profiles for children
- **FAQ Accordion** - Interactive frequently asked questions with smooth animations
  - What is Netflix?
  - Pricing information
  - Where to watch
  - Cancellation policy
  - Content library details
  - Kids safety features

### Footer

- **Support Links** - Quick access to help and account management
- **Company Information** - Jobs, investor relations, and corporate links
- **Contact Details** - Customer support phone number
- **Language Options** - Localization controls

### Responsive Design

- **Mobile-First Approach** - Optimized for screens as small as 320px
- **Tablet Support** - Perfect layout on medium-sized devices
- **Desktop Experience** - Full-featured interface on large screens
- **Touch-Friendly** - Buttons and interactive elements scaled for mobile

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required

### Installation

1. **Clone or download the repository**

   ```bash
   git clone https://github.com/tebogo222/Netflix-Landing-page.git
   cd Netflix-Landing-page
   ```

2. **Open in your browser**

   - Simply double-click `index.html` to open locally, or
   - Use a local server for best results:

   ```bash
   # Using Python 3
   python -m http.server 8000

   # Using Python 2
   python -m SimpleHTTPServer 8000

   # Using Node.js (if you have http-server installed)
   http-server
   ```

3. **View in browser**
   - Open `http://localhost:8000` in your browser

## 📁 Project Structure

```
Netflix-Landing-page/
├── index.html          # Main HTML markup
├── style.css          # Styling and responsive design
├── README.md          # This file
└── Assets/            # Media files
    ├── logo.png              # Netflix logo
    ├── favicon.png           # Browser tab icon
    ├── header-image.png      # Hero section background
    ├── feature-1.png         # TV feature image
    ├── feature-2.png         # Download feature image
    ├── feature-3.png         # Multi-device feature image
    ├── feature-4.png         # Kids profile feature image
    ├── down-icon.png         # Dropdown indicator
    ├── world.png             # World/globe icon
    └── w.png                 # Additional asset
```

## 🛠 Technologies Used

| Technology       | Purpose                                    | Version |
| ---------------- | ------------------------------------------ | ------- |
| **HTML5**        | Semantic markup and structure              | ES5     |
| **CSS3**         | Styling, animations, and responsive layout | -       |
| **FontAwesome**  | Icon library for UI elements               | 6.x     |
| **Poppins Font** | Modern typography via Google Fonts         | -       |

## 💻 Code Highlights

### Responsive Breakpoints

- **Mobile**: 0 - 600px
- **Tablet**: 600px - 1024px
- **Desktop**: 1024px+

### Key CSS Features

- **Flexbox Layout** - Modern, flexible component arrangement
- **CSS Gradients** - Beautiful color transitions and overlays
- **CSS Transitions** - Smooth animations on interactive elements
- **Media Queries** - Mobile-responsive design patterns
- **CSS Grid** - Footer layout optimization

### Interactive Elements

- **Accordion FAQ** - Expand/collapse with smooth animations
- **Hover Effects** - Visual feedback on buttons and links
- **Form Validation** - HTML5 email input validation
- **Language Dropdown** - Multi-select interface

## 🎨 Design Features

### Color Palette

- **Primary Red**: `#db0001` - Netflix brand signature
- **Dark Background**: `#000` - Premium dark theme
- **Accent Gray**: `#303030` - Content sections
- **Text Gray**: `#777` - Secondary text

### Typography

- **Font Family**: Poppins (via Google Fonts)
- **Weights**: 500 (medium), 700 (bold), 800 (extra bold)
- **Responsive Scaling**: Font sizes adapt to screen size

## 🔍 Performance

- **Lightweight**: Minimal CSS (~30KB uncompressed)
- **Fast Loading**: Single CSS file, no external scripts
- **Optimized Images**: All assets are compressed PNGs
- **No Dependencies**: Pure HTML, CSS, and standard web APIs
- **SEO Friendly**: Semantic HTML5 markup

## 📱 Browser Compatibility

| Browser           | Support    | Notes               |
| ----------------- | ---------- | ------------------- |
| Chrome            | ✅ Full    | Latest 2 versions   |
| Firefox           | ✅ Full    | Latest 2 versions   |
| Safari            | ✅ Full    | iOS 12+             |
| Edge              | ✅ Full    | Latest 2 versions   |
| Internet Explorer | ⚠️ Limited | Basic functionality |

## 🎯 Use Cases

This project is perfect for:

- **Learning Web Development** - Study modern HTML/CSS practices
- **Portfolio Showcase** - Demonstrate responsive design skills
- **Template Reference** - Base for streaming service projects
- **Practice Project** - Hands-on coding experience
- **Interview Preparation** - Real-world website recreation

## 📝 Customization

### Change Colors

Edit the CSS color variables in `style.css`:

```css
/* Primary brand color */
background-color: #db0001;

/* Dark theme background */
background-color: #000;
```

### Update Logo and Images

Replace image files in the `Assets/` folder with your own:

- `logo.png` - Company/brand logo
- `header-image.png` - Hero section background
- `feature-*.png` - Feature section images

### Modify Content

Edit `index.html` to change:

- Headlines and descriptions
- FAQ questions and answers
- Footer links and information
- Contact details

### Adjust Styling

Modify `style.css` to customize:

- Font sizes and weights
- Spacing and padding
- Breakpoints for different devices
- Animation durations and effects

## 🚀 Future Enhancements

Potential improvements for this project:

- [ ] Add JavaScript interactivity
- [ ] Implement working sign-in functionality
- [ ] Create backend integration
- [ ] Add dark/light mode toggle
- [ ] Implement carousel for featured content
- [ ] Add search functionality
- [ ] Optimize images for faster loading
- [ ] Add smooth scroll behavior
- [ ] Implement lazy loading
- [ ] Add accessibility features (ARIA labels)

## 📄 License

This project is open source and available under the MIT License. See the [LICENSE](LICENSE) file for more details.

## 👤 Author

**Tebogo**

- GitHub: [@tebogo222](https://github.com/tebogo222)
- Project: [Netflix Landing Page](https://github.com/tebogo222/Netflix-Landing-page)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## ⭐ Show Your Support

If you found this project helpful, please consider giving it a ⭐ on GitHub!

## 📞 Support

For questions or support:

- Open an issue on GitHub
- Check the FAQ section for common questions
- Review the code comments for implementation details

---

<div align="center">

**Made with ❤️ by Tebogo**

[⬆ Back to top](#netflix-landing-page)

</div>
