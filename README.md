# GYMFLEX - Premium Modern Fitness Website

GYMFLEX is a comprehensive, multi-page fitness platform designed for modern gym facilities. It features a high-energy **Sky Blue** and **Dark** theme, providing a professional and motivating digital experience for fitness enthusiasts.

## 🚀 Key Features

### 1. High-Impact Landing Page
- **Dynamic Hero Section**: Engaging visuals with clear Call-to-Action (CTA) buttons.
- **Expert Trainers**: Dedicated profiles for certified professionals with social connectivity.
- **Member Testimonials**: Integrated social proof to build community trust.
- **Quick BMI Tool**: Access the Body Mass Index calculator directly from the home page.

### 2. Specialized Pages
- **About Us**: Detailed mission statement, core values, and an interactive **FAQ section** with smooth toggle animations.
- **Workouts**: A showcase of training programs (Bodybuilding, Yoga, Cardio, Crossfit) with specialized descriptions.
- **Membership Plans**: A professional three-tier pricing model (Basic, Pro, Elite) with detailed feature lists and Indian Rupee (₹) currency support.
- **Contact Hub**: Interactive form, real-time working hours, and physical location details.

### 3. Advanced Utilities
- **Interactive BMI Calculator**: A custom-built JavaScript tool that calculates BMI and provides health status feedback (Underweight, Healthy, Overweight, Obese).
- **Responsive Navigation**: A sticky header with smooth hover effects and a standardized footer across all pages.

## 🛠️ Technical Implementation

- **Architecture**: Organized asset structure using an `assets/` directory for clean codebase management.
- **Frontend**: 
  - **HTML5**: Semantic elements for better SEO and accessibility.
  - **CSS3**: Custom variables (`:root`) for easy theme management, CSS Grid, and Flexbox for ultra-responsive layouts.
  - **JavaScript**: Lightweight, vanilla JS for interactive elements (BMI Calculator, FAQ Toggles).
- **Design Assets**:
  - **Typography**: Optimized with Google Fonts (Poppins).
  - **Iconography**: Font Awesome 6.0.0 for high-resolution vector icons.
  - **Theme**: Customizable primary color (`#87ceeb`) for consistent branding.

## 📁 Project Structure

```bash
GYM/
├── assets/
│   ├── css/
│   │   └── style.css       # Centralized modern stylesheet
│   └── img/
│       ├── gym.png         # Main branding & interior assets
│       ├── workout.jpg     # Professional training visuals
│       ├── trainer1.png    # Expert profile assets
│       └── trainer2.jpg    # Expert profile assets
├── home.html               # Main landing & entry point
├── about.html              # Mission, Values & FAQ
├── workout.html            # Programs & BMI Utility
├── plans.html              # Membership pricing tiers
├── contact.html            # Contact & Location details
├── .gitignore              # Git configuration
└── README.md               # Professional documentation
```

## 💻 Installation & Local Development

1. **Clone the Project**:
   ```bash
   git clone https://github.com/nsrun/GYM-Website.git
   ```
2. **Setup**:
   Ensure all files are in the correct directory structure as shown above.
3. **Run**:
   - For the best experience, run via a local server:
     ```bash
     python -m http.server 8000
     ```
   - Access at `http://localhost:8000/home.html`

## 🤝 Contribution Guidelines

We value community feedback! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/NewFeature`).
3. Commit your changes (`git commit -m 'Add NewFeature'`).
4. Push to the branch (`git push origin feature/NewFeature`).
5. Open a Pull Request for review.

## 📄 License

This project is licensed under the MIT License - providing freedom for personal and commercial use.

---
**Crafted with excellence by [nsrun](https://github.com/nsrun)**
