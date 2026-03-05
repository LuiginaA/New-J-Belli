# Dr Janique Chiropractic Website

A modern, responsive website for Dr Janique's chiropractic practice in Boksburg, South Africa. Designed to provide patients with comprehensive information about chiropractic services, treatment approaches, and easy appointment booking.

---

## 🌟 Features

### Interactive Elements
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Animated Components**: Smooth scroll animations using AOS library
- **Modal Popups**: Detailed information for treatments and conditions
- **Interactive Timelines**: Visual patient journey on First Visit page
- **Dropdown Navigation**: Organized menu structure with animated arrows
- **Social Media Tooltips**: Hover tooltips on social media icons
- **Underline Hover Effects**: Elegant link animations (navbar and footer)

### Key Pages
- **Home**: Introduction to the practice with featured services
- **About Dr Janique**: Professional background, approach, and philosophy
- **What We Treat**: 16 conditions organized in 4 categories with detailed modals
- **Your First Visit**: Interactive 5-step timeline with animations
- **Modalities Used**: Chiropractic adjustment + 6 complementary therapies
- **Blog**: Article list page with individual blog post pages
- **Contact**: Appointment booking and practice information
- **Legal**: Terms & Conditions and Privacy Policy (POPI Act compliant)
- **404 Page**: Custom error page with navigation

---

## 🎨 Design System

### Color Palette
```css
Primary Purple: #3F3B51 (--bg-color-c)
Warm Brown:     #887561 (--text-color-b)
Soft Beige:     #EDE6DE (--bg-color-d)
Cream:          #F8F8EF (--bg-color-b)
White:          #FEFEFE (--bg-color-a)
Charcoal:       #252525 (--text-color-a)
```

### Typography
- **Headings**: Merriweather (Serif, Google Fonts)
- **Body Text**: Lato (Sans-serif, Google Fonts)

### Key Design Features
- Clean card-based layouts with shadows
- Gradient backgrounds using brand colors
- 20px gaps in multi-image sections
- Consistent border-radius (15px for cards)
- Subtle hover effects and transitions
- Professional medical aesthetic

---

## 📂 Project Structure
```
drjanique-website/
│
├── index.html                  # Homepage
├── about.html                  # About Dr Janique
├── conditions-treated.html     # Conditions page (16 conditions)
├── first-visit.html            # Your First Visit timeline
├── modalities.html             # Treatment modalities
├── blog.html                   # Blog list page
├── blog-post.html              # Blog post template
├── blog-post-2.html            # Individual blog posts
├── terms.html                  # Terms & Conditions
├── privacy.html                # Privacy Policy (POPI Act)
├── 404.html                    # Error page
│── contact.html                # Contact & booking
├── assets/
│   ├── css/
│   │   ├── style.css           # Main stylesheet
│   │   └── blog.css            # Blog-specific styles
│   │
│   ├── image/                  # Images folder
│   │   ├── logo.png
│   │   ├── footerlogo.png
│   │   ├── hero-*.jpg
│   │   ├── conditions/         # Condition images
│   │   ├── modalities/         # Modality images
│   │   └── blog-post-*.jpg     # Blog images
│   │
│   └── js/                     # JavaScript files
│       ├── script.js           # Main scripts
│       └── carousel.js         # Carousel functionality
│
└── README.md                   # This file
```

---

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup
- **CSS3**: 
  - Custom properties (CSS variables)
  - Flexbox & Grid layouts
  - Animations & transitions
  - Media queries for responsiveness
- **Bootstrap 5**: 
  - Grid system
  - Modal components
  - Dropdown navigation
  - Responsive utilities
- **JavaScript**: 
  - Carousel functionality
  - Modal interactions
  - Smooth scrolling

### Libraries & Frameworks
- **AOS (Animate On Scroll)**: Scroll-triggered animations
- **Font Awesome**: Icon library
- **Ionicons**: Social media icons
- **Google Fonts**: Merriweather & Lato typography
- **FormSubmit.co**: Newsletter form handling (free service)

---

