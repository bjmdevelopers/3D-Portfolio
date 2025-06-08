# **Modern 3D Portfolio**
 
## Live Demo

[Live Demo](https://bjmdevelopers.github.io/3D-Portfolio/)


## 🌟 **Features**
- **Immersive 3D Particle Background** with interactive connections
- **Dark/Light Mode Toggle** with smooth transitions
- **Scroll-Triggered Animations** for all sections
- **Interactive Project Cards** with modal details
- **Mobile-Optimized Design** that works on all devices
- **Form Validation** with live feedback
- **No Frameworks** - Pure HTML, CSS, and Vanilla JS

## 🚀 **Quick Start**
1. **Download** the repository
2. **Open** `index.html` in any modern browser
3. **That's it!** No build step required

## 🛠️ **Customization**

### **Change Colors**
Edit the CSS variables at the top of the `<style>` section:
```css
:root {
  --primary-color: #6366f1;  /* Main brand color */
  --secondary-color: #ec4899; /* Accent color */
  --bg-color: #f8fafc;       /* Light background */
}
```

### **Modify 3D Effects**
Adjust the particle settings in the JavaScript:
```javascript
// In the initParticles() function:
const particleCount = window.innerWidth / 10; /* Adjust density */
const maxDistance = 100; /* Connection distance */
```

### **Update Content**
Edit the HTML directly:
```html
<!-- Example: Change hero text -->
<section id="home" class="hero">
  <h1>Your Custom Headline Here</h1>
</section>
```

## 📱 **Mobile Optimization**
The portfolio automatically:
- Reduces particle count on mobile
- Simplifies animations for better performance
- Adjusts layout for smaller screens

## 🏗️ **Project Structure**
```
/
├── index.html          # Main HTML file
├── assets/             # (Optional) For images/fonts
└── (No build files needed!)
```

## 🌐 **Deployment Options**
1. **GitHub Pages**: Just upload and enable
2. **Netlify/Vercel**: Drag-and-drop `index.html`
3. **Any Static Hosting**: Works everywhere

## 💡 **Troubleshooting**
| Issue | Solution |
|-------|----------|
| 3D effects not loading | Check browser console for errors |
| Animations feel sluggish | Reduce particle count |
| Theme not saving | Ensure localStorage is enabled |

## 📜 **License**
MIT License - Free for personal and commercial use

## ✨ **Pro Tips**
- Add your own 3D models by extending the Three.js code
- Integrate with EmailJS for form submissions
- Add Google Analytics for visitor tracking

**Star ⭐ the repo if you find this useful!**

---
