# Personal Portfolio Website - AWT Practical 7

A modern, responsive portfolio website for a BCA student showcasing expertise in Photography, Graphic Designing, and IT Fundamentals.

## 🌟 Features

- **Fully Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations and transitions
- **Interactive Navigation**: Fixed navbar with smooth scrolling and mobile hamburger menu
- **Dynamic Content Sections**:
  - Hero section with gradient background and call-to-action buttons
  - About section with experience statistics
  - Skills section with animated progress bars for three categories
  - Portfolio section with filterable project showcase (9 projects)
  - Contact section with form and social media links
- **Advanced JavaScript Features**:
  - Portfolio filtering by category (All, Photography, Design, Web Projects)
  - Intersection Observer for scroll animations
  - Toast notification system for form feedback
  - Mobile menu toggle functionality

## 🛠️ Technologies Used

- **HTML5**: Semantic markup for better accessibility and SEO
- **CSS3**: Modern features including Flexbox, Grid, animations, and custom properties
- **JavaScript (ES6+)**: Vanilla JavaScript with no dependencies
- **Font Awesome**: Icon library (via CDN)

## 📁 Project Structure

```
AWT_Practical7/
├── index.html      # Main HTML file with all sections
├── styles.css      # Complete stylesheet with responsive design
├── script.js       # JavaScript for interactivity
├── README.md       # Project documentation
├── LICENSE         # License file
└── .gitignore      # Git ignore file
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, but recommended for testing)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/naeshby/AWT_Practical7.git
cd AWT_Practical7
```

2. Open the website:
   - **Option 1**: Open `index.html` directly in your browser
   - **Option 2**: Use a local server (recommended):
   ```bash
   # Using Python 3
   python3 -m http.server 8080
   
   # Using Node.js http-server
   npx http-server -p 8080
   ```
   Then open `http://localhost:8080` in your browser

## 📱 Sections Overview

### 1. Hero Section
Eye-catching introduction with:
- Gradient background (blue to green)
- Professional tagline: "Photographer | Graphic Designer | IT Enthusiast"
- Two call-to-action buttons

### 2. About Section
Detailed profile including:
- Introduction to BCA background
- Description of skills and passion
- Experience statistics cards for Photography, Design, and IT Skills

### 3. Skills Section
Three categorized skill sets with progress bars:
- **Photography**: Portrait, Landscape, Photo Editing, Lighting & Composition
- **Graphic Designing**: Photoshop, Illustrator, Logo Design, UI/UX
- **IT Fundamentals**: HTML & CSS, JavaScript, Computer Networks, Database

### 4. Portfolio Section
Showcase of 9 projects across three categories:
- **Photography**: Portrait Series, Nature & Landscape, Event Photography
- **Design**: Brand Identity & Logos, Poster & Flyer Designs, Social Media Graphics
- **Web Projects**: Personal Portfolio Website, College Management System, Business Landing Page

### 5. Contact Section
Get in touch with:
- Email, phone, and location information
- Social media links (Instagram, LinkedIn, GitHub, Behance)
- Working contact form with validation and toast notifications

## 🎨 Customization

### Colors
Colors are defined as CSS custom properties in `styles.css`:
```css
--primary-color: #4a90e2;   /* Blue */
--secondary-color: #50c878; /* Green */
--accent-color: #ff6b6b;    /* Red */
--dark-color: #2c3e50;      /* Dark gray */
--light-color: #ecf0f1;     /* Light gray */
```

### Content
- Update text content in `index.html`
- Replace placeholder images with actual project images
- Modify skills and percentages as needed
- Update contact information and social media links

## 📊 Responsive Breakpoints

- **Desktop**: > 768px
- **Tablet**: 768px and below
- **Mobile**: 480px and below

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍🎓 Academic Context

This project was created as part of BCA 3rd Semester Advanced Web Technology (AWT) Practical 7, demonstrating proficiency in:
- Modern web development practices
- Responsive design principles
- JavaScript DOM manipulation
- Clean code organization
- User experience design

## 🤝 Contributing

This is an academic project, but suggestions and improvements are welcome! Feel free to open an issue or submit a pull request.

## 📧 Contact

For any queries related to this project, please use the contact form on the website or reach out via the provided contact information.

---

**Made with ❤️ for BCA 3rd Semester AWT Practical**
