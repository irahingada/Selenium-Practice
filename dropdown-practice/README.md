# ✈️ Dropdown Practice – Selenium Java

This folder contains automated test scripts using Selenium WebDriver in Java to practice working with dropdowns, checkboxes, and radio buttons in a flight booking form.

Website used: [https://rahulshettyacademy.com/dropdownsPractise/](https://rahulshettyacademy.com/dropdownsPractise/)

---

## 🧪 Covered Scenarios

### ✅ `seleniumpracticedropdowns.java`
- Handling dropdown with `<select>` tag using `Select` class
- Selecting values by index, visible text, and value
- Interacting with passenger count pop-up and increment buttons
- Validating selected passenger count using `Assert`

### ✅ `seleniumpracticedropdowns2.java`
- Selecting source and destination using dynamic dropdowns (not `<select>`)
- Working with date pickers using CSS selectors
- Toggling checkboxes (e.g., Friends & Family)
- Validating radio button behavior (One Way vs Round Trip)
- Checking element state using DOM attributes
- Using `Assert.assertTrue()` and `Assert.assertFalse()` for validation

---

## 🛠 Tools & Tech

- **Java**
- **Selenium WebDriver**
- **TestNG** (used for assertions)
- **ChromeDriver**
- IDE: **Eclipse**

---

## 🧠 Key Learnings

- Difference between static and dynamic dropdowns
- Locators: `id`, `className`, `xpath`, `cssSelector`
- Using `Thread.sleep()` for wait simulation (note: not ideal for production)
- DOM attribute handling using `getDomAttribute()` and `getAttribute()`
- Using assertions to validate test steps

---

## 👩‍💻 Author

**Ira Jade Hingada**  
Career Shifter | QA Manual Tester | Learning Selenium Automation  
