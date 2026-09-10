# Uday Roy — Personal Portfolio Website

A modern, high-performance personal portfolio website for **Uday Roy**, an enterprise **RPA & Automation Developer | Microsoft Power Platform Specialist | Power BI Expert**, inspired by the **Mikon** portfolio design aesthetic.

---

## 🌟 Key Features

- **Mikon-Inspired Aesthetic**: Sleek glassmorphism navigation, modern typography (`Outfit` & `Plus Jakarta Sans`), subtle glowing accents, and animated floating badges.
- **Dark & Light Mode**: Seamless theme toggle with smooth transitions and persistent preference memory via `localStorage`.
- **Hero Banner with Dynamic Typing**: Displays core roles (`UiPath Certified RPA Developer`, `Microsoft Power Platform Architect`, etc.) with quick contact badges and portrait frame.
- **Key Metrics Counter**: Interactive number increment animations for 15+ years experience, 50+ bots, 100+ dashboards, and 5 certifications.
- **Enterprise Career Timeline**: In-depth work history at **Concentrix**, **Capgemini**, **Genpact**, **Bajaj Allianz**, and **Ureka Technologies**.
- **Specialized Services**: 6 cards highlighting RPA, Power Platform, Power BI, Excel VBA modernization, AI & RAG systems, and process architecture consulting.
- **Comprehensive Skills Grid**: Visual proficiency bars and technology tags across RPA, Power Platform, AI tools, and Agile leadership.
- **Filterable Projects Showcase**: Interactive category filters (`All`, `Power Platform`, `RPA & Bots`, `Excel & VBA`, `AI & Python`) with deep-dive modal popups.
- **Certifications & Education**: Showcases UiPath Certified RPA Developer, Agile Scrum, Six Sigma, Python, SQL, and University degrees.
- **Interactive Contact Form**: Client-side validation, direct email generator, and one-click WhatsApp/Call shortcuts.
- **Fully Responsive**: Optimized for ultra-wide desktops, laptops, tablets, and smartphones.
- **Zero-Build Overhead**: Pure, standards-compliant HTML5, CSS3, and JavaScript that runs out of the box in any browser.

---

## 🚀 How to Run Locally

### Option 1: Direct Browser
Simply double-click `index.html` to open the website directly in Google Chrome, Microsoft Edge, Firefox, or Safari.

### Option 2: Python HTTP Server
Run from PowerShell or Command Prompt:
```bash
python -m http.server 3000
```
Then open: `http://localhost:3000`

### Option 3: Node / npm
```bash
npm start
```

---

## 🌐 Free Deployment Options

### 1. GitHub Pages (1-Click Free Hosting)
1. Initialize a git repository:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio website"
   ```
2. Create a repository on GitHub (e.g. `uday-roy-portfolio`).
3. Push your code and enable **GitHub Pages** under repository **Settings > Pages > Branch: main**.

### 2. Netlify
Drag-and-drop the entire `Profile Website` folder into [Netlify Drop](https://app.netlify.com/drop) for instant global deployment.

### 3. Vercel
Run `npx vercel` in the project directory or import the GitHub repository into [Vercel](https://vercel.com).

---

## 📁 Project Structure

```
c:\Users\ROY\Desktop\Profile Website\
├── index.html                   # Semantic HTML5 single-page application
├── assets\
│   ├── css\
│   │   ├── style.css            # Mikon-inspired themes, variables, and animations
│   │   └── responsive.css       # Breakpoint optimizations & print styles
│   ├── js\
│   │   ├── main.js              # Theme switcher, scrollspy, typing effect & modal
│   │   └── projects-data.js     # Structured project metadata and metrics
│   └── img\
│       ├── uday-roy.jpg         # Profile photograph
│       └── projects\            # Custom SVG graphics for each project
├── package.json                 # Dev scripts
└── README.md                    # Documentation
```
