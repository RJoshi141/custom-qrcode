# Custom QR Code Generator

A vanilla HTML/CSS/JS QR code generator with full customization options. Create styled QR codes with custom colors, patterns, eye markers, logos, and background colors.

## Features

- **URL/Link input** – Encode any URL or text (default: `https://example.com`)
- **Custom dot color** – Color picker plus hex input for precise colors
- **Dot patterns** – Square, Rounded, Extra Rounded, Dots, Classy, Classy Rounded
- **Corner square (outer eye)** – Custom color and style for the finder pattern squares
- **Corner dot (inner eye)** – Custom color and style for the inner eye dots
- **Background color** – Custom background with color picker
- **Logo** – Upload a local image or paste an image URL
- **Logo size** – Adjustable logo size (20–50% of QR code)
- **Download** – Export as PNG, JPEG, or SVG

## Usage

1. Open `index.html` in a browser (double-click or drag into the browser).
2. Enter the URL or text to encode in the **URL or Link** field.
3. Customize colors, patterns, and markers using the controls.
4. Optionally add a logo via file upload or image URL.
5. Use the PNG, JPEG, or SVG buttons to download your QR code.

### Note on Logo URLs

If you use an external image URL for the logo, some sites may block cross-origin requests. In that case, download may fail—use a file upload instead.

## Tech Stack

- Vanilla HTML, CSS, JavaScript
- [qr-code-styling](https://www.npmjs.com/package/qr-code-styling) (v1.9.2) via CDN

## File Structure

```
custom-qrcode/
├── index.html   # Single-file app (HTML, CSS, JS)
└── README.md    # This file
```

## License

MIT
