# Frontend Mentor - Recipe Page Solution

This is a responsive, high-fidelity, and accessibility-first solution to the [Recipe page challenge on Frontend Mentor](https://frontendmentor.io). 

The project has been engineered from a Mobile-First perspective, ensuring a seamless visual translation from fluid mobile environments up to fixed 1440px desktop displays.

## 🚀 Technical Features & Core Implementations

- **Mobile-First Responsive Layout**: Standardized layout scaling that eliminates desktop padding on mobile displays to allow the hero asset to touch screen edges natively, snapping into a beautifully carded layout on screen widths above `640px`.
- **Pixel-Perfect Typography Scaling**: Integrated official Google Fonts typography chains (`Young Serif` and `Outfit`) using explicit weight mappings to ensure character lengths match the design blueprint precisely.
- **Strict Accessibility (Axe Linter Approved)**: Built with clean semantic markup trees. The nutrition section features a fully accessible data table utilizing explicit `scope="row"` headers (`<th>`) rather than generic structural block definitions, optimizing readability for assistive screen reader technology.
- **List Marker Optimization**: Leveraged clean vector bullet positioning rules (`list-style-position: outside`) combined with specific inline offsets, preventing text wrapping anomalies underneath the decimal and bullet icons.
- **Modern CSS Engineering**: Fully decupled theme values into organized design tokens located in the stylesheet's `:root` component for maintainable style architecture.

## 📁 Repository Blueprint

```text
recipe-page/
├── assets/
│   └── images/
│       ├── favicon-32x32.png
│       └── image-omelette.jpeg
├── index.html       # Semantically validated markup tree architecture
├── styles.css       # Complete style sheets with Design Tokens and media queries
└── README.md        # Technical deployment and specification document
```

## 🛠️ Tech Stack & Workspace Environment

- **Operating System**: Ubuntu Linux
- **Integrated Development Environment (IDE)**: Visual Studio Code + Live Server Extension
- **Core Technologies**: HTML5 Core Structures, CSS3 (Design Tokens, Nested Component Layouts, Media Feature Rules)

## 🎨 Style Guide Specifications Addressed

Conforming directly to the official Frontend Mentor design constraints:
- **Mobile Width Bounds**: Optimized around a `375px` physical constraint layout.
- **Desktop Grid Bounds**: Constrained to a tight `736px` wrapper centered perfectly inside a `1440px` viewport frame.
- **Color System Applied**:
  - Primary Accents: `Nutmeg (hsl(14, 45%, 36%))`, `Dark Raspberry (hsl(332, 51%, 32%))`
  - Neutrals Base: `Eggshell`, `Rose White`, `White`, `Light Grey`, `Wenge Brown`, `Dark Charcoal`
- **Typography Scale**: 16px body base copy tracking. `Young Serif` fixed strictly at weight `400`. `Outfit` applied dynamically via weight bounds `400`, `600`, and `700`.

---
Coded with precision by Ciprian Danila — Continuously refining web development layout methodologies.
