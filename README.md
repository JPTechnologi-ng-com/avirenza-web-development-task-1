**Live site:** https://JPTechnologi-ng-com.github.io/avirenza-web-development-task-1/

# Responsive Personal Portfolio Website in Plain HTML and CSS

AVIRENZA Web Development Task 1, by Joseph Clement Adogbe (AVZ-2026-000274).

## What I built

A single-page personal portfolio written with only HTML and CSS, with no frameworks, templates or page builders. It has a sticky header with in-page navigation, a hero section, About, an Education timeline, Skills grouped into Languages, Tools and Soft skills, three project cards, a contact form layout and a footer.

- Semantic HTML5: `header`, `nav`, `main`, `section`, `article`, `footer`, one `h1` and a logical heading order
- Mobile-first layout with breakpoints at 768 px and 1024 px
- Projects use CSS Grid (1 column on phones, 2 on tablets, 3 on desktops); Skills use Flexbox
- CSS custom properties for colours and spacing in one external stylesheet
- Accessibility: alt text, labelled form fields, visible focus styles, skip link, contrast of at least 4.5:1

## Tools used

VS Code, HTML5, CSS3, Chrome DevTools, Lighthouse, Git and GitHub Pages.

## How to open or run it

1. Clone the repository: `git clone https://github.com/JPTechnologi-ng-com/avirenza-web-development-task-1.git`
2. Open `index.html` in any browser. No build step or install is needed.

## Screenshots

| 360 px (phone) | 768 px (tablet) | 1280 px (desktop) |
|---|---|---|
| ![Phone](screenshots/phone-360.png) | ![Tablet](screenshots/tablet-768.png) | ![Desktop](screenshots/desktop-1280.png) |

### Lighthouse

![Lighthouse report](screenshots/lighthouse.png)

## What I learned

- How to structure a page with semantic landmarks so it makes sense to screen readers
- When to use Flexbox (one direction) and CSS Grid (rows and columns)
- How mobile-first CSS keeps styles simple, with media queries only adding changes
- How custom properties keep colours and spacing consistent
- How to test with DevTools and Lighthouse, and publish a static site with GitHub Pages
