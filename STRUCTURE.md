# Project Structure Guide

## Directory Tree

```
ngo-awareness-webpage/
│
├── 📄 index.html                 # Main webpage file
├── 🎨 styles.css                 # CSS styling
├── 📖 README.md                  # Project documentation
├── 📋 CONTENT.md                 # Content sources & references
├── 📐 STRUCTURE.md               # This file
│
├── 📁 images/                    # Images and visuals folder
│   ├── logo.png                  # NGO logo
│   ├── hero-banner.jpg           # Hero section background
│   ├── project-sewa.jpg          # Sewa project image
│   ├── project-bachpanshala.jpg  # Bachpanshala project image
│   ├── project-jeev.jpg          # Jeev project image
│   ├── project-udaan.jpg         # Udaan project image
│   ├── project-prakriti.jpg      # Prakriti project image
│   ├── project-vikas.jpg         # Vikas project image
│   ├── team.jpg                  # Team/volunteer photo
│   ├── community.jpg             # Community impact image
│   └── [other images]/           # Additional visuals
│
└── 📁 assets/                    # Additional assets folder
    ├── documents/                # PDF documents, reports
    ├── videos/                   # Video files (embedded links)
    └── data/                     # Data files, statistics

```

## File Descriptions

### HTML File
**`index.html`**
- Single-page HTML file with all sections
- Semantic HTML structure
- Meta tags for SEO
- Responsive viewport settings
- Internal links to all sections

### CSS File
**`styles.css`**
- Global styles and variables
- Component-specific styling
- Responsive breakpoints (768px, 480px)
- Print styles
- No external dependencies

### Documentation Files

**`README.md`**
- Project overview
- Features description
- How to use the webpage
- Customization guide
- Browser compatibility

**`CONTENT.md`**
- Content sources and references
- Information verification
- Hashtag research guide
- Update schedule

**`STRUCTURE.md`**
- Directory structure
- File descriptions
- Image guidelines
- Folder organization

## Images Folder Organization

### Recommended Images (12-15 total)

| Filename | Purpose | Dimensions | Format |
|----------|---------|-----------|--------|
| logo.png | Navigation bar | 200x100px | PNG |
| hero-banner.jpg | Hero section bg | 1400x600px | JPG |
| project-*.jpg | Project cards (6 images) | 400x300px | JPG |
| team.jpg | Team/volunteer photo | 800x500px | JPG |
| community.jpg | Community impact | 800x500px | JPG |
| event-*.jpg | Event photos | 600x400px | JPG |

### Image Guidelines
- ✅ **Format**: JPG for photos, PNG for logos/icons
- ✅ **Resolution**: 72-150 DPI for web
- ✅ **Size**: Compress for fast loading (< 200KB each)
- ✅ **Dimensions**: 16:9 aspect ratio for consistency
- ✅ **Optimization**: Use tools like TinyPNG or ImageOptim

## Assets Folder Organization

### documents/
- Impact reports
- Annual reports
- Project documentation
- Certifications

### videos/
- YouTube links for embedding
- Project showcase videos
- Volunteer testimonials
- Event coverage

### data/
- Statistics JSON files
- Impact metrics
- Beneficiary data (anonymized)
- Geographic reach data

## How to Integrate Images

### Step 1: Add Images to Folder
Place all images in the `images/` subfolder

### Step 2: Reference in HTML
```html
<!-- Hero section background (in CSS) -->
background: url('../images/hero-banner.jpg');

<!-- Project card image -->
<img src="images/project-sewa.jpg" alt="Sewa project - Food assistance">

<!-- Team photo -->
<img src="images/team.jpg" alt="InAmigos volunteers and team">
```

### Step 3: Update CSS
```css
.hero {
    background-image: url('../images/hero-banner.jpg');
    background-size: cover;
    background-position: center;
}
```

## File Organization Best Practices

### Do's ✅
- Use clear, descriptive filenames
- Organize by category (images, assets, etc.)
- Keep related files together
- Use lowercase with hyphens (hero-banner.jpg)
- Maintain consistent image sizes

### Don'ts ❌
- Don't use spaces in filenames
- Don't mix image formats unnecessarily
- Don't store large files in root
- Don't use special characters in names
- Don't create unnecessary subdirectories

## Total File Count

```
Summary:
├── HTML Files: 1 (index.html)
├── CSS Files: 1 (styles.css)
├── Documentation: 3 (README.md, CONTENT.md, STRUCTURE.md)
├── Images: 12-15 (to be added)
└── Assets: 3+ subfolders (optional)

Total: 4 core files + 3 docs + images folder
```

## Performance Optimization

### HTML/CSS
- ✅ No external CSS frameworks
- ✅ Minimal CSS file size (~15KB)
- ✅ No JavaScript required
- ✅ Pure HTML & CSS

### Images
- ✅ Compress all images before adding
- ✅ Use responsive images
- ✅ Lazy loading recommended
- ✅ CDN recommended for deployment

## Deployment Checklist

Before uploading to web server:
- [ ] All images added to `images/` folder
- [ ] File paths verified
- [ ] Links updated (social media, donation pages)
- [ ] Mobile responsiveness tested
- [ ] All sections complete
- [ ] Spelling and grammar checked
- [ ] Images compressed
- [ ] Cross-browser testing done

---

**Last Updated**: June 2026  
**Next Review**: When adding images or new sections
