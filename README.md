# Personal Projects Website

A modern, responsive static website showcasing personal projects and applications. Built with HTML, CSS, and designed for GitHub Pages deployment.

## 🌟 Features

- **Modern Design**: Clean, professional interface with smooth animations
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Project Showcase**: Dedicated sections for different projects
- **Contact Pages**: Professional contact and privacy policy pages for projects
- **GitHub Pages Ready**: Configured for automatic deployment

## 📁 Project Structure

```
website/
├── index.html              # Main homepage
├── styles.css              # Global styles
├── ioGram/                 # ioGram project pages
│   ├── contact-us.html     # Contact page
│   └── privacy-policy.html # Privacy policy
└── README.md               # This file
```

## 🚀 Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd website
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

### GitHub Pages Deployment

This website is configured for automatic deployment on GitHub Pages:

1. **Repository Setup**: Ensure your repository is public or you have GitHub Pages enabled for private repos
2. **Branch Configuration**: The site will deploy from the `main` branch
3. **Automatic Deployment**: Every push to the main branch will trigger a new deployment

#### Manual GitHub Pages Setup (if needed):

1. Go to your repository on GitHub
2. Navigate to **Settings** → **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch and **/(root)** folder
5. Click **Save**

Your site will be available at: `https://<username>.github.io/<repository-name>`

## 🎨 Customization

### Adding New Projects

1. Create a new directory for your project (e.g., `myNewApp/`)
2. Add your project pages (contact, privacy policy, etc.)
3. Update the main `index.html` to include your new project in the projects grid

### Styling

- Main styles are in `styles.css`
- Each page can have additional inline styles for specific components
- Uses Inter font family for modern typography
- Color scheme can be customized by modifying CSS variables

### Content Updates

- Update project descriptions in `index.html`
- Modify contact information in project-specific pages
- Update privacy policies as needed

## 📱 Projects Included

### ioGram
- **Description**: AI-powered, highly secure unofficial Telegram client
- **Pages**: Contact Us, Privacy Policy
- **URLs**: 
  - `/ioGram/contact-us`
  - `/ioGram/privacy-policy`

## 🔧 Technical Details

- **HTML5**: Semantic markup for accessibility
- **CSS3**: Modern styling with Flexbox and Grid
- **Responsive Design**: Mobile-first approach
- **Performance**: Optimized for fast loading
- **SEO**: Proper meta tags and structure

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Submit a pull request

## 📞 Support

For questions or issues:
- Create an issue in this repository
- Contact through the project-specific contact pages

---

Built with ❤️ for showcasing amazing projects! 