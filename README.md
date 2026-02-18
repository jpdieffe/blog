# Professional Blog

A clean, professional blog website hosted on GitHub Pages featuring sections for blog posts, publications, funded proposals, and engineering consulting services.

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Clean Navigation**: Easy-to-use navigation menu with 4 main sections
- **Professional Styling**: Modern, professional appearance suitable for academic and engineering professionals
- **GitHub Pages Ready**: Pre-configured for deployment on GitHub Pages

## Sections

1. **Blog**: Share insights, experiences, and thoughts
2. **Publications**: Showcase research publications and papers
3. **Funded Proposals**: Highlight successfully funded research projects
4. **Engineering Consulting**: Display consulting services and expertise

## Getting Started

### Deployment on GitHub Pages

1. Create a new repository on GitHub (e.g., `your-username.github.io` or `blog`)
2. Push these files to your repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/your-username/your-repo.git
   git push -u origin main
   ```
3. Go to your repository's Settings > Pages
4. Under "Source", select the branch you want to deploy (usually `main`)
5. Click Save
6. Your site will be published at `https://your-username.github.io/your-repo/`

### Customization

#### Update Content

1. **Home Page** (`index.html`): Edit the hero section and featured content
2. **Blog Posts** (`blog.html`): Add your blog entries
3. **Publications** (`publications.html`): Add your research publications
4. **Funded Proposals** (`funded-proposals.html`): List your funded projects
5. **Consulting** (`consulting.html`): Update services and contact information

#### Customize Styling

- Edit `styles.css` to change colors, fonts, and layout
- The color scheme uses:
  - Primary: `#667eea` (purple-blue)
  - Dark: `#2c3e50`
  - Light background: `#f8f9fa`

#### Update Site Name

Replace "My Blog" in the navigation logo across all HTML files:
```html
<div class="logo">
    <a href="index.html">Your Name</a>
</div>
```

#### Add Your Email

In `consulting.html`, update the contact email:
```html
<a href="mailto:your.email@example.com" class="btn">Contact Me</a>
```

## File Structure

```
blog/
├── index.html              # Home page
├── blog.html               # Blog posts page
├── publications.html       # Publications page
├── funded-proposals.html   # Funded proposals page
├── consulting.html         # Engineering consulting page
├── styles.css              # Global stylesheet
└── README.md               # This file
```

## Technologies Used

- HTML5
- CSS3
- No JavaScript required (pure HTML/CSS implementation)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Feel free to use this template for your own professional website.

## Contributing

This is a personal project template. Feel free to fork and customize for your own use.
