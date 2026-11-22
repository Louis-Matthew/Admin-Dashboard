# Admin Dashboard

A responsive-style admin dashboard layout built with HTML and CSS. The goal of the project was to practice **CSS Grid** by recreating a provided design.

## Features

- Fixed sidebar with a logo and two groups of navigation links
- Header with a search bar, notifications bell, and user info
- Welcome section with the user's avatar and quick-action buttons (New, Upload, Share)
- "Your Projects" card grid with star, watch, and fork actions
- Announcements panel with divided entries
- Trending panel listing users and their projects
- Hover states on navigation links, buttons, and card actions

## Built With

- HTML5 (semantic elements: `header`, `aside`, `nav`, `main`, `section`, `article`)
- CSS3 (Grid, Flexbox, custom properties)
- Inline SVG icons from [Material Design Icons](https://pictogrammers.com/library/mdi/)
- [Roboto](https://fonts.google.com/specimen/Roboto) font

## What I Practiced

- Building the page layout with nested **CSS Grid** (`grid-template-columns`, `grid-template-rows`, `grid-auto-flow`, `repeat()` with `auto-fit` and `minmax()`)
- Using `fr` units alongside `auto` and fixed sizes
- Splitting a design into smaller grids instead of one large one
- Styling inline SVGs with `fill: currentColor` so icons follow the text color
- Organizing colors with CSS custom properties

## Project Structure

```
admin-dashboard/
├── index.html
├── style.css
├── README.md
├── fonts/
│   ├── Roboto-Regular.woff2
│   └── Roboto-Italic.woff2
└── images/
    ├── avatar.png
    ├── tegan.png
    ├── kendall.png
    └── alex.png
```

## Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/Louis-Matthew/Admin-Dashboard
   ```
2. Open the folder
   ```bash
   cd Admin-Dashboard
   ```
3. Open `index.html` in your browser

No build tools or dependencies are needed.

## Color Palette

| Use | Color |
|---|---|
| Primary blue | `#1992D4` |
| Background | `#E2E8F0` |
| Accent | `#F0B429` |
| Muted text | `#636363` |

## Credits

- Design and project brief by [The Odin Project](https://www.theodinproject.com/)
- Icons from [Material Design Icons](https://pictogrammers.com/library/mdi/)

## Future Improvements

- Make the layout fully responsive for tablets and phones
- Collapse the sidebar into a menu on small screens
- Add active states for the current page in the sidebar