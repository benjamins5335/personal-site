# Ian & Mads Wedding Website

A beautiful, responsive static wedding website built with HTML, CSS, and JavaScript. Features a clean, classy design with Scottish touches and mobile optimization.

## 🎨 Features

- **Responsive Design**: Optimized for all devices (mobile, tablet, desktop)
- **Scottish Theme**: Subtle Highland touches with appropriate colors and icons
- **Smooth Animations**: Elegant fade-in effects and transitions
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Interactive Elements**: Hover effects, button animations, and scroll effects
- **Accessibility**: Semantic HTML and proper contrast ratios
- **Fast Loading**: Optimized images and minimal dependencies

## 📁 Project Structure

```
wedding-website/
├── index.html          # Homepage with portrait and basic info
├── schedule.html       # Wedding schedule and timeline
├── travel.html        # Travel and accommodation information
├── rsvp.html          # RSVP page with form link
├── styles.css         # Main stylesheet with all styling
├── script.js          # JavaScript for interactivity
├── portrait.jpg       # Your portrait image (add this file)
└── README.md          # This file
```

## 🚀 Quick Start

1. **Add Your Portrait**: Replace the placeholder by adding your portrait image as `portrait.jpg` in the root directory
2. **Update RSVP Link**: In `rsvp.html`, replace the `#` in the RSVP button with your actual form URL
3. **Customize Colors**: Modify the CSS variables in `styles.css` if you want different colors
4. **Deploy**: Upload all files to your chosen hosting platform

## 🎯 Hosting Options

### Recommended: Netlify (Easiest)
1. Go to [netlify.com](https://netlify.com)
2. Sign up for a free account
3. Drag and drop your website folder to deploy
4. Get instant HTTPS and custom domain support

### Alternative Options:
- **Vercel**: Similar to Netlify, developer-friendly
- **Cloudflare Pages**: Excellent performance and security
- **GitHub Pages**: Free hosting through GitHub (requires Git knowledge)

## 📝 Customization

### Adding Your Portrait Image
1. Save your portrait image as `portrait.jpg` in the root directory
2. The image will automatically replace the placeholder
3. Recommended size: 400x600px (portrait orientation)

### Updating the RSVP Form
In `rsvp.html`, find this line:
```html
<a href="#" class="rsvp-button" target="_blank" rel="noopener">
```
Replace `#` with your Google Form, Typeform, or other RSVP form URL.

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2c3e50;    /* Main text color */
    --accent-color: #d4af37;     /* Gold accent color */
    --highland-blue: #4a6741;    /* Scottish green */
    --heather-purple: #967bb6;   /* Scottish purple */
}
```

### Adding Content
- Edit the HTML files directly to add more information
- Use the existing CSS classes for consistent styling
- Follow the established pattern for new sections

## 📱 Mobile Optimization

The website is built mobile-first and includes:
- Responsive navigation with hamburger menu
- Scalable typography using `clamp()`
- Touch-friendly button sizes
- Optimized layouts for small screens

## 🎨 Design Philosophy

- **Typography**: Playfair Display (serif) for headings, Source Sans Pro for body text
- **Colors**: Warm, Scottish-inspired palette with gold accents
- **Layout**: Clean, centered design with plenty of white space
- **Animations**: Subtle, elegant transitions that enhance UX without distraction

## 🔧 Technical Details

- **No Dependencies**: Pure HTML, CSS, and JavaScript
- **Modern CSS**: Uses CSS Grid, Flexbox, and CSS Variables
- **Progressive Enhancement**: Works without JavaScript for core functionality
- **SEO Friendly**: Semantic HTML and proper meta tags

## 📞 Support

If you need help customizing the website:
1. Check the CSS comments for guidance
2. Use browser developer tools to inspect elements
3. Test changes on different devices and browsers

## 🌟 Additional Features You Can Add

- **Google Maps integration** for venue locations
- **Photo gallery** from engagement shoots
- **Guest book** functionality
- **Live streaming** information for remote guests
- **Gift registry** links
- **Wedding countdown timer**

## 📄 License

This website template is provided as-is for personal use. Feel free to modify and customize for your wedding.

---

**Congratulations on your upcoming wedding! 🎉**

*May your love story be as beautiful as the Scottish Highlands.*