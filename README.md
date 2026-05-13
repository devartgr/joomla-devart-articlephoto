# DevArt Article Photo for Joomla

![Joomla](https://img.shields.io/badge/Joomla-6.x-blue)
![PHP](https://img.shields.io/badge/PHP-8.2%2B-green)
![License](https://img.shields.io/badge/License-GPLv3-red)
![Release](https://img.shields.io/badge/Version-1.0.3-orange)

Lightweight Joomla 6 component for generating optimized article-ready images for news, editorial, magazine, and high-traffic publishing websites.

DevArt Article Photo helps editors quickly prepare clean, lightweight, properly sized article images directly inside Joomla with a fast, secure, and efficient workflow built for modern newsroom production environments.

---

## Overview

DevArt Article Photo is a focused administrator tool for fast article image preparation.

It is designed specifically for publishers who need a simple and stable workflow for converting uploaded images into clean, optimized article-ready assets without relying on external editing tools.

---

## Features

### Image Processing

Generate optimized article-ready JPG images from:

- JPG
- PNG
- WEBP

Per-image output size selection:

- 1200 × 800
- 1620 × 1080

- Crop position and zoom controls
- Fast preview generation
- Auto Preview without full page refresh
- Optimized JPG compression workflow
- Automatic temporary preview cleanup

---

### Editorial Workflow

- Instant image download
- Save directly to `/images/YYYY/MM/`
- Automatic year/month folder creation
- Fast newsroom-friendly administrator workflow
- Lightweight and distraction-free interface

---

### Branding Options

- Optional logo overlay
- Optional center watermark overlay

---

### Filename Safety

- Live filename prefix sanitization
- Automatic lowercase filename conversion
- Automatic space-to-hyphen conversion
- Non-Latin character filtering
- Safer filesystem-compatible filenames

---

### Security & Stability

- Joomla ACL permissions support
- CSRF protection for administrator actions
- Strict upload validation
- Enhanced MIME validation using `finfo_file()` when available
- Image verification using `getimagesize()`
- Dual upload validation workflow
- Temporary file cleanup protection
- Modern Joomla 6 architecture
- PHP 8.4 compatible

---

### Update Support

- Joomla native update system support
- GitHub update server integration

---

## Screenshots

### Dashboard

![Dashboard](assets/screenshots/devartarticlephoto_dashboard.jpg)

### New Photo

![New Photo](assets/screenshots/devartarticlephoto_newphoto.jpg)

### Joomla Options

![Options](assets/screenshots/devartarticlephoto_options.jpg)

### Settings

![Settings](assets/screenshots/devartarticlephoto_settings.jpg)

---

## Requirements

- Joomla 6.x
- PHP 8.2+
- PHP GD extension with:
  - JPEG support
  - PNG support
  - WEBP support

Recommended:

- PHP Fileinfo extension (for enhanced MIME validation)

---

## Installation

1. Download the latest release ZIP package
2. Open Joomla Administrator
3. Go to:

`System → Extensions → Install`

4. Upload the package ZIP
5. Open:

`Components → DevArt Article Photo`

---

## Default Workflow

1. Upload source image
2. Adjust crop and zoom
3. Enable logo or watermark if needed
4. Select output size
5. Generate preview
6. Download image or save directly to server

---

## File Storage

Generated images are stored automatically under:

`/images/YYYY/MM/`

Example:

`/images/2026/05/`

Folders are created automatically when needed.

---

## Designed For

Ideal for:

- Joomla news portals
- Editorial websites
- Magazine publishers
- Blog networks
- High-traffic publishing environments
- Fast newsroom editorial workflows

---

## Performance Notes

Built for lightweight administrator use.

Highlights:

- no frontend overhead
- fast image generation workflow
- optimized JPG output
- automatic cleanup of temporary preview files
- safe source image size limits
- minimal administrator complexity

---

## Security Highlights

- ACL-protected administrator actions
- CSRF token validation
- strict upload validation
- MIME verification
- image integrity checks
- temporary file cleanup
- safe filename sanitization
- GPL-compliant source headers for JED readiness

---

## Joomla Native Updates

DevArt Article Photo supports Joomla native updates through GitHub.

Update server:

`https://raw.githubusercontent.com/devartgr/joomla-devart-articlephoto/main/update.xml`

After installation:

`System → Extensions → Update`

---

## Compatibility

Supported:

- Joomla 6.x
- PHP 8.2+
- PHP 8.3
- PHP 8.4
- Modern Joomla MVC architecture

Not supported:

- Joomla 3
- Joomla 4
- Joomla 5
- Legacy PHP versions

---

## Current Version

**1.0.3**

---

## Changelog 1.0.3

- Added missing GPL PHP file headers for Joomla Extensions Directory compliance
- Added enhanced MIME validation using `finfo_file()`
- Added dual upload verification workflow
- Improved upload hardening
- Improved production security
- Improved JED submission readiness
- Improved PHP 8.4 compatibility consistency

---

## Production Notes

Recommended usage:

- Use optimized JPG output for article publishing
- Keep source images within reasonable size limits
- Test watermark/logo overlays before production use
- Always validate workflows on staging before deployment

---

## Disclaimer / Limitation of Liability

This software is provided "as is", without warranty of any kind.

DevArt shall not be held liable for any damages, data loss, downtime, security issues, or other problems resulting from the use or misuse of this software.

Users are responsible for testing the software in their own environment and maintaining proper backups before installation or upgrades.

Always test on a staging environment before using in production.

---

## Author

**Stathopoulos Kostas – DevArt**  
https://devart.gr

GitHub Repository:

https://github.com/devartgr/joomla-devart-articlephoto

---

## License

GNU General Public License v3 or later
