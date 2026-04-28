# Safari Logo

Safari Logo built using HTML, CSS and a touch of JavaScript.

<p align="center">
  <img src="./Screenshot%202024-05-24%20003130.png" alt="Safari Logo Preview" width="480" />
</p>

## Preview
A clean, CSS-driven recreation of the macOS Safari compass logo. Hover the card to watch the needle animate.

## Files
- `index.html` — markup for the logo.
- `style.css` — styling, layout and hover animation.
- `Screenshot 2024-05-24 003130.png` — preview image used above.

## How it works
The logo is built entirely with HTML and CSS:
- The circular compass is created with a container (`.circle-lines`) and multiple `span` elements. Each span uses a CSS custom property (`--i`) to rotate into place and form the compass ticks.
- The needle is an element (`.niddle`) styled using pseudo-elements (`::before` and `::after`) and rotated on hover using a CSS transform and transition.
- No external images are required to render the logo — only the included screenshot is for preview in the README.

## Usage
1. Clone or download this repository:

   git clone https://github.com/BinaryVortex/Safari-Logo.git

2. Open `index.html` in your browser (double-click or serve with a static server).

3. Hover the logo to see the needle rotate.

## Customize
- Change the size by editing the `.safari` width/height in `style.css`.
- Adjust the gradient colors in `.circle-lines` for different themes.
- Modify the number of ticks by adding/removing `span` elements in `index.html` and updating their `--i` values.

## Contributing
Contributions and improvements are welcome — open an issue or submit a pull request with your suggestions.

## License
No license specified. Add a `LICENSE` file to set the project license.
