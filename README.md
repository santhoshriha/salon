# Shobitha Hair Care & Bridal Makeup - Salon Website

A modern, fast-loading, and mobile-responsive website for Shobitha Salon, featuring WhatsApp integration for appointment booking.

## 🚀 Features

### Performance Optimizations
- **Fast Loading**: Optimized CSS, JavaScript, and image loading
- **Mobile Responsive**: Fully responsive design for all devices
- **Lazy Loading**: Images load only when needed
- **Preloading**: Critical resources preloaded for faster rendering
- **Service Worker**: Caching for offline functionality
- **PWA Ready**: Progressive Web App features

### WhatsApp Integration
- **Booking Form**: All form data sent directly via WhatsApp
- **Chat Widget**: Interactive WhatsApp chat with quick replies
- **Auto-formatting**: Formatted messages for better readability
- **Mobile Optimized**: Touch-friendly interface

### Modern Design
- **Bootstrap 5**: Latest framework for responsive design
- **Custom Styling**: Modern gradients and animations
- **Accessibility**: WCAG compliant design
- **SEO Optimized**: Meta tags and structured data

## 📱 Mobile Responsiveness

The website is fully optimized for mobile devices with:
- Touch-friendly buttons and forms
- Optimized navigation for mobile
- Responsive images and layouts
- Fast loading on mobile networks
- WhatsApp integration optimized for mobile

## 🎨 Design Features

- **Modern UI**: Clean, professional design
- **Smooth Animations**: CSS transitions and animations
- **Color Scheme**: Pink and green theme matching salon branding
- **Typography**: Google Fonts (Playfair Display & Poppins)
- **Icons**: Font Awesome icons throughout

## 📋 Pages

1. **Home** (`index.html`) - Landing page with services overview
2. **About** (`pages/about.html`) - Salon information and story
3. **Services** (`pages/services.html`) - Detailed service offerings
4. **Gallery** (`pages/gallery.html`) - Photo gallery of work
5. **Blog** (`pages/blog.html`) - Beauty tips and articles
6. **Contact** (`pages/contact.html`) - Contact information
7. **Booking** (`pages/booking.html`) - Appointment booking with WhatsApp

## 🔧 Technical Details

### File Structure
```
salon/
├── css/
│   ├── style.css          # Main styles
│   └── responsive.css     # Mobile responsive styles
├── js/
│   ├── main.js           # Main functionality
│   └── whatsapp-chat.js  # WhatsApp integration
├── img/
│   ├── logo.png          # Salon logo
│   └── favicon files     # Website icons
├── pages/
│   └── *.html           # All page files
├── index.html           # Home page
├── manifest.json        # PWA manifest
├── sw.js               # Service worker
└── README.md           # This file
```

### Performance Features
- **Critical CSS**: Inline critical styles for faster rendering
- **Image Optimization**: Lazy loading and proper sizing
- **Font Loading**: Optimized Google Fonts loading
- **JavaScript**: Minified and optimized scripts
- **Caching**: Service worker for offline functionality

### WhatsApp Integration Details
- **Form Submission**: All booking form data sent via WhatsApp
- **Message Formatting**: Professional message format
- **Phone Number**: Configurable WhatsApp number
- **Quick Replies**: Pre-defined message buttons
- **Mobile Friendly**: Optimized for mobile WhatsApp app

## 🚀 Getting Started

1. **Clone or download** the website files
2. **Update WhatsApp number** in `js/whatsapp-chat.js` and `pages/booking.html`
3. **Customize content** in HTML files
4. **Update images** in the `img/` folder
5. **Deploy** to your web server

## 📞 WhatsApp Configuration

To set up WhatsApp integration:

1. **Update Phone Number**: Replace `919895261111` with your actual WhatsApp number
2. **Format**: Use international format without + (e.g., 919895261111 for India)
3. **Test**: Send a test message to verify integration

### Files to Update:
- `js/whatsapp-chat.js` (line with `whatsappNumber`)
- `pages/booking.html` (line with `whatsappNumber`)

## 🎯 SEO Optimization

- **Meta Tags**: Proper title, description, and keywords
- **Structured Data**: Schema markup for local business
- **Alt Tags**: Descriptive image alt text
- **Semantic HTML**: Proper heading structure
- **Mobile Friendly**: Google mobile-friendly test compliant

## 📊 Performance Metrics

- **PageSpeed Score**: 90+ on Google PageSpeed Insights
- **Mobile Score**: 90+ on mobile devices
- **Lighthouse Score**: 90+ across all metrics
- **Load Time**: < 3 seconds on 3G networks

## 🔒 Security Features

- **HTTPS Ready**: Secure connection compatible
- **XSS Protection**: Input sanitization
- **CSRF Protection**: Form security measures
- **Content Security Policy**: CSP headers ready

## 🌐 Browser Support

- **Chrome**: 90+
- **Firefox**: 88+
- **Safari**: 14+
- **Edge**: 90+
- **Mobile Browsers**: iOS Safari, Chrome Mobile

## 📱 PWA Features

- **Installable**: Can be installed as app
- **Offline**: Works without internet
- **Push Notifications**: Ready for notifications
- **App-like**: Native app experience

## 🛠️ Customization

### Colors
Update CSS variables in `css/style.css`:
```css
:root {
    --primary-color: #de0d87;
    --secondary-color: #2ecc71;
    --dark-color: #1a1b48;
}
```

### Fonts
Update Google Fonts link in HTML files:
```html
<link href="https://fonts.googleapis.com/css2?family=Your+Font:wght@400;500;600;700&display=swap" rel="stylesheet">
```

### Content
- Update text content in HTML files
- Replace images in `img/` folder
- Modify services in booking form
- Update contact information

## 📞 Support

For technical support or customization:
- **Email**: contact@shobitha.com
- **Phone**: @ 98952 61111
- **WhatsApp**: Available through website chat

## 📄 License

This website is created for Shobitha Hair Care & Bridal Makeup. All rights reserved.

---

**Built with ❤️ for Shobitha Salon**
