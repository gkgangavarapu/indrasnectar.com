# Indra's Nectar Website

A beautiful, responsive website for Indra's Nectar brand, inspired by the mythology of Lord Indra from Indian mythology.

## Website Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Elegant fade-in effects and smooth scrolling
- **Interactive Elements**: Hover effects, form validation, and notifications
- **Mythology Content**: Information about Lord Indra, Amrita, and Samudra Manthan
- **Modern Design**: Clean, professional layout with divine color scheme

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- No external dependencies

## Deployment on GitHub Pages

### Method 1: Simple Deployment (Recommended)

1. **Create a GitHub Repository**
   - Go to [GitHub.com](https://github.com) and create a new repository named `indrasnectar.com` or similar

2. **Upload Files**
   - Upload all the files from this project to your repository
   - Make sure `index.html` is in the root directory

3. **Enable GitHub Pages**
   - Go to your repository settings
   - Scroll down to "GitHub Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose the `main` branch and `/ (root)` folder
   - Click "Save"

4. **Configure Custom Domain** (for indrasnectar.com)
   - In the GitHub Pages section, add your custom domain `indrasnectar.com`
   - Create a `CNAME` file in your repository with the content: `indrasnectar.com`
   - Update your DNS settings with your domain provider:
     - Create a `CNAME` record pointing to `yourusername.github.io`
     - Or create `A` records pointing to GitHub's IP addresses:
       - 185.199.108.153
       - 185.199.109.153
       - 185.199.110.153
       - 185.199.111.153

### Method 2: Using Git Commands

```bash
# Clone your repository (replace with your repo URL)
git clone https://github.com/yourusername/indrasnectar.com.git

# Navigate to the project directory
cd indrasnectar.com

# Add all files
git add .

# Commit changes
git commit -m "Initial website deployment"

# Push to GitHub
git push origin main
```

Then follow steps 3 and 4 from Method 1.

## File Structure

```
indrasnectar/
├── index.html          # Main website file
├── styles.css          # All styling and responsive design
├── script.js           # Interactive functionality
├── README.md           # This file
└── CNAME              # Custom domain configuration (create this)
```

## Local Development

To run the website locally:

1. **Simple Method**: Open `index.html` in your web browser
2. **Using Local Server** (recommended for testing):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```
   Then visit `http://localhost:8000` in your browser

## Customization

### Colors
The website uses a divine color scheme:
- Primary Purple: `#8e44ad`
- Secondary Purple: `#9b59b6`
- Gradient Background: `#667eea` to `#764ba2`

### Content
You can easily update:
- Text content in `index.html`
- Styling in `styles.css`
- Interactive features in `script.js`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For questions about deployment or customization, please contact:
- Email: info@indrasnectar.com
- Website: indrasnectar.com

---

**Note**: This is a static website optimized for GitHub Pages hosting. All functionality works without server-side processing.
