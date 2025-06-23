# Budget App - Final Submission

## Overview

This budget tracking app allows users to record income and expenses, visualize spending habits, set financial goals, and stay motivated through gamification.

---

## ✅ Required Final POE Features Implemented

### 1. **Graph of Spending per Category**

* Users can select a time period (Last Week or Last Month).
* A bar graph displays how much was spent in each category.

### 2. **Spending Goals Visualization**

* Bars turn **green** if spending per category is within the set minimum (R300) and maximum (R800) budget.
* A message shows whether the user is under, over, or within budget.

### 3. **Gamification Elements**

* 🏅 **Budget Master** badge for staying within budget.
* 📈 **Consistent Logger** badge for using 5+ categories.
* 🔔 **Keep Going!** encouragement if neither badge criteria are met.

---

## ✨ Custom Features (Required: 2)

### Feature 1: **Average Spending per Category**

* When the user selects a time period, the app calculates the average amount spent across all categories.
* This is displayed in a toast message: `📊 Average spent per category: RXXX.XX`

### Feature 2: **Savings Goal Calculator**

* Users can input:

  * A target savings amount
  * A time period in weeks
* The app calculates if the savings are possible based on current income and expenses.
* Displays:

  * Required weekly savings
  * If savings goal is achievable
  * Shortfall message if not achievable

---

## 📱 App Icon & Assets

* A custom launcher icon has been included in the `mipmap` folders.
* Final graphical assets such as category icons and graph styling are added in `res/drawable`.

---

## 🔧 Tech Stack

* **Language**: Kotlin
* **Layout**: XML
* **Min SDK**: 24
* **Target SDK**: 35

---

## 🧪 Testing

* All features have been tested manually on Android 13 and 14 emulators.
* User input validation, goal calculation, and graph rendering verified.

---

## 🚀 How to Run

1. Clone or download the project.
2. Open in Android Studio.
3. Sync Gradle and run the app on a device or emulator.

---

## 🎓 Notes

This project was developed as a practical submission for the final POE. It meets all specified requirements and includes two additional enhancements.
