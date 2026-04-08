# Buyer Avatar – Profiling Sheet

A sleek, dark-themed single-page form designed to build detailed buyer personas for **Meta Ads campaigns targeting Algeria**.

![Status](https://img.shields.io/badge/status-production-brightgreen) ![Version](https://img.shields.io/badge/version-2.0-blue) ![Year](https://img.shields.io/badge/year-2026-yellow)

---

## Overview

This tool helps marketers and media buyers create a comprehensive **Buyer Avatar** — a detailed customer profile that drives high-converting Facebook and Instagram ad campaigns across all 69 Algerian wilayas.

Fill out the form, click **Generate PDF Report**, and get a beautifully formatted, print-ready document.

---

## Features

- **12 Profiling Sections** covering demographics, psychology, buying behavior, and ad strategy
- **Real-time Progress Tracker** — sticky bar shows completion percentage as you fill fields
- **PDF Export** — generates a multi-page dark-themed PDF report via jsPDF
- **Deep Trigger Builder** — distill the avatar's core desire into a single hook sentence
- **Responsive Design** — works on desktop, tablet, and mobile
- **Zero Dependencies** — single HTML file, no build tools needed

---

## Sections

| #  | Section                              | Purpose                                      |
|----|--------------------------------------|----------------------------------------------|
| 01 | Basic Information                    | Demographics, location, language, housing     |
| 02 | Daily Life Snapshot                  | Habits, devices, content preferences          |
| 03 | Core Problem                         | Pain points and frustrations                  |
| 04 | Emotional Layer                      | Fears, shame, identity, self-talk             |
| 05 | Past Failed Solutions                | What they tried and why it didn't work        |
| 06 | Desired Outcome                      | Dream transformation and success metrics      |
| 07 | Buying Behavior                      | Price sensitivity, trust signals, channels    |
| 08 | Main Buying Objections               | 8 common objection patterns                   |
| 09 | Awareness Level                      | Eugene Schwartz awareness spectrum            |
| 10 | Product Details                      | Product info, USP, competitive advantages     |
| 11 | Ad Creative & Messaging Angles       | Hooks, CTAs, tone, visual style               |
| 12 | Competitive Context & Brand Positioning | Competitors, positioning statement          |

---

## Tech Stack

| Technology      | Purpose                          |
|-----------------|----------------------------------|
| HTML5           | Structure                        |
| CSS3 (Vanilla)  | Styling — dark theme, Inter font |
| JavaScript      | Form logic, progress tracking    |
| [jsPDF](https://github.com/parallax/jsPDF) | Client-side PDF generation |
| [Inter](https://fonts.google.com/specimen/Inter) | Typography (Google Fonts) |

---

## Getting Started

1. **Open the file** — double-click `buyer-avatar-form.html` in any modern browser
2. **Fill out the sections** — work through each section, watch the progress bar
3. **Generate the PDF** — click the yellow "Generate PDF Report" button
4. **Download** — the PDF saves automatically with the avatar's name

> No server, no install, no build step. Just open and use.

---

## File Structure

```
buyer avatar/
├── buyer-avatar-form.html   # The complete application (single file)
└── README.md                # This file
```

---

## Customization

### Adding new dropdown options
Find the relevant `<select>` element by its `id` and add/remove `<option>` tags.

### Changing the color scheme
Edit the CSS custom properties in the `:root` block at the top of the `<style>` section:

```css
:root {
  --bg: #0c0c0e;        /* Page background */
  --accent: #e8ff47;     /* Primary accent (lime-yellow) */
  --accent2: #ff6b35;    /* Secondary accent (orange) */
  --text: #ececf0;       /* Main text color */
  --muted: #6e6e80;      /* Muted/label text */
}
```

### Modifying the PDF
The `buildPDF()` function in the `<script>` block handles all PDF generation. Each section maps field IDs to labels.

---

## Browser Support

| Browser         | Supported |
|-----------------|-----------|
| Chrome 90+      | ✅        |
| Firefox 90+     | ✅        |
| Edge 90+        | ✅        |
| Safari 15+      | ✅        |
| Mobile browsers | ✅        |

---

## License

Private use — internal marketing tool.

---

*Built for Meta Ads campaigns in Algeria · 2026*
