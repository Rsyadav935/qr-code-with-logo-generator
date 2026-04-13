# QR Code With Logo Generator

A quick browser-based tool to convert any URL or text into a QR code, with optional logo placement in the center.

## Features

- Generate QR code from any URL or plain text
- Optional center logo support (PNG/JPG/etc.)
- High error correction (`H`) for better logo compatibility
- Download generated QR as a PNG image
- Fallback QR generation path if the primary QR library is unavailable

## Project Structure

- `../index.html`: Main app (single-file HTML/CSS/JS tool)

## How to Run

1. Open `index.html` in any modern browser.
2. Enter a URL or text.
3. Optional: upload a logo image.
4. Click **Generate QR**.
5. Click **Download PNG** to save the final output.

## Logo Behavior

- If a logo file is selected, logo mode is auto-enabled.
- A white background plate is added behind the logo to improve scan reliability.
- Keep logo size reasonable for best scanning results.

## Troubleshooting

- **`QRCode is not defined`**:
  - The app already includes a fallback path. Refresh and try again.
  - Ensure internet access is available for external QR resources.
- **Logo not visible**:
  - Re-upload logo and regenerate.
  - Prefer PNG/JPG files.
  - Avoid fully transparent or white-only logos.
- **QR not scanning**:
  - Use shorter text/URL where possible.
  - Reduce logo complexity/size.

## Browser Support

Works on current versions of:

- Chrome
- Edge
- Firefox
- Safari

## Future Improvements

- Fully offline QR generation (no network dependency)
- Custom QR colors and sizes
- Adjustable logo size slider
