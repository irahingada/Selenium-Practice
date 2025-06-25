# 🔡 Auto-Suggestive Dropdown Practice with Selenium

This script demonstrates how to handle **auto-suggestive dropdowns** using Selenium WebDriver in Java.

---

## 🔍 Features Covered

- Typing a partial string into an input field
- Waiting for the auto-suggestions to appear
- Capturing the dropdown suggestions as a list of `WebElement`
- Iterating through the list and selecting the matching suggestion (e.g., **"India"**)

---

## 🎯 Purpose

Auto-suggestive dropdowns are dynamic elements that require specific handling techniques. This script helps you:

- Work with dynamic lists
- Use `List<WebElement>` to capture multiple options
- Loop through and interact with the correct value

---

## 🛠 Tools Used

- **Java**
- **Selenium WebDriver**
- **ChromeDriver**
- **Eclipse IDE**

---

## 📌 Notes

- A short `Thread.sleep()` is used to allow time for suggestions to load. In real-world applications, it's better to use **explicit waits**.
- This test uses the **Rahul Shetty practice site** and is intended for learning purposes only.
