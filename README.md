# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Showcase your skills, projects, education, and achievements with a beautiful, interactive design.

## ✨ Features

### 🎨 Design & User Experience
- **Modern & Responsive Design** - Works perfectly on all devices
- **Smooth Animations** - Engaging scroll animations and hover effects
- **Dark/Light Theme Toggle** - Switch between themes with a click
- **Interactive Elements** - Hover effects, skill level indicators, and more
- **Professional Typography** - Clean, readable fonts using Inter

### 📱 Interactive Features
- **Mobile-First Navigation** - Hamburger menu for mobile devices
- **Smooth Scrolling** - Seamless navigation between sections
- **Skill Level Animations** - Animated progress bars for skills
- **Project Showcase** - Interactive project cards with hover effects
- **Contact Form** - Functional contact form with email notifications
- **Scroll Progress Indicator** - Visual progress bar at the top

### 🚀 Technical Features
- **SEO Optimized** - Meta tags, structured data, and semantic HTML
- **Performance Optimized** - Lazy loading, debounced scroll events
- **Accessibility** - ARIA labels, keyboard navigation support
- **Cross-Browser Compatible** - Works on all modern browsers
- **No Dependencies** - Pure HTML, CSS, and JavaScript

## 📋 Sections Included

1. **Hero Section** - Introduction with call-to-action buttons
2. **About Section** - Personal story and statistics
3. **Skills Section** - Technical skills with progress indicators
4. **Projects Section** - Portfolio of work with live demos
5. **Education Section** - Academic background and certifications
6. **Contact Section** - Contact form and social links
7. **Footer** - Additional links and copyright

## 🛠️ Setup Instructions

### Prerequisites
- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. **Clone or Download**
   ```bash
   git clone <repository-url>
   cd portfolio-website
   ```

2. **Open the Website**
   - Simply open `index.html` in your web browser
   - Or use a local server for better development experience

3. **Using a Local Server (Recommended)**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

4. **Access the Website**
   - Open your browser and go to `http://localhost:8000`

## 🎨 Customization Guide

### Personal Information
1. **Update Personal Details** in `index.html`:
   - Replace "Your Name" with your actual name
   - Update email, phone, and location in the contact section
   - Modify the hero section description

2. **Update Profile Picture**:
   - Replace the placeholder icon with your actual photo
   - Update the profile card in the hero section

### Skills & Technologies
1. **Modify Skills** in the skills section:
   - Add/remove skill categories (Frontend, Backend, Tools)
   - Update skill levels (0-100%)
   - Change icons using Font Awesome classes

2. **Update Skill Levels**:
   ```html
   <div class="skill-level" data-level="85"></div>
   ```

### Projects
1. **Add Your Projects**:
   - Replace the example projects with your own
   - Update project descriptions, technologies used
   - Add actual links to live demos and GitHub repositories

2. **Project Structure**:
   ```html
   <div class="project-card">
       <div class="project-image">
           <!-- Add project image or icon -->
       </div>
       <div class="project-content">
           <h3>Project Name</h3>
           <p>Project description</p>
           <div class="project-tech">
               <span>Technology</span>
           </div>
           <div class="project-links">
               <a href="#" class="btn btn-small">Live Demo</a>
               <a href="#" class="btn btn-small btn-outline">GitHub</a>
           </div>
       </div>
   </div>
   ```

### Education & Certifications
1. **Update Timeline**:
   - Replace education entries with your own
   - Add certifications and achievements
   - Update dates and institutions

### Contact Information
1. **Update Contact Details**:
   - Replace email, phone, and address
   - Update social media links
   - Configure email service for contact form

## 📧 Email Integration

The contact form is currently set up with a simulated email service. To enable real email notifications:

### Option 1: EmailJS (Recommended for beginners)
1. Sign up at [EmailJS](https://www.emailjs.com/)
2. Create an email service and template
3. Update the `sendEmailNotification` function in `script.js`:
   ```javascript
   // Add EmailJS script to HTML
   <script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
   
   // Update the function
   return emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', templateParams);
   ```

### Option 2: Formspree
1. Sign up at [Formspree](https://formspree.io/)
2. Replace the form action with your Formspree endpoint
3. Update the form in `index.html`:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

### Option 3: Netlify Forms
1. Deploy to Netlify
2. Add `netlify` attribute to the form
3. Forms will be automatically handled

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to [Netlify](https://netlify.com)
2. Or connect your GitHub repository
3. Your site will be deployed automatically

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts to deploy

### Custom Domain
1. Purchase a domain from any registrar
2. Update DNS settings to point to your hosting provider
3. Configure your hosting provider to use the custom domain

## 🎯 SEO Optimization

The website includes several SEO features:

### Meta Tags
- Title and description tags
- Open Graph tags for social sharing
- Keywords and author information

### Structured Data
- Add JSON-LD structured data for better search results
- Include schema markup for person, organization, and creative work

### Performance
- Optimized images and lazy loading
- Minified CSS and JavaScript (for production)
- Fast loading times

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Mobile Responsiveness

The website is fully responsive and includes:
- Mobile-first design approach
- Touch-friendly navigation
- Optimized layouts for all screen sizes
- Proper viewport meta tags

## 🎨 Color Scheme

The current color scheme uses:
- Primary: `#667eea` (Blue)
- Secondary: `#764ba2` (Purple)
- Background: `#ffffff` (White)
- Text: `#2d3748` (Dark Gray)
- Accent: `#f8fafc` (Light Gray)

You can customize colors by updating the CSS variables in `styles.css`.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

If you have any questions or need help with customization, please:
1. Check the documentation above
2. Look for similar issues in the repository
3. Create a new issue with your question

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Inter font family for clean design
- CSS Grid and Flexbox for layouts

---

**Happy coding! 🚀**

Feel free to customize this portfolio to match your personal brand and showcase your unique skills and projects.