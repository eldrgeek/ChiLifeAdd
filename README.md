# Chi Life Movement - Ad Portfolio

A responsive portfolio website showcasing ad campaigns for Chi Life Movement.

## Features

- Responsive design that works on all devices
- Interactive ad previews with iframe embedding
- Modern gradient background and clean styling
- Auto-refreshing development server

## Development

### Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server with auto-refresh:
   ```bash
   npm run dev
   ```
   This will start the server on `http://localhost:5173` and automatically open your browser. The page will automatically refresh whenever you make changes to any files.

3. For production server (without auto-refresh):
   ```bash
   npm start
   ```
   This starts the server on `http://localhost:8000` without opening the browser.

### Building for Production

```bash
npm run build
```
This creates a `dist/` folder with all the production files.

## Project Structure

```
ChiLifeAdd/
├── index.html              # Main portfolio page
├── ads/                    # Ad content files
│   ├── ad1-face-lifes-challenges.md
│   └── ad2-right-path-to-wellness.md
├── designs/                # Ad design files
│   └── ad1-design1.html
├── images/                 # Image assets
│   └── Tai Chi.jpg
└── dist/                  # Built files (generated)
```

## Development Server Features

- **Auto-refresh**: The development server automatically refreshes your browser when you save changes
- **Live reload**: Works with HTML, CSS, JavaScript, and all other static files
- **Port configuration**: Runs on port 5173 by default, configurable in package.json
- **Cross-platform**: Works on Windows, macOS, and Linux

## Making Changes

When you edit any file in the project, the browser will automatically refresh to show your changes. This includes:
- HTML files (index.html, design files)
- CSS styles (embedded or external)
- JavaScript files
- Image files
- Markdown content

No manual refresh needed!
