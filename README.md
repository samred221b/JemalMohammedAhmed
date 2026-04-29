# Jemal Mohammed Foreign Employment Agency Website

A modern, professional, and elegant website for Jemal Mohammed Foreign Employment Agency - an approved recruitment agency based in Ethiopia that helps people find overseas employment opportunities in Kuwait, Saudi Arabia, and expanding to other countries.

## 🌟 Features

### Design & Branding
- **Ethiopian-Inspired Color Palette**: Green (#078930), Gold (#FCDD09), and Blue accents
- **Modern & Clean Layout**: Professional UI with smooth animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Accessibility**: Clean fonts, high contrast, and semantic HTML

### Pages & Sections

#### 1. Home Page
- Powerful hero section with tagline: "Connecting Ethiopian Talent With Global Opportunities"
- Statistics showcase (5000+ workers placed, 98% success rate)
- Current destinations (Kuwait, Saudi Arabia + Coming Soon)
- Featured job categories with icons
- Success stories carousel
- Call-to-action buttons

#### 2. About Us
- Agency history and mission
- Government certifications and license numbers
- Commitment to ethical recruitment
- Key features: Government Approved, Ethical Recruitment, Continuous Support

#### 3. Opportunities/Jobs Page
- Searchable and filterable job listings
- Filter by: Country, Job Type, Salary Range
- Job cards with detailed information
- Mobile-friendly application modal form
- Dynamic job population via JavaScript

#### 4. Services Page
- 6 core services with icons:
  - Recruitment & Placement
  - Visa Processing
  - Pre-Departure Training
  - Document Legalization
  - Travel Arrangements
  - Continuous Support
- Step-by-step recruitment workflow visualization
- Required documents checklist

#### 5. Country Information Pages
- Tabbed interface for Kuwait and Saudi Arabia
- High demand sectors
- Salary expectations overview
- Worker rights and benefits
- Cultural tips and quick facts

#### 6. Contact Page
- Office location information
- WhatsApp direct contact button
- Phone numbers and email
- Contact form
- FAQ accordion section
- Social media links

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, and CSS Variables
- **JavaScript (ES6+)**: Interactive features and dynamic content
- **Font Awesome 6.4.0**: Professional icons
- **Google Fonts**: Inter & Poppins font families

## 📁 File Structure

```
Mohammed-Jemal-Agency/
├── index.html              # Main HTML file with all sections
├── full-page.html          # Complete integrated page
├── styles.css              # Complete stylesheet
├── script.js               # JavaScript functionality
├── opportunities.html      # Job opportunities section
├── services.html           # Services section
├── countries.html          # Country information section
├── contact.html            # Contact and FAQ section
└── README.md              # This file
```

## 🎨 Color Palette

```css
--ethiopian-green: #078930
--ethiopian-gold: #FCDD09
--ethiopian-red: #DA121A
--primary-color: #078930
--secondary-color: #C9A961 (Gulf luxury gold)
--accent-teal: #00A896
```

## 🚀 Getting Started

1. **Open the website**:
   - Open `index.html` or `full-page.html` in your web browser
   - Or use a local server for best experience

2. **Customize content**:
   - Update license numbers in the HTML
   - Replace placeholder contact information
   - Add real office address and phone numbers
   - Update job listings in `script.js`

3. **Add images**:
   - Replace `.image-placeholder` divs with actual images
   - Add hero background image
   - Include team photos and office pictures

## ✨ Key Features

### Interactive Elements
- **Smooth Scrolling**: Navigation links smoothly scroll to sections
- **Testimonials Carousel**: Auto-playing with manual controls
- **Job Filters**: Real-time filtering of job listings
- **Application Modal**: Pop-up form for job applications
- **FAQ Accordion**: Expandable/collapsible FAQ items
- **Country Tabs**: Switch between country information
- **Mobile Menu**: Responsive hamburger menu
- **Scroll Animations**: Elements fade in on scroll

### Forms
- Job application form with validation
- Contact form with subject selection
- File upload for CV/Resume
- Language selection checkboxes

### Responsive Design
- Mobile-first approach
- Breakpoints at 968px and 640px
- Touch-friendly buttons and links
- Optimized for all screen sizes

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Customization Guide

### Update License Number
Find and replace `ET-2024-XXXX` with your actual license number in:
- `index.html` (About section)
- `full-page.html` (About section and Footer)

### Update Contact Information
Replace placeholder contact details:
- Phone: `+251 11 XXX XXXX`
- Email: `info@jemalmohammedagency.com`
- Address: Update with specific street address

### Add More Jobs
Edit the `jobListings` array in `script.js`:
```javascript
{
    title: 'Job Title',
    country: 'kuwait' or 'saudi',
    countryFlag: '🇰🇼' or '🇸🇦',
    location: 'City, Country',
    type: 'hospitality', 'domestic', 'construction', etc.,
    salary: '$XXX - $XXX/month',
    salaryRange: 'low', 'medium', or 'high',
    time: 'Full Time', 'Part Time', etc.,
    badge: 'New', 'Hot', or null,
    requirements: ['Requirement 1', 'Requirement 2', ...]
}
```

### Multi-Language Support
The language switcher buttons are ready. To implement:
1. Create translation files (JSON format recommended)
2. Update the language switcher function in `script.js`
3. Load translations dynamically based on selected language

## 📊 Performance Optimization

- Minify CSS and JavaScript for production
- Optimize and compress images
- Use CDN for Font Awesome and Google Fonts
- Enable browser caching
- Consider lazy loading for images

## 🔒 Security Considerations

- Implement server-side form validation
- Add CAPTCHA to prevent spam
- Sanitize all user inputs
- Use HTTPS in production
- Implement rate limiting on forms

## 📈 Future Enhancements

- [ ] Backend integration for form submissions
- [ ] Database for job listings
- [ ] Admin panel for content management
- [ ] Email notifications for applications
- [ ] Multi-language translations (Amharic, Arabic)
- [ ] Blog/News section
- [ ] Worker portal for application tracking
- [ ] Integration with Google Maps for office location
- [ ] Live chat support
- [ ] Payment gateway for service fees

## 📞 Support

For questions or support regarding this website:
- Email: info@jemalmohammedagency.com
- Phone: +251 11 XXX XXXX
- WhatsApp: +251 91 XXX XXXX

## 📄 License

© 2024 Jemal Mohammed Foreign Employment Agency. All rights reserved.

---

**Built with ❤️ for Ethiopian workers seeking global opportunities**
