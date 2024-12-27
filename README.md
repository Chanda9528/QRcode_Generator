# QR Code Generator with Logo

A Python-based project that generates QR codes for any input data (e.g., URLs) and optionally adds a logo at the center for branding. This tool is built using the `qrcode` and `Pillow` libraries, ensuring high-quality, scannable QR codes.

---

## Features
- Generate QR codes for any text or URL.
- Add a custom logo at the center of the QR code.
- Supports high error correction to ensure the QR code is scannable even with a logo overlay.
- Fully customizable QR code size, colors, and border width.

---

## Requirements

Ensure you have Python installed on your system, then install the required libraries:
```bash
pip install qrcode[pil] pillow
