# Fun with CSS

A collection of creative CSS-only layouts and animations that demonstrate the power of modern CSS without using any JavaScript.

## Project Description

This project explores advanced CSS techniques including sprite sheets, transitions, custom form controls, and animated menus. Each task showcases how to create interactive and visually appealing interfaces using only HTML and CSS.

## Tasks

### 0. Sprite Languages
**File:** `0-styles.css`

Create a language list that uses CSS sprites to display icons for HTML, CSS, and JavaScript. This demonstrates efficient use of image sprites to reduce HTTP requests while maintaining visual quality.

**Constraints:**
- Cannot modify the HTML
- Must use the provided sprite image (`0-sprite.png`)

---

### 1. Move the (under)line
**File:** `1-styles.css`

Implement a smooth animated underline effect on a link that appears on hover. The underline should be hidden by default and smoothly transition into view.

**Features:**
- Smooth CSS transitions
- Hover effects without JavaScript

**Constraints:**
- Cannot modify the HTML

---

### 2. Toggle
**File:** `2-styles.css`

Style a custom toggle switch using pure CSS. Transform a standard checkbox input into a modern, iOS-style toggle that changes state when clicked.

**States:**
- **Checked:** Toggle switch slides to the right
- **Unchecked:** Toggle switch slides to the left

**Constraints:**
- Cannot modify the HTML
- Must style the existing checkbox input

---

### 3. Menu
**File:** `3-styles.css`

Create an animated circular menu that expands from a hamburger button. When clicked, menu items fan out in a circular pattern with smooth animations.

**Features:**
- Hamburger menu icon animation
- Circular menu item distribution
- Font Awesome icons integration
- Smooth open/close transitions

**Constraints:**
- Cannot modify the HTML
- Pure CSS implementation (no JavaScript)

---

## Repository Structure

```
holbertonschool-Fun-with-CSS/
├── README.md
├── 0-styles.css
├── 1-styles.css
├── 2-styles.css
└── 3-styles.css
```

## Learning Objectives

- Master CSS sprites for efficient image handling
- Understand CSS transitions and animations
- Create custom-styled form controls
- Implement advanced CSS selectors (`:checked`, `:hover`, etc.)
- Build interactive interfaces without JavaScript
- Use CSS transforms for dynamic layouts

## Technologies

- **HTML5** - Structure
- **CSS3** - Styling and animations
- **Font Awesome 4.7.0** - Icons (Task 3 only)

## How to Use

1. Clone the repository:
```bash
git clone https://github.com/yousrakdc/holbertonschool-Fun-with-CSS/.git
```

2. Open each HTML file in a web browser to see the corresponding CSS in action

3. Modify the CSS files to experiment with different styles and animations

## Key CSS Concepts Demonstrated

- **Sprites:** Background positioning and image optimization
- **Transitions:** Smooth property changes over time
- **Pseudo-classes:** `:hover`, `:checked` for state management
- **Transforms:** `translate`, `rotate`, `scale` for animations
- **Pseudo-elements:** `::before`, `::after` for additional styling
- **Custom checkbox styling:** Hiding default inputs and creating custom controls
- **Flexbox/Positioning:** Layout management

## Author

Yousra Kerdouchi

## License

This project is part of the Holberton School curriculum.

---

**Note:** All tasks must be completed using only CSS. No JavaScript is allowed!
