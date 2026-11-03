# Responsive Navbar
A responsive, animated navigation bar built with HTML, Tailwind CSS v4, and vanilla JavaScript. The project is a practice exercise in responsive layouts, Css transitions, clipping, DOM selection and class manipulation.

---

## Technologies
- HTML
- Tailwind CSS v4
- Vanilla JavaScript

---

## Features
- Hmaburger navigation toggle: Clicking the hamburger opens and closes the navigation.
- Animated hamburger icon: The three bars transform into a close icon whnen the menu is open.
- Responsive navigation: On smaller screens, the menu us revealed vertically using ```clip-path```. At the ```md``` breakpoint and above, it behaves like a side panel that slides in horizontally from the right.
- Background overlay: A semi-transparent dark overlay appears when the navigation is open.
- Click-outside closing: Clicking the overlay closes the navigation.
- Animated link underline: Navigation links use a pseudo-element for their hover underline.

---

## Running the Project
- Make sure Node.js and the Tailwind CSS v4 CLI are installed in your development environment.
- Run the tailwind watch command configured for your project so that your source stylesheet compiles to ```src/output.css```.
- Open ```index.html``` through a local developemnt server.
- Resize the browser to test both the mobile dropdown and desktop side panel layouts.

---

## Current Learning Scope
Thia version focuses on the visual behaviour and JvaScript interaction of the navbar. Accessibility enhancements are planned as a later learning step. In particular, the current implementation has not yet added the full set of accessible menu-state attributes and keyboard behaviours, so it should not yet be considered a fully accessible navigation component.

### Possible next improvements include:
- Adding an accessible name and ``` aris-expanded / aria-controls ``` to the hamburger button.
- Closing the navigation with the ```Escape``` key.
- Cloing the navigation after a link is selected.
- Preventing keyboard focus from entering the closed navigation.