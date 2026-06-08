# InAmigos Foundation - Awareness Webpage

## Project Overview
This is a professional awareness webpage for **InAmigos Foundation**, an NGO dedicated to spreading hope and building futures across India through collective action.

## Project Structure

```
ngo-awareness-webpage/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── images/             # Folder for images and visuals
├── assets/             # Additional assets folder
├── README.md           # Project documentation
└── CONTENT.md          # Content references and sources
```

## Webpage Sections

### 1. **Navigation Bar**
   - Logo with foundation name
   - Quick navigation links to all sections
   - Sticky positioning for easy access

### 2. **Hero Section**
   - Compelling headline: "Collective Action for Social Change"
   - Call-to-action button
   - Professional gradient background

### 3. **About Section**
   - Foundation introduction
   - Certifications and recognition
   - Key statistics (50,000+ beneficiaries, 200+ volunteers, 28 states)

### 4. **Projects Section** (6 Core Initiatives)
   - **Sewa**: Food & Clothing Assistance
   - **Bachpanshala**: Educational Access
   - **Jeev**: Animal Welfare
   - **Udaan**: Women Empowerment
   - **Prakriti**: Environmental Conservation
   - **Vikas**: Employment Readiness

### 5. **Impact Section**
   - Social impact statistics
   - Focus areas
   - Communities served

### 6. **Call-to-Action Section**
   - Volunteer opportunity
   - Donation option
   - Awareness spreading
   - Links to official website and social media

### 7. **Footer**
   - Organization information
   - Quick links
   - Social media links
   - Contact details
   - Copyright

## Features

✅ **Responsive Design** - Works on desktop, tablet, and mobile  
✅ **Modern UI** - Clean, professional, and attractive design  
✅ **Accessibility** - Proper semantic HTML structure  
✅ **Performance** - Lightweight CSS with no external dependencies  
✅ **Smooth Animations** - Hover effects and transitions  
✅ **SEO Friendly** - Proper meta tags and structure  

## Color Scheme

- **Primary**: #2563eb (Professional Blue)
- **Secondary**: #1e40af (Darker Blue)
- **Accent**: #f59e0b (Warm Orange)
- **Background**: #f8fafc (Light Gray)
- **Text**: #1f2937 (Dark Gray)

## How to Use

### Method 1: Open in Browser
1. Locate the `index.html` file
2. Double-click it to open in your default browser
3. The page will load with all styling applied

### Method 2: Using a Local Server (Recommended)
1. Open Command Prompt or Terminal
2. Navigate to the project folder:
   ```bash
   cd path/to/ngo-awareness-webpage
   ```
3. Start a simple HTTP server:
   - **Python 3.x**:
     ```bash
     python -m http.server 8000
     ```
   - **Python 2.x**:
     ```bash
     python -m SimpleHTTPServer 8000
     ```
   - **Node.js (if http-server is installed)**:
     ```bash
     http-server
     ```
4. Open your browser and go to `http://localhost:8000`

## Adding Images

To add images to the webpage:

1. **Save images** in the `images/` folder
2. **Reference images** in the HTML by updating the `style` or adding `<img>` tags:
   ```html
   <img src="images/your-image.jpg" alt="Description">
   ```

## Content Sources

- **Official Website**: https://inamigosfoundation.org.in/
- **Social Media**: Search #InAmigos on social platforms
- **Information Used**:
  - NGO mission and values
  - Six project details
  - Impact statistics
  - Certifications and recognition
  - Community reach (28 states, 50,000+ beneficiaries)

## Customization Tips

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;      /* Change primary color */
    --accent-color: #f59e0b;        /* Change accent color */
    /* ... other colors ... */
}
```

### Modify Fonts
Update the `font-family` in the `body` style section:
```css
body {
    font-family: 'Your Font Name', fallback-font;
}
```

### Adjust Layout
Modify `grid-template-columns` values for project cards and other sections

## Browser Compatibility

✓ Chrome/Chromium  
✓ Firefox  
✓ Safari  
✓ Edge  
✓ Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Notes

- **Page Load**: Fast (no external dependencies)
- **Optimization**: CSS is minifiable if needed
- **Images**: Add compressed images to `images/` folder for best performance

## Next Steps

1. ✅ Add actual project images to the `images/` folder
2. ✅ Update social media links in the footer
3. ✅ Customize colors to match brand guidelines
4. ✅ Deploy to a web hosting service
5. ✅ Submit for evaluation

## File Sizes

- `index.html`: ~12 KB
- `styles.css`: ~15 KB
- **Total (HTML + CSS)**: ~27 KB (without images)

## Support & Maintenance

For updates, additional content, or modifications:
- Review the official InAmigos website for latest information
- Check social media for recent campaigns
- Update project details as new initiatives launch

---

**Created**: 2026  
**Foundation**: InAmigos Foundation  
**Website**: https://inamigosfoundation.org.in/
