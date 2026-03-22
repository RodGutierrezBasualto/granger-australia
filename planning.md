# PLANNING.md — Granger Australia Website Migration & Update Plan

**Status**: Active Migration in Progress
**Last Updated**: 2026-03-15
**Project**: Granger Australia (Travisa Template Migration)

---

## 📋 QUICK START: Read This First

Before making changes to ANY file, **always check this document** to understand:
1. What's been completed ✅
2. What needs work 🔧
3. What content/structure is needed
4. Priority phases and dependencies

---

## 🗺️ COMPLETE SITE STRUCTURE & MIGRATION STATUS

### **HOMEPAGE (index.html) — 85% COMPLETE**

**Status**: Partially migrated, core content updated

**✅ COMPLETED:**
- [x] Meta tags (title, keywords, description)
- [x] Topbar contact info (email: info@grangeraustralia.com.au, phone: +61 2 9389 8610)
- [x] Logo updated to logogranger.png
- [x] Navbar branding: "Granger Australia"
- [x] Hero carousel slide 1: Title + tagline updated
- [x] Hero carousel slide 2: About services updated
- [x] About section: Company info & founding date
- [x] Testimonial carousel: 4 detailed real client testimonials (Renata, Heiko, Khadiza, Ki Ki) with photos & quotes
- [x] Footer contact info & social links updated

**🔧 NEEDS WORK:**
- [x] **Services Section (8 cards)**: ✅ COMPLETE with real Australian visa descriptions
  - Card 1: Skilled Workers (189, 190, 491)
  - Card 2: 457 Employer Sponsorship (482)
  - Card 3: Regional Sponsorship (187, 191)
  - Card 4: Business Visas (188, 888) ✅ Updated per DHA - closed codes removed
  - Card 5: Family Visas (309, 100, 802, 804)
  - Card 6: Student Visas (500)
  - Card 7: Partner Visas (820, 801, 300)
  - Card 8: Visitor Visas (600)
- [ ] **Office Cards (4 locations)**: Replace placeholder emails (travisa@example.com) with real Bondi Junction address
- [ ] **Testimonial section heading**: Update from "OUR CLIENTS REVIEWS" (already done) ✓
- [ ] **"Buy Pro Version" button**: Remove or replace with "Get Free Consultation" CTA (appears in navbar)

**Content Needed**:
- 2-3 sentence descriptions for each visa category (use CLAUDE.md service descriptions as template)
- Ensure office section shows SINGLE location (Bondi Junction) not multiple worldwide offices

---

### **ABOUT PAGE (about.html) — 40% COMPLETE**

**Status**: Branding updated, core content missing

**✅ COMPLETED:**
- [x] Meta tags (title, keywords, description)
- [x] Logo updated to logogranger.png
- [x] Navbar branding: "Granger Australia"
- [x] Topbar contact info updated

**🔧 NEEDS WORK:**
- [ ] **Main about paragraph (line 128)**: Currently Lorem ipsum
  - **Replace with**: "Granger Australia is a MARA-registered migration consultancy founded in 1999 by Jonathan Granger. With 25+ years of industry expertise, we provide expert visa assistance for temporary and permanent migration to Australia. Our team specializes in skilled migration, family visas, student education pathways, business sponsorship, and regional opportunities."

- [ ] **Jonathan Granger Bio Section**: MISSING entirely
  - **Add section with**:
    - Professional photo (if available)
    - Full bio: Director & Principal Migration Agent (MARA 0318801)
    - Credentials: Former MIA National President (2017), NSW/ACT State President (2015-2017)
    - Media expertise: Appeared on ABC, SBS, The Australian, SMH
    - NSW Justice of the Peace #132844

- [ ] **Team Expertise Section**: Update or clarify team specializations

- [ ] **Office Locations (4 items on lines 194-234)**:
  - **Current state**: Generic (Los Angeles, Toronto, London, Mumbai)
  - **Replace with**: SINGLE Bondi Junction office details:
    - East Tower, Suite 405, Level 4, 9-13 Bronte Rd
    - Bondi Junction NSW 2022
    - Phone: +61 2 9389 8610
    - Fax: +61 2 8569 2383
    - Email: info@grangeraustralia.com.au
    - Hours: By appointment (in-person, Skype, telephone)

