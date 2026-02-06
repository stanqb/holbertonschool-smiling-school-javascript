# Smiling School - JavaScript

A fully responsive multi-page website with dynamic content loading using Bootstrap, jQuery, and AJAX API calls.

## 📋 Project Description

This project implements a complete website based on designer mockups by Nicolas Philippot (UI/UX designer). The site features dynamic content loading from an external API, responsive carousels, filtering systems, and smooth animations.

## 🎯 Objectives

- Build pixel-perfect web pages matching the designer's specifications
- Implement dynamic content loading via AJAX requests
- Maximize Bootstrap classes usage to minimize custom CSS
- Create reusable carousel components
- Ensure full responsiveness across all device sizes
- Follow accessibility and web standards best practices

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styling (minimal)
- **Bootstrap 4.4.1** - CSS framework for layout and components
- **jQuery 3.4.1** - JavaScript library for DOM manipulation and AJAX
- **Google Fonts** - Source Sans Pro & Coiny

## 📦 Dependencies

All dependencies are loaded via CDN:

- Bootstrap CSS & JS (v4.4.1)
- jQuery (v3.4.1)
- Popper.js (v1.12.9)
- Google Fonts (Source Sans Pro & Coiny)

## 🚀 Getting Started

1. Clone this repository
```bash
git clone https://github.com/[username]/holbertonschool-smiling-school-javascript.git
```
2. Open any HTML file in your browser
3. No build process required - all dependencies are CDN-based

## 📁 Project Structure

- `0-homepage.html` - Static homepage (base)
- `0-pricing.html` - Static pricing page (base)
- `0-courses.html` - Static courses page (base)
- `1-homepage.html` - Homepage with dynamic quotes
- `2-homepage.html` - Homepage with dynamic quotes and popular tutorials
- `homepage.html` - Complete homepage with all dynamic features
- `pricing.html` - Pricing page with dynamic quotes
- `courses.html` - Courses page with search and filters
- `styles.css` - Custom CSS (minimal, Bootstrap classes prioritized)
- `scripts.js` - JavaScript functionality (jQuery-based, AJAX calls)

## ✨ Features

### Responsive Breakpoints
- **Tablet version**: 768px
- **Mobile version**: 576px

### Interactive Elements
- Button hover/active state: `opacity: 0.9`
- Loading spinners during AJAX requests
- Smooth carousel transitions (card-by-card sliding)

### Dynamic Content Loading

#### Quotes Section
- API: `https://smileschool-api.hbtn.info/quotes`
- Dynamic carousel of testimonial quotes

#### Popular Tutorials Section
- API: `https://smileschool-api.hbtn.info/popular-tutorials`
- Card-by-card sliding carousel

#### Latest Videos Section
- API: `https://smileschool-api.hbtn.info/latest-videos`
- Card-by-card sliding carousel

#### Courses Search & Filter
- API: `https://smileschool-api.hbtn.info/courses`
- GET parameters:
  - `q`: search keywords
  - `topic`: topic filter
  - `sort`: sorting order
- Dynamic dropdowns (topics and sort options from API)
- Real-time filtering on search/selection change

## 📝 Requirements Met

✅ Bootstrap framework utilized throughout  
✅ Minimal custom CSS (Bootstrap classes prioritized)  
✅ jQuery for all JavaScript functionality  
✅ JavaScript executes only after document load  
✅ AJAX requests with loading states  
✅ Reusable carousel components  
✅ Fully responsive design  
✅ Matches designer specifications

## 🎨 Design

All designs by **Nicolas Philippot** (UI/UX Designer)

## 👥 Authors

- **[Your Name]** - Project implementation

## 📄 Repository

- **GitHub repository**: `holbertonschool-smiling-school-javascript`

## 📜 License

This project is part of the Holberton School curriculum.

## Author

Stan QUEUNIEZ