# Portfolio practise

This project is a personal portfolio website, created as a practical exercise for Module 2 of the Her-Tech JavaScript Bootcamp. It showcases the professional profile of a web developer through a clean, modern design, featuring a personal introduction, services, project highlights, client testimonials, and a contact form.

## Main Sections

- Hero with Name and Tagline.

- Includes a prominent title, a brief professional subtitle, and a representative image.

### Services Offered

- A visual section using icons to present the services provided, such as web design, frontend development, and responsive design.

### Highlighted Projects

- A project gallery with images, short descriptions, and titles showing previous work.

##Client Opininos

- A section with testimonial cards from real or sample clients, adding credibility to the profile.

### Contact Form

- A simple form that lets users send messages directly through the website.

### Footer with Social Media Links

- Contains links to professional profiles, legal disclaimer, and contact access.

## Technologies Used

### HTML

- General structure divided into main sections:

- header: contains the logo/name and possibly a navigation bar.

- main: core content split into:

- hero-section: main introduction.

- services-section: service overview.

- work-section: project gallery.

- clients-section: testimonials and feedback.

- footer-section: contact form and social links.

### CSS

- Selectors Used:

- Universal:

* to set base font and global box-sizing.

- Element selectors:

footer, form, input, textarea, for general layout and input styles.

- Class selectors:

.hero-text, .service, .work-item, .opinion, .client-info, .social-icons, etc., to group reusable semantic styles.

- Combined selectors:

.topnav a, .footer-links ul li a, .client-info h4 span for specific nested element styling.

- Grouped selectors:

.about-text, .mission-text, .contact-text to avoid duplication between similarly styled sections.

- Pseudoclasses:

- :hover: used on links, buttons, and icons to enhance interactivity.

- Flexbox:

- Widely used (display: flex) for structure and alignment in:

- .hero-content, .services-section, .work-section, .footer-content, etc., managing layout and spacing.

- Properties like justify-content, align-items, flex-direction, gap, flex-wrap, and flex: 1 used for responsive layout and element distribution.

## Fonts & Resources

- Google Fonts:
- Poppins in multiple weights (regular, semibold) used across the website.

- SVG Icons:
- Manually inserted SVG files for social media icons and service representations.

## Tools:

- Visual Studio Code as the code editor.

- Chrome DevTools for responsive design adjustments.