- [ ] **Footer Contact (lines 252-255)**: Update from generic (123 Street, New York) to Bondi Junction

**Content Needed**:
- Jonathan Granger professional biography
- Team member profiles (if available)
- Professional photo of Jonathan Granger
- Clarification on team size/structure

---

### **SERVICES PAGE (service.html) — 20% COMPLETE ⚠️ CRITICAL**

**Status**: Not migrated, placeholder content throughout

**✅ COMPLETED:**
- [ ] (NONE YET)

**🔧 NEEDS WORK:**
- [ ] **Meta Tags** (line 6-9):
  - Title: Change from "Travisa - Visa & Immigration Website Template"
  - **To**: "Granger Australia - Visa & Migration Services"
  - Keywords: "visa services, skilled migration, family visa, student visa, business visa, Australia"
  - Description: "Expert visa and migration services in Australia. Skilled migration (189, 190), family sponsorship, student visas, business visas, and regional opportunities."

- [ ] **Topbar Contact** (line 48-49): Replace Example@gmail.com & +01234567890
  - **With**: info@grangeraustralia.com.au & +61 2 9389 8610

- [ ] **Logo**: Already updated to logogranger.png ✓

- [ ] **Navbar Branding**: Already updated to "Granger Australia" ✓

- [ ] **Section Intro** (line 123): Currently Lorem ipsum
  - **Replace with**: "Granger Australia offers comprehensive visa and migration services for all Australian visa categories. Whether you're seeking skilled migration, family reunification, education pathways, or business sponsorship, our MARA-registered agents provide expert guidance and personalized assessment."

- [ ] **Service Cards (6 items, lines 142-262)**:
  All currently Lorem ipsum. Replace with:

  **Card 1 - Skilled Migration**:
  - Subclass 189 (Independent), 190 (Nominated), 482 (Temporary Skill Shortage)
  - For professionals in occupation-shortage roles
  - Personalized eligibility assessment available

  **Card 2 - Family & Partner Visas**:
  - Spouse visa (820/801), Partner visas (309/100)
  - Child, Parent, Prospective Marriage visas
  - Specialized in family reunification pathways

  **Card 3 - Student Visas**:
  - Subclass 500 (Full-time study, English courses)
  - Assistance with institution selection and applications
  - Pathway to permanent residence options explained

  **Card 4 - Business Visas**:
  - Business Innovation visas (188/888)
  - Business Talent (132), Investor visas (891/893)
  - Tailored to your business requirements

  **Card 5 - Regional Sponsorship**:
  - Subclass 187 (Regional Sponsored Migration)
  - New provisional regional visas
  - Regional pathways to permanent residence

  **Card 6 - Visitor Visas**:
  - Subclass 600 (Tourist, Business Visitor, Family)
  - Quick turnaround processing
  - Multiple entry options available

- [ ] **Testimonial Carousel** (lines 284-348):
  - Currently has Lorem ipsum & "Person Name" placeholders
  - **Action**: Either replace with 3 of the 5 real testimonials OR remove section (testimonials on testimonial.html are primary)

- [ ] **Newsletter Section** (line 409): Lorem ipsum
  - **Update with**: "Stay informed about visa requirements, processing timeframes, and migration opportunities. Subscribe to our monthly updates."

**Content Needed**:
- Detailed descriptions for 6 visa categories (2-3 sentences each)
- Links to official DHA pages for each visa type
- Processing timelines for each category
- Key documents checklist for each visa type

---

### **TESTIMONIALS PAGE (testimonial.html) — 95% COMPLETE ✓**

**Status**: Excellent, nearly complete

