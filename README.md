# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. This portfolio showcases your skills, projects, and professional information in an elegant and interactive design.

## Features

- **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, hover effects, and form validation
- **Mobile-First**: Optimized for mobile devices with hamburger navigation
- **Accessibility**: Built with accessibility best practices
- **Cross-Browser Compatible**: Works on all modern browsers

## Sections Included

1. **Header**: Navigation with your name and tagline
2. **Hero Section**: Eye-catching introduction with call-to-action buttons
3. **About Section**: Personal information with statistics
4. **Skills Section**: Visual representation of your technical skills
5. **Projects Section**: Showcase of your work with project details
6. **Resume Section**: Download link for your resume
7. **Contact Section**: Contact form and contact information
8. **Footer**: Additional links and copyright information

## Getting Started

### 1. Download and Setup

1. Download all files to your local machine
2. Open `index.html` in your web browser to preview
3. Customize the content to match your information

### 2. Customization Guide

#### Personal Information
- **Name**: Replace "Your Name" throughout the HTML file
- **Tagline**: Update the tagline in the header and hero section
- **About Text**: Modify the bio in the About section
- **Contact Details**: Update email, phone, and location information

#### Profile Images
- Replace the placeholder icons with your actual profile photos
- Update the `src` attributes in the HTML
- Recommended image sizes:
  - Hero profile: 300x300px
  - About section: 250x250px
  - Project images: 400x200px

#### Skills
- Modify the skill names and percentages in the HTML
- Update the `style="width: X%"` attributes for skill bars
- Add or remove skill categories as needed

#### Projects
- Replace the sample projects with your actual work
- Update project titles, descriptions, and technologies used
- Add real project images and links
- Modify the number of project cards as needed

#### Resume
- Replace the resume download link with your actual PDF file
- Update the resume filename in the download button

#### Social Links
- Update the social media links in the contact section
- Modify the social media platforms as needed

### 3. File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── README.md           # This file
└── assets/             # Create this folder for images
    ├── profile.jpg     # Your profile photo
    ├── project1.jpg    # Project screenshots
    ├── project2.jpg
    └── project3.jpg
```

### 4. Adding Your Images

1. Create an `assets` folder in your portfolio directory
2. Add your profile photos and project images
3. Update the HTML to reference your actual image files
4. Ensure images are optimized for web (compressed, appropriate dimensions)

## Customization Examples

### Changing Colors
The main color scheme uses CSS custom properties. You can modify the colors in `styles.css`:

```css
/* Primary colors */
--primary-color: #667eea;
--secondary-color: #764ba2;
--accent-color: #ffd89b;
```

### Adding New Sections
To add a new section, follow this pattern:

```html
<section id="new-section" class="new-section">
    <div class="container">
        <h2 class="section-title">New Section Title</h2>
        <!-- Your content here -->
    </div>
</section>
```

### Modifying Animations
Animation speeds and effects can be adjusted in the CSS:

```css
/* Animation duration */
transition: all 0.3s ease;

/* Animation delay */
animation-delay: 0.2s;
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## Performance Tips

1. **Optimize Images**: Compress images before uploading
2. **Minimize CSS/JS**: Consider minifying files for production
3. **Use WebP**: Convert images to WebP format for better compression
4. **Lazy Loading**: Implement lazy loading for project images if you have many

## Deployment

### GitHub Pages
1. Push your portfolio to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your portfolio will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your portfolio folder to Netlify
2. Your site will be deployed automatically
3. Customize the domain name in Netlify settings

### Vercel
1. Connect your GitHub repository to Vercel
2. Deploy automatically on every push
3. Get a custom domain and SSL certificate

## Troubleshooting

### Common Issues

1. **Images not displaying**: Check file paths and ensure images exist
2. **Styles not loading**: Verify CSS file is in the same directory
3. **JavaScript not working**: Check browser console for errors
4. **Mobile menu not working**: Ensure JavaScript file is properly linked

### Debug Mode
Open browser developer tools (F12) to:
- Check for JavaScript errors
- Inspect CSS styles
- Test responsive design
- Validate HTML structure

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio:
1. Check the browser console for errors
2. Review the HTML structure
3. Verify all file paths are correct
4. Test in different browsers

## Future Enhancements

Consider adding these features to make your portfolio even better:
- Blog section
- Testimonials from clients/colleagues
- Portfolio filtering by category
- Dark/light theme toggle
- Multi-language support
- Analytics integration
- SEO optimization

---

**Happy coding! 🚀**

Your portfolio is now ready to showcase your skills and impress potential employers or clients. Remember to keep it updated with your latest projects and achievements! 