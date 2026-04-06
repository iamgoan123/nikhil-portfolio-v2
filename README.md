# Nikhil Deshpande — Portfolio V2

> Architecting the Source of Truth for Global Brands | GA4 | GTM | Data Strategy

🔗 **Live Site:** [[nikhil-portfolio-rouge-phi.vercel.app](https://nikhil-portfolio-v2-qmbonh9y2.vercel.app/)]([https://nikhil-portfolio-rouge-phi.vercel.app](https://nikhil-portfolio-v2-qmbonh9y2.vercel.app/))

---

## 🎯 About

A premium personal portfolio website for **Nikhil Deshpande**, Digital Marketing Analyst at Pattern®. Built as a single `index.html` file with advanced animations, deployed for free on Vercel.

This site was built entirely through **vibe coding** — using AI (Claude) as a force multiplier to design, develop, and ship a production-ready portfolio without traditional development experience.

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Structure and semantic markup |
| **CSS3** | Styling, animations, responsive design |
| **JavaScript (Vanilla)** | Interactivity and dynamic behavior |
| **GSAP 3.12.5** | Advanced scroll-triggered animations |
| **GSAP ScrollTrigger** | Scroll-based animation triggers |
| **Google Fonts (Inter, Fira Code)** | Typography |
| **Vercel** | Hosting and deployment |
| **GitHub** | Version control |

---

## ✨ Features & Animations

### Preloader
- SVG circle stroke-draw animation
- Text blur-in reveal effect
- Smooth fade-out transition to hero section

### Hero Section
- Parallax background text ("NIKHIL") moves on scroll
- Blur-in headline animation
- Fade-up staggered content reveal
- Floating blob with organic morphing border-radius
- Scroll indicator with floating animation

### Scroll Animations (GSAP ScrollTrigger)
- **Blur-in reveals** — Section headings start blurred, sharpen on scroll
- **Fade-up reveals** — Content slides up with opacity transition
- **Batch processing** — Multiple elements animate with stagger timing
- **Parallax layers** — Background elements move at different scroll speeds

### Blob Animation
- Fixed position morphing shape on the right side
- Continuous border-radius animation using randomized values
- Slow rotation (360° over 30 seconds)
- Parallax scroll offset

### Navigation
- Mix-blend-mode difference (inverts over content)
- Scroll-aware — adds background blur after 50px scroll
- Smooth anchor link scrolling
- Active section highlighting

### Interactive Elements
- Hover effects on all cards (experience, projects, testimonials, recognition)
- Project cards with animated top-line reveal on hover
- Skill pills with lift and scale on hover
- Contact links with translateX shift on hover

### Design System
- **Color Palette:** Deep black (#0a0a0f) background, warm white (#f0e7e9) text, indigo accents
- **Typography:** Inter (weights 200-900) for body, Fira Code for metadata
- **Layout:** Section numbering system ((01), (02), (03)...)
- **Borders:** Zero border-radius (sharp, editorial aesthetic)
- **Dividers:** Thin horizontal lines between sections

---

## 📄 Sections

1. **Hero** — Name, tagline, CTA buttons, scroll indicator
2. **About** — Bio, Pattern® role, motorcycle mention, 3 stat cards (4+ years, 3 companies, 50+ brands)
3. **Experience** — 3 roles with colored left borders (Pattern®, Sumeru, Mantra Properties)
4. **Projects** — Vibe Coder intro box + 6 project cards:
   - Analytics Auditor (Groq AI, Python)
   - GTM Auditor (Python, GTM API)
   - Amazon Mockup Generator (AI, Lovable) — with live demo link
   - Tech Spotter (HTML, Python) — frontend + backend repos
   - Automated Dashboards (Looker Studio, Tableau)
   - n8n Workflow Automation
5. **Testimonials** — 4 recommendations:
   - Stephanie Terrett (Pattern® Awardco)
   - Shubham Shukla (LinkedIn)
   - Mikhil Khattar (LinkedIn)
   - Katie McKelvie (LinkedIn)
6. **Recognition** — 6 Awardco peer recognition cards from Pattern®
7. **Skills** — 22 skill pills (GA4, GTM, SQL, Python, Tableau, etc.)
8. **Contact** — Email, Phone (+919998785317), LinkedIn, GitHub

---

## 🚀 Deployment

### Prerequisites
- A GitHub account
- A Vercel account (free)

### Steps
1. Create a new GitHub repository
2. Add `index.html` file with the portfolio code
3. Go to [vercel.com](https://vercel.com)
4. Click "Add New Project" → Import the GitHub repo
5. Set Framework Preset to "Other"
6. Click Deploy
7. Site is live at `your-project.vercel.app`

### Custom Domain (Optional)
1. Purchase a domain (Namecheap, GoDaddy, Hostinger)
2. In Vercel → Settings → Domains → Add your domain
3. Follow DNS configuration instructions

---

## 📱 Responsive Design

- **Desktop (769px+):** Full animations, blob, parallax effects
- **Mobile (768px and below):** Simplified layout, single column grids, blob hidden, nav links collapsed

---

## 📂 File Structure

```
nikhil-portfolio-v2/
├── index.html    ← Single file contains everything
└── README.md     ← This file
```

No build step. No npm. No dependencies to install. Just one HTML file.

---

## 🎨 Color Reference

| Color | Hex | Usage |
|---|---|---|
| Background | `#0a0a0f` | Page background |
| Text Primary | `#f0e7e9` | Headings, body text |
| Text Secondary | `rgba(240,231,233,.45)` | Descriptions, metadata |
| Text Muted | `rgba(240,231,233,.25)` | Overlines, dividers |
| Accent | `#818cf8` | Highlights, links |
| Accent Dark | `#6366f1` | Gradients, secondary accent |
| Border | `rgba(240,231,233,.06)` | Dividers, card borders |

---

## 🏗 Built With

This portfolio was built through conversational AI-assisted development using **Claude (Anthropic)**. The entire design, code, content structure, and deployment workflow was created in a single conversation — demonstrating the "vibe coding" approach where understanding the problem and leveraging AI bridges the gap between idea and execution.

---

## 📝 License

Personal portfolio. All content © 2026 Nikhil Deshpande.

---

## 📬 Contact

- **Email:** nikhildeshpande62@gmail.com
- **Phone:** +91 999 878 5317
- **LinkedIn:** [linkedin.com/in/nikhildeshpande1305](https://www.linkedin.com/in/nikhildeshpande1305)
- **GitHub:** [github.com/iamgoan123](https://github.com/iamgoan123)