**✅ COMPLETED:**
- [x] Meta tags (title, keywords, description)
- [x] Logo updated to logogranger.png
- [x] All 5 client testimonials with real quotes:
  - Vishal (India) → MBA/Accounting → Permanent Resident
  - Renata (Brazil) → Hairdressing → Student Visa
  - Heiko (Germany) → Business Studies → Student Visa
  - Khadiza (Bangladesh) → Accountancy → Permanent Resident
  - Ki Ki (China) → Accountancy → PR & Australian Citizen
- [x] Footer contact info updated

**🔧 NEEDS WORK:**
- [ ] **Footer Copyright** (line 309): Change "Your Site Name" to "Granger Australia Pty Ltd"
- [ ] **Social Links** (topbar): Add missing URLs if available

---

### **CONTACT PAGE (contact.html) — 70% COMPLETE**

**Status**: Mostly updated, form content needs work

**✅ COMPLETED:**
- [x] Meta tags (title, keywords, description)
- [x] Logo updated to logogranger.png
- [x] Navbar branding updated
- [x] Topbar contact info updated

**🔧 NEEDS WORK:**
- [ ] **Contact Form Intro** (line 124): Currently Lorem ipsum
  - **Replace with**: "Get in touch with Granger Australia for a confidential consultation. Our MARA-registered agents will assess your eligibility and discuss your visa pathway options."

- [ ] **Form Email Field**: Verify it properly captures "visa type" as mentioned in CLAUDE.md
  - Should include dropdown: Individual, Corporate, Inquiry

- [ ] **Contact Methods Section**: Ensure all contact details are visible:
  - Email: info@grangeraustralia.com.au
  - Phone: +61 2 9389 8610
  - Address: East Tower, Suite 405, Level 4, 9-13 Bronte Rd, Bondi Junction NSW 2022

- [ ] **Consultation Fees Display**: Add section showing:
  - Individual Consultation: $410 + GST
  - Corporate Consultation: $440 + GST
  - Fee credited to retainer if retained

- [ ] **Working Form Backend**: Form currently non-functional
  - **Options**:
    1. Formspree (easiest - no backend needed)
    2. Netlify Forms (if hosting on Netlify)
    3. Custom backend (Node.js, PHP)

- [ ] **Privacy Statement**: Add MARA compliance notice about data handling

---

### **OFFICE/LOCATION PAGE (office.html) — 20% COMPLETE ⚠️ CRITICAL**

**Status**: Not migrated, critical issues

**✅ COMPLETED:**
- [ ] (NONE YET)

**🔧 NEEDS WORK:**
- [ ] **Meta Tags** (line 6-9):
  - Title: Change from "Travisa - Visa & Immigration Website Template"
  - **To**: "Contact Granger Australia - Office Location & Hours"
  - Keywords: "Granger Australia office, Bondi Junction, Sydney visa agent"
  - Description: "Visit Granger Australia office in Bondi Junction, Sydney. MARA-registered migration consultants available for in-person, Skype, and phone consultations."

- [ ] **Topbar Contact** (line 48-49): Replace placeholder
  - **With**: info@grangeraustralia.com.au & +61 2 9389 8610

- [ ] **Logo**: Already updated to logogranger.png ✓

- [ ] **Section Intro** (line 124): Currently Lorem ipsum
  - **Replace with**: "Granger Australia is located in Bondi Junction, Sydney. We offer in-person consultations, telephone consultations, and online appointments via Skype for clients worldwide."

- [ ] **Office Locations (4 items, lines 135-174)**:
  - **Current**: Generic international offices (Australia, Canada, UK, India with placeholder emails)
  - **Replace with**: SINGLE location with full details:
    - **Address**: East Tower, Suite 405, Level 4, 9-13 Bronte Rd, Bondi Junction NSW 2022
    - **Phone**: +61 2 9389 8610
    - **Fax**: +61 2 8569 2383
    - **Email**: info@grangeraustralia.com.au
    - **Hours**: By appointment
    - **Services**: In-person, Telephone, Skype/Online

- [ ] **Google Maps Embed**: Add embedded map showing Bondi Junction location
  - Find address: 9-13 Bronte Rd, Bondi Junction NSW 2022
  - Generate embed code from Google Maps
  - Insert in office section

