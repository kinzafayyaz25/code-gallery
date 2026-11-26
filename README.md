# code-gallery
# Gallery

A clean, responsive image gallery for showcasing photos and artwork. Browse images in a grid, open them in a full-screen lightbox, and filter by category.

## Features

- Responsive grid layout (desktop, tablet, mobile)
- Full-screen lightbox with next/previous navigation
- Category filtering
- Lazy loading for fast page loads
- Keyboard navigation (← → to browse, Esc to close)
- Easy to customize with your own images

## Demo

<!-- Add a screenshot or live link -->
![Gallery screenshot](docs/screenshot.png)

Live demo: https://your-username.github.io/gallery

## Getting Started

### Prerequisites

- A modern web browser
- (Optional) [Node.js](https://nodejs.org/) 18+ if you use the dev server

### Installation

```bash
git clone https://github.com/your-username/gallery.git
cd gallery
npm install
```

### Run locally

```bash
npm start
```

Then open `http://localhost:3000` in your browser.

If the project is plain HTML/CSS/JS, you can simply open `index.html` directly.

## Project Structure

```
gallery/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── gallery.js
├── images/
│   ├── thumbs/
│   └── full/
├── docs/
│   └── screenshot.png
└── README.md
```

## Adding Images

1. Put full-size images in `images/full/`.
2. Put thumbnails in `images/thumbs/` (recommended width: 400px).
3. Add an entry to the gallery data:

```js
{
  title: "Sunset at the Lake",
  category: "nature",
  thumb: "images/thumbs/sunset.jpg",
  full: "images/full/sunset.jpg"
}
```

## Customization

| Option          | Description                         | Default |
| --------------- | ----------------------------------- | ------- |
| `columns`       | Number of grid columns on desktop   | `4`     |
| `gap`           | Space between images (px)           | `12`    |
| `lazyLoad`      | Enable lazy loading                 | `true`  |
| `showCaptions`  | Show titles under images            | `true`  |

Colors and fonts can be changed in `css/style.css` via CSS variables.

## Tech Stack

- HTML5, CSS3, JavaScript (ES6+)
- *(Update this section with your framework, e.g. React, Vue, Tailwind)*

## Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add my feature"`
4. Push the branch: `git push origin feature/my-feature`
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for details.

## Contact

Your Name – your.email@example.com
Project link: https://github.com/your-username/gallery
