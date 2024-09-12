# Gutenberg Inner Blocks Example

This is a custom WordPress Gutenberg block created as a part of learning Gutenberg block development using ReactJS. The block includes Inner Blocks to demonstrate how to allow nested content in your custom blocks.

## Features

- Custom Gutenberg block with support for inner blocks.
- Users can add and customize child blocks within the main block.
- Fully compatible with the WordPress Block Editor (Gutenberg).
- Built using modern JavaScript (ES6+), React, and WordPress block editor libraries.

## Installation

1. Clone this repository to your local WordPress setup:
  ```bash
  git clone https://github.com/tekrajbhatta/gutenberg-innerblocks-example.git
  ```
2. Navigate to the plugin folder inside your WordPress installation:
  ```bash
 cd /path/to/wordpress/wp-content/plugins/
  ```
3. Copy the plugin folder into the plugins directory:
  ```bash
  cp -r /path/to/gutenberg-innerblocks-example gutenberg-innerblocks-example
  ```
4. Activate the plugin via the WordPress Admin dashboard:

   - Go to `Plugins > Installed Plugins`.
   - Find **Gutenberg Inner Blocks Example** and click **Activate**.

## Usage

1. Once the plugin is activated, go to the block editor of any post or page.
2. Search for the "Inner Blocks Example" block.
3. Add the block to the editor, and then you can insert inner blocks within it.
4. Customize the inner blocks as needed.

## Development

### Prerequisites

- WordPress development environment (local or remote).
- Node.js and npm installed.

### Build

To work on the plugin locally, follow these steps:

1. Install dependencies:
  ```bash
  npm install
  ```
2. Build the block:
  ```bash
  npm run build
  ```
3. If you're making changes, use the following command to watch for file changes and rebuild automatically:
  ```bash
  npm run build
  ```

## File Structure
  ```bash
    gutenberg-innerblocks-example/
  ├── build/               # Compiled block assets (JS/CSS)
  ├── src/                 # Source code for the block
  │   ├── block.js         # Block registration and logic
  │   ├── editor.js        # Editor-side JavaScript
  │   ├── style.scss       # Editor styles
  ├── gutenberg-innerblocks-example.php # Main plugin file
  ├── package.json         # Node.js dependencies and scripts
  ├── webpack.config.js    # Webpack configuration
  └── README.md            # Project documentation
  ```

## License

This project is open-source and available under the MIT License.

## Contributing

Feel free to submit pull requests or open issues to improve the project!
