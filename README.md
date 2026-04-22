<div align="center">

# 💸 ExpenseTracker

### *Take control of every penny — right from your pocket.*

[![Android](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com)
[![Java](https://img.shields.io/badge/Language-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com)
[![Android Studio](https://img.shields.io/badge/IDE-Android%20Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white)](https://developer.android.com/studio)
[![SQLite](https://img.shields.io/badge/Database-SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

<br/>

> 🎓 Built by college students, for college students — because your budget deserves better than a spreadsheet.

<br/>

---

</div>

## 📖 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🧾 About

**ExpenseTracker** is a native Android application that helps you log, categorize, and visualize your daily expenses and income — all stored locally on your device. No sign-up, no cloud, no fuss.

Born out of the very real struggle of budgeting on a student income, this app puts a powerful financial diary right in your pocket. Whether you're tracking your coffee habit or your monthly rent, ExpenseTracker keeps it simple and visual.

---

## ✨ Features

### 🏠 Main Dashboard
- **Interactive Pie Chart** — instantly see how your spending breaks down by category
- **Time-period filtering** — view your data across custom date ranges
- **Category quick-view** — tap any category icon to see the total spent/earned at a glance

### 💳 Expense Logging
- Add expenses with a **date picker** and **category selector**
- Data is saved instantly to the **local SQLite database**
- Expenses appear on the main dashboard pie chart in real time

### 💰 Income Tracking
- Log multiple income sources just as easily as expenses
- Unified interface keeps the learning curve flat

### 🔍 Smart Search
- Tap the search icon in the action bar to find expenses **by category**
- Browse a detailed list of all matching transactions
- **Swipe or tap to delete** any record instantly

---

## 📱 Screenshots

> _Coming soon — screenshots will be added here._

<!-- Uncomment and replace paths once you have screenshots:
| Dashboard | Expense Page | Income Page | Search |
|-----------|-------------|-------------|--------|
| ![Dashboard](screenshots/dashboard.png) | ![Expense](screenshots/expense.png) | ![Income](screenshots/income.png) | ![Search](screenshots/search.png) |
-->

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| **Language** | Java |
| **IDE** | Android Studio |
| **Build System** | Gradle 7.0.4 |
| **Database** | SQLite (`SQLiteOpenHelper`) |
| **UI Components** | `RecyclerView`, `ListView`, `GridView`, `CircleView` |
| **Navigation** | Navigation Drawer, Bottom Navigation Bar |
| **Charts** | Pie Chart (CircleView) |
| **Search** | `SearchView` |
| **Layouts** | Relative Layout, Drawer Layout |

---

## 🚀 Getting Started

### Prerequisites

- **Android Studio** Arctic Fox or newer
- **Android SDK** API 21+ (Android 5.0 Lollipop)
- **JDK 8** or higher

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Ammarahmed-git/ExpenseTrackerApp.git

# 2. Open in Android Studio
#    File → Open → Select the cloned folder

# 3. Let Gradle sync automatically

# 4. Run on an emulator or physical device
#    Run → Run 'app'  (or press Shift + F10)
```

> 💡 **Tip:** Make sure your emulator or device is running **Android 5.0 (API 21)** or above.

---

## 📁 Project Structure

```
ExpenseTrackerApp/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/         # Java source files (Activities, DB helpers, Adapters)
│   │       ├── res/          # Layouts, drawables, menus, values
│   │       └── AndroidManifest.xml
│   └── build.gradle          # Module-level dependencies
├── build.gradle              # Project-level Gradle config
├── gradle.properties
├── settings.gradle
└── README.md
```

---

## 🤝 Contributing

Contributions are welcome and appreciated! Here's how to get involved:

1. **Fork** the repository
2. **Create** a feature branch — `git checkout -b feature/amazing-feature`
3. **Commit** your changes — `git commit -m 'Add some amazing feature'`
4. **Push** to the branch — `git push origin feature/amazing-feature`
5. **Open a Pull Request**

Please make sure your code follows the existing style and that you test on at least one physical or emulated device before submitting.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

Made with ❤️ by [Ammar Ahmed](https://github.com/Ammarahmed-git)

⭐ If you found this useful, consider giving it a star!

</div>
