# Excellence College Website

A modern, 3D-themed college website built with Python Flask, featuring a black background with white and red color scheme.

## Features

- **3D Visual Effects**: Interactive 3D cards and image transformations
- **Modern Design**: Black background with white and red accents
- **Responsive Layout**: Works on desktop, tablet, and mobile devices
- **Smooth Animations**: CSS animations and JavaScript interactions
- **College Information Sections**:
  - Hero section with call-to-action
  - About the college
  - Academic programs
  - Facilities
  - Contact information

## Installation

1. Install Python dependencies:
```bash
pip install -r requirements.txt
```

2. Add your college photographs to `static/images/`:
   - `college1.jpg` (for hero section)
   - `college2.jpg` (for about section)
   - `college3.jpg` (for facilities section)

## Running the Application

Start the Flask development server:

```bash
python app.py
```

The website will be available at `http://localhost:5000`

## Project Structure

```
pro/
├── app.py                 # Flask application
├── requirements.txt       # Python dependencies
├── templates/
│   └── index.html        # Main HTML template
├── static/
│   ├── css/
│   │   └── style.css    # Stylesheet with 3D effects
│   ├── js/
│   │   └── script.js    # JavaScript for interactions
│   └── images/          # College photographs (add your images here)
└── README.md
```

## Customization

- Edit `templates/index.html` to modify content
- Update `static/css/style.css` to change colors and styling
- Modify `static/js/script.js` for different interactions
- Replace placeholder images in `static/images/` with your college photographs

## Color Scheme

- Background: Black (#000000)
- Primary Accent: Red (#ff0033)
- Text: White (#ffffff)
- Secondary Text: Light Gray (#cccccc)