- [ ] **Newsletter Section** (line 236): Update Lorem ipsum

---

## 📊 MIGRATION PHASES & PRIORITY

### **PHASE 1: CRITICAL (Make it Granger) — PRIORITY NOW**
*Most of these are COMPLETE ✓*

- [x] Replace placeholder text with Granger info (name, address, phone, email)
- [x] Update all contact details across pages
- [x] Add MARA registration number (0318801)
- [x] Add MIA member badge references
- [x] Replace hero image branding (logo updated)
- [x] Update meta tags/SEO
- [x] Add all 5 client testimonials
- [ ] **STILL NEEDED**:
  - service.html & office.html meta tags
  - service.html & office.html contact header
  - Remove/replace "Buy Pro Version" button

### **PHASE 2: IMPORTANT (Service Details) — PRIORITY NEXT**

- [ ] service.html: Populate 6 visa category descriptions
- [ ] service.html & office.html: Update all placeholder email/phone references
- [ ] Add requirements, timelines, eligibility for each visa type
- [ ] Link to official DHA pages for visa info
- [ ] about.html: Add Jonathan Granger full bio section
- [ ] about.html: Replace Lorem ipsum main content
- [ ] contact.html: Add consultation fees display
- [ ] contact.html: Implement working contact form backend
- [ ] office.html: Replace 4 generic offices with 1 Bondi Junction location
- [ ] office.html: Add Google Maps embed

### **PHASE 3: ENHANCEMENT (Trust & Engagement) — PRIORITY AFTER PHASE 2**

- [ ] Add professional photos (Jonathan Granger if available)
- [ ] Optimize all images (compress, proper dimensions)
- [ ] Add MARA Code of Conduct page or section
- [ ] Add Privacy Policy page
- [ ] Add Legal Disclaimer page
- [ ] Add schema markup for local business (JSON-LD)
- [ ] Newsletter signup functionality
- [ ] Blog/Resources section (visa news, updates, tips)
- [ ] FAQ section for common visa questions
- [ ] Testimonial video options (if clients available)

---

## 🔴 CRITICAL BLOCKERS (MUST FIX FIRST)

1. **service.html & office.html**: Meta tags completely empty
   - **Impact**: Poor SEO, site looks unfinished
   - **Fix time**: 10 minutes
   - **Ownership**: Backend/Content

2. **service.html & office.html**: Placeholder contact info (Example@gmail.com, +01234567890)
   - **Impact**: Users cannot contact Granger via these pages
   - **Fix time**: 5 minutes
   - **Ownership**: Backend

3. **Service descriptions all Lorem ipsum** (12 service cards across index + service pages)
   - **Impact**: Visitors don't understand what Granger offers
   - **Fix time**: 30 minutes (if content provided)
   - **Ownership**: Content

4. **"Buy Pro Version" button on all pages**
   - **Impact**: Unprofessional, links to external site
   - **Fix time**: 5 minutes
   - **Ownership**: Backend

5. **about.html main content is Lorem ipsum**
   - **Impact**: No information about the company
   - **Fix time**: 15 minutes (if content provided)
   - **Ownership**: Content

---

## 📝 CONTENT CHECKLIST

**Content Provided** (in CLAUDE.md):
- ✓ Client testimonials (5 real quotes)
- ✓ Company contact details
- ✓ Jonathan Granger credentials
- ✓ Visa categories & subclass numbers
- ✓ MARA & MIA registration info
- ✓ Consultation fee structure

**Content Still Needed**:
- [ ] Service descriptions for 6 visa categories (2-3 sentences each)
- [ ] Jonathan Granger professional photo
- [ ] Team member photos/bios
- [ ] Processing timelines for each visa type
- [ ] Key documents checklists by visa type
- [ ] Links to official DHA pages
- [ ] Google Maps location embed
- [ ] Company mission/vision statement
- [ ] FAQ content
- [ ] Blog post ideas/samples

---

## 🛠️ TECHNICAL TASKS