## 📱 Responsive Breakpoints
```css
Desktop:        992px and above
Tablet:         768px - 991px
Mobile (Large): 576px - 767px
Mobile (Medium):480px - 575px
Mobile (Small): 320px - 479px
```

### Responsive Features
- Flexible grid layouts that adapt to screen size
- Stacked navigation on mobile devices
- Optimized image sizes for different viewports
- Touch-friendly button sizes
- Readable font sizes across all devices

---

## 📝 Blog System

### Structure
- **blog.html**: Main blog page showing all posts in a responsive grid
- **blog-post.html**: Template for individual blog posts
- **blog-post-2.html, 3.html, etc.**: Individual articles

### Adding New Blog Posts

**Step 1: Create the blog post file**
```bash
1. Duplicate blog-post.html
2. Rename to blog-post-X.html (where X is next number)
```

**Step 2: Update content in the new file**
```html
- Change title in <h1> tag
- Update date and author
- Replace featured image path
- Write article content
- Update category badge
```

**Step 3: Add card to blog.html**
```html
<article class="blog-card">
    <div class="blog-card-image">
        <img src="assets/image/blog-post-X.jpg" alt="Post Title">
        <span class="blog-category">Category Name</span>
    </div>
    <div class="blog-card-content">
        <div class="blog-meta">
            <span class="blog-date"><i class="far fa-calendar"></i> Date</span>
            <span class="blog-author"><i class="far fa-user"></i> Dr Janique</span>
        </div>
        <h3>Post Title</h3>
        <p>Short excerpt (2-3 sentences)</p>
        <a href="blog-post-X.html" class="blog-read-more">Read More <i class="fas fa-arrow-right"></i></a>
    </div>
</article>
```

**Step 4: Prepare images**
```
Featured image:  1200x600px (landscape)
Thumbnail:       800x600px
Related posts:   400x300px
Save as:         blog-post-X.jpg
```

### Blog Image Guidelines
- Use descriptive alt text
- Compress images before upload
- Maximum file size: 500KB
- Preferred format: JPG or WebP

---

## 📧 Newsletter System

### Current Setup (FormSubmit.co)
- Free email collection service
- Sends subscriber emails to: `janiquechiro@gmail.com`
- Manual list management
- No cost, no setup required

### Form Location
- Blog page footer section
- Sidebar in single blog posts

### Future Migration (Recommended)
Upgrade to **Mailchimp** when you reach 20+ subscribers:

**Benefits:**
- Automated welcome emails
- Campaign creation tools
- Analytics (open rates, clicks)
- Subscriber management
- Professional templates

