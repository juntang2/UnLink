# UnLink

A privacy-first, native Android application that removes tracking parameters from URLs locally on the device. It features a clean, modern UI built with Jetpack Compose, system sharing integrations, local history tracking, bulk cleaning, and local QR code generation.

## Features
- **Local Link Cleaning:** Removes tracking parameters (like UTM tags, `fbclid`, `gclid`, etc.) natively on your device without sending your browsing history to a server.
- **Short Link Expansion:** Safely follows redirects to expand short links (like `bit.ly` or `youtu.be`) before cleaning them.
- **History Tracking:** Maintains a local history of cleaned URLs with search, favorites, and swipe-to-delete functionality.
- **Bulk Mode:** Clean multiple URLs simultaneously.
- **Modern UI:** Built with Jetpack Compose, supporting Light mode, Dark mode, and Material You / Dynamic Color.
- **System Integrations:** Seamlessly handle incoming shared links, share cleaned URLs to other apps, and generate QR codes locally.

## Credit
The core link cleaning logic and parameter rules for this project are based on the open-source project [corbindavenport/link-cleaner](https://github.com/corbindavenport/link-cleaner).

## License
This project is licensed under the GNU General Public License v3.0 (GPL-3.0). See the [LICENSE](LICENSE) file for more details.
