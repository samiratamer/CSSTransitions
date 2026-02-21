# CSS Pseudo-Elements, Transitions & Hover Effects – Blog Page

A CSS styling project adding advanced interactive effects and animations to a blog 
page using pseudo-elements, transitions, and hover states.

## Requirements Met

**Typography**
- First letter of each article's main text styled with Times New Roman, 36px 
  using ::first-letter pseudo-element
- "Read More" links are unaffected by the drop cap styling

**Custom Link Icons**
- Each "Read More" link pointing to Google displays an arrow icon to its right
- Arrow sourced and implemented using CSS pseudo-elements

**Article Hover Animations**
- Articles begin with lightly colored text
- On hover, text darkens and the article expands smoothly over 2 seconds
- On mouse-out, article returns to original state over 2 seconds
- Achieved using CSS transitions

**Navigation Interactions**
- Navigation button backgrounds change color on hover
- Hovering over the "Recent Articles" button reveals a dropdown list of article links
- Hovering over links in the dropdown changes both font color and background color

## Files
- `index.html` — provided HTML file
- `styles.css` — external CSS file with all effects and animations

## How to View
Open `index.html` in any web browser — no setup required.
Hover over articles and navigation buttons to see all interactive effects.

## Concepts Used
- CSS ::first-letter and ::after pseudo-elements
- CSS transitions and timing functions
- Hover state styling with :hover pseudo-class
- Dropdown navigation menus in pure CSS
- CSS content property for injecting icons
- Animation timing and easing over defined durations

## Course
Web-Based Information Technology (CIS 4004) – University of Central Florida
