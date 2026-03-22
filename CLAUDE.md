# CLAUDE.md — Granger Australia Migration Website

## Project Overview

This is a professional Bootstrap-based website for **Granger Australia**, an established (since 1999) Australian migration/visa agency and education consultancy based in Sydney. The site showcases visa solutions, education pathways, sponsorship options, and client success stories.

**Key Purpose**: Populate the Travisa template with Granger Australia's services, credentials, and content to create a modern, responsive website.

---

## ⚠️ IMPORTANT: Always Check planning.md FIRST

**Before making ANY changes to HTML files, ALWAYS**:
1. Read `planning.md` to understand current migration status
2. Check the section for the file you're editing
3. Review what's ✅ completed vs 🔧 needs work
4. Understand dependencies and blockers
5. Update `planning.md` when tasks are complete

`planning.md` is the **single source of truth** for:
- Current completion status (% by page)
- What content is needed for each section
- Critical blockers
- Phase priorities
- Quality checklist

**Without checking planning.md first, you risk**:
- Duplicating work already done
- Missing critical blockers
- Wasting time on low-priority items
- Conflicting with content needing decision

---

**Client Details**:
- **Name**: Granger Australia Pty Ltd
- **Founded**: 1999
- **Location**: East Tower, Suite 405, Level 4, 9-13 Bronte Rd, Bondi Junction NSW 2022
- **Phone**: +61 2 9389 8610
- **Email**: info@grangeraustralia.com.au
- **Key Contact**: Jonathan Granger (Director, Principal Migration Agent, MARA 0318801)
- **Credentials**: MARA Registered, MIA Member, 20+ years industry experience

---

## Project Structure

```
Travisa/
├── index.html              # Homepage - hero, key services, testimonials, CTA
├── about.html              # Agency story, team, credentials, expertise
├── service.html            # Detailed visa/migration services offered
├── testimonial.html        # Client success stories & case studies
├── office.html             # Office locations, team contacts, hours
├── contact.html            # Contact form, inquiry channels
│
├── css/
│   ├── bootstrap.min.css   # Bootstrap 5 framework
│   └── style.css           # Custom theme styling
│
├── js/
│   └── main.js             # Navigation, animations, form handling
│
├── lib/                    # Third-party libraries
│   ├── animate/            # Wow.js animations on scroll
│   ├── owlcarousel/        # Image carousels (testimonials)
│   ├── waypoints/          # Scroll triggers
│   └── easing/             # Animation easing
│
└── img/                    # All images (team, logos, banners, icons)
```

---

## Key Pages & Content Priorities

### **1. index.html** (Homepage)
- **Hero**: "Visa, Migration & Education Solutions"
- **Tagline**: "Expert assistance for temporary or permanent migration to Australia"
- **3 Main Pillars**:
  - Visas (with green accent)
  - Education (with orange accent)
  - Sponsorship (with purple accent)
- **Key Stats**: 20+ years experience, MARA registered, 1999-established
- **Client Testimonials**: 5 real case studies (Vishal, Renata, Heiko, Khadiza, Ki Ki)
- **CTA**: "Get Free Consultation" / "Arrange Appointment"
- **Trust Elements**: MARA badge, MIA badge, 20+ years history

### **2. service.html** (Services)
**Main Visa Categories**:
- **Skilled Migration**: 189 (Independent), 190 (Nominated), 482 (TSS)
- **Family & Partner Visas**: Spouse (820/801, 309/100), Child (802), Parent (804), Prospective Marriage (300)
- **Student Visas**: Subclass 500 (Full-time courses, English courses)
- **Business Visas**: 188 (provisional), 888 (permanent) - Business Innovation & Significant Investor streams
- **Regional Sponsorship**: Subclass 187, new regional provisional visas
- **Visitor Visas**: Subclass 600 (Tourist, Business Visitor, Family)

For each: requirements, process steps, timeline, eligibility, key docs needed

