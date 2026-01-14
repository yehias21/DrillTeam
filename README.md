# DrillTeam

Advanced Drilling Operations & Technology

## Overview

DrillTeam is a professional website showcasing expertise in drilling operations, technology, and innovation. The site provides information about advanced drilling techniques, operational excellence, safety practices, and environmental considerations across multiple application domains.

## Features

- **Modern, Responsive Design**: Clean and professional layout that works on all devices
- **Comprehensive Content**: Detailed information about drilling technologies and applications
- **Team Showcase**: Profiles of experts and team members
- **Project Timeline**: Clear visualization of project phases and milestones
- **Resource Center**: Links to technical standards, training materials, and research

## Structure

```
DrillTeam/
├── index.html          # Main landing page
├── css/
│   └── styles.css      # Stylesheet with responsive design
├── assets/
│   └── images/         # Image assets (team photos, etc.)
├── README.md           # This file
└── .gitignore         # Git ignore rules
```

## Sections

1. **Header**: Project title and mission statement
2. **Introduction**: Overview of DrillTeam's focus and objectives
3. **Focus Areas**: Technical innovation, operational excellence, and safety
4. **Application Domains**: Oil & gas, geothermal, mining, water wells, etc.
5. **Team Members**: Expert profiles and affiliations
6. **Project Timeline**: Quarterly roadmap for 2026
7. **Resources**: Technical documentation and training materials
8. **Contact**: Email and contact information

## Deployment

This is a static website that can be easily deployed to:

- **GitHub Pages**: Simply enable GitHub Pages in repository settings
- **Netlify**: Drag and drop deployment
- **Vercel**: Automatic deployment from Git
- **Any static hosting service**

### GitHub Pages Deployment

1. Go to repository Settings
2. Navigate to "Pages" section
3. Select branch (usually `main` or `master`)
4. Save and wait for deployment
5. Access at: `https://[username].github.io/DrillTeam/`

## Customization

### Updating Team Members

Edit the team section in `index.html` and add team member photos to `assets/images/`:

```html
<div class="team-member">
    <div class="member-photo">
        <img src="assets/images/member-name.jpg" alt="Member Name">
    </div>
    <h3>Member Name</h3>
    <p>Title</p>
    <p class="affiliation">Institution</p>
</div>
```

### Changing Colors

Update CSS variables in `css/styles.css`:

```css
:root {
    --primary-color: #1a365d;
    --secondary-color: #2c5282;
    --accent-color: #3182ce;
}
```

### Adding Content

Simply add new sections following the existing HTML structure in `index.html`.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

© 2026 DrillTeam. All rights reserved.

## Contact

For questions or support: info@drillteam.org