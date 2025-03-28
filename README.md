# English Optics - Custom Error Page

## Overview
This repository contains the custom error page that is displayed when the English Optics website is offline. The page is designed to inform visitors that the site is temporarily unavailable while we're training our AI models.

## Purpose
At English Optics, we regularly train our AI models to improve our services. During these training periods, our main website may be temporarily offline. Rather than showing a generic error message, this custom page provides a more professional and informative experience for our visitors.

## Implementation
This page is served through Cloudflare Workers when our main site is unavailable. The Worker detects when our origin server is unreachable and automatically redirects visitors to this custom error page.

## Files
- `EO_404.html` - The main error page
- `/css` - Stylesheet directory
- `/js` - JavaScript directory
- `/images` - Image assets
- `/fonts` - Custom fonts

## Maintenance
To update the error page, simply modify the files in this repository and commit the changes. The changes will be automatically reflected when the page is displayed.

## Contact
For any questions or concerns regarding this repository, please contact:
hello-world@english-optics.com

---
© 2025 English Optics | All Rights Reserved
