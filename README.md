# Personal Website

This is a static personal website built with HTML5 and CSS3, designed to be simple, responsive, and compatible with GitHub Pages.

## Features
- **Responsive Design**: Works on desktops, tablets, and mobile devices.
- **Semantic HTML**: Accessible and SEO-friendly structure.
- **Clean Aesthetics**: Modern typography and layout.

## Files
- `index.html`: The main structure of the site.
- `style.css`: Custom styles for the page.
- `assets/`: Folder containing the profile image and CV.

## How to Preview Locally

To view the website on your local machine, you can use one of the following methods:

### Method 1: Open Directly
Simply double-click `index.html` in your file explorer to open it in your default web browser.

### Method 2: Python (Recommended)
If you have Python installed, run the following command in the root directory:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

### Method 3: Node.js / npm
If you have Node.js installed, you can use `serve`:
```bash
npx serve .
```
Then open the URL provided in the terminal (usually `http://localhost:3000`).

## Customization
- Replace `assets/profile.jpg` with your own photo.
- Replace `assets/cv.pdf` with your actual resume.
- Edit `index.html` to update your name, bio, and project details.
