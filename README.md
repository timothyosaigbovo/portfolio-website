# Timothy Osaigbovo - Portfolio Website

![Timothy Osaigbovo Portfolio](assets/images/profile-photo.png)

## Project Overview

This is a professional portfolio website for Timothy Osaigbovo, a Computing Educator, DevOps Engineer and Data Enthusiast. The site presents professional qualifications, experience, research projects and contact information to recruiters, educational institutions and industry employers.

The site provides a clear, well-defined purpose addressing the needs of a particular target audience: recruiters and hiring managers seeking a computing professional with both teaching and practical industry experience.

**Live Site:** [https://timothyosaigbovo.github.io/portfolio-website](https://timothyosaigbovo.github.io/portfolio-website)

**Repository:** [https://github.com/timothyosaigbovo/portfolio-website](https://github.com/timothyosaigbovo/portfolio-website)

## Target Audience

Recruiters, academic managers and technology employers who wish to quickly assess professional suitability for computing, DevOps and education roles.

## User Stories

### First-Time Visitor Stories

| ID | User Story | How It Is Met |
|----|-----------|---------------|
| US-01 | As a first-time visitor, I want to immediately understand who this person is and what they do. | Hero section displays name, role tagline and professional summary above the fold. |
| US-02 | As a first-time visitor, I want to easily navigate the site to find the information I need. | Consistent navigation bar on all pages with clear labels and active page highlighting. |
| US-03 | As a first-time visitor, I want to see evidence of qualifications and certifications. | About page displays education cards with institution names and qualification details. |
| US-04 | As a first-time visitor, I want to view a portfolio of work. | Portfolio page shows project cards with descriptions, technologies and tags. |
| US-05 | As a first-time visitor, I want to find contact information easily. | Contact page with form and direct details; CTAs on every content page. |

### Returning Visitor Stories

| ID | User Story | How It Is Met |
|----|-----------|---------------|
| US-06 | As a returning visitor, I want to quickly access the contact page. | Navigation provides direct link; CTA buttons on all pages. |
| US-07 | As a returning visitor, I want to check for updates to projects or experience. | Portfolio and About pages clearly display current content. |

### Site Owner Stories

| ID | User Story | How It Is Met |
|----|-----------|---------------|
| US-08 | As the site owner, I want visitors to be encouraged to contact me. | Prominent CTAs in hero, after content sections, and dedicated contact page. |
| US-09 | As the site owner, I want the site to work on all devices. | Fully responsive using Bootstrap grid and custom CSS media queries. |
| US-10 | As the site owner, I want the site to demonstrate technical competence. | Clean, validated code with semantic HTML, custom CSS and accessibility compliance. |

## Design

### Colour Scheme

| Colour | CSS Variable | Hex Code | Usage |
|--------|-------------|----------|-------|
| Primary Blue | --primary-colour | #1A3A5C | Nav, headings, hero backgrounds |
| Primary Light | --primary-light | #2A5A8C | Hover states, secondary elements |
| Primary Dark | --primary-dark | #0D1F33 | Footer, deep backgrounds |
| Accent Gold | --accent-colour | #E8A838 | CTAs, highlights, active states |
| Text Dark | --text-colour | #2C2C2C | Body text |
| Background | --bg-light | #F5F7FA | Alternating section backgrounds |

All colour combinations meet WCAG AA contrast requirements (minimum 4.5:1 ratio).

### Typography

- **Headings:** Montserrat (Google Fonts) - A modern geometric sans-serif that conveys professionalism and clarity.
- **Body:** Open Sans (Google Fonts) - A highly readable humanist sans-serif optimised for screen legibility at all sizes. Set at 16px base with 1.7 line-height.

### Wireframes

Wireframes were created for mobile, tablet and desktop screen sizes to plan the responsive layout before development began.

See [assets/docs/wireframes/](assets/docs/wireframes/) for all wireframe files.

## Features

### Implemented Features

| Feature | Description |
|---------|-------------|
| Responsive Navbar | Bootstrap navbar with hamburger toggle on mobile, active page highlighting |
| Skip to Content | Keyboard accessibility link visible on focus |
| Hero Section | Full-width gradient with name, tagline, profile photo, summary and two CTAs |
| Skill Cards | Three interactive cards with hover effects and skill badges |
| Project Cards | Hover-animated cards with descriptions and technology tags |
| Experience Timeline | Vertical timeline with dates, roles and descriptions |
| Education Cards | Qualification cards with institution names and details |
| Contact Form | Four-field form with HTML5 validation and success page redirect |
| CSS Custom Properties | Colour and font variables in :root for consistency |
| CSS Media Queries | Four custom breakpoints for responsive layout (advanced technique) |
| Social Links | Footer social links opening in new tabs with aria-labels |
| Success Page | Form confirmation with return navigation |

### Future Features

- Downloadable CV (PDF)
- Project filtering by technology
- Blog section for educational insights
- Dark mode toggle

## Site Structure

| Page | URL | Purpose |
|------|-----|---------|
| Home | index.html | Hero section, core competencies, featured projects, contact CTA |
| About | about.html | Profile, education, experience timeline, memberships, awards |
| Portfolio | portfolio.html | Project cards, technologies, future goals |
| Contact | contact.html | Contact form and direct contact details |
| Success | success.html | Form submission confirmation |

## Technologies Used

| Technology | Purpose |
|-----------|---------|
| HTML5 | Semantic markup and page structure |
| CSS3 | Custom styling with CSS custom properties and media queries |
| Bootstrap 5.3.3 | Responsive grid system, navbar component, utility classes |
| Font Awesome 6.5.1 | Iconography with accessible aria-hidden attributes |
| Google Fonts | Montserrat (headings) and Open Sans (body) typefaces |
| Git | Version control with descriptive commit messages |
| GitHub | Repository hosting and deployment via GitHub Pages |
| GitHub Pages | Static site hosting for the deployed project |

## Testing

Full testing documentation is available in the
[TESTING.md](TESTING.md) file.

A formal test plan with 76 test cases is available in
[assets/docs/MP1_Test_Plan.docx](assets/docs/MP1_Test_Plan.docx).

Testing covers the following areas:
- HTML Validation (W3C Validator)
- CSS Validation (Jigsaw Validator)
- Lighthouse Audits (Performance, Accessibility, Best Practices, SEO)
- Responsive Design Testing (320px to 1200px+)
- Browser Compatibility Testing
- Link Testing
- Form Testing
- User Story Testing

## Deployment

### GitHub Pages

The site was deployed to GitHub Pages using the following steps:

1. Navigate to the repository on GitHub
2. Click the **Settings** tab
3. Scroll down and click **Pages** in the left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Under **Branch**, select **main** and folder **/ (root)**
6. Click **Save**
7. Wait 2-3 minutes for the site to deploy

The live site is available at: [https://timothyosaigbovo.github.io/portfolio-website](https://timothyosaigbovo.github.io/portfolio-website)

### How to Clone This Repository

1. Go to [https://github.com/timothyosaigbovo/portfolio-website](https://github.com/timothyosaigbovo/portfolio-website)
2. Click the green **Code** button
3. Copy the HTTPS URL
4. Open your terminal and run: `git clone https://github.com/timothyosaigbovo/portfolio-website.git`
5. Open the folder in VS Code: `cd portfolio-website` then `code .`

## Credits

### Content

- All text content was written by Timothy Osaigbovo
- Icons provided by [Font Awesome](https://fontawesome.com)

### Frameworks and Libraries

- [Bootstrap 5.3.3](https://getbootstrap.com) - Responsive grid system and components
- [Font Awesome 6.5.1](https://fontawesome.com) - Icon library
- [Google Fonts](https://fonts.google.com) - Montserrat and Open Sans typefaces

### Acknowledgements

- Code Institute for the learning materials and project guidance
- Bootstrap documentation for component reference
- Google Fonts for free typography