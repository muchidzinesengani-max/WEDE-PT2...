# Mabaso Electrical Services Website

## Project Title
WEDE5020 Portfolio of Evidence - Mabaso Electrical Services Website

## Student Information
- **Name:** MUTSHIDZI NESENGANI
- **Student Number:** ST10518407
- **Module:** WEDE5020 - Web Development
- **Institution:** The Independent Institute of Education (IIE)

## Project Overview
This repository contains the website project for **Mabaso Electrical Services**, a
family-owned electrical contracting business based in Polokwane, Limpopo. The site is
being developed in three parts as part of the WEDE5020 Portfolio of Evidence:

- **Part 1:** HTML structure, content, navigation, and file organisation.
- **Part 2:** CSS styling and responsive design.
- **Part 3:** JavaScript functionality and SEO optimisation.

The website aims to give Mabaso Electrical Services a professional online presence,
allowing prospective customers to learn about the business, browse services, and submit
quote requests online rather than relying solely on word-of-mouth and Facebook.

## Website Goals and Objectives
- Establish a professional, trustworthy online presence for the business.
- Clearly communicate the full range of electrical services offered.
- Make it easy for visitors to request a quote or contact the business directly.
- Improve local search visibility for terms such as "electrician Polokwane."

**Key Performance Indicators (KPIs):**
- Number of quote/enquiry form submissions per month.
- Reduction in average response time to customer enquiries.
- Growth in organic search visibility for local search terms.
- Click-through rate on WhatsApp/phone call-to-action buttons.

## Key Features and Functionality
- Responsive, mobile-first design suitable for customers searching urgently from a phone.
- Five linked pages: Home, About, Services, Enquiry (quote request form), and Contact.
- Quote request form capturing job type, preferred date, address, and job description.
- Contact page with two service-area locations shown on embedded maps.
- Consistent header navigation and footer across all pages.

## Timeline and Milestones
| Milestone | Target |
|---|---|
| Proposal finalised, repository set up | Week 1 |
| Five HTML pages built and linked (Part 1) | Week 2-3 |
| CSS styling and responsive design (Part 2) | Week 4-5 |
| JavaScript functionality and SEO (Part 3) | Week 6-7 |
| Final testing, debugging, and submission | Week 8 |

## Part 1 Details (Complete)
Part 1 delivers the foundational HTML structure for all five pages, a clear file and
folder structure, and initial styling to support layout during development.

## Part 2 Details (Complete)
Part 2 delivers full CSS styling and a responsive design for the desktop, tablet, and
mobile experience:
- A consistent typographic scale and CSS custom properties for colour, spacing, and
  font sizing, applied across all five pages via the shared `style.css`.
- CSS Grid used for card, footer, and contact layouts; Flexbox used for the header,
  navigation, and hero content.
- Interactive states added using `:hover`, `:focus-visible`, and `:active` on buttons,
  cards, nav links, and form fields.
- A CSS-only (checkbox-driven) mobile navigation toggle, so the menu collapses behind a
  hamburger icon on small screens without requiring JavaScript.
- Two responsive breakpoints: tablet (`max-width: 900px`) and mobile
  (`max-width: 600px`), adjusting the typographic scale, section spacing, grid columns,
  and navigation layout at each stage.
- Responsive images: each content image has 400/800/1200px wide variants served via
  `srcset`/`sizes` so the browser picks the right file for the viewport, and the hero
  background image swaps to a smaller file at the tablet/mobile breakpoints.
- Screenshot evidence of the desktop, tablet, and mobile views should be added to this
  README as they are captured.

**File and folder structure:**
```
mabaso-electrical-website/
├── index.html
├── about.html
├── services.html
├── enquiry.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
└── README.md
```

## Sitemap
```
Home (index.html)
├── About (about.html)
├── Services (services.html)
├── Get a Quote (enquiry.html)
└── Contact (contact.html)
```
All five pages are linked via a consistent navigation menu in the header, and the footer
repeats quick links on every page.

## Changelog
- **[Date] - v0.1 (Part 1):** Initial repository setup, file/folder structure created.
- **[Date] - v0.2 (Part 1):** Built and linked all five HTML pages (index, about,
  services, enquiry, contact) with semantic structure (header, nav, main sections,
  footer).
- **[Date] - v0.3 (Part 1):** Added base CSS (style.css) to support layout during
  development and a placeholder script.js for future JavaScript work.
- **[Date] - v0.4 (Part 1):** Added README.md documentation, sitemap, and references.
- **[Date] - v1.0 (Part 2):** Rebuilt `style.css` with CSS custom properties for a
  consistent typographic scale, colour palette, and spacing system.
- **[Date] - v1.1 (Part 2):** Added a CSS-only mobile navigation toggle (checkbox +
  label pattern) and matching markup to all five HTML pages.
- **[Date] - v1.2 (Part 2):** Added `:hover`, `:focus-visible`, and `:active`
  pseudo-class styling to buttons, cards, nav links, footer links, and form fields for
  clearer interactivity and accessibility.
- **[Date] - v1.3 (Part 2):** Introduced two responsive breakpoints (tablet at 900px,
  mobile at 600px) covering typographic scale, section padding, grid column counts, and
  the collapsing navigation menu.
- **[Date] - v1.4 (Part 2):** Generated 400px/800px/1200px wide versions of every
  content image and added `srcset`/`sizes`/`loading="lazy"` to all `<img>` tags so
  browsers download an appropriately sized file instead of the full-resolution
  original. Also swapped the hero background image to a smaller variant at the tablet
  and mobile breakpoints using CSS media queries.

## References
Referencing style: Harvard (adapted for The IIE), as required by the WEDE5020 module
guide.

- Afrihost, 2026. *Web hosting plans*. [online] Available at: <https://www.afrihost.com>
  [Accessed 9 August 2026].
- DOMAINS.CO.ZA, 2026. *.co.za domain registration*. [online] Available at:
  <https://www.domains.co.za> [Accessed 9 August 2026].
- Electrical Contractors' Association of South Africa (ECASA), 2026. *Certificate of
  Compliance requirements*. [online] Available at: <https://www.eca.co.za> [Accessed 9
  August 2026].
- Mozilla Developer Network (MDN), 2026. *HTML: HyperText Markup Language*. [online]
  Available at: <https://developer.mozilla.org/en-US/docs/Web/HTML> [Accessed 9 August
  2026].
- Google, 2026. *Google Maps embed without an API key*. [online] Available at:
  <https://www.google.com/maps> [Accessed 9 August 2026].

## Image Sources

The website images were added to the `images` folder for the project. Sources used for the visual content include:

- ProLane – Electrical installation image: https://www.prolane.io/AK.jpeg
- OM Power Services – Electrical technician image: https://om-airconditioning-electrical.com/images/electrical-tec.jpg
- Electric Company of Omaha – Electrical wiring image: https://www.ecomaha.com/wp-content/uploads/2017/11/electrician-wires-worker-wiring-electrical-man.jpg
- Certiweb – Electrical testing image: https://www.certiweb.be/wp-content/uploads/2021/10/hoeveel-kost-een-elektriciteitskeuring.jpg
- OKRA Solar – Solar installation image: https://cdn.prod.website-files.com/64107caa41980be9eb3047ba/6818e4c0268cdb79d7eca649_south-africa-solar.jpg

Image sources should be reviewed against their current licence/usage terms before any commercial publication of the website.
