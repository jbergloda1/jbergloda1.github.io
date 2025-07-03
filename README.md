# Tran Nhat Linh - Software Developer Portfolio

A modern, responsive portfolio website showcasing software development projects and skills.

## 🌟 Features

- **Modern Design**: Clean, professional design with gradient backgrounds and smooth animations
- **Responsive Layout**: Fully responsive design that works on all devices
- **SEO Optimized**: Complete SEO setup with meta tags, structured data, and sitemap
- **Fast Loading**: Optimized for performance with preconnect links and efficient CSS
- **Contact Form**: Interactive contact form for potential clients
- **Project Showcase**: Beautiful project cards with technology tags
- **Mobile Menu**: Hamburger menu for mobile devices

## 🚀 Technologies Used

- **HTML5**: Semantic markup with proper structure
- **CSS3**: Modern CSS with CSS Grid, Flexbox, and custom properties
- **JavaScript**: Vanilla JS for interactivity
- **Font Awesome**: Icons for better visual appeal
- **Google Fonts**: Inter font family for typography

## 📁 File Structure

```
jbergloda1.github.io/
├── index.html              # Main portfolio page
├── cv.html                 # Detailed CV page
├── cv.txt                  # Plain text CV
├── robots.txt              # Search engine crawling instructions
├── sitemap.xml             # XML sitemap for SEO
├── site.webmanifest        # PWA manifest file
├── favicon.svg             # SVG favicon
├── seo.html                # Structured data for SEO
├── README.md               # This file
└── CNAME                   # Custom domain configuration
```

## 🎨 Design Features

### Color Scheme
- **Primary**: #667eea (Blue)
- **Secondary**: #764ba2 (Purple)
- **Text**: #333 (Dark Gray)
- **Background**: #f8f9fa (Light Gray)

### Sections
1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About Section**: Personal information and key skills
3. **Projects Section**: Featured projects with technology tags
4. **Contact Section**: Contact information and contact form
5. **Footer**: Social links and copyright information

## 🔧 SEO Features

### Meta Tags
- Title and description optimized for search engines
- Open Graph tags for social media sharing
- Twitter Card tags for Twitter sharing
- Canonical URL to prevent duplicate content

### Structured Data
- Person schema for personal information
- WebSite schema for website details
- CreativeWork schema for portfolio
- ItemList schema for projects
- Organization schema for business information
- BreadcrumbList for navigation

### Technical SEO
- XML sitemap for search engine indexing
- Robots.txt for crawling instructions
- Favicon and app icons for branding
- Web app manifest for PWA capabilities

## 📱 Responsive Design

The website is fully responsive with breakpoints:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🚀 Performance Optimizations

- **Preconnect**: External domain preconnections
- **CSS Variables**: Efficient styling with custom properties
- **Optimized Images**: SVG icons and efficient image formats
- **Minimal JavaScript**: Lightweight vanilla JS
- **Efficient CSS**: Grid and Flexbox for layout

## 📋 Projects Showcased

1. **Taurus Mobile App** - React Native, Redux, TypeScript
2. **MCH Cotocellar** - Vue.js, Vuex, AWS Cognito
3. **KB Global Banking** - Vue.js, Node.js, TypeScript
4. **Video Generation Platform** - Remotion, React, AWS
5. **T-Pest System** - React Native, React, TypeScript
6. **Japanese Sign Language Recognition** - Flutter, AngularJS, AI/ML

## 🛠️ Setup Instructions

1. **Clone or Download**: Get the files to your local machine
2. **Customize Content**: Update personal information, projects, and contact details
3. **Add Images**: Create an `images/` folder and add:
   - `profile.jpg` - Your profile picture
   - `og-image.jpg` - Social media sharing image (1200x630px)
   - `twitter-card.jpg` - Twitter card image (1200x600px)
   - `logo.png` - Your logo
4. **Update Links**: Replace placeholder social media links
5. **Deploy**: Upload to GitHub Pages or your preferred hosting service

## 📧 Contact Information

- **Email**: tran.nhat.linh@email.com
- **Phone**: +84 XXX XXX XXX
- **Location**: Ho Chi Minh City, Vietnam
- **GitHub**: [jbergloda1](https://github.com/jbergloda1)

## 🔄 Customization

### Colors
Update CSS custom properties in `:root`:
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --text-color: #333;
    --light-text: #666;
    --background: #f8f9fa;
    --white: #ffffff;
}
```

### Content
- Update personal information in the hero and about sections
- Modify project details in the projects section
- Change contact information in the contact section
- Update social media links in the footer

### SEO
- Modify meta tags in the `<head>` section
- Update structured data in `seo.html`
- Change URLs in `sitemap.xml` and `robots.txt`

## 📈 Analytics Setup

To add Google Analytics:

1. Get your Google Analytics tracking ID
2. Add this script before the closing `</head>` tag:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

## 🎯 Future Enhancements

- [ ] Blog section for technical articles
- [ ] Dark mode toggle
- [ ] Project filtering by technology
- [ ] Animated skill progress bars
- [ ] Testimonials section
- [ ] Downloadable resume PDF
- [ ] Multi-language support
- [ ] Contact form backend integration

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

---

**Built with ❤️ by Tran Nhat Linh**