### **3. about.html** (About Agency)
- **Founded 1999** - over 20 years experience
- **Jonathan Granger** bio:
  - Director & Principal Migration Agent (MARA 0318801)
  - Former MIA National President (2017)
  - Former NSW/ACT State President (2015-2017)
  - National Vice President (2015-2017)
  - MIA Service Award (2012)
  - Media expert on immigration matters
  - NSW Justice of the Peace #132844
- **Team expertise**: Skilled, Family, Student, Business, Regional visas
- **Credentials**: MARA registered, MIA member, 20+ years industry
- **Professional services**: Compliance, appeals, employer sponsorship

### **4. testimonial.html** (Client Success Stories)
✓ Already have 5 real testimonials:
1. **Vishal** (India) → MBA/Accounting → Permanent Resident
2. **Renata** (Brazil) → Hairdressing → Student → Future PR
3. **Heiko** (Germany) → Business studies → Living on beach
4. **Khadiza** (Bangladesh) → Accountancy → Permanent Resident
5. **Ki Ki** (China) → Accountancy → PR & Australian Citizenship

### **5. office.html** (Contact Details & Location)
- **Address**: East Tower, Suite 405, Level 4, 9-13 Bronte Rd, Bondi Junction NSW 2022
- **Phone**: +61 2 9389 8610
- **Fax**: +61 2 8569 2383
- **Email**: info@grangeraustralia.com.au
- **Consultation Methods**: In-person (Bondi Junction), Skype, Telephone
- **Consultation Fees**:
  - Individual: $410 (+GST)
  - Corporate: $440 (+GST)
  - Fee credited to retainer if retained
- **Map**: Google Maps embedded

### **6. contact.html** (Contact Form & Inquiry)
- Inquiry form: Name, Email, Visa Type, Message
- Contact methods: Phone, Email, Online form
- **Response time**: Contact ASAP for consultation
- **Payment options**: Cash, EFTPOS, VISA, MasterCard (2.5% surcharge on cards)
- Privacy statement and MARA compliance notice

---

## Development Workflow

### **Before Editing**
1. Understand the current content → identify placeholder/generic text
2. Know the client's actual services, locations, credentials
3. Have MARA number, ABN, accreditations ready
4. Collect team bios, real client testimonials, office addresses

