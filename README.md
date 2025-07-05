# Professional Resume Website

A modern, responsive resume website designed specifically for showcasing skills to recruiters during placement drives. Built with clean HTML5, CSS3, and JavaScript.

## 🚀 Features

- **Responsive Design** - Looks great on all devices (mobile, tablet, desktop)
- **Modern UI/UX** - Clean, professional design that impresses recruiters
- **Smooth Animations** - Subtle animations and transitions for better user experience
- **Interactive Elements** - Contact form, smooth scrolling, mobile navigation
- **SEO Optimized** - Proper HTML structure and meta tags
- **Fast Loading** - Optimized performance for quick access
- **Easy Customization** - Simple to update with your information

## 📁 File Structure

```
resume-website/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # Interactive functionality
├── profile-photo.jpg   # Your profile picture
├── project1.jpg        # Project showcase image 1
├── project2.jpg        # Project showcase image 2
├── project3.jpg        # Project showcase image 3
├── resume.pdf          # Your resume PDF
└── README.md           # This file
```

## 🛠️ Quick Setup

1. **Download/Clone** this project to your computer
2. **Replace placeholder content** with your information (see customization guide below)
3. **Add your images** (profile photo and project screenshots)
4. **Upload your resume PDF**
5. **Deploy** to your preferred hosting platform

## ✏️ Customization Guide

### 1. Personal Information

**In `index.html`, update:**

- **Line 7**: Page title (`<title>Your Name - Software Developer</title>`)
- **Line 15**: Navigation logo (`<a href="#home">Your Name</a>`)
- **Line 31**: Hero title (`Hi, I'm <span class="highlight">Your Name</span>`)
- **Line 32**: Professional subtitle
- **Line 33-36**: Hero description
- **Line 42-45**: Social media links
- **Line 49**: Profile photo (`src="profile-photo.jpg"`)

### 2. About Section

**Lines 62-76**: Update the about text with your story, background, and passion for technology.

### 3. Skills Section

**Lines 89-139**: Customize the skills based on your expertise:

- **Programming Languages**: Add/remove languages you know
- **Frameworks & Libraries**: Update with frameworks you've used
- **Databases & Tools**: Modify based on your experience
- **Cloud & DevOps**: Add technologies you're familiar with

### 4. Projects Section

**Lines 144-220**: Replace with your actual projects:

```html
<div class="project-card">
    <div class="project-image">
        <img src="your-project-image.jpg" alt="Project Name">
        <div class="project-overlay">
            <a href="https://your-live-demo-link.com" class="project-link">
                <i class="fas fa-external-link-alt"></i>
            </a>
            <a href="https://github.com/your-username/project-repo" class="project-github">
                <i class="fab fa-github"></i>
            </a>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Brief description of what the project does and its key features.</p>
        <div class="project-tech">
            <span>Tech1</span>
            <span>Tech2</span>
            <span>Tech3</span>
        </div>
    </div>
</div>
```

### 5. Education Section

**Lines 225-269**: Update with your educational background:

- University/College name
- Degree details
- CGPA/Percentage
- Relevant coursework
- Certifications

### 6. Contact Information

**Lines 280-310**: Update your contact details:

- Email address
- Phone number
- Location
- Social media links

## 📸 Adding Images

### Required Images:

1. **profile-photo.jpg** (200x200px recommended)
   - Professional headshot
   - Clear, well-lit photo
   - Neutral background preferred

2. **project1.jpg, project2.jpg, project3.jpg** (800x400px recommended)
   - Screenshots of your projects
   - Clean, clear interface shots
   - Consistent styling across all project images

### Image Optimization Tips:

- Use JPEG for photos, PNG for graphics with transparency
- Compress images to reduce file size (aim for <200KB each)
- Use consistent aspect ratios for project images

## 🎨 Color Customization

The website uses a purple gradient theme. To change colors, update these CSS variables in `styles.css`:

```css
/* Change primary colors around line 45 */
.btn-primary {
    background: linear-gradient(135deg, #your-color1 0%, #your-color2 100%);
}

/* Update highlight color */
.highlight {
    background: linear-gradient(135deg, #your-color1 0%, #your-color2 100%);
}
```

## 🚀 Deployment Options

### Option 1: Netlify (Recommended - Free & Easy)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your `resume-website` folder onto their deploy area
3. Your site is live instantly!
4. Get a custom domain like `yourname.netlify.app`

### Option 2: GitHub Pages (Free)

1. Create a GitHub repository
2. Upload your files
3. Go to repository Settings > Pages
4. Select source branch
5. Your site will be at `yourusername.github.io/repository-name`

### Option 3: Vercel (Free)

1. Go to [vercel.com](https://vercel.com)
2. Connect your GitHub repository
3. Deploy with one click
4. Get automatic HTTPS and global CDN

### Option 4: Traditional Web Hosting

Upload all files to your web hosting provider's public_html or www folder.

## 🔧 Advanced Customization

### Adding New Sections

1. Add HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Update navigation menu if needed
4. Add smooth scrolling in `script.js`

### Form Integration

The contact form currently shows a demo notification. To make it functional:

1. Sign up for a form service like [Formspree](https://formspree.io) or [Netlify Forms](https://www.netlify.com/products/forms/)
2. Replace the form action in `script.js` with your endpoint
3. Update the form submission handling

### Analytics

Add Google Analytics by inserting the tracking code before the closing `</head>` tag in `index.html`.

## 📱 Mobile Optimization

The website is fully responsive and optimized for:

- Mobile phones (320px and up)
- Tablets (768px and up)
- Desktops (1024px and up)
- Large screens (1200px and up)

## 🎯 Tips for Placement Success

1. **Keep it professional** - Use a clean, business-appropriate design
2. **Highlight relevant skills** - Focus on technologies mentioned in job descriptions
3. **Showcase real projects** - Include links to live demos and GitHub repositories
4. **Make it fast** - Recruiters often have limited time
5. **Include contact info** - Make it easy for recruiters to reach you
6. **Mobile-first** - Many recruiters browse on mobile devices
7. **Update regularly** - Keep your projects and skills current

## 🐛 Troubleshooting

### Images not loading?
- Check file names match exactly (case-sensitive)
- Ensure images are in the same folder as `index.html`
- Use supported formats (JPG, PNG, WebP)

### Contact form not working?
- The demo form shows notifications only
- Integrate with a form service for real functionality

### Site not responsive?
- Clear your browser cache
- Test on actual devices, not just browser dev tools

## 📄 License

This template is free to use and modify for personal and commercial purposes.

## 🤝 Support

If you need help customizing this template:

1. Check this README thoroughly
2. Review the code comments in each file
3. Test changes on a local copy first
4. Use browser developer tools for debugging

---

**Good luck with your placements! 🎓**

Remember: A great resume website can set you apart from other candidates and make a lasting impression on recruiters.