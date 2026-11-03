# IRP LMS – HTML & CSS Website Recreation

A responsive three-page website that recreates the IRP LMS learning platform, built as a **Web Development Foundations** assignment using only **HTML5 and CSS3**.

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero section with call-to-action and the five-step Learning Journey (Learn, Practice, Build Projects, Prepare, Get Placed) |
| Courses | `courses.html` | Course banner and nine embedded YouTube crash-course videos (HTML, CSS, JavaScript, React, Python, Java, Spring Boot, Hibernate, Django), plus an Explore More Courses bar |
| Contact Us | `contact.html` | Contact details panel (email, phone, address) and a message form |

## Technologies Used

- HTML5 (semantic elements)
- CSS3 (custom properties, Flexbox, CSS Grid, media queries)

No JavaScript, frameworks or external libraries are used.

## Project Structure

```
IRP-LMS/
├── index.html
├── courses.html
├── contact.html
├── style.css
└── README.md
```

## Features

- Consistent navigation bar on all pages, with the current page highlighted
- Logo links to the Home page; Explore Courses opens the Courses page
- Nine YouTube videos embedded with `<iframe>` in 16:9 containers
- Clickable `mailto:` email link and `tel:` phone link
- Contact form with Full Name, Email Address, Subject dropdown and Message fields
- Responsive layout for desktop, tablet and mobile (no horizontal scrolling)
- Navigation that works on mobile without JavaScript

## Color Palette

| Color | Hex |
|-------|-----|
| Navy Blue | `#003366` |
| Orange | `#FE781E` |
| Secondary Blue | `#5F9FE0` |
| Light Blue | `#E2F2FD` |
| White | `#FFFFFF` |
| Light Blue Border | `#D6E9FF` |

The colors are defined as CSS variables in `:root` at the top of `style.css`.

## Responsive Design

| Screen | Layout |
|--------|--------|
| Desktop | 5 journey cards per row, 3-column course grid, 2-column contact layout |
| Tablet (up to 900px) | 3 journey cards per row, 2-column course grid, stacked contact layout |
| Mobile (up to 600px) | Single-column layout, navigation links on their own row |

## How to Run

1. Download or clone this repository.
2. Open the `IRP-LMS` folder.
3. Double-click `index.html` to open it in your browser.

An internet connection is needed to load the images and YouTube videos.

## Notes

- The Sign In button and the contact form are visual only. There is no backend, database or authentication.
- All images are hosted assets provided in the assignment.

## Author

**Your Name**
- GitHub: [Pavani-2116](https://github.com/Pavani-2116/IRP_LMS_PORTAL)
