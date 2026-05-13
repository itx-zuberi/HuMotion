# HuMotion — AI-Powered Prosthetic Arm

A modern, cinematic landing page for HuMotion, Pakistan's first AI-powered prosthetic arm that doesn't require surgery.

## 🎯 Features

- **Responsive Design** - Works perfectly on mobile, tablet, and desktop
- **Cinematic Animations** - Smooth intro overlay and scroll reveal effects
- **Interactive Elements** - Mobile menu, smooth scrolling, particle effects
- **Performance Optimized** - Lightweight with CDN-loaded dependencies
- **Accessibility Ready** - Semantic HTML with proper ARIA support
- **SEO Friendly** - Proper meta tags and structured content

## 🚀 Deployment on Vercel

### Quick Start

1. **Clone or fork this repository**
   ```bash
   git clone https://github.com/yourusername/humotion.git
   cd humotion
   ```

2. **Push to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/humotion.git
   git push -u origin main
   ```

3. **Deploy to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Click "Add New" → "Project"
   - Import your GitHub repository
   - Vercel will auto-detect it's a static site
   - Click "Deploy"
   - Your site is live! 🎉

### Alternative: Direct Deploy Button
Click the button below to deploy directly:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/humotion)

## 📁 Project Structure

```
humotion/
├── index.html          # Main landing page
├── vercel.json         # Vercel configuration
├── package.json        # Project metadata
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

## 🛠 Local Development

To run locally:

```bash
# Simple HTTP server
npx http-server . -p 3000

# Or using Python
python -m http.server 3000

# Or using Node.js
node -e "require('http').createServer((req,res)=>{res.end(require('fs').readFileSync('./index.html'))}).listen(3000)"
```

Then open `http://localhost:3000` in your browser.

## 📦 Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Lucide Icons** - Beautiful icon library
- **Vanilla JavaScript** - No frameworks, pure JS
- **Canvas API** - Particle effects
- **Intersection Observer API** - Scroll animations

## 🎨 Customization

### Change Colors
Edit the gradient colors in the CSS section (lines 10-20 in `index.html`):
```css
.gradient-text {
  background: linear-gradient(135deg, #22d3ee, #06b6d4, #7c3aed);
}
```

### Update Contact Information
Find and replace:
- `03338971343` - Phone number
- `zuberi1508@icloud.com` - Email
- `qasimmustafa112@gmail.com` - Alternative email
- `https://www.linkedin.com/in/zuberiii/` - LinkedIn URL

### Modify Pricing
Edit the pricing section (around line 430-480) in `index.html`

### Update Copy
Simply edit the text content in the HTML - all sections are clearly marked with comments.

## 🔐 Security Headers

The `vercel.json` includes security headers:
- **X-Frame-Options** - Prevents clickjacking
- **X-Content-Type-Options** - Prevents MIME sniffing
- **Referrer-Policy** - Controls referrer information

## ⚡ Performance Tips

- Static site serves instantly - no build process needed
- All external resources (Tailwind, Lucide icons) use CDN for fast delivery
- Optimized caching headers in `vercel.json`
- Minimal JavaScript - only 3KB of custom code

## 📊 Analytics (Optional)

Add analytics by inserting tracking code in `<head>`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🐛 Troubleshooting

### Site doesn't look right
- Clear browser cache (Ctrl+Shift+Delete)
- Check that CDNs are loading (check Network tab in DevTools)
- Ensure JavaScript is enabled

### Animations not working
- Check browser compatibility (modern browsers only)
- Verify Intersection Observer support
- Check browser console for errors (F12)

### Mobile menu not closing
- Refresh the page
- Clear browser cache
- Check for JavaScript errors

## 📱 Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari 14+, Chrome Mobile)

## 📄 License

MIT License - feel free to use this for your project

## 👥 Team

- **Founder**: Zuberi
- **Team**: HuMotion Team
- **Location**: Rawalpindi, Pakistan

## 📞 Support

- **Phone**: 0333-8971343
- **Email**: zuberi1508@icloud.com
- **LinkedIn**: [Zuberi's Profile](https://www.linkedin.com/in/zuberiii/)

## 🚨 Emergency Services

- **General Emergency**: 1122
- **Disability Helpline**: 1214

---

**Made with ❤️ for amputees worldwide. No surgery required.**
