# 🌍 Carbon Footprint Calculator
 
An interactive web-based calculator that helps users measure their annual carbon footprint and receive AI-powered personalized sustainability tips.
 
![Carbon Footprint Calculator](https://img.shields.io/badge/CO₂-Calculator-4ade80?style=for-the-badge)
![Built with HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![AI Powered](https://img.shields.io/badge/AI-Powered-blueviolet?style=for-the-badge)
 
## ✨ Features
 
- **Interactive Step-by-Step Quiz**: Engaging multi-step questionnaire covering all major carbon footprint categories
- **Real-Time CO₂ Counter**: Live calculation updates as you answer each question
- **Beautiful Animations**: Smooth card transitions, emoji reactions, and confetti celebrations
- **Personalized AI Tips**: Get custom sustainability recommendations powered by Groq AI (Llama 3.1)
- **Comprehensive Categories**:
  - 🚗 Transportation (daily car usage)
  - ⚡ Energy consumption (electricity usage)
  - 🍽️ Diet choices (vegan, vegetarian, balanced, meat-heavy)
  - 🛍️ Lifestyle (shopping habits, electronics, recycling)
  - 🚿 Water usage (shower duration, conservation efforts)
  - 🗑️ Waste management (food waste, plastics, general waste)
- **Global Comparison**: See how your footprint compares to the global average (4 tonnes/year)
- **Visual Breakdown**: Interactive charts showing emissions by category
- **Responsive Design**: Works seamlessly on desktop and mobile devices
## 🚀 Quick Start
 
### Option 1: Direct Use
1. Download `index.html`
2. Open it in any modern web browser
3. Start calculating your carbon footprint!
### Option 2: Host Online
Deploy to any static hosting service:
- **GitHub Pages**: Push to a repository and enable GitHub Pages
- **Vercel**: `vercel --prod`
- **Netlify**: Drag and drop the HTML file
- **Replit**: Import and run
## 🎮 How to Use
 
1. **Start the Quiz**: Click through 7 interactive steps covering different aspects of your lifestyle
2. **Answer Questions**: Use sliders and radio buttons to input your daily habits
3. **Watch Live Updates**: See your CO₂ total update in real-time in the top-right corner
4. **Get Your Results**: View your total annual footprint with a detailed breakdown by category
5. **Receive AI Tips**: Get personalized suggestions to reduce your environmental impact
## 🧮 Calculation Methodology
 
The calculator uses scientifically-backed emission factors:
 
- **Car Travel**: 0.00021 tonnes CO₂ per km
- **Electricity**: 0.00082 tonnes CO₂ per kWh/month (annualized)
- **Diet**: 
  - Vegan: 1.5t/year
  - Vegetarian: 1.7t/year
  - Balanced: 2.5t/year
  - Meat-heavy: 3.3t/year
- **Lifestyle, Water, and Waste**: Category-specific emission factors based on consumption patterns
**Global Average Benchmark**: 4 tonnes CO₂ per person per year
 
## 🤖 AI Integration
 
The calculator uses the **Groq API** with the Llama 3.1 8B model to generate personalized tips:
 
### Getting a Groq API Key (Free)
1. Visit [console.groq.com](https://console.groq.com)
2. Sign up for a free account
3. Navigate to API Keys section
4. Create a new API key
5. Enter the key when prompted by the calculator
The API key is stored locally in your browser and never sent to any server except Groq's API.
 
### AI Tip Generation Logic
- **Above 4 tonnes**: Receives 5 specific, actionable tips targeting highest-impact areas
- **Below 4 tonnes**: Receives encouragement and compliments to maintain good habits
## 🎨 Design Features
 
- **Modern Gradient UI**: Clean, contemporary design with animated background blobs
- **Custom Color Palette**: 
  - Primary: Forest green tones (#1a472a, #2d5a3d, #4ade80)
  - Accents: Gold (#f9a825), Pink (#e879f9), Blue (#38bdf8)
- **Typography**: Nunito for body text, Syne for headings
- **Micro-interactions**: 
  - Bounce animations for emojis
  - Smooth card transitions
  - Progress bar animations
  - Confetti celebration for low footprints
## 📁 Project Structure
 
```
carbon-footprint-calculator/
│
├── index.html          # Single-file application
│   ├── HTML structure
│   ├── CSS styling (embedded)
│   └── JavaScript logic (embedded)
│
└── README.md           # This file
```
 
## 🔧 Technical Details
 
- **Zero Dependencies**: Pure HTML, CSS, and JavaScript - no frameworks or libraries needed
- **Local Storage**: API key stored securely in browser localStorage
- **External APIs**: Groq API for AI tip generation
- **Fonts**: Google Fonts (Nunito, Syne)
- **Browser Support**: Modern browsers (Chrome, Firefox, Safari, Edge)
## 🌱 Carbon Footprint Categories Breakdown
 
| Category | Questions | Impact Factors |
|----------|-----------|----------------|
| Transport | Daily km, Days/week | Distance × Days × Emission factor |
| Energy | Monthly kWh | Usage × 12 months × Grid factor |
| Diet | Food choices | Preset annual values by diet type |
| Lifestyle | Clothes, Electronics, Recycling | Consumption patterns |
| Water | Shower time, Conservation | Usage duration & efficiency |
| Waste | Food waste, Plastics, General waste | Waste volume & type |
 
## 🎯 Educational Value
 
Perfect for:
- **Science Fair Projects** on environmental sustainability
- **Educational Demonstrations** about carbon footprints
- **Personal Awareness** tools for eco-conscious individuals
- **Classroom Activities** for environmental science
- **Workshop Tools** for sustainability advocates
## 🔒 Privacy & Data
 
- **No server**: All calculations happen in your browser
- **No tracking**: No analytics or data collection
- **Local storage only**: API key stored locally, never transmitted
- **No personal data**: Only anonymous usage statistics are calculated
## 🤝 Contributing
 
Contributions are welcome! Here are some ideas:
- Add more emission categories (flights, public transport)
- Improve calculation accuracy with region-specific factors
- Add multi-language support
- Create data export/share features
- Enhance accessibility features
## 📄 License
 
This project is open source and available under the [MIT License](LICENSE).
 
## 🙏 Acknowledgments
 
- Emission factors based on EPA and IPCC guidelines
- AI tips powered by [Groq](https://groq.com) and Llama 3.1
- Design inspiration from modern sustainability platforms
- Built for the Science Fair: Future Technologies & Sustainable Solutions
## 📞 Contact
 
For questions, suggestions, or feedback:
- Open an issue on GitHub
- Contribute via pull requests
- Share your carbon footprint journey!
---
 
<div align="center">
**Made with 💚 for a sustainable future**
 
*Every tonne of CO₂ reduced makes a difference*
 
</div>
