# Dr Janique Chiropractic Website

A modern, responsive website for Dr Janique's chiropractic practice, designed to provide patients with comprehensive information about services, treatment approaches, and booking appointments.

---

## 🌟 Features

- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: 
  - Animated hero sections
  - Modal popups for detailed information
  - Smooth scroll animations (AOS library)
  - Interactive timelines
  - Dropdown navigation menus

- **Key Pages**:
  - **Home**: Introduction to the practice with featured services
  - **About Dr Janique**: Professional background and approach
  - **What We Treat**: Comprehensive list of conditions treated (16 conditions across 4 categories)
  - **Your First Visit**: 5-step timeline explaining the patient journey
  - **Modalities Used**: Treatment techniques and complementary therapies
  - **Contact**: Appointment booking and practice information
  - **404 Page**: Custom error page

---

## 🎨 Design Features

### Color Palette
- Primary: `#3F3B51` (Deep Purple)
- Secondary: `#887561` (Warm Brown)
- Accent: `#EDE6DE` (Soft Beige)
- Background: `#F8F8EF` (Cream)
- Text: `#252525` (Charcoal)

### Typography
- **Headings**: Merriweather (Serif)
- **Body**: Lato (Sans-serif)

### Visual Elements
- Gradient backgrounds
- Card-based layouts
- Animated rhombus frames
- 4-split panoramic image sections
- Puzzle-piece image layouts with gaps

---

## 📂 Project Structure
```
drjanique-website/
│
├── index.html                 # Homepage
├── about.html                 # About Dr Janique
├── conditions-treated.html    # Conditions page
├── first-visit.html           # Your First Visit timeline
├── modalities.html            # Treatment modalities
├── contact.html               # Contact & booking
├── 404.html                   # Error page
│
├── assets/
│   ├── css/
│   │   └── new.css           # Main stylesheet
│   │
│   ├── image/                # Images
│   │   ├── logo.png
│   │   ├── hero-*.jpg
│   │   ├── conditions/
│   │   └── modalities/
│   │
│   └── js/                   # JavaScript files
│       ├── script.js
│       └── carousel.js
│
└── README.md                 # This file
```

---

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: 
  - Custom properties (CSS variables)
  - Flexbox & Grid layouts
  - Animations & transitions
  - Media queries for responsiveness
- **Bootstrap 5**: 
  - Grid system
  - Modal components
  - Responsive utilities
  - Dropdown navigation
- **JavaScript**: 
  - Carousel functionality
  - Modal interactions
  - Smooth scroll
- **AOS (Animate On Scroll)**: Scroll-triggered animations
- **Font Awesome**: Icons
- **Google Fonts**: Typography

---

## 📱 Responsive Breakpoints

- **Desktop**: 992px and above
- **Tablet**: 768px - 991px
- **Mobile (Large)**: 576px - 767px
- **Mobile (Medium)**: 480px - 575px
- **Mobile (Small)**: 320px - 479px

---

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, but recommended)

### Installation

1. **Clone or download the repository**
```bash
   git clone [your-repo-url]
   cd drjanique-website
```

2. **Open in browser**
   - Option A: Double-click `index.html`
   - Option B: Use a local server:
```bash
     # Python 3
     python -m http.server 8000
     
     # Python 2
     python -m SimpleHTTPServer 8000
     
     # Node.js (with http-server)
     npx http-server
```

3. **Navigate to** `http://localhost:8000` in your browser

---

## 📄 Page Descriptions

### Homepage (`index.html`)
- Hero section with call-to-action
- Overview of services
- "Why Choose Dr Janique" section
- Quick contact information

### About Page (`about.html`)
- Animated rhombus section with spinning image
- Professional background
- Treatment philosophy
- 4-split image with modal explanations

### Conditions Treated (`conditions-treated.html`)
- 16 conditions organized in 4 categories
- Overlapping card design
- Modal popups with detailed information
- Responsive grid layout

### Your First Visit (`first-visit.html`)
- Animated X-ray section with overlaid text
- 5-step interactive timeline:
  1. First Consultation
  2. Full Assessment
  3. Chiropractic Adjustment
  4. Home Care Instructions
  5. Book Follow-up
- Modal explanations for each step

### Modalities Used (`modalities.html`)
- Hero section: "The Chiropractic Adjustment"
- 6 complementary modalities:
  - Hypervolt / Massage Gun
  - FAKTR / Blading
  - Dry Needling
  - Dry Cupping
  - Kinesiology Taping
  - Ergonomic Exercises & Stretches
- Card grid with modal details

### Contact Page (`contact.html`)
- Contact form
- Practice location & hours
- Phone/email/WhatsApp links
- Embedded map (optional)

---

## 🎯 Key Features by Section

### Navigation
- Sticky header with dropdown menu
- "About" dropdown contains:
  - About Dr Janique
  - Modalities Used
  - FAQ
- Mobile-friendly hamburger menu
- Smooth transitions

### Footer
- Social media links with hover tooltips
- Quick links (site navigation)
- Practice information
- Copyright notice

### Modals
- Consistent styling across all pages
- Compact headers (not overwhelming)
- "Read More on Blog" + "Close" buttons
- Scrollable content
- Responsive design

---

## 🔧 Customization

### Changing Colors
Edit CSS variables in `assets/css/new.css`:
```css
:root {
  --bg-color-a: #fefefe;     /* White */
  --bg-color-b: #F8F8EF;     /* Cream */
  --bg-color-c: #3F3B51;     /* Purple */
  --bg-color-d: #EDE6DE;     /* Beige */
  /* ... more variables */
}
```

### Adding New Pages
1. Create new HTML file
2. Copy header and footer from existing page
3. Add page link to navigation
4. Update sitemap in footer

### Modifying Animations
- Adjust AOS attributes: `data-aos="fade-up"` `data-aos-duration="1000"`
- Edit CSS keyframes in stylesheet
- Change animation delays: `animation-delay: 2s;`

---

## 📊 Performance Considerations

- **Image Optimization**: Use WebP/AVIF formats with JPG fallbacks
- **Lazy Loading**: Images load as user scrolls
- **Minification**: Consider minifying CSS/JS for production
- **Caching**: Implement browser caching headers
- **CDN**: Consider using CDN for Bootstrap and Font Awesome

---

## 🐛 Known Issues / Future Improvements

- [ ] Add blog functionality
- [ ] Implement online booking system
- [ ] Add patient testimonials section
- [ ] Create FAQ page
- [ ] Integrate with practice management software
- [ ] Add accessibility improvements (ARIA labels, keyboard navigation)
- [ ] Implement contact form backend
- [ ] Add Google Analytics

---

## 📞 Contact & Support

**Practice Contact:**
- **Phone**: +27 83 572 4444
- **Email**: [practice-email]
- **Address**: [practice-address]

**Website Developer:**
- [Your contact information]

---

## 📜 License

© 2024 Dr Janique Chiropractic. All rights reserved.

---

## 🙏 Acknowledgments

- **Bootstrap Team** - UI components
- **Font Awesome** - Icons
- **AOS Library** - Scroll animations
- **Google Fonts** - Typography
- **Claude (Anthropic)** - Development assistance

---

## 📝 Changelog

### Version 1.0.0 (2024)
- Initial website launch
- 7 main pages created
- Responsive design implemented
- Modal system integrated
- Timeline feature added
- Social media integration
- 404 error page

---

**Last Updated**: [Current Date]
**Version**: 1.0.0
**Status**: ✅ Production Ready