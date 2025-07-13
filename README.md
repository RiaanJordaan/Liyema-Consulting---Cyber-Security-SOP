# Liyema Consulting - Cyber Security SOP

A comprehensive cyber security Standard Operating Procedures (SOP) website providing essential guidelines and best practices for organizations.

## How to Use This Repository

### 🌐 Accessing the Website

This is a static HTML website that can be accessed in multiple ways:

#### Option 1: Direct File Access
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/RiaanJordaan/Liyema-Consulting---Cyber-Security-SOP.git
   ```
2. Navigate to the project directory
3. Open `index.html` in your web browser

#### Option 2: Web Server
For the best experience, serve the files through a web server:
```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

### 📚 Website Content Structure

The website contains six main Standard Operating Procedure sections:

1. **Business Continuity Plan** (`page1.html`)
   - Alternative working premises
   - Hybrid working models
   - Meeting schedules and protocols

2. **System Security** (`page2.html`)
   - System security protocols and procedures
   - Security implementation guidelines

3. **Cyber Security Basics** (`page3.html`)
   - Fundamental cyber security concepts
   - Essential security practices

4. **Cyber Security Awareness** (`page4.html`)
   - Training and awareness programs
   - Security culture development

5. **System Backup & Recovery** (`page5.html`)
   - Backup procedures and schedules
   - Disaster recovery protocols

6. **System Support** (`page6.html`)
   - Technical support procedures
   - System maintenance guidelines

### 🧭 Navigation

- **Home Page**: `index.html` - Central navigation hub with links to all SOP sections
- **Navigation Links**: Each page includes "Home", "Next Page", and "Previous Page" links
- **Responsive Design**: The website adapts to different screen sizes (mobile-friendly)

### 🎨 Customization

#### Styling
- Main stylesheet: `css/styles.css`
- Uses Bootstrap 3.4.1 for additional styling
- Dark theme with aquamarine accents
- Responsive design with mobile breakpoints

#### Images
- Logo: `images/liyema_logo.png`
- Background: `images/background_image.jpg`
- Content images: `images/pic1.png` through `images/pic39.jpg`

#### Modifying Content
1. Edit HTML files directly to update content
2. Add new images to the `images/` directory
3. Update CSS in `css/styles.css` for styling changes
4. Maintain the existing navigation structure when adding new pages

### 📱 Mobile Compatibility

The website includes responsive CSS media queries that optimize the layout for:
- Desktop computers
- Tablets
- Mobile phones (600px and below)

### 🔧 Technical Requirements

- **Browser**: Any modern web browser (Chrome, Firefox, Safari, Edge)
- **Server**: Optional - any static file server for optimal performance
- **Dependencies**: Bootstrap 3.4.1 (loaded via CDN)

### 📄 File Structure
```
├── README.md           # This documentation
├── index.html          # Main navigation page
├── page1.html          # Business Continuity Plan
├── page2.html          # System Security
├── page3.html          # Cyber Security Basics
├── page4.html          # Cyber Security Awareness
├── page5.html          # System Backup & Recovery
├── page6.html          # System Support
├── css/
│   └── styles.css      # Main stylesheet
└── images/             # All website images
    ├── liyema_logo.png
    ├── background_image.jpg
    └── pic*.png/jpg/gif
```

### 🤝 Contributing

To contribute to this cyber security SOP repository:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test the website locally
5. Submit a pull request

### 📞 Support

For questions about using this repository or the cyber security SOPs contained within, please refer to the System Support section (`page6.html`) or contact Liyema Consulting directly.

---

**Note**: This repository contains Standard Operating Procedures for cyber security. Please ensure you understand and follow your organization's specific security policies and procedures in addition to these general guidelines.