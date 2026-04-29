# Squad-Site-

A collaborative multi-page website project showcasing Squad Titans' identity, creativity, and collaboration skills. Built with HTML5, CSS3, and Git best practices.

## 📁 Project Structure

```
Squad-Site-/
├── index.html              # Main dashboard page
├── styles/
│   └── style.css           # Main stylesheet
├── members/
│   ├── alex.html           # Alex's profile page
│   ├── jordan.html         # Jordan's profile page
│   ├── casey.html          # Casey's profile page
│   └── morgan.html         # Morgan's profile page
├── images/                 # Team photos and assets (add here)
└── README.md              # This file
```

## 🚀 Getting Started

1. **Clone the repository** (already done):
   ```bash
   git clone https://github.com/juniorsince2004/Squad-Site-.git
   cd Squad-Site-
   ```

2. **Open in browser**:
   - Double-click `index.html` to view
   - Or use a local server (recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Then visit: http://localhost:8000
     ```

## 🎯 Features

- **Responsive Design**: Works on desktop, tablet, and mobile
- **Semantic HTML5**: Proper structure with `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`
- **Modern CSS**: Gradient effects, flexbox, CSS grid, smooth transitions
- **Multi-page Navigation**: Dashboard + 4 member profile pages
- **Contact Form**: Ready for integration
- **Accessibility**: WCAG compliant

## 👥 Team Members

- **Alex** - Team Lead (`members/alex.html`)
- **Jordan** - UI Designer (`members/jordan.html`)
- **Casey** - Developer (`members/casey.html`)
- **Morgan** - Git & Collaboration Expert (`members/morgan.html`)

## 🤝 Git Workflow

### Making Changes

1. **Create a feature branch**:
   ```bash
   git checkout -b feature/section-name
   ```

2. **Make your changes** and test locally

3. **Commit with clear messages**:
   ```bash
   git add .
   git commit -m "Added team member bio and styling"
   git commit -m "Created responsive navbar"
   ```

4. **Push to GitHub**:
   ```bash
   git push origin feature/section-name
   ```

5. **Create Pull Request** on GitHub for team review

### Good Commit Messages

✅ Good examples:
- `Added responsive mobile menu navigation`
- `Styled footer with gradient background`
- `Created individual member profile pages`
- `Fixed form validation and styling`

❌ Bad examples:
- `fixed stuff`
- `updates`
- `work in progress`

## 📚 What You'll Learn

By completing this project:
- ✅ HTML5 semantic structure
- ✅ CSS styling with Flexbox & Grid
- ✅ Responsive design principles
- ✅ Git and GitHub collaboration
- ✅ Project organization
- ✅ Team workflow best practices

## 🎨 Design System

**Colors:**
- Primary: `#667eea` (Purple)
- Secondary: `#764ba2` (Dark Purple)
- Accent: `#f093fb` (Pink)
- Background: `#f8f9fa` (Light Gray)

**Typography:**
- Font: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- Responsive sizing for mobile and desktop

## 📝 Customization

### Update Squad Name
Replace "Squad Titans" throughout:
- `index.html` - Header and title
- Member pages - Titles and content
- `style.css` - Color scheme if desired

### Add Team Members
1. Create new HTML file in `members/` folder
2. Copy structure from existing member page
3. Update name, role, and bio
4. Add link to `index.html` member section

### Add Images
1. Place images in `images/` folder
2. Reference in HTML: `<img src="images/team.jpg" alt="Team Photo">`

## 🐛 Common Issues

**Links not working?**
- Check file paths are relative (e.g., `members/alex.html`)
- Ensure files are in correct folders

**Styling not showing?**
- Hard refresh browser: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
- Check CSS file path: `styles/style.css`

**Images not loading?**
- Verify image path is correct
- Use relative paths from root

## 📞 Team Communication

- Use commit messages to inform teammates
- Pull latest changes before starting work: `git pull`
- Avoid merge conflicts by working on different sections

## 🚀 Deployment

Host your site on:
- GitHub Pages (free!)
- Netlify
- Vercel
- Firebase Hosting
