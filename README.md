# TechHive Website

A modern, responsive website for TechHive - a technology company specializing in mobile app development, web development, and ongoing support services. Based in Kenya, serving clients globally.

## 🌟 Features

- **Modern Design**: Clean, professional design with TechHive branding
- **Responsive Layout**: Optimized for all devices (desktop, tablet, mobile)
- **SEO Optimized**: Meta tags, structured data, sitemap, and robots.txt
- **Performance Focused**: Fast loading times and optimized assets
- **Contact Forms**: Functional contact forms with validation
- **Blog Ready**: Structure in place for future content marketing

## 🎨 Brand Identity

- **Colors**: Deep Blue (#1e40af) and Teal (#0f766e) for "Tech", Light Blue (#06b6d4) and Green (#10b981) for "Hive"
- **Logo**: Custom SVG with honeycomb/hive motif representing collaboration and innovation
- **Typography**: Modern sans-serif fonts (SF Pro Display, system fonts)
- **Style**: Modern, innovative, trustworthy, high-tech

## 📁 Project Structure

```
techhive-website/
├── index.html              # Homepage
├── assets/
│   ├── css/
│   │   └── main.css        # Main stylesheet
│   ├── js/
│   │   └── main.js         # JavaScript functionality
│   ├── images/
│   │   └── techhive-logo.svg  # Company logo
│   └── icons/              # Additional icons
├── pages/
│   ├── services.html       # Services page
│   ├── about.html          # About Us page
│   └── contact.html        # Contact page
├── blog/
│   └── index.html          # Blog landing page
├── sitemap.xml             # SEO sitemap
├── robots.txt              # Search engine directives
└── README.md               # This file
```

## 🚀 Deployment Instructions

### Option 1: Traditional Web Hosting

1. **Upload Files**: Upload all files to your web server's public directory
2. **Domain Configuration**: Point your domain (techhive.co.ke) to the server
3. **SSL Certificate**: Enable HTTPS for security
4. **Test**: Verify all pages load correctly and forms work

### Option 2: Netlify (Recommended)

1. **Connect Repository**: Link your Git repository to Netlify
2. **Build Settings**: 
   - Build command: (none needed - static site)
   - Publish directory: `/` (root directory)
3. **Custom Domain**: Add techhive.co.ke in Domain settings
4. **SSL**: Netlify provides free SSL certificates
5. **Form Handling**: Netlify can handle contact forms automatically

### Option 3: Vercel

1. **Import Project**: Import from Git repository
2. **Deploy**: Vercel automatically builds and deploys
3. **Custom Domain**: Add techhive.co.ke in project settings
4. **SSL**: Automatic HTTPS

### Option 4: GitHub Pages

1. **Enable Pages**: In repository settings, enable GitHub Pages
2. **Source**: Select main branch as source
3. **Custom Domain**: Add techhive.co.ke in Pages settings
4. **SSL**: GitHub provides HTTPS for custom domains

## 🔧 Configuration

### Analytics Setup

1. **Google Analytics**: Replace `GA_TRACKING_ID` in the HTML files
2. **Google Search Console**: Verify domain ownership
3. **Meta Pixel**: Add Facebook/Meta pixel if needed

### Email Configuration

The contact forms are currently set up to work with:
- **Netlify Forms**: No additional setup needed on Netlify
- **Formspree**: Add your Formspree endpoint
- **EmailJS**: Configure EmailJS for client-side email sending
- **Custom Backend**: Connect to your own form processing service

### SEO Optimization

- ✅ Meta descriptions and keywords
- ✅ Open Graph tags for social sharing
- ✅ Structured data (JSON-LD)
- ✅ XML sitemap
- ✅ Robots.txt
- ✅ Semantic HTML structure
- ✅ Alt tags for images

## 📱 Mobile Optimization

- Responsive grid system
- Mobile-first CSS approach
- Touch-friendly navigation
- Optimized images and assets
- Fast loading on mobile networks

## 🎯 Performance Features

- CSS custom properties (variables)
- Optimized SVG graphics
- Efficient JavaScript (vanilla JS, no heavy frameworks)
- Compressed and minified assets
- Semantic HTML for better performance

## 🔍 Browser Compatibility

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Progressive enhancement for older browsers

## 🛠️ Development

### Local Development

1. **Clone Repository**: `git clone <repository-url>`
2. **Serve Files**: Use any local server (Live Server extension, Python HTTP server, etc.)
3. **Make Changes**: Edit HTML, CSS, or JavaScript files
4. **Test**: Test on different devices and browsers

### File Serving

For local development, you can use:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js
npx serve .

# PHP
php -S localhost:8000
```

## 📧 Contact Form Setup

### Netlify Forms (Recommended)

The contact forms are ready for Netlify. Just add `netlify` attribute to forms:
```html
<form netlify>
  <!-- form fields -->
</form>
```

### Custom Backend

For custom form handling, modify the JavaScript in `assets/js/main.js` to point to your endpoint.

## 🚀 Performance Optimization

- **Images**: Optimize all images before uploading
- **CSS**: Consider using CSS purging tools for production
- **JavaScript**: Minify JS files for production
- **Caching**: Set up appropriate cache headers on your server

## 📊 Analytics and Monitoring

1. **Google Analytics**: Track website traffic and user behavior
2. **Google Search Console**: Monitor search performance
3. **PageSpeed Insights**: Check and improve loading speed
4. **Uptime Monitoring**: Use services like UptimeRobot

## 🔒 Security

- HTTPS enabled
- No inline scripts (CSP-friendly)
- Form validation on client and server side
- Sanitized user inputs

## 📝 Content Management

- Update content directly in HTML files
- Add new blog posts in the `/blog/` directory
- Update services, pricing, or company information as needed

## 🤝 Support

For technical support or questions about the website:
- Email: info@techhive.co.ke
- Repository Issues: Create an issue in the Git repository

## 📄 License

© 2024 TechHive. All rights reserved.

---

Built with ❤️ in Kenya 🇰🇪