### **Editing Process**
1. Edit HTML files directly in VS Code
2. Keep Bootstrap classes intact (don't modify structure unnecessarily)
3. Replace generic text (e.g., "Example@gmail.com") with real contact info
4. Update images in `img/` folder
5. Refresh browser to preview changes (hot reload if using a dev server)

### **Testing Checklist**
- [ ] All links work (internal navigation, external links)
- [ ] Forms submit correctly (contact form, newsletter signup)
- [ ] Mobile responsive (test on mobile device or DevTools)
- [ ] Images load correctly
- [ ] Contact details are accurate
- [ ] No broken links to external resources (DIBP, government sites)
- [ ] Spelling/grammar checked (especially legal terms)

---

## Customization Priorities

### **Phase 1: Critical (Make it Granger Australia)**
- [ ] Replace placeholder text with Granger info (name, address, phone, email)
- [ ] Update all contact details across all pages
- [ ] Add MARA registration number (0318801) & links
- [ ] Add MIA member badge & links
- [ ] Replace hero image with Granger branding
- [ ] Update meta tags/SEO (Granger Australia, migration, visa, Sydney)
- [ ] Add Jonathan Granger bio to About page
- [ ] Add all 5 client testimonials to testimonial.html
- [ ] Set up consultation fee info ($410/$440)
- [ ] Add office address & map (Bondi Junction)

### **Phase 2: Important (Service Details)**
- [ ] Populate service.html with all visa categories (Skilled, Family, Student, Business, Regional, Visitor)
- [ ] Add requirements, timelines, eligibility for each visa type
- [ ] Link to official DHA pages for visa info
- [ ] Create individual pages or sections for major visa types
- [ ] Add Skilled Occupation List (SOL) reference & links
- [ ] Document 482 TSS vs 187 Regional pathways
- [ ] Add education section (English, Universities, Vocational, Professional Year)

### **Phase 3: Enhancement (Trust & Engagement)**
- [ ] Add professional photos (if available) of Jonathan Granger
- [ ] Optimize images (compress, proper dimensions)
- [ ] Add MARA Code of Conduct & Privacy Policy
- [ ] Add disclaimer & legal notices
- [ ] Implement working contact form (Formspree, Netlify Forms, or backend)
- [ ] Add schema markup for local business (Name, Address, Phone)
- [ ] Newsletter signup (visa updates & seminars)
- [ ] Blog/Resources section (visa news, recent changes, tips)

---

## Content Guidelines for Granger Australia

### **Compliance & Legal Requirements**
- **MARA Registration**: Always display "MARA 0318801" with link to register
- **MIA Membership**: Display MIA badge, link to Jonathan Granger's MIA profile
- **Disclaimers**: Add legal disclaimer noting Granger Australia provides immigration advice (not legal counsel)
- **DHA/DIBP Links**: Always link to official Department of Home Affairs for current visa info
- **Code of Conduct**: Display MARA Code of Conduct prominently
- **Privacy Statement**: Outline data handling per GDPR/Australian Privacy Principles

### **Tone & Voice**
- **Expert but personable**: 20+ years of expertise, but accessible to first-timers
- **Empathetic**: "Immigration can be stressful; we handle the complexity for you"
- **Honest**: Realistic timelines, clear requirements, no false promises
- **Consultative**: "Let us assess your eligibility and find the best visa pathway"
- **Trust-focused**: Emphasize MARA registration, MIA membership, industry recognition

### **Key Brand Elements**
- **Jonathan Granger**: Emphasize his 20+ years experience, MIA presidency, media expertise
- **Established 1999**: 25 years of consistent service
- **MARA/MIA badges**: Always visible in header/footer
- **"Expert Advice" positioning**: vs. generic template services
- **Consultation-first approach**: Emphasis on personalized assessment ($410 initial fee)

### **Service Description Template**
```
## [Visa Name] (Subclass XXX)

**Who is eligible?**
- Specific occupation/skill requirements
- English language level
- Age restrictions (if applicable)
- Qualifications needed

**How it works:**
- Step-by-step application process
- Key documents needed
- Assessment level

**Timeline:**
- Realistic processing timeframe
- Visa validity period

**Next steps:**
- "Contact Granger Australia for a free eligibility assessment"
- "Call +61 2 9389 8610 or email info@grangeraustralia.com.au"
```

---

## Key Files to Update

### **Meta Tags (All Pages)**
```html
<title>Travisa - Australian Migration Specialists</title>
<meta name="description" content="Expert visa & immigration services for Australia">
<meta name="keywords" content="Australia visa, migration, skilled worker, family visa">
```

### **Header & Footer**
- Logo path: Update to Travisa logo
- Navigation links: Ensure all point to real pages
- Contact info: Phone, email in header
- Footer: Copyright, privacy policy, terms, MARA details

### **Color Scheme**
- Primary color (blue): Professional, trustworthy
- Secondary color (orange/gold): Energy, action
- Adjust in `css/style.css` via CSS variables or direct class overrides

---

## Common Customizations

### **Add New Service Section**
1. Open `service.html`
2. Copy an existing service card block
3. Update heading, description, icon
4. Add to HTML structure
5. Test responsive layout

### **Update Contact Form Submission**
- Current form: Check `js/main.js` for form handler
- To make functional: Set up backend (PHP, Node.js) or use service (Formspree, Netlify Forms)
- Include privacy notice: "We respect your data and never share it"

### **Add Google Maps**
- In `office.html`, embed iframe:
```html
<iframe src="https://www.google.com/maps/embed?pb=..." width="100%" height="400"></iframe>
```

### **Update Testimonial Carousel**
- Edit HTML carousel structure in `testimonial.html`
- Images in `img/testimonial/`
- Author name, role, quote
- Use `owl-carousel` library (already included)

---

## Performance & Best Practices

### **Image Optimization**
- Use WebP format where possible (fallback to JPG/PNG)
- Compress images before upload (TinyPNG, ImageOptim)
- Lazy load images below the fold
- Use `<img loading="lazy">` attribute

### **SEO Best Practices**
- Each page needs unique `<title>` and `<meta name="description">`
- Use heading hierarchy (H1 → H2 → H3), one H1 per page
- Add internal links between related pages
- Alt text on all images
- Schema markup for local business (address, phone, hours)

### **Accessibility**
- Ensure color contrast meets WCAG AA standards
- Use semantic HTML (headings, lists, etc.)
- Add alt text to all images
- Test keyboard navigation

---

## Deployment

### **Local Development**
```bash
# Start a simple local server
python3 -m http.server 8000
# Visit: http://localhost:8000
```

### **Live Deployment**
Options:
1. **Shared Hosting** (GoDaddy, Bluehost, HostGator): Upload via FTP/SFTP
2. **Netlify**: Drag & drop folder, auto-deploys on git push
3. **GitHub Pages**: Free, requires git knowledge
4. **AWS S3 + CloudFront**: Scalable, professional

**Recommended for Travisa**: Netlify (simple, free, auto-HTTPS, fast)

---

## Workflow Summary

1. **Understand Requirements**: Gather all agency info (MARA #, services, team, locations)
2. **Plan Content**: Map out what goes on each page
3. **Edit HTML**: Replace placeholders with real content
4. **Customize Styling**: Adjust colors, fonts if needed (in `css/style.css`)
5. **Test Thoroughly**: Links, forms, mobile, accessibility
6. **Optimize**: Images, SEO, performance
7. **Deploy**: Choose hosting and launch

---

## Quick Reference: Granger Australia Details

**Contact & Location**:
- **Phone**: +61 2 9389 8610
- **Fax**: +61 2 8569 2383
- **Email**: info@grangeraustralia.com.au
- **Address**: East Tower, Suite 405, Level 4, 9-13 Bronte Rd, Bondi Junction NSW 2022
- **MARA Registration**: 0318801
- **MIA Member**: Jonathan Granger (ID 2363)

**Key Credentials**:
- Jonathan Granger: Former MIA National President (2017), NSW/ACT State President (2015-2017)
- 20+ years industry experience
- Appeared before Senate Legal & Constitutional Affairs Committee
- Media expert (interviewed by ABC, SBS, The Australian, SMH)
- NSW Justice of the Peace #132844

**Important External Links**:
- **MARA Register**: https://mara.gov.au/ (search: 0318801 or Jonathan Granger)
- **Migration Institute of Australia**: https://mia.org.au/
- **Department of Home Affairs**: https://immi.homeaffairs.gov.au/
- **Skilled Occupation List**: https://immi.homeaffairs.gov.au/visas/working-in-australia/skill-occupation-list
- **SkillSelect**: https://immi.homeaffairs.gov.au/visas/working-in-australia/visas-for-skilled-workers/skilled-independent
- **Australian Business Register**: https://abr.business.gov.au/

**Client Testimonials** (Already have permission):
1. Vishal (India) - MBA & Accountancy → Permanent Resident
2. Renata (Brazil) - Hairdressing/Salon Management → Student
3. Heiko (Germany) - Business studies → Living in Australia
4. Khadiza (Bangladesh) - Accountancy → Permanent Resident
5. Ki Ki (China) - Accountancy → PR & Australian Citizenship

---

## Notes for Implementation

- **MARA compliance**: Always display 0318801 & link to MARA register
- **Jonathan Granger's credentials**: Highlight his MIA leadership & media appearances
- **Visa codes**: Use official subclass numbers (e.g., 189, 190, 482, 500, 820, 801)
- **DHA references**: Link to official pages for timelines & requirements
- **Testimonials**: All 5 are real — use exact names, countries, and visa types
- **Consultation fees**: Individual $410+GST, Corporate $440+GST (can be credited to retainer)
- **Response time**: "Contact us to arrange a consultation" — Jonathan is responsive
- **Tone**: Professional & expert, but warm & consultative
- **Privacy**: Include privacy statement for client data handling