**Setup Steps:**
1. Sign up at [mailchimp.com](https://mailchimp.com)
2. Create audience list
3. Design welcome email
4. Get embedded form code
5. Replace FormSubmit code
6. Test subscription flow

---

## 🔍 SEO Optimization

### Implemented
- ✅ Semantic HTML structure
- ✅ Descriptive page titles
- ✅ Clean URL structure
- ✅ Internal linking
- ✅ Responsive design (mobile-friendly)
- ✅ Fast loading times
- ✅ Accessible navigation

### To Be Added
- ⏳ Meta descriptions for all pages
- ⏳ Alt text for all images
- ⏳ Schema.org markup for local business
- ⏳ XML sitemap
- ⏳ Robots.txt file
- ⏳ Open Graph tags for social sharing
- ⏳ Google Analytics integration
- ⏳ Google Search Console setup

### Local SEO Checklist
- [ ] Google My Business listing
- [ ] Local directory submissions (YellowPages, HealthPages)
- [ ] Consistent NAP (Name, Address, Phone) across web
- [ ] Patient reviews on Google
- [ ] Location-specific content (Boksburg, Johannesburg)
- [ ] Local keywords in content

---

## 🚀 Deployment Guide

### Prerequisites
- Web hosting service
- Domain name (recommended)
- FTP client (for traditional hosting)

### Deployment Options

#### Option A: Netlify (Recommended - FREE)
**Best for:** Static sites, beginners, automatic deployments

**Steps:**
1. Create account at [netlify.com](https://netlify.com)
2. Drag and drop your website folder
3. Site goes live instantly
4. Add custom domain in settings
5. Automatic HTTPS included

**Features:**
- Free hosting for static sites
- Automatic HTTPS/SSL
- Custom domain support
- Continuous deployment from Git
- Form handling included

#### Option B: GitHub Pages (FREE)
**Best for:** Developers familiar with Git

**Steps:**
1. Create GitHub account
2. Create new repository
3. Upload all website files
4. Go to Settings → Pages
5. Enable GitHub Pages
6. Access at `username.github.io/repository-name`

#### Option C: Traditional Hosting
**Best for:** Full control, existing hosting plans

**Recommended Hosts:**
- SiteGround (South Africa)
- Afrihost (South Africa)
- Bluehost (International)

**Steps:**
1. Purchase hosting plan
2. Register domain name
3. Download FTP client (FileZilla)
4. Upload files to `public_html` folder
5. Configure domain DNS

### Pre-Deployment Checklist
- [ ] Test all pages in multiple browsers (Chrome, Firefox, Safari, Edge)
- [ ] Test on mobile devices (iOS and Android)
- [ ] Verify all links work (no 404 errors)
- [ ] Check all images load correctly
- [ ] Test contact forms
- [ ] Optimize images (compress with TinyPNG)
- [ ] Test 404 page displays
- [ ] Add favicon.ico
- [ ] Set up Google Analytics
- [ ] Create backup of all files

### Post-Deployment Tasks
- [ ] Submit to Google Search Console
- [ ] Create and submit XML sitemap
- [ ] Set up Google My Business
- [ ] Test website speed (GTmetrix, PageSpeed Insights)
- [ ] Check mobile-friendliness (Google Mobile-Friendly Test)
- [ ] Set up email forwarding (if using custom domain)
- [ ] Monitor website analytics weekly

---

## 📋 Page Status & Features

| Page | Status | Key Features |
|------|--------|--------------|
| Homepage | ✅ Complete | Hero, services overview, CTA sections |
| About | ✅ Complete | 4-split panoramic image, philosophy, modals |
| What We Treat | ✅ Complete | 16 conditions, 4 categories, modals |
| Your First Visit | ✅ Complete | 5-step timeline, X-ray animation, modals |
| Modalities | ✅ Complete | Hero section, 6 modality cards, modals |
| Blog | ✅ Complete | Post grid, single post template, newsletter |
| Contact | ✅ Complete | Form, location, hours, map |
| Terms & Conditions | ✅ Complete | South African legal template |
| Privacy Policy | ✅ Complete | POPI Act compliant |
| 404 Error | ✅ Complete | Custom error page with navigation |
| FAQ | ⏳ Optional | Linked in About dropdown |

---

## 🎨 Component Library

### Navigation Components
- **Top Bar**: Contact info, practice hours
- **Main Navbar**: Logo, dropdown menus, responsive mobile menu
- **Registration Bar**: AHPCSA registration number
- **Footer**: 4-column layout, social media, sitemap, copyright

### Interactive Elements
- **Modal Popups**: Treatment details, condition information
- **Dropdown Menus**: About submenu, Legal submenu
- **Timeline**: Vertical timeline with numbered steps
- **Card Grids**: Blog posts, conditions, modalities
- **Social Tooltips**: Hover labels on social icons

### Form Elements
- **Contact Form**: Name, email, phone, message
- **Newsletter Form**: Email subscription
- **FormSubmit Integration**: Form handling without backend

---

## 🔧 Maintenance Guide

### Regular Updates (Monthly)
- Add new blog posts (aim for 2-4 per month)
- Check and update practice hours
- Verify contact information is current
- Monitor and respond to form submissions
- Update newsletter subscriber list

### Quarterly Tasks
- Review and update Terms & Conditions
- Check Privacy Policy for compliance
- Test all forms and links
- Update treatment information if needed
- Review Google Analytics data
- Check for broken images

### Annual Tasks
- Renew domain name and hosting
- Update copyright year in footer
- Review and refresh website content
- Update professional photos if needed
- Audit SEO performance
- Review and update meta descriptions

### Image Management
- Use WebP format when possible (with JPG fallback)
- Compress all images before upload (use TinyPNG.com)
- Maximum file size: 500KB per image
- Name files descriptively: `chiropractic-adjustment.jpg`
- Maintain consistent aspect ratios

---

## 🆘 Troubleshooting

### Common Issues

**Images not loading:**
```
- Check file path is correct
- Verify image exists in assets/image/ folder
- Check file extension matches (jpg vs jpeg)
- Ensure filename has no spaces
```

**Navbar dropdown not working:**
```
- Verify Bootstrap JS is loaded
- Check dropdown-toggle class is present
- Ensure data-bs-toggle="dropdown" attribute exists
- Confirm Bootstrap version is 5.3.0+
```

**Forms not submitting:**
```
- Verify FormSubmit.co email address
- Check form method="POST"
- Ensure action URL is correct
- Test with different email addresses
```

**Mobile menu not opening:**
```
- Check navbar-toggler button exists
- Verify data-bs-target matches collapse ID
- Ensure Bootstrap JS is loaded
- Test on actual device, not just browser resize
```

**Animations not working:**
```
- Verify AOS library is loaded
- Check data-aos attributes are present
- Ensure AOS.init() is called in JavaScript
- Try refreshing the page
```

---

## 📞 Support & Contact

### Practice Information
- **Name**: Dr Janique Chiropractic
- **Location**: 87 6th Street, Boksburg North, South Africa
- **Phone**: +27 83 572 4444
- **Email**: janiquechiro@gmail.com
- **Registration**: AHPCSA A08186

### Technical Support
- **Website Developer**: [Your name/company]
- **Contact**: [Your contact information]
- **Support Hours**: [Your availability]

### Useful Resources
- [Bootstrap Documentation](https://getbootstrap.com/docs/5.3/)
- [Font Awesome Icons](https://fontawesome.com/icons)
- [AOS Animation Library](https://michalsnik.github.io/aos/)
- [FormSubmit Documentation](https://formsubmit.co/)
- [Google Analytics Help](https://support.google.com/analytics)

---

## 🙏 Credits & Acknowledgments

### Technologies
- **Bootstrap 5** - UI framework
- **Font Awesome** - Icon library
- **Ionicons** - Social media icons
- **AOS Library** - Scroll animations
- **Google Fonts** - Typography (Merriweather, Lato)
- **FormSubmit.co** - Form handling service


### Development
- **Design & Development**: [Your name]
- **Content**: Dr Janique
- **AI Development Assistant**: Claude (Anthropic)
- **Inspiration**: Modern healthcare website design principles
- **Kevin Powell** - Creating an inverted border-radius with CSS https://www.youtube.com/@KevinPowell
- **https://squoosh.app/** - To make images more adaptable
To down scale images for better AOS animation
- **https://www.remove.bg/** -To remove Backgrounds from images


### Special Thanks
- Bootstrap team for responsive framework
- Font Awesome for comprehensive icon set
- AOS library for smooth animations
- FormSubmit for free form handling
- Online Tutorials
- Kevin Powell
- Coding yaar
- Tahmid Ahmed
- Coding 2Go
- Code writer
- CodingNepal
- 
---

## 📄 License

© 2025 Dr Janique Chiropractic. All Rights Reserved.

This website and its content are proprietary. Unauthorized copying, distribution, or modification is prohibited without written permission from Dr Janique Chiropractic.

---

## 📝 Changelog

### Version 1.0.0 (February 2025)
- ✅ Initial website launch
- ✅ 10 main pages created
- ✅ Responsive design implemented
- ✅ Blog system integrated
- ✅ Modal system for treatments
- ✅ Timeline feature for First Visit
- ✅ Social media integration
- ✅ Legal pages (Terms, Privacy)
- ✅ 404 error page
- ✅ Newsletter signup forms

### Upcoming Features (Roadmap)
- ⏳ FAQ page
- ⏳ Patient testimonials section
- ⏳ Online booking system integration
- ⏳ Multilingual support (Afrikaans)
- ⏳ Blog categories and search
- ⏳ Photo gallery
- ⏳ Video testimonials

---

**Last Updated**: February 2026  
**Version**: 1.0.0  
**Status**: ✅ Production Ready