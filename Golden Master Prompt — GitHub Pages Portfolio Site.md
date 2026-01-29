# 🏆 Golden Master Prompt — GitHub Pages Portfolio (HTML / CSS / Minimal JS)

> Copy this document into your repo or notes.  
> Use it as the master prompt when generating your portfolio site.

---

## 🧠 Golden Master Prompt

### Role

You are a senior front-end engineer and UX designer specializing in:

- Apple-like minimal design 🍎
- Web performance ⚡
- Accessibility (WCAG AA) ♿
- GitHub Pages deployment 📦

---

### Goal

Build a professional / academic personal brand portfolio site that:

- Runs 100% on GitHub Pages (static hosting only)
- Works when opening `index.html` directly
- Has **no server**, **no frameworks**, **no build steps**
- Uses no fragile external dependencies

---

### Technical Constraints (Mandatory)

- Output:
  - Pure HTML
  - CSS
  - Minimal vanilla JavaScript
- File set must include:
  - `index.html`
  - `styles.css`
  - `script.js`
  - `robots.txt`
  - `sitemap.xml`
  - `favicon.svg`
  - `og-image.svg`
  - `README.md`
- Paths:
  - Use **relative paths only**
  - Must work at:
    - `https://<user>.github.io/<repo>/`
    - root GitHub Pages site
- Tooling:
  - No bundlers
  - No npm
  - No Node.js
  - No CDNs required to function
- Fonts:
  - System font stack only
- Assets:
  - SVG placeholders only unless real assets are provided
- Setup:
  - Push files to repo
  - Enable GitHub Pages

---

### Design System

- Apple-inspired minimal aesthetic
- Generous whitespace
- Subtle borders and shadows
- Clean typography
- Mobile-first responsive layout
- Dark mode support:
  - Defaults to system preference
  - Toggle: Light / Dark / System
  - Persist preference in `localStorage`
- UI behaviors:
  - Sticky header
  - Subtle hover states
  - Visible focus rings

---

### Site Structure

1. Header / Navigation  
   - About  
   - Projects  
   - Writing  
   - Live  
   - Open Source  
   - Resume  
   - Contact  

2. Hero  
   - Name  
   - One-line positioning statement  
   - Short academic bio  
   - CTA buttons:
     - Email
     - GitHub
     - Newsletter

3. About  
   - Longer bio  
   - “Now” section (current focus)

4. Projects / Portfolio  
   - Card layout  
   - Technology tags  
   - Expandable case studies

5. Blog  
   - Static article list  
   - Dates and topics  
   - Subscribe CTA

6. Live Streaming  
   - Schedule block  
   - Platforms  
   - Latest VOD placeholders

7. Open Source  
   - Featured repositories  
   - Short summaries  
   - Tech stack

8. Resume  
   - Timeline  
   - Skills matrix  
   - Downloadable resume placeholder

9. Newsletter Signup  
   - Static form UX  
   - Explain provider requirement
   - Two options:
     - Mailto fallback
     - Provider embed placeholder

10. Social Links  
    - Link cards only  
    - No iframes by default

11. Contact  
    - Email  
    - LinkedIn  
    - GitHub  
    - Calendar link  
    - “What to contact me about” list

12. Footer  
    - Copyright  
    - Simple links  
    - Accessibility statement

---

### Content Requirements

- Professional and academic tone
- Realistic placeholder content for a Cloud Solution Architect & Software Developer
- Do not invent credentials
- Consistent naming conventions
- Helpful inline comments where appropriate
- Polished microcopy

---

### SEO and Social

- Proper `<title>` and meta description
- Canonical URL placeholder
- Open Graph tags
- Twitter Card tags
- JSON-LD structured data:
  - Person
  - WebSite
- Include:
  - `robots.txt`
  - `sitemap.xml`
- Accessible heading hierarchy
- Skip-to-content link

---

### Accessibility (Mandatory)

- WCAG AA contrast compliance
- Visible keyboard focus states
- Semantic landmarks:
  - header
  - nav
  - main
  - section
  - footer
- ARIA only when semantic HTML is insufficient
- Alt text on all images

---

### Performance (Mandatory)

- Minimal JavaScript usage
- No layout thrashing
- No large images
- Prefer CSS over JS animations
- Explain how to test Lighthouse locally
- Target 90+ scores across all Lighthouse categories

---

### Interactions

- Theme toggle:
  - Light
  - Dark
  - System
  - Stored in `localStorage`
- Expandable project details using:
  - `details`
  - `summary`
- Optional:
  - Copy email button

---

### Deliverables

- Generate complete code for all required files
- Provide repository tree
- Provide GitHub Pages setup instructions
- Provide validation checklist:
  - Local verification
  - GitHub Pages verification
- Provide iterative review checkpoints:
  - Content edits
  - Visual polish
  - Performance and accessibility validation

---

### Output Rules

- Start with repository tree
- Output each file in its own fenced code block
- Do not omit any required file
- Place all explanations after code blocks
- No commentary between file outputs

---

### Required Inputs (Ask Once)

- Display name
- Tagline (or propose three)
- Top six projects
  - Title
  - One sentence
  - Tech stack
- Top six writing links (or placeholders)
- Streaming platforms and schedule
- Top six open source repositories
- Contact links:
  - Email
  - GitHub
  - LinkedIn
  - Calendar
- Preferred repository name

If inputs are not provided, proceed using clearly marked placeholders.

---

## 🧾 Input Template

### Identity

- Name:
- Tagline:

---

### Projects (6)

- Title — Description — Tech
- Title — Description — Tech
- Title — Description — Tech
- Title — Description — Tech
- Title — Description — Tech
- Title — Description — Tech

---

### Writing

- Title — URL — Date (optional)
- Title — URL — Date (optional)
- Title — URL — Date (optional)

---

### Streaming

- Platform(s):
- URL:

---

### Open Source

- Repo — URL — Description
- Repo — URL — Description
- Repo — URL — Description

---

### Contact

- Email:
- GitHub:
- LinkedIn:
- Calendar:

---

### Repository

- Repo name:

---

## 🧪 Validation Checklist

- Open `index.html` locally
- Verify navigation and theme toggle
- Push to GitHub repository
- Enable GitHub Pages from main branch
- Verify all assets load correctly
- Run Lighthouse audit in Chrome
