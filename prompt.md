Build a single-page developer portfolio website in plain HTML + CSS + JS (no frameworks needed).

## Design Reference
Inspired by: https://myport-sirinat.netlify.app/
- Dark background (#0a0a0a)
- Clean serif + sans-serif font pairing
- Editorial layout with large section numbers like "01 / Section Name"
- Project cards with thumbnail image, tag badge, title, short description, and link
- Sticky top navbar with name on left, nav links on right + Contact button
- Italic accent text in headings (e.g. "Backend *Engineer*")
- Minimal, no animations — just clean spacing and typography

## Fonts (use Google Fonts)
- Display/Heading: "Playfair Display" (italic for accent words)
- Body/Mono: "DM Mono" for tags, labels, nav links
- Body text: "Inter" or "DM Sans"

## Color Palette
- Background: #0a0a0a
- Surface: #111111
- Border: #1e1e1e
- Text primary: #e8e4dc
- Text muted: #555555
- Accent green: #3ddc84 (for tags, highlights, active states)

## Page Structure

### Navbar (sticky)
- Left: my name (e.g. "YOURNAME")
- Right: nav links [Engineering, Experience, About] + [Contact] button styled as outline pill
- Bottom border: 1px solid #1e1e1e

### Hero Section
- Two column layout
- Left: small badge "Available for Internship 2026" with green dot, big heading with italic accent word, short bio 2 lines, two buttons [Explore Works] [Resume CV ↗]
- Right: profile image (round or square with border, use placeholder for now)

### 01 / Projects Section
- Section label: "01 / Projects & Works" in DM Mono small caps
- Project cards grid (2 columns)
- Each card: thumbnail image (use placeholder), tag badge top-left, title, Thai or English description, [View on GitHub ↗] link

Projects to include:
1. URL Shortener API — NestJS + TypeScript + PostgreSQL + AWS — Backend REST API with JWT auth, click analytics, rate limiting
2. (placeholder for future project)

### 02 / Experience Section
- Timeline style, simple list
- Each item: date on left, role + company on right

### 03 / About Section
- Two column: left big heading with italic, right bio text + Technical Toolkit as bullet list
- Toolkit: TypeScript, NestJS, Next.js, React, PostgreSQL, AWS, Git

### Contact / Footer
- Big heading: "Let's Build *The Future.*"
- Email, GitHub links
- Copyright line bottom

## Technical Requirements
- Single HTML file with embedded CSS and JS
- Google Fonts loaded via @import
- No libraries, no frameworks
- Responsive: works on mobile (stack columns at 768px)
- Smooth scroll for nav links
- Clean semantic HTML

## Placeholders
- Use https://placehold.co/600x400/111111/333333 for project images
- Use https://placehold.co/400x400/111111/333333 for profile photo
- Replace [YOURNAME] with actual name where noted

Output: single index.html file ready to push to GitHub Pages or Netlify.