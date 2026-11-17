# EXIM-TRADE-ANALYTICS
# EX-IM: Global Export-Import Data & Trade Analytics Platform

A modern, responsive frontend web application designed for the **Web Development Lab (WDL)** coursework. This project showcases an AI-powered global trade intelligence platform interface that visualizes supply chain networks, HS code shipment records, and real-time trade data streams.

---

## 📌 Project Overview

**EX-IM** is an interactive frontend prototype built to demonstrate how exporters and importers can discover global buyers, analyze supplier networks, and track trade flows. The interface combines responsive layout engineering, custom SVG data visualizations, and smooth DOM-driven interactions.

### Key Highlights for Lab Evaluation
* **Semantic HTML5 Architecture:** Structured using accessible landmarks, ARIA attributes (`aria-labelledby`, `aria-expanded`, `role="img"`), and clean sectioning.
* **Interactive SVG Supply Chain ("Company Nexus"):** A dynamic Sankey-style flow diagram comparing 2025 and 2026 supplier-to-buyer trade volumes (`HS 1511.10`) with interactive year toggles.
* **Animated Data Fusion Engine:** Built with native SVG paths and `<animateMotion>` elements to illustrate 10+ live trade data streams feeding into a central processing core.
* **Responsive Media & Motion Handling:** Uses JavaScript `window.matchMedia` to adapt background video playback across desktop and mobile viewports while respecting `prefers-reduced-motion` accessibility settings.
* **Privacy-Safe Vector Avatars:** Uses custom-coded inline SVG gradients for all user profile avatars in the testimonials section.

---

## 🚀 Features & Page Sections

1. **Navigation & Hero Section:**
   * Sticky responsive navigation bar with smooth in-page anchor routing.
   * Smart search bar for **HS Codes, Products, and CAS numbers** with quick-try filter chips (`basmati rice`, `HS 1006`, `coffee`).
2. **Trusted Partner Marquee:**
   * Infinite-scroll CSS logo carousel displaying global logistics and enterprise partners.
3. **Company & Product Nexus (`#exim-nexus`):**
   * Interactive supply chain visualization mapping upstream suppliers (*Buying From*) and downstream buyers (*Sells To*) with trade value proportions and sanction watchlist indicators.
4. **The EX-IM Foundation (`#exim-foundation`):**
   * Animated metric counters (8B+ shipment records, 181+ countries, 500+ ports).
   * Orbital SVG architecture diagram illustrating AI Enrichment, Named Entity Recognition, Data Fusion, and Deduplication.
5. **Institutional Collaborations & Experience Centre:**
   * Tabbed partner spotlight and interactive video showcase.
6. **Client Testimonials (`#tm-title`):**
   * Accordion-style featured case studies and a responsive testimonial grid using custom SVG vector avatars.
7. **Mobile App Dashboard Preview (`#app-shrink`):**
   * CSS-rendered mobile device frame displaying an interactive country-wise buyer/seller analytics dashboard.

---

## 🛠️ Tech Stack

* **Markup:** HTML5 (Semantic Elements, ARIA Accessibility)
* **Styling:** CSS3 (Custom Properties/Variables, Flexbox, CSS Grid, Keyframe Animations, Backdrop Filters)
* **Scripting:** Vanilla JavaScript (ES6+, DOM Manipulation, Responsive Media Queries)
* **Graphics & Icons:** Inline SVG, SMIL Path Animations (`<animateMotion>`), Linear/Radial SVG Gradients

---

## 📂 Project Structure

```text
WDL-EXIM-Project/
│
├── index.html          # Main application entry point (self-contained HTML & SVG visualizations)
└── README.md           # Project documentation for WDL submission
