# Centro Asistencial de Marketing

Static web project built with HTML and CSS. It presents a modern startup-style website focused on digital marketing services.

---

## Project Structure

project/
│
├── index.html
├── css/
│ ├── styles.css
│ ├── social.css
│ ├── services.css
│ └── logo.jpg
│
└── subpaginas/
├── productos.html
├── Historia.html
├── Nuestras_redes.html
└── Trabajar_con_nosotros.html

---

## Features

### Navigation Bar
- Startup-style design
- Transparent over the hero section
- Dropdown menu under "About"
- Reused across all pages

### Home Page (index.html)
- Hero section with background image
- Main heading and "Learn More" button
- Modal implemented without JavaScript using :target
- Footer with social media links

### Services Page (productos.html)
- Grid layout with 10 marketing services
- Service cards with Bootstrap icons
- Call-to-action contact section

### Careers Page (Trabajar_con_nosotros.html)
- Job listings
- Application form
- Embedded Google Maps location

### Additional Pages
- Company history
- Social media
- General company information

---

## Technologies Used

- HTML5
- CSS3
- Bootstrap Icons (CDN)

---

## Technical Highlights

- Relative path navigation between pages
- CSS-only modal implementation:

```css
.modal:target {
    opacity: 1;
    pointer-events: auto;
}
