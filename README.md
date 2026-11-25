# Personal Resume Website

A modern, responsive resume website built with HTML5 and CSS3. This website showcases my professional experience, skills, and projects in a clean and organized layout.

## Features

- Responsive design that works on all devices
- Modern and clean user interface
- Organized sections for experience, skills, and projects
- Light and dark themes, plus a print stylesheet for saving as PDF
- Google Fonts (Noto Sans, Noto Serif, Noto Serif Armenian)

## Technologies Used

- HTML5
- CSS3
- Google Fonts
- Responsive Design principles

## Setup

1. Clone the repository
2. Open `index.html` in your browser
3. Customize the content in `index.html` with your information
4. Modify styles in `styles.css` as needed

## Updating

- The header examples are a JSON list near the end of `index.html`. Each `output` is a recorded Grich-S output; the page works out which marks were added.
- `Artush_Habetyan_CV.pdf` is the page printed to A4. After editing the page, regenerate it:

```bash
google-chrome --headless=new --no-pdf-header-footer --virtual-time-budget=8000 \
  --print-to-pdf=Artush_Habetyan_CV.pdf "file://$PWD/index.html"
```

## Contact

For any questions or suggestions, please reach out through the contact information provided in the resume.
