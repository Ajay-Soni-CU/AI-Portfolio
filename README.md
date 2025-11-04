# 🤖 Ajay’s Portfolio — Machine Learning Engineer  
### _Where AI Meets Creativity in Web Design_  

**Live Demo:** [https://learnerportfolio.rf.gd](#)  
**Author:** Ajay Soni  


---

## 🚀 Overview

A stunning, futuristic, and fully responsive **AI-integrated portfolio website** for an aspiring **Machine Learning Engineer**.  
This project reimagines what a personal portfolio can be — combining **modern web design**, **AI-driven interactivity**, and **seamless performance**.

Built entirely with **HTML5**, **CSS3**, and **Vanilla JavaScript (ES6+)**, this portfolio is optimized for elegance, performance, and intelligence.

---

## ✨ Highlights — _AI at the Core_

### 🤖 **AI Chatbot Assistant** — The Star Feature ⭐

Your portfolio doesn’t just **show your work** — it **talks about it intelligently**.

- 💬 **Real-Time Conversations:** Interactive AI-powered chat that responds naturally.  
- 🧠 **Context-Aware Responses:** Knows your projects, skills, and experience dynamically.  
- 🌐 **Powered by OpenRouter API (Gemini 2.0 Flash):** Delivers lightning-fast, accurate answers.  
- 🧩 **Integrated Personality:** The AI introduces Ajay professionally and engages conversationally.  
- 🔄 **Session Memory:** Maintains context during chat sessions.  
- 📱 **Floating Chat Button:** Elegant bottom-right AI icon that opens an animated chat window.  
- 💾 **Local Conversation Persistence:** Keeps your chat history during active sessions.  
- ⚡ **Fail-Safe Fallbacks:** Graceful offline mode and default responses when API is unavailable.

> 🧩 _Try asking:_  
> “What machine learning projects has Ajay built?”  
> “Tell me about Ajay’s data science certifications.”  
> “How can I reach Ajay directly?”  

---

## 🎨 Design & UX

| Feature | Description |
|----------|-------------|
| 🎭 **Dual Theme System** | Beautiful **dark/light mode toggle** with saved preferences. |
| 📱 **Responsive Design** | Fully optimized for desktop, tablet, and mobile. |
| 🎞️ **Smooth Animations** | Scroll-triggered transitions, hover highlights, and fade-ins. |
| 💎 **Professional Layout** | Grid-based visual hierarchy for modern UX. |
| ♿ **Accessible & Inclusive** | WCAG-compliant color contrast, keyboard navigation. |

---

## 🧠 Portfolio Sections

### 🏠 Hero Section  
- Dynamic gradient headline  
- Animated introduction text  
- “Hire Me” and “Explore Projects” call-to-action buttons  

### 👨‍💻 About Me  
- Clear narrative about Ajay’s background in **Machine Learning & Data Science**  
- Educational details and professional journey  

### 🚀 Projects Showcase  
- 8+ machine learning and AI-based projects  
- Live demos + GitHub links  
- Hover animations and smooth card transitions  

### 🧩 Skills Matrix  
- Animated skill bars (Python, ML, DL, Data Structures, etc.)  
- Grouped by domain: ML, Python, Frontend, and Tools  

### 🏅 Certifications  
- IBM ML Professional Certificate  
- AI & ChatGPT (Udemy), Data Structures (Coursera), etc.  

### 📞 Contact Section  
- Integrated **WhatsApp API** for one-tap messaging  
- Social icons (LinkedIn, GitHub, Email)

---

## 🤖 AI Chatbot Breakdown

| Capability | Description |
|-------------|--------------|
| 🧠 **Knowledge Base** | Reads from Ajay’s `portfolioData` JSON — skills, projects, and bio. |
| 🧾 **Dynamic Context** | Adjusts tone and answers based on query type (tech/academic/personal). |
| ⚙️ **OpenRouter Integration** | Connects to Gemini 2.0 Flash model for low-latency responses. |
| 💬 **Typing Simulation** | Animated dots mimic natural human-like chat flow. |
| 📡 **Offline Mode** | Graceful fallback responses if API is down. |

---

## 🛠️ Technologies Used

**Frontend Stack**
- HTML5  
- CSS3 (Grid, Flexbox, Custom Properties)  
- JavaScript ES6+  
- Font Awesome 6.4.0  
- Google Fonts (Inter, Space Grotesk)

**AI & Integrations**
- OpenRouter API (Gemini 2.0 Flash model)  
- WhatsApp API (direct messaging)  
- Unsplash API (project imagery)  

**Development Enhancements**
- Local Storage (for theme + chat persistence)  
- Intersection Observer API (scroll animations)  
- CSS Variables for color theme control  

---

## 🚀 Quick Start

### 1️⃣ Prerequisites  
- Modern web browser (Chrome, Firefox, Edge, Safari)  
- Basic knowledge of HTML/CSS/JavaScript for personalization  

### 2️⃣ Setup  
```bash
git clone https://github.com/Ajay-Soni-CU/portfolio-website.git
cd portfolio-website
```

### 3️⃣ Run Locally  
```bash
# Option 1: Python
python -m http.server 8000

# Option 2: Node.js
npx http-server

# Option 3: PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

---

## ⚙️ Configuration Guide

### 🔑 AI Chatbot Setup
1. Get your **OpenRouter API key**  
   👉 [https://openrouter.ai](https://openrouter.ai)
2. In `script.js`, replace:
```javascript
const API_KEY = "YOUR_API_KEY_HERE";
```
3. Update your `portfolioData` JSON:
```javascript
const portfolioData = {
  name: "Ajay Soni",
  title: "Machine Learning Engineer",
  projects: [...],
  skills: [...]
};
```

### 🎨 Theme Customization
Edit `:root` in CSS:
```css
:root {
  --primary: #ffffff;
  --accent: #3a86ff;
  --text-primary: #1a1a2e;
  --bg-dark: #121212;
}
```

---

## 📁 Project Structure

```bash
portfolio-website/
│
├── index.html                  # Main portfolio file
├── assets/
│   ├── images/                 # Project visuals
│   ├── css/                    # Theme and layout styles
│   └── js/                     # Chatbot logic, animations
│
└── README.md                   # Documentation
```

---

## 🌟 Highlights

- 🧠 **AI-Powered Personalization** — Your portfolio talks intelligently about your career  
- 💬 **Real-Time Conversational Experience**  
- ⚙️ **No Dependencies, 100% Vanilla Code**  
- 🌈 **Dark/Light Theme Memory Persistence**  
- 🧩 **Fast, Secure, and Fully Private Execution**

---

## 🔐 Security Recommendations
- Use environment variables or `.env` files for API keys  
- Validate user inputs in chatbot responses  
- Apply rate limiting for public chatbot deployments  

---

## 🚀 Deployment Options
- **Netlify** (recommended — instant deploy & HTTPS)  
- **Vercel** (easy GitHub integration)  
- **GitHub Pages** (free static hosting)

---

## 🤝 Contributing
Suggestions, feature ideas, and pull requests are always welcome!

```bash
git checkout -b feature-enhancement
git commit -m "Added chatbot theme customization"
git push origin feature-enhancement
```

---

## 📄 License
This project is licensed under the **MIT License** — free for personal and educational use.

---

## 📞 Contact & Socials

| Platform | Link |
|-----------|------|
| 🌐 **Portfolio** | [Live Demo](#) |
| 💼 **LinkedIn** | [Ajay Soni](#) |
| 💻 **GitHub** | [@Ajay-Soni-CU](https://github.com/Ajay-Soni-CU) |
| ✉️ **Email** | programmingwithcode@gmail.com |

---

⭐ **Don’t just view the portfolio — _talk to it!_**  
Experience AI-powered interactivity right in the browser.  

_“Built with ❤️ by Ajay — Aspiring Machine Learning Engineer.”_
