# Gumroad WordPress Integration

A WordPress plugin/script that seamlessly integrates Gumroad product listings into WordPress posts using custom meta fields and embedded buy buttons.

## Overview

This project provides a JavaScript solution for WordPress bloggers and content creators to easily sell digital products through Gumroad without leaving their WordPress site. It creates styled buy buttons that display Gumroad products in a shadow box overlay.

## Features

- **Easy Integration**: Works with WordPress post meta fields
- **Custom Buttons**: Display Gumroad buy buttons with custom labels
- **Shadow Box Display**: Products appear in an elegant overlay when customers click
- **Minimal Setup**: Requires only button label and Gumroad link in post metadata

## How It Works

The script reads two custom fields from WordPress post metadata:

1. **Button Field** - The text displayed on the buy button
2. **Link Field** - The Gumroad product URL

When a visitor clicks the button, it displays the Gumroad product in an overlay window.

## Installation

1. Add `gumroad.html` script to your WordPress theme or use as a plugin
2. Add the script reference to your WordPress post template or header
3. In your WordPress post, add custom fields:
   - Field 1: Button label (e.g., "Buy Now: $9.99")
   - Field 2: Gumroad link (e.g., "//gumroad.com/your-product")

## Usage

Once installed, the script will automatically:
- Read your custom post meta fields
- Parse the button label and Gumroad link
- Inject a buy button into your post content
- Load the Gumroad widget on click

## Requirements

- WordPress installation
- jQuery (included in most WordPress themes)
- Gumroad product URL

## Technical Details

- **Language**: JavaScript
- **Dependencies**: jQuery, Gumroad.js API
- **Target**: WordPress post content divs

## License

See LICENSE file for details.

## Contributing

Contributions are welcome! Feel free to fork and submit pull requests.

---

**Last Updated**: July 2013
