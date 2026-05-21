# Bikes for Refugees Seville — Website

A static website for **Bikes for Refugees Seville**, a volunteer-led initiative that collects and donates bicycles to refugees and asylum seekers in Seville and Andalusia.

***

## 🚲 About the Project

This site serves as the public face of the organization, allowing visitors to learn about the cause, find upcoming events, and donate or volunteer. It displays a counter of bikes donated, a sidebar with upcoming events, and calls to action for community involvement.

***

## 📁 Project Structure

```
├── index.html    # Main HTML page
└── style.css     # Stylesheet
```

***

## 🛠️ Tech Stack

- **HTML5** — semantic markup with accessibility attributes (`aria-label`, `aria-current`, `aria-labelledby`, etc.)
- **CSS3** — custom layout with a two-column content + sidebar structure
- **Cloudinary** — external image hosting for hero image, event thumbnails, and logo

No JavaScript. No build tools. No dependencies.

***

## 🚀 Getting Started

No installation required. Open the project directly in the browser:

```bash
# Clone the repository
git clone https://github.com/your-username/bikes-for-refugees-seville.git

# Open in browser
open index.html
```

Or use a live server extension (e.g. VS Code's **Live Server**) for hot reload during development.

***

## 🏗️ Page Structure

| Section         | Element     | Description                                             |
|-----------------|-------------|---------------------------------------------------------|
| Header          | `<header>`  | Logo, main navigation, "Donate Now" CTA                 |
| Notice banner   | `<section>` | Milestone counter of bikes donated                      |
| Hero            | `<section>` | Full-width image with headline and action buttons       |
| Learn More      | `<section>` | Two info cards: why bikes matter, how to help           |
| Upcoming Events | `<aside>`   | Three event cards with thumbnail images and descriptions|
| Footer          | `<footer>`  | Short description of the organization                   |

***

## ♿ Accessibility

- Semantic HTML5 landmarks (`<header>`, `<main>`, `<aside>`, `<footer>`)
- All images include descriptive `alt` text
- Navigation uses `aria-label` and `aria-current="page"`
- Section headings linked via `aria-labelledby`
- SVG icon marked with `aria-hidden="true"` and `focusable="false"`
- Event images use `loading="lazy"` for performance

***
