# QR Code & Barcode Scanner - Website

This folder contains the complete website for the QR Code & Barcode Scanner application, including privacy policy, terms of service, and marketing content.

## 📁 File Structure

```
website/
├── index.html              # Main homepage with features and CTA
├── privacy-policy.html     # Comprehensive privacy policy (GDPR, CCPA compliant)
├── terms.html              # Terms of service
├── contact.html            # Contact page with form
├── styles.css              # Main stylesheet
└── README.md               # This file
```

## 📄 Pages Overview

### 1. **index.html** - Homepage
- Hero section with app showcasing
- Features grid (6 key features)
- Scanning capabilities section
- Code generation showcase
- Privacy-first design highlights
- How it works section
- Technical specifications
- FAQ section
- Testimonials
- Download CTAs
- Footer with links

### 2. **privacy-policy.html** - Privacy Policy
**Comprehensive 15-section privacy policy covering:**

- Introduction and consent
- Information collection (direct & automatic)
- Sensitive information handling
- Data usage and advertising
- Information sharing and third parties
- Data security measures
- Data retention policies
- User privacy rights (access, deletion, opt-out)
- Children's privacy protection
- International data transfers
- Cookies & tracking
- Third-party links
- California CCPA rights
- GDPR compliance (EU/EEA)
- Policy updates
- Contact information

**Compliance Standards:**
- ✅ GDPR compliant (EU/EEA)
- ✅ CCPA compliant (California)
- ✅ GDPR Article 13/14 requirements
- ✅ Google Mobile Ads disclosure
- ✅ Cookie policy
- ✅ Data processing transparency

### 3. **terms.html** - Terms of Service
**Comprehensive 21-section terms including:**

- Acceptance of terms
- License grant with restrictions
- User responsibilities
- Intellectual property rights
- Disclaimers and warranties
- Limitation of liability
- Indemnification
- Termination policies
- Service modifications
- Payment terms (if applicable)
- Advertisement policies
- Third-party services
- Permissions & privacy
- App store terms
- Governing law & jurisdiction
- Dispute resolution
- Severability and waiver
- Contact information

### 4. **contact.html** - Contact & Support
- Multiple contact methods
- Email support categories
- Contact form with validation
- Response time commitments
- Support resources
- Quick links
- Office information
- FAQ resources

### 5. **styles.css** - Styling
- Modern, responsive design
- CSS variables for easy theming
- Mobile-first responsive design
- Dark color scheme with gradients
- Professional card-based layouts
- Smooth transitions and hover effects
- Print-friendly styles

## 🎨 Design Features

### Colors
- **Primary**: #2563eb (Blue)
- **Secondary**: #0891b2 (Cyan)
- **Accent**: #f59e0b (Amber)
- **Dark Background**: #1f2937
- **Light Background**: #f9fafb

### Responsive Design
- Desktop: Full layout with sidebars
- Tablet: Optimized grid layouts
- Mobile: Single column with touch-friendly buttons

### Accessibility
- Semantic HTML structure
- ARIA labels where needed
- Color contrast compliance
- Keyboard navigation support

## 🚀 Deployment Instructions

### Option 1: Static Hosting (Recommended)
1. **Netlify** (Free, automatic deployments)
   ```bash
   netlify deploy --prod --dir website
   ```

2. **Vercel** (Free, GitHub integration)
   - Push to GitHub
   - Connect to Vercel
   - Auto-deploys on push

3. **GitHub Pages**
   - Push to GitHub
   - Enable Pages in settings
   - Set source to `website` folder

### Option 2: Traditional Web Hosting
- Upload all files to your web host via FTP
- Ensure all HTML, CSS files are in root directory
- No server-side processing required

### Option 3: CDN + Storage
- Upload to AWS S3
- CloudFront CDN in front
- Route 53 for DNS

## 🔧 Configuration Required

Before deploying, update the following:

### 1. **Google Play & App Store Links**
In all HTML files, replace:
```html
https://play.google.com/store/apps/details?id=com.example.qrcodebarcodescanner
https://apps.apple.com/app/qr-code-barcode-scanner/idXXXXXXXXXX
```

### 2. **Email Addresses**
Replace in `privacy-policy.html`, `terms.html`, `contact.html`:
- `privacy@qrcodebarcodescanner.app`
- `support@qrcodebarcodescanner.app`
- `bugs@qrcodebarcodescanner.app`
- `features@qrcodebarcodescanner.app`
- `hello@qrcodebarcodescanner.app`

### 3. **Contact Form**
In `contact.html`, update the form action:
```html
<form ... action="https://formspree.io/f/YOUR_FORM_ID">
```
Get a form ID from [Formspree.io](https://formspree.io) (free)

### 4. **Company Information**
Update in multiple pages:
- Company name
- Address
- Business hours
- Contact person
- Jurisdiction for legal documents

### 5. **Domain**
Replace `qrcodebarcodescanner.app` with your actual domain

## 📱 Mobile Optimization

The website is fully optimized for mobile with:
- Responsive grid layouts
- Touch-friendly buttons (min 44x44px)
- Mobile menu support
- Fast loading (< 3 seconds)
- Optimized images
- Minimal JavaScript

## 🔒 Security Considerations

- Use HTTPS (Let's Encrypt free)
- Implement Content Security Policy headers
- No sensitive data in forms (use server handler)
- Regular security audits
- Keep contact information updated

## 📊 SEO Optimization

Meta tags included for:
- Mobile responsiveness
- Social sharing
- Search engines
- Page titles and descriptions
- Structured data ready

Recommended:
- Add Google Analytics
- Submit sitemap to Google Search Console
- Configure robots.txt
- Add structured schema markup

## 🎯 Marketing Content

### Hero Section
- Compelling headline
- Clear value proposition
- Strong CTA buttons
- Visual mockup

### Features Grid
- 6 key selling points
- Icon-based visual hierarchy
- Hover animations

### Privacy Messaging
- Trust builder
- Security highlights
- Data ownership emphasis

### Social Proof
- Testimonials section
- Star ratings
- User quotes

## 📋 Compliance Checklist

- [x] Privacy Policy
  - [x] GDPR compliant
  - [x] CCPA compliant
  - [x] Cookie policy
  - [x] Data retention policy

- [x] Terms of Service
  - [x] App store compliance
  - [x] Limitation of liability
  - [x] User responsibilities
  - [x] Dispute resolution

- [x] Contact Information
  - [x] Multiple contact methods
  - [x] Response time SLAs
  - [x] Support channels
  - [x] Privacy contact

- [x] Accessibility
  - [x] Color contrast
  - [x] Mobile responsive
  - [x] Semantic HTML
  - [x] Keyboard navigation

## 🔄 Maintenance

### Regular Updates Needed
- Update app links (version releases)
- Update privacy policy (policy changes)
- Update contact information
- Monitor form submissions
- Keep HTTPS certificate valid

### Annual Review
- Privacy policy compliance
- GDPR/CCPA changes
- Terms of service updates
- Contact methods verification

## 📞 Support

For website issues:
- File bugs at: `bugs@qrcodebarcodescanner.app`
- Feature requests: `features@qrcodebarcodescanner.app`
- General inquiries: `hello@qrcodebarcodescanner.app`

## 📄 License

All website content is copyrighted. Update copyright year as needed.

---

**Created:** December 18, 2025  
**Last Updated:** December 18, 2025  
**Version:** 1.0
