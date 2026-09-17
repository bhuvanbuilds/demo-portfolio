# Demo Portfolio

A responsive personal portfolio built with HTML and CSS only.

## Links

- Live site: https://bhuvanbuilds.github.io/demo-portfolio/
- Repository: https://github.com/bhuvanbuilds/demo-portfolio

## Project Features

- Responsive personal portfolio layout for desktop and mobile screens
- Home section with introduction, calls to action, profile image, location, focus, and availability details
- About section with real developer information
- Work section with three project cards and technology lists
- Skills section covering HTML, CSS, responsive design, accessibility, and UI design
- Contact section with labeled name, email, and message fields
- Footer with email, GitHub, and LinkedIn links

## Semantic HTML

The page uses meaningful HTML elements to describe the document structure and content:

- `<header>` for the site header, hero introduction, section headings, and project headings
- `<nav>` for primary navigation, hero actions, and footer links
- `<main>` for the page's primary content
- `<section>` for Home, About, Work, Skills, and Contact areas
- `<article>` for individual portfolio projects
- `<figure>` and `<img>` for the profile image
- `<dl>`, `<dt>`, and `<dd>` for hero details such as location and availability
- `<ul>` and `<li>` for project technologies and skills
- `<form>`, `<label>`, `<input>`, and `<textarea>` for the contact form
- `<footer>` for project actions and the site footer

All form fields have associated labels, and the profile image includes descriptive alternative text.

## CSS Implementation

- CSS custom properties define the color and typography system
- Flexbox is used for the header, navigation, hero layout, skills, and footer
- CSS Grid is used for the project list and hero detail list
- A mobile media query changes the layout for smaller screens
- The palette is based on:
	- Navy: `#1B2C4C`
	- Blue: `#7692FF`
	- Light blue: `#ABD2FA`
	- White: `#FFFFFF`
- Typography uses a sans-serif body font and a serif heading font
- Styling stays intentionally simple with no JavaScript, animation, or gradient dependencies

## Files

- `index.html` - Semantic portfolio page structure and content
- `style.css` - Color system, typography, layout, and responsive styles
- `profile.png` - Profile image used in the hero section

## Run Locally

Open `index.html` in a browser, or serve the folder with any static web server.
