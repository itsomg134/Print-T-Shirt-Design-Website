# Print T-Shirt Design Website

A interactive, browser-based t-shirt design tool that allows users to upload images, customize shirt colors, and position prints in real-time. Built with vanilla HTML, CSS, and JavaScript.

![Screenshot_20-2-2026_22119_127 0 0 1](https://github.com/user-attachments/assets/c9b48749-663b-41b3-a0a4-495549b997f3)

## Features

- **Live Preview** - See your design on a realistic t-shirt mockup instantly
- **Image Upload** - Drag & drop or click to upload PNG, JPG, or SVG files
- **Shirt Color Customization** - 8 preset colors with active state highlighting
- **Print Size Control** - Adjustable slider from 40% to 200%
- **Quick Position Presets** - Center, left chest, right chest, and large center placement
- **Sample Design** - Add a "DESIGN" text sample to test the interface
- **Toggle Visibility** - Show/hide the print to check placement
- **Background Removal Simulation** - Demo effect for transparent-like appearance
- **Reset Options** - Individual print reset or full studio reset
- **Fully Responsive** - Works on desktop and tablet devices

## Live Demo

[View Live Demo](https://yourusername.github.io/print-tshirt-designer) *(Update with your GitHub Pages link)*

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Custom Properties)
- Vanilla JavaScript (ES6)
- SVG for shirt template
- FileReader API for image uploads

## How to Use

1. **Upload an Image** - Click the upload box or drag an image file
2. **Choose Shirt Color** - Click any color swatch below the shirt
3. **Resize Print** - Use the slider to adjust print size
4. **Position Design** - Click preset buttons for common placements
5. **Experiment** - Try sample text, toggle visibility, or simulate background removal

## Local Development

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- Basic code editor (VS Code, Sublime Text, etc.)

### Setup
1. Clone the repository
```bash
git clone https://github.com/yourusername/print-tshirt-designer.git
```

2. Navigate to project folder
```bash
cd print-tshirt-designer
```

3. Open `index.html` in your browser
```bash
# On Mac
open index.html

# On Windows
start index.html

# Or simply double-click the file
```

### Project Structure
```
print-tshirt-designer/
│
├── index.html          # Main application file
├── README.md           # Documentation
└── assets/            # (Optional) For images, icons
```

## Customization Options

### Adding More Shirt Colors
Edit the color swatches in the HTML:
```html
<div class="color-dot" style="background: #hexcode;" data-color="#hexcode" data-name="color-name"></div>
```

### Modifying Position Presets
Update the `setPrintPosition` function in JavaScript:
```javascript
case 'your-position':
  style.top = 'XX%';
  style.left = 'XX%';
  style.maxWidth = 'XX%';
  break;
```

### Changing Shirt Template
The shirt SVG can be modified in the `shirt-svg` element. Adjust the path coordinates for different shirt shapes.

## Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Improvements
- [ ] Add text overlay functionality
- [ ] Implement real background removal API
- [ ] Add more shirt styles (v-neck, long sleeve, etc.)
- [ ] Download final design as PNG
- [ ] Save designs to local storage
- [ ] Add undo/redo functionality
- [ ] Support for multiple print layers

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- SVG shirt template inspired by classic t-shirt design
- Icons and UI elements from system fonts
- Thanks to all contributors and testers

## Contact & Support

Om Gedam

GitHub: @itsomg134

Email: omgedam123098@gmail.com

Twitter (X): @omgedam

LinkedIn: Om Gedam

Portfolio: https://ogworks.lovable.app
