# Carbon Footprint Calculator

## 🌍 What is This Project?

This is a **Carbon Footprint Calculator** - a tool that helps you understand how much CO₂ you produce every year based on your daily activities.

## 📝 Project Explanation (For Teacher)

**Science Concept:** Carbon footprint measures the total greenhouse gases (mainly CO₂) produced by human activities. This project helps students understand:
- How different lifestyle choices affect the environment
- How to calculate environmental impact using real formulas
- Comparison with global averages
- How AI can provide personalized sustainability tips

**What Students Learn:**
- Environmental science concepts (carbon emissions)
- Web development (HTML, CSS, JavaScript)
- Real-world data and calculations
- How to interact with AI APIs for personalized insights

**How it Works:** Students input their daily/monthly activities (car travel, flights, electricity use, diet) and the calculator shows their yearly carbon footprint in tonnes of CO₂. Then an AI gives tips on how to reduce it.

---

## 🚀 How to Run (Step by Step)

### Step 1: Open Terminal
Press `Ctrl + Shift + P` in VS Code and type "Terminal: Create New Terminal"

### Step 2: Install Dependencies
Copy and paste this command:
```bash
npm install
```
Wait for it to finish (you'll see "added X packages").

### Step 3: Start the Application
Copy and paste this command:
```bash
npm run dev
```

### Step 4: Open in Browser
A browser window will automatically open showing: `http://localhost:3000`

If not, manually open your browser and go to: `http://localhost:3000`

✅ **Done!** You should see the Carbon Footprint Calculator.

---

## 📊 How to Use the Calculator

1. **Move the sliders** to enter your lifestyle data:
   - Car Travel (km per day)
   - Flights (per year)
   - Monthly Electricity Use (kWh)

2. **Select your diet type** from the dropdown

3. **Click "Calculate Footprint"** button

4. **See your results:**
   - Your total CO₂ footprint (tonnes per year)
   - Comparison with global average (4.0 tonnes)
   - AI tips to reduce your carbon footprint

---

## 🤖 Enable AI Tips (Optional)

The calculator can give personalized tips using AI. To turn this on:

1. Go to [console.groq.com](https://console.groq.com) and get a FREE API key
2. Open `index.html` in a text editor
3. Find this line (around line 9):
   ```javascript
   const GROQ_API_KEY = "YOUR_GROQ_API_KEY_HERE";
   ```
4. Replace it with your actual key:
   ```javascript
   const GROQ_API_KEY = "your-key-here";
   ```
5. Save the file and refresh the browser

---

## 📁 Project Files

- **`index.html`** - The entire app (HTML + CSS + JavaScript in one file)
- **`package.json`** - Project settings
- **`README.md`** - This file

That's it! No complicated folders or files.

---

## 🧮 How the Calculations Work

The calculator uses real environmental science formulas:

- **Car:** km/day × 365 × 0.00021 = annual CO₂
- **Flights:** number of flights × 0.5 tonnes
- **Electricity:** kWh/month × 12 × 0.00082 = annual CO₂
- **Diet:** Fixed values (vegan = 1 tonne, vegetarian = 1.5, etc.)

Global average is **4.0 tonnes per person per year**.

---

## ✏️ Want to Change Something?

Edit `index.html` to customize:
- **Colors:** Search for `#1a472a` or `#2d5a3d`
- **Formulas:** Look for the `calculate()` function
- **Diet options:** Change `DIET_CO2` object
- **Global average:** Change `const GLOBAL_AVERAGE = 4.0;`
