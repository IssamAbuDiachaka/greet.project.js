# ⏰ Smart Time-Based Greeter

A clean and modern JavaScript web app that greets users based on the current time of day.  
This README serves as the **project specification** to guide step-by-step implementation.

---

## 🎯 Project Objective

Build a portfolio-ready JavaScript project that demonstrates:
- Time-based logic
- DOM manipulation
- Clean code structure
- UX & accessibility awareness

---

## 🛠 Tech Stack

- HTML5
- CSS3 (CSS Variables & Transitions)
- Vanilla JavaScript (ES6+)

No frameworks. No libraries.

---

## 🎨 Design & UX Specification

### Time Periods & Themes

| Time Period | Time Range | Theme Style |
|------------|-----------|-------------|
| Morning    | 05:00–11:59 | Light / Soft |
| Afternoon  | 12:00–16:59 | Bright / Blue |
| Evening    | 17:00–20:59 | Warm / Sunset |
| Night      | 21:00–04:59 | Dark Mode |

Each theme must affect:
- Background
- Text color
- Accent elements (buttons, highlights)

---

## ✅ Feature Specifications (Implementation Order)

### Step 1 — Base Layout
- Static HTML structure
- Greeting placeholder
- “Greet Me” button
- Digital clock placeholder
- No JavaScript logic

---

### Step 2 — Time Detection Logic
- Detect current hour using JavaScript
- Map hour → time period
- Return structured data:
```
{ period: "morning", greeting: "Good morning" }
```

---

### Step 3 — Greeting Rendering
- Button click triggers greeting
- Greeting updates text content
- Keyboard support (Enter key)

---

### Step 4 — Dynamic Theme Switching
- CSS classes for each theme
- JavaScript applies/removes theme classes
- No inline styles

---

### Step 5 — Live Clock
- Display HH:MM:SS
- Update every second
- Must not require page refresh

---

### Step 6 — Personalization (Local Storage)
- Ask user for name once
- Store name in localStorage
- Greeting includes name
- Data persists after reload

---

### Step 7 — Auto-Greet Mode
- Greet user on page load
- Greeting updates automatically when time period changes
- Manual greeting still available

---

### Step 8 — Quotes by Time Period
- One quote per time period
- Quotes stored in JS object/array
- Quote updates with greeting

---

### Step 9 — Accessibility & UX
- Accessible labels
- Keyboard navigation
- Smooth transitions
- Responsive design

---

## 📂 Suggested Folder Structure

```
smart-time-greeter/
├── index.html
├── styles.css
├── app.js
├── utils/
│   ├── timeUtils.js
│   └── storage.js
└── README.md
```

---

## 🧪 Testing Checklist

- Correct greeting per time
- Correct theme per time
- Name persists after refresh
- Clock runs continuously
- No console errors

---

## 🚀 Deployment

Deploy using GitHub Pages or Netlify.

---

## 👨‍💻 Author

Issam Abu  
Computer Science Student
