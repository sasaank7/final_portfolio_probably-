# AI Engineer Portfolio - Sasaank Aalla

A modern, responsive portfolio website showcasing AI Engineering projects, skills, and experience.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean and professional design with smooth animations
- **Project Showcase**: Filterable project gallery with categories (ML, DL, NLP, Deployment)
- **Skills Section**: Organized display of technical skills and expertise
- **Contact Section**: Easy-to-access contact information and social links
- **Fast Loading**: Optimized for performance with minimal dependencies

## Quick Start

### View Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/final_portfolio_probably-.git
   cd final_portfolio_probably-
   ```

2. Open `index.html` in your web browser, or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx serve
   ```

3. Visit `http://localhost:8000` in your browser

### Deploy to GitHub Pages

1. Go to your GitHub repository settings
2. Navigate to **Pages** section
3. Under **Source**, select the branch you want to deploy (usually `main`)
4. Click **Save**
5. Your portfolio will be live at `https://yourusername.github.io/final_portfolio_probably-/`

## Customization Guide

### 1. Personal Information

Update the following in `index.html`:

- **Line 8**: Page title
- **Lines 15-16**: Your name in navigation and hero section
- **Lines 28-32**: Hero section introduction text
- **Lines 52-64**: About Me section content
- **Social Links**: Update URLs on lines 37-45 and 222-230

### 2. Contact Information

Replace placeholder contact details:
- **Email**: Search for `your.email@example.com` and replace
- **LinkedIn**: Search for `linkedin.com/in/yourprofile` and replace
- **GitHub**: Search for `github.com/yourusername` and replace

### 3. Projects

Each project card is in the `index.html` file starting around line 145. Update:
- Project title
- Description
- Technologies used
- Metrics/Results
- GitHub repository links
- Demo links (if available)

To add new projects, copy a project card block and modify the details.

### 4. Skills

Update skills in the Skills Section (lines 73-120 in `index.html`):
- Programming Languages
- ML/DL Frameworks
- AI Techniques
- Tools & Technologies

### 5. Resume

Replace `Sasaank_Aalla_Resume.pdf` with your own resume file. Make sure to:
- Keep the same filename, OR
- Update the filename in `index.html` line 34

### 6. Color Scheme

Customize colors in `styles.css` (lines 2-13):
```css
:root {
    --primary-color: #6366f1;      /* Main accent color */
    --secondary-color: #8b5cf6;     /* Secondary accent */
    --dark-bg: #0f172a;             /* Dark background */
    --light-bg: #f8fafc;            /* Light background */
    /* ... other colors */
}
```

### 7. Project Images

Currently using placeholder icons. To add real images:

1. Create an `images/` folder
2. Add your project screenshots
3. Update the project cards in `index.html`:
   ```html
   <div class="project-image">
       <img src="images/your-project-image.jpg" alt="Project Name">
   </div>
   ```

## Project Structure

```
final_portfolio_probably-/
│
├── index.html              # Main HTML file
├── styles.css              # CSS styling
├── script.js               # JavaScript functionality
├── Sasaank_Aalla_Resume.pdf  # Resume PDF
└── README.md               # This file
```

## Technologies Used

- HTML5
- CSS3 (with CSS Variables and Flexbox/Grid)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts

## Features Breakdown

### Navigation
- Fixed navigation bar with smooth scrolling
- Mobile-responsive hamburger menu
- Active link highlighting based on scroll position

### Hero Section
- Eye-catching gradient background
- Call-to-action buttons
- Social media links
- Downloadable resume button

### Projects Section
- Filterable project gallery
- Project cards with hover effects
- Technology tags
- Links to GitHub repos and live demos
- Performance metrics display

### Skills Section
- Categorized skill display
- Icon integration
- Hover animations

### Contact Section
- Multiple contact methods
- Social media integration
- Clean, accessible design

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

1. **Optimize Images**: Compress project images before adding them
2. **Lazy Loading**: For many projects, consider implementing lazy loading
3. **Minimize Dependencies**: Currently using only Font Awesome CDN
4. **Caching**: GitHub Pages automatically handles caching

## SEO Optimization

The portfolio includes:
- Meta description tag
- Semantic HTML5 elements
- Proper heading hierarchy
- Alt text for images (add when using real images)
- Mobile-responsive design

## Accessibility

- Semantic HTML structure
- ARIA labels on social links
- Keyboard navigation support
- Focus states on interactive elements
- Sufficient color contrast

## Future Enhancements

Consider adding:
- [ ] Blog section for technical articles
- [ ] Dark mode toggle
- [ ] Project detail modal/pages
- [ ] Contact form with backend
- [ ] Analytics integration (Google Analytics)
- [ ] Loading animations
- [ ] More interactive demos

## License

This project is open source and available under the MIT License.

## Contact

For questions or suggestions, feel free to reach out:
- Email: your.email@example.com
- LinkedIn: [Your Profile](https://linkedin.com/in/yourprofile)
- GitHub: [@yourusername](https://github.com/yourusername)

---

**Built with passion for AI Engineering** ❤️
