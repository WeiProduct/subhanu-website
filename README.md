# Subhanu Nath Khanal - Personal Website

A modern, responsive personal website showcasing professional experience, education, and skills for Subhanu Nath Khanal, a Public Policy Professional and Research Analyst.

## 🌐 Live Website

Once deployed, the website will be available at: `https://[your-username].github.io/[repository-name]/`

## ✨ Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Navigation**: Mobile-friendly hamburger menu with smooth scrolling
- **Professional Sections**: 
  - Hero section with contact information
  - Timeline-style education display
  - Experience cards with detailed responsibilities
  - Skills categorization with hover effects
  - Contact section with multiple ways to reach out
- **Performance Optimized**: Fast loading with modern CSS and JavaScript
- **Accessibility**: Built with accessibility best practices
- **Print-Friendly**: Optimized for printing/PDF generation

## 🚀 How to Deploy to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in to your account
2. Click the "+" icon in the top right corner and select "New repository"
3. Name your repository (e.g., `subhanu-website` or `personal-website`)
4. Make sure it's set to **Public** (required for free GitHub Pages)
5. Check "Add a README file" if you want
6. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**
1. Click "uploading an existing file" link on your repository page
2. Drag and drop all the files (`index.html`, `styles.css`, `script.js`, `README.md`)
3. Write a commit message like "Initial website setup"
4. Click "Commit changes"

**Option B: Using Git Commands (if you have Git installed)**
```bash
git clone https://github.com/[your-username]/[repository-name].git
cd [repository-name]
# Copy all website files to this directory
git add .
git commit -m "Initial website setup"
git push origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on the "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

### Step 4: Access Your Website

- GitHub will provide you with a URL like: `https://[your-username].github.io/[repository-name]/`
- It may take a few minutes for the site to be available
- The website will automatically update whenever you make changes to the files

## 📁 File Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization

### Updating Content

To modify the content, edit the `index.html` file:

- **Personal Information**: Update the contact details in the hero section
- **Education**: Modify the timeline items in the education section
- **Experience**: Update the experience cards with new job information
- **Skills**: Add or remove skills in the skills section

### Changing Colors

The main color scheme can be changed in `styles.css`:

- **Primary Color**: Search for `#2563eb` and replace with your preferred color
- **Text Colors**: Modify the color variables in the CSS file
- **Background Colors**: Update the gradient backgrounds as needed

### Adding New Sections

To add new sections:

1. Add the HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Update the navigation menu to include the new section

## 🔧 Technical Details

### Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons for visual enhancement
- **Google Fonts**: Inter font family for typography

### Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+ (limited support)

### Performance Features

- Intersection Observer API for scroll animations
- Lazy loading support for images
- Optimized CSS with minimal render-blocking
- Efficient JavaScript with error handling

## 📱 Mobile Responsive

The website is fully responsive and includes:

- Mobile-first design approach
- Hamburger menu for mobile navigation
- Touch-friendly buttons and links
- Optimized typography for different screen sizes
- Flexible grid layouts

## 🛠️ Local Development

To run the website locally:

1. Download all files to a folder
2. Open `index.html` in your web browser
3. Or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have live-server installed)
   live-server
   ```

## 📧 Contact & Support

If you need help with customization or encounter any issues:

- **Email**: subhanunkhanal@gmail.com or snkhanal@umass.edu
- **Phone**: 413-466-1600

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🎯 Future Enhancements

Potential improvements for the website:

- [ ] Add a blog section
- [ ] Include project portfolio
- [ ] Add testimonials section
- [ ] Integrate contact form with backend
- [ ] Add dark mode toggle
- [ ] Include analytics tracking
- [ ] Add language switcher
- [ ] Include downloadable PDF resume

---

**Note**: Remember to keep your contact information updated and review the content regularly to ensure it reflects your current professional status.

Happy coding! 🚀 