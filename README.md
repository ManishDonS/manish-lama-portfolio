# Manish Lama - Personal Portfolio Website

A modern, responsive personal website showcasing professional achievements, blog posts, and portfolio for Manish Lama, CEO of Software Shark Tech Pvt Ltd.

## 🌟 Features

- **Modern Design**: Premium aesthetics with glassmorphism effects, smooth animations, and gradient accents
- **Dark/Light Mode**: Seamless theme switching with localStorage persistence
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Blog System**: Dynamic blog with search, filtering by category, and individual post pages
- **SEO Optimized**: Proper meta tags, semantic HTML, and accessibility features
- **Fast Performance**: Lightweight vanilla JavaScript, no heavy frameworks

## 🚀 Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, flexbox, grid, animations
- **Vanilla JavaScript** - No dependencies, pure JS
- **Google Fonts** - Inter & Outfit typefaces
- **Font Awesome** - Icons

## 📁 Project Structure

```
manish-lama-portfolio/
├── index.html              # Main homepage
├── blog.html               # Blog listing page
├── CNAME                   # Custom domain configuration
├── assets/
│   ├── css/
│   │   └── styles.css      # All styles with design system
│   ├── js/
│   │   ├── main.js         # Core functionality
│   │   └── blog-data.js    # Blog post data
│   └── images/
│       └── profile.png     # Profile picture
└── blog/
    └── [blog-posts].html   # Individual blog post pages
```

## 🎨 Design System

The website uses a comprehensive design system with CSS custom properties:

- **Colors**: Modern HSL-based palette with primary (blue) and accent (purple) colors
- **Typography**: Inter for body text, Outfit for headings
- **Spacing**: Consistent spacing scale (0.25rem to 6rem)
- **Shadows**: Layered shadow system for depth
- **Animations**: Smooth transitions and micro-interactions

## 🌐 Deployment to GitHub Pages

### 1. Initialize Git Repository

```bash
cd /Users/sujanale404/my\ projects/manish-lama-portfolio
git init
git add .
git commit -m "Initial commit: Personal portfolio website"
```

### 2. Create GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository named `manish-lama-portfolio`
2. Don't initialize with README, .gitignore, or license

### 3. Push to GitHub

```bash
git remote add origin https://github.com/ManishDonS/manish-lama-portfolio.git
git branch -M main
git push -u origin main
```

### 4. Enable GitHub Pages

1. Go to your repository settings
2. Navigate to **Pages** section
3. Under **Source**, select **main** branch
4. Click **Save**

Your site will be available at: `https://manishdons.github.io/manish-lama-portfolio/`

### 5. Configure Custom Domain

#### On GitHub:
1. In repository settings > Pages
2. Enter your custom domain: `manish-lama.com.np`
3. Save

#### On Your Domain Provider:
Add these DNS records:

**For root domain (manish-lama.com.np):**
```
Type: A
Name: @
Value: 185.199.108.153
Value: 185.199.109.153
Value: 185.199.110.153
Value: 185.199.111.153
```

**For www subdomain:**
```
Type: CNAME
Name: www
Value: manishdons.github.io
```

**Note**: DNS propagation can take 24-48 hours.

## 🔧 Local Development

To run the website locally:

```bash
# Navigate to project directory
cd /Users/sujanale404/my\ projects/manish-lama-portfolio

# Start a simple HTTP server (Python 3)
python3 -m http.server 8000

# Or using PHP
php -S localhost:8000

# Or using Node.js (if you have http-server installed)
npx http-server -p 8000
```

Then open `http://localhost:8000` in your browser.

## 📝 Adding New Blog Posts

### 1. Add post data to `assets/js/blog-data.js`:

```javascript
{
  id: 7,
  title: "Your Blog Post Title",
  excerpt: "Brief description of your post...",
  category: "Technology", // or Leadership, Business, etc.
  date: "Month DD, YYYY",
  author: "Manish Lama",
  image: "URL_to_image",
  slug: "your-blog-post-slug"
}
```

### 2. Create new HTML file in `blog/` directory:

Copy `blog/future-of-gps-tracking-iot.html` as a template and modify the content.

## 🎯 Features Implemented

- ✅ Responsive navigation with mobile menu
- ✅ Dark/light theme toggle
- ✅ Smooth scrolling
- ✅ Animated hero section
- ✅ Experience timeline
- ✅ Skills showcase
- ✅ Blog system with search and filters
- ✅ Contact section with social links
- ✅ SEO optimization
- ✅ Accessibility features

## 📱 Browser Support

- Chrome/Edge (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

© 2025 Manish Lama. All rights reserved.

## 👤 Author

**Manish Lama**
- CEO at Software Shark Tech Pvt Ltd
- Managing Director at Info Shark Tech Pty Ltd
- LinkedIn: [linkedin.com/in/manishlama2000](https://linkedin.com/in/manishlama2000)

---

Built with passion in Nepal 🇳🇵
