# LX Library Terms of Service Repository

This repository hosts the Terms of Service documentation and viewer for LX Library (Pty) Ltd. It provides a versioned, accessible way to view our terms of service through a modern web interface.

## Overview

The repository contains:
- Terms of Service documents in PDF format
- A web-based viewer implementation
- Version tracking for all TOS updates

## Structure

```
├── index.html          # Web viewer interface
├── tos/               
│   └── tos-v1.0.0.pdf  # Current TOS version
```

## Viewing the Terms of Service

The Terms of Service can be viewed in two ways:
1. Directly through our hosted page at [https://lxlibrary.github.io/tos](https://lxlibrary.github.io/tos)
2. By accessing specific versions using URL parameters
    - Example: `https://lxlibrary.github.io/tos?version=v1.0.0`
    - When using a version parameter, the version selector will be hidden

## Implementation Details

- Built using PDF.js for reliable PDF rendering
- Supports direct version linking via URL parameters
- Implements version control for TOS documents
- Responsive design for all devices
- Minimal dependencies for maximum reliability

## Version History

- v1.0.0 - Initial Terms of Service release

## License

This repository is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries regarding this repository or our Terms of Service:

**LX Library (Pty) Ltd**  
Keagan Gilmore  
Email: keagangilmore@gmail.com  
Tel: +27 83 510 7047

---
© 2024 LX Library (Pty) Ltd. All rights reserved.