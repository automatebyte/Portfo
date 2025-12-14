# Junior Full-Stack Developer Portfolio

A modern, responsive portfolio website built with HTML5, CSS3, and JavaScript. Designed for junior developers to showcase their skills, projects, and experience to potential employers.

## 🚀 Features

- **Responsive Design**: Mobile-first approach with seamless adaptation across devices
- **Modern UI/UX**: Clean, professional design with navy blue (#0A1F44) and white (#FFFFFF) color scheme
- **Smooth Animations**: Subtle hover effects and smooth scrolling
- **Accessibility**: WCAG compliant with keyboard navigation and screen reader support
- **Performance Optimized**: Lightweight, fast-loading with throttled scroll events
- **SEO Ready**: Semantic HTML structure with proper meta tags

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles with modern features
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Modern features including CSS Grid, Flexbox, and CSS Variables
- **JavaScript (ES6+)**: Modern JavaScript with event handling and DOM manipulation
- **No Frameworks**: Pure vanilla code for maximum performance and learning

## 📱 Sections Included

1. **Hero Section**: Name, title, professional summary, and CTA buttons
2. **About Me**: Background and growth mindset focus
3. **Skills**: Organized by Frontend, Backend, Database, and Tools
4. **Projects**: Featured project (Mvule Catering) plus additional projects
5. **Education**: Diploma in Software Engineering from Moringa School
6. **Contact**: Contact form and social links

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- A local web server (optional, for development)

### Installation

1. **Clone or download** the project files to your local machine

2. **Open the project** in your preferred code editor

3. **Customize the content**:
   - Update personal information in `index.html`
   - Modify colors in CSS variables if needed
   - Add your actual resume file and update the download link
   - Replace placeholder project links with real URLs

4. **Run locally**:
   
   **Option 1: Direct file opening**
   ```bash
   # Simply open index.html in your browser
   open index.html  # macOS
   # or double-click the file
   ```
   
   **Option 2: Local server (recommended)**
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have live-server installed)
   npx live-server
   
   # Using PHP
   php -S localhost:8000
   ```
   
   Then open `http://localhost:8000` in your browser

## 🎨 Customization Guide

### Personal Information
Update the following in `index.html`:
- Name and title in the hero section
- Professional summary
- About me content
- Skills lists
- Project details
- Contact information
- Social media links

### Styling
Modify CSS variables in `styles.css`:
```css
:root {
    --primary-color: #0A1F44;    /* Change primary color */
    --secondary-color: #FFFFFF;   /* Change secondary color */
    /* Add more customizations */
}
```

### Resume Download
1. Add your resume PDF to the project folder
2. Update the download functionality in `script.js`:
```javascript
// Replace the placeholder code with:
const link = document.createElement('a');
link.href = 'path/to/your/resume.pdf';
link.download = 'Your_Name_Resume.pdf';
link.click();
```

### Contact Form
The contact form currently shows notifications only. To make it functional:
1. Set up a backend service (Node.js, PHP, etc.)
2. Update the form action and method
3. Modify the JavaScript to handle actual form submission

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Performance Features

- **CSS Variables**: Easy theming and maintenance
- **Throttled Scroll Events**: Optimized scroll performance
- **Minimal Dependencies**: No external libraries for fast loading
- **Responsive Images**: Optimized for different screen sizes
- **Semantic HTML**: Better SEO and accessibility

## ♿ Accessibility Features

- Semantic HTML structure
- ARIA labels where needed
- Keyboard navigation support
- Focus indicators
- Screen reader friendly
- Reduced motion support for users with vestibular disorders

## 📈 SEO Optimization

- Proper meta tags
- Semantic HTML structure
- Descriptive alt texts (add when including images)
- Clean URL structure
- Fast loading times

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to Netlify
2. Or connect your GitHub repository
3. Your site will be deployed automatically

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements that could benefit others, pull requests are welcome!

## 📞 Support

If you have questions or need help customizing the portfolio, feel free to reach out or create an issue in the repository.

---

**Happy coding! 🚀**