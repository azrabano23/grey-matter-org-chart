# Grey Matter - Organizational Chart 2025-2026

A modern, interactive organizational chart for Grey Matter at Yale University.

## ✨ Features

- 🎨 Modern, responsive design with smooth animations
- 📱 Mobile-friendly interface
- ✨ Interactive hover effects
- 🧠 Brain emoji favicon
- 🌐 Optimized for web deployment
- 🎯 Clean, professional layout

## 🏢 Departments

- **Administrative Department** - Leadership and operations
- **Treasury Department** - Financial management and fundraising
- **Research Department** - Research initiatives and publications
- **Education Department** - Curriculum and educational programs
- **Technology & Engineering Department** - Software and hardware projects
- **Public Affairs Department** - Marketing, outreach, and recruitment
- **Legislative Department** - Advocacy and government relations

## 🚀 Quick Deploy to Vercel

1. **One-Click Deploy**: Upload the `index.html` file directly to Vercel
2. **GitHub Integration**: 
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/your-username/grey-matter-org-chart.git
   git push -u origin main
   ```
   Then connect to Vercel through their GitHub integration

3. **Vercel CLI**:
   ```bash
   npm install -g vercel
   vercel
   ```

## 💻 Local Development

```bash
# Serve locally
npm run dev
# or
npx serve .
```

Open `http://localhost:3000` to view the organizational chart.

## 📁 Project Structure

```
grey-matter-org-chart/
├── index.html          # Main organizational chart page (complete app)
├── package.json        # Project configuration
└── README.md          # This documentation
```

## 🛠 Customization

The organizational chart is fully self-contained in `index.html`. To make changes:

1. **Update member information**: Edit the HTML content in the respective department sections
2. **Modify styling**: Update the CSS variables in the `:root` section for colors and effects
3. **Add/remove departments**: Copy department sections and update the CSS classes
4. **Change animations**: Modify the CSS animations and transitions

### Color Variables

```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --card-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    --hover-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
    --border-radius: 12px;
    --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}
```

## 🎨 Design Features

- **Inter Font Family** - Modern typography from Google Fonts
- **Smooth Animations** - CSS3 transitions and hover effects
- **Responsive Layout** - Works on desktop, tablet, and mobile
- **Department Color Coding** - Each department has its own gradient theme
- **Interactive Elements** - Hover effects on positions and member tags
- **Clean Card Design** - Modern card-based layout with shadows

## 📱 Mobile Responsiveness

The design automatically adapts to different screen sizes:
- **Desktop**: Full layout with hover effects
- **Tablet**: Optimized spacing and typography
- **Mobile**: Single-column layout with adjusted member tags

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)  
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 📄 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Grid, Flexbox, and animations
- **Google Fonts** - Inter typeface for modern typography
- **CSS Variables** - For easy theming and customization
- **Responsive Design** - Mobile-first approach

## 🎯 Performance

- **Single File** - Entire application in one HTML file
- **No Dependencies** - Pure HTML/CSS/JavaScript
- **Fast Loading** - Optimized images and efficient CSS
- **SEO Friendly** - Proper meta tags and semantic HTML

## 🔧 Development

This is a static HTML application that requires no build process. Simply edit the `index.html` file to make changes.

### Adding New Members

1. Find the appropriate department section
2. Add a new member tag in the `committee-members` div:
```html
<span class="member">New Member Name</span>
```

### Adding New Positions

1. Add a new position div in the department content:
```html
<div class="position">
    <div class="position-title">Position Title</div>
    <div class="position-name">Person Name<span class="star">*</span></div>
    <div class="position-description">→ Position description</div>
</div>
```

## 📝 License

MIT License - Free to use and modify for educational purposes.

---

**Grey Matter** · Yale University · 2025–2026

*Executive board members indicated with asterisk (*)*
