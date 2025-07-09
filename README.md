# SDG Awareness Website

A responsive web application dedicated to raising awareness about the United Nations Sustainable Development Goals (SDGs), specifically focusing on **SDG 14: Life Below Water** and **SDG 15: Life on Land**.

Video Walk through: [[Video](https://drive.google.com/file/d/1ajrwoKQbtrYTP1wBSnNDW3rXulznS7f6/view?usp=sharing)]

## 🌍 About

This website educates visitors about two critical environmental SDGs:
- **SDG 14**: Conserve and sustainably use the oceans, seas and marine resources
- **SDG 15**: Protect, restore and promote sustainable use of terrestrial ecosystems

## 🚀 Quick Start

### Prerequisites
- [Node.js](https://nodejs.org/) (v18 or higher)
- npm (comes with Node.js)

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd sdg-website/project1
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   node server.js
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

The server will start on port 3000. Press `Ctrl+C` to stop the server.

## 📁 Project Structure

```
project1/
├── public/                     # Static files served by Express
│   ├── index.html             # Homepage
│   ├── about-life-below-water.html    # SDG 14 information
│   ├── about-life-on-land.html       # SDG 15 information
│   ├── register.html          # Registration form
│   ├── css/                   # Stylesheets
│   │   ├── main.css          # Main styles
│   │   ├── water.css         # SDG 14 specific styles
│   │   ├── land.css          # SDG 15 specific styles
│   │   └── register.css      # Form styles
│   └── images/               # Image assets
│       ├── SDG logos and icons
│       └── Educational graphics
├── server.js                 # Express.js server
├── package.json             # Node.js dependencies
└── README.md               # Documentation
```

## ✨ Features

### 🏠 Homepage
- Interactive navigation with SDG-themed design
- Information cards for SDG 14 and SDG 15
- Responsive layout optimized for all devices
- Social media integration

### 🌊 Life Below Water (SDG 14)
- Comprehensive information about marine conservation
- Visual targets and indicators
- Educational content about ocean protection
- Interactive elements and imagery

### 🌳 Life on Land (SDG 15)
- Detailed information about terrestrial ecosystems
- Conservation strategies and targets
- Wildlife protection initiatives
- Biodiversity preservation content

### 📝 Registration System
- User registration form for newsletter/updates
- Form validation and sanitization
- POST request handling with Express.js
- Secure data processing

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3 (Grid & Flexbox), Vanilla JavaScript
- **Fonts**: Google Fonts (Oswald, Roboto)
- **Images**: UN SDG official graphics and Unsplash photography
- **Development**: Modern responsive design principles

## 🎨 Design Principles

### Accessibility First
- ♿ Full keyboard navigation support
- 🎯 WCAG 2.1 AA compliance
- 🔍 Screen reader optimized
- 📱 Responsive design (360px+)
- ⚡ Fast loading times

### Visual Design
- 🎨 UN SDG official color palette
- 📐 12-column grid system
- 📱 Mobile-first responsive design
- 🖼️ High-quality imagery from official SDG resources
- ✨ Clean, modern interface

### Performance
- ⚡ Optimized images and assets
- 🚀 Fast server response times
- 📦 Minimal dependencies
- 🔧 Production-ready configuration

## 📋 Development Guidelines

### Code Standards
- Semantic HTML5 elements
- BEM CSS methodology for class naming
- Progressive enhancement
- Cross-browser compatibility
- Clean, maintainable code structure

### Form Handling
- Server-side form processing with Express.js
- Input sanitization and validation
- User-friendly error messages
- Accessible form design

## 🚦 Getting Started for Developers

### Local Development Setup

1. **Environment Setup**
   ```bash
   # Ensure Node.js is installed
   node --version  # Should be v18+
   npm --version   # Should be v8+
   ```

2. **Project Setup**
   ```bash
   # Install dependencies
   npm install
   
   # Start development server
   npm start  # or node server.js
   ```

3. **Development Workflow**
   - Server runs on `http://localhost:3000`
   - Static files served from `public/` directory
   - Form submissions handled via POST to `/register`
   - Press `Ctrl+C` to stop the server

### Available Scripts

```bash
npm start          # Start the development server
npm install        # Install dependencies
node server.js     # Alternative way to start server
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Code Contribution Guidelines
- Follow existing code style and structure
- Ensure accessibility standards are maintained
- Test across different browsers and devices
- Update documentation as needed

## 📄 License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

The project uses official UN SDG graphics and materials for educational purposes. All SDG-related imagery and content remain the property of the United Nations.

## 📞 Support & Contact

- **Project Issues**: [GitHub Issues](https://github.com/your-repo/issues)
- **SDG Information**: [UN Sustainable Development Goals](https://sdgs.un.org/)
- **Author**: Brett Ritter <swiftone@swiftone.org>

## 🔗 External Resources

- [UN SDG 14: Life Below Water](https://sdgs.un.org/goals/goal14)
- [UN SDG 15: Life on Land](https://sdgs.un.org/goals/goal15)
- [SDG Indicators Database](https://unstats.un.org/sdgs/indicators/database/)
- [UN Environment Programme](https://www.unep.org/)


## ⚡ Performance

- Lighthouse Score: 90+ (Performance, Accessibility, Best Practices, SEO)
- Core Web Vitals: All metrics in green
- Mobile-first responsive design
- Optimized images and assets

---

*Built with 💚 for a sustainable future*

