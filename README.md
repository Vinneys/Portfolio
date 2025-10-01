# Vincent's Portfolio

A modern, responsive portfolio website showcasing my projects and skills.

## 🚀 Quick Start

### Prerequisites
- [Node.js](https://nodejs.org/) (version 14 or higher)
- npm (comes with Node.js)

### Installation & Setup

1. **Clone or download this repository**
   ```bash
   git clone <your-repo-url>
   cd Portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   - The site will automatically open at `http://localhost:3000`
   - Any changes you make to HTML, CSS, or JS files will automatically reload the browser

## 📁 Project Structure

```
Portfolio/
├── index.html          # Home page
├── projects.html       # Projects showcase
├── contact.html        # Contact form
├── Style.css          # Main stylesheet
├── script.js          # JavaScript functionality
├── images/            # All images and assets
│   ├── Bakground.jpg
│   ├── Proffsbild.jpg
│   └── ...
├── package.json       # Project configuration
└── README.md          # This file
```

## 🛠️ Available Scripts

- `npm run dev` - Start development server with live reload (port 3000)
- `npm start` - Start production server (port 3000)
- `npm run serve` - Start server on port 8080
- `npm run build` - No build process needed (static site)

## ✨ Features

- **Responsive Design** - Works on all devices
- **Live Reload** - See changes instantly during development
- **Modern UI** - Clean, professional design
- **Contact Form** - Integrated with Formspree
- **Project Showcase** - Interactive project cards
- **Mobile Menu** - Hamburger menu for mobile devices

## 🎨 Customization

### Adding New Projects
1. Open `projects.html`
2. Add a new `.project-card` in the `.projects-grid` section
3. Follow the existing structure:
   ```html
   <article class="project-card">
     <h3>Project Name</h3>
     <p>Project description</p>
     <a href="project-url" target="_blank">Visit project</a>
   </article>
   ```

### Updating Content
- **About section**: Edit `index.html`
- **Styling**: Modify `Style.css`
- **Functionality**: Update `script.js`

### Adding Images
1. Place images in the `images/` folder
2. Reference them in your HTML/CSS
3. Use version parameters to prevent caching: `image.jpg?v=1`

## 🌐 Deployment

This is a static website that can be deployed to:
- **GitHub Pages** (free)
- **Netlify** (free tier available)
- **Vercel** (free tier available)
- **Any web hosting service**

### GitHub Pages Deployment
1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio!

## 📄 License

MIT License - feel free to use this template for your own projects.

---

**Built with ❤️ by Vincent**