**Logo**:
- ✓ Created/Uploaded: logogranger.png
- ✓ Updated all 6 HTML files to reference logogranger.png

**Contact Form Backend**:
- [ ] Choose backend solution (Formspree, Netlify Forms, or custom)
- [ ] Integrate with form on contact.html
- [ ] Test form submission
- [ ] Add email notification setup
- [ ] Add form success/error messages

**SEO/Meta Tags**:
- ✓ index.html: Complete
- ✓ about.html: Complete (needs content)
- ✓ testimonial.html: Complete
- ✓ contact.html: Complete
- [ ] service.html: NEEDS UPDATE
- [ ] office.html: NEEDS UPDATE

**Images**:
- [ ] Verify logogranger.png displays correctly
- [ ] Optimize carousel images (compress, correct dimensions)
- [ ] Add professional photo of Jonathan Granger
- [ ] Ensure all images have alt text
- [ ] Verify office location image/map embed

**Links**:
- [ ] All internal navigation links working
- [ ] Social media links verified and updated
- [ ] External links to DHA, MARA, MIA pages added
- [ ] "Buy Pro Version" button removed or hidden

---

## 📅 RECOMMENDED WORKFLOW

**TODAY (URGENT)**:
1. Fix service.html & office.html meta tags (5 min)
2. Update service.html & office.html topbar contact (5 min)
3. Remove "Buy Pro Version" buttons (5 min)
4. Test all pages load correctly (5 min)

**THIS WEEK (HIGH PRIORITY)**:
1. Create/verify service descriptions for 6 visa categories (30 min)
2. Update about.html with real company info & Jonathan bio (30 min)
3. Update service.html with visa descriptions & links (45 min)
4. Update office.html with single Bondi Junction location (20 min)
5. Add Google Maps embed to office.html (15 min)

**NEXT WEEK (MEDIUM PRIORITY)**:
1. Replace all Lorem ipsum text across remaining sections (45 min)
2. Add consultation fee information to contact.html (10 min)
3. Implement working contact form backend (30-60 min depending on choice)
4. Add Jonathan Granger professional photo to about.html (10 min)
5. Add schema markup for local business (15 min)

**LATER (NICE-TO-HAVE)**:
1. Create FAQ section
2. Add blog/resources area
3. Add testimonial videos
4. Create downloadable visa guides
5. Add newsletter signup automation

---

## ✅ QUALITY CHECKLIST (Before Launch)

- [ ] All pages have correct Granger Australia branding
- [ ] All contact info is accurate across all pages
- [ ] No Lorem ipsum placeholder text remains
- [ ] No "Example@" or "+0123" placeholder contacts visible
- [ ] Meta tags complete & accurate on all pages
- [ ] All internal links work (test each nav item)
- [ ] External links to DHA, MARA, MIA pages are correct
- [ ] Images load correctly (no broken img src paths)
- [ ] Logo displays properly on all pages
- [ ] Mobile responsive (test on phone/tablet)
- [ ] Contact form works and submissions received
- [ ] Google Maps embed displays location correctly
- [ ] All sections have real, professional content
- [ ] No "Buy Pro Version" or external CTA buttons
- [ ] Footer information is current
- [ ] Social media links are correct and live
- [ ] Accessibility: alt text on all images, keyboard navigation works
- [ ] Performance: pages load quickly (optimize large images)
- [ ] Security: no hardcoded sensitive data, form uses HTTPS

---

## 📞 CONTACT INFO (Always Current)

**Email**: info@grangeraustralia.com.au
**Phone**: +61 2 9389 8610
**Fax**: +61 2 8569 2383
**Address**: East Tower, Suite 405, Level 4, 9-13 Bronte Rd, Bondi Junction NSW 2022
**MARA Registration**: 0318801
**MIA Member**: Jonathan Granger (ID 2363)

---

## 📌 LAST NOTE

This document is your **source of truth** for the migration status. Before editing any file, check the relevant section here to understand:
- What's already done ✓
- What needs work 🔧
- What content you need

**Update this document as you complete tasks** — it keeps the team synchronized and prevents duplicate work.
