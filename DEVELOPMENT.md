# Development Guide

## Setup

1. Clone the repository
2. Open `index.html` in your browser

That's it! No build tools or dependencies required.

## Running Locally

### Using Python (Recommended)
If you want to serve the files over HTTP:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

### Using Node.js
If you have Node.js installed:
```bash
npx http-server
```

### Direct File Opening
Simply open `index.html` directly in your browser (the app will work with `file://` protocol).

## File Structure

```
├── index.html      - Main HTML file with structure
├── style.css       - All styling and responsive design
├── script.js       - Vanilla JavaScript logic
├── README.md       - Project documentation
├── CONTRIBUTING.md - Contribution guidelines
├── CODE_OF_CONDUCT.md - Community guidelines
├── SECURITY.md     - Security policy
├── LICENSE         - MIT License
├── CHANGELOG.md    - Version history
└── .github/        - GitHub-specific files
    ├── ISSUE_TEMPLATE/
    ├── workflows/
    └── pull_request_template.md
```

## Making Changes

1. Edit the HTML/CSS/JS files as needed
2. Open `index.html` in your browser to test
3. Check across different browsers for compatibility
4. Commit and push your changes

## Testing

Test your changes across:
- Chrome/Chromium
- Firefox
- Safari
- Edge

Ensure responsive design works on:
- Desktop (1920px+)
- Tablet (768px-1024px)
- Mobile (320px-480px)

## Browser DevTools

Use browser DevTools to:
- Test responsive design
- Check console for errors
- Inspect localStorage data
- Debug JavaScript
