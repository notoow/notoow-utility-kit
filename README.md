# notoow Utility Kit

A single-file browser utility app with a polished translucent glass interface.

## Features

- File encryption and decryption in the browser with AES-GCM
- URL shortening with copy/open actions and a `vietls` watermark
- QR code generation with color themes, an invert toggle, and PNG export
- Batch PNG conversion for SVG, JPG/JPEG, WebP, GIF, BMP, AVIF, and every page of PDF files
- Batch image resize and compression with JPG, WebP, and PNG output
- Automatic ZIP bundling when PNG or resized-image tools produce multiple output files
- Image-to-PDF generation for multiple JPG, PNG, WebP, GIF, BMP, AVIF, and SVG files
- Batch audio and video to MP3 conversion with ZIP bundling for multiple outputs
- Quick links for browser and Windows default-app settings
- Persistent local settings for cleanup reminders and URL copy behavior
- Encrypted file metadata with version, algorithm, timestamp, original name, type, and size
- File processing progress, encrypted data checksum validation, and automatic decrypt-mode detection
- Footer contact links for `antcow0706@gmail.com`, `vietls.com`, and `buymeacoffee.com/notoow`

## Run Locally

Open `index.html` directly in a browser, or serve the folder with a local static server:

```powershell
python -m http.server 4173 --bind 127.0.0.1
```

Then open:

```text
http://127.0.0.1:4173/index.html
```

## Copyright And Licensing

The application source code in this repository is licensed under the MIT License. See [LICENSE](LICENSE).

The app uses third-party open-source libraries and fonts from public CDNs. Their notices are listed in [NOTICE.md](NOTICE.md).

The UI styling and app code are original to this repository. No third-party design images, UI kit assets, or trademarked platform assets are included in the published source.

## Contact

- Email: antcow0706@gmail.com
- Website: https://vietls.com
- Support: https://buymeacoffee.com/notoow
