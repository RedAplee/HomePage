# Homepage

**Homepage** is a customizable personal start page designed to bring your favorite websites, useful tools, notes, tasks, deadlines, and everyday information together in one place.

It works as a personal dashboard that you can organize around your own workflow — whether you use it for studying, work, projects, gaming, browsing, or everyday tasks.

---

## ✨ Features

### 🔗 Personal Website Dashboard

Create your own collection of website shortcuts directly on the homepage.

You can:

* Create custom categories
* Add websites to categories
* Rename and organize categories
* Delete categories
* Remove individual links
* Drag and drop categories to change their order
* Drag and drop links between categories
* Reorder links inside categories
* Open websites directly from the dashboard

The dashboard starts with an empty collection, so you can build it exactly the way you want.

---

### 👤 Personal Profile

On the first launch, Homepage asks you to choose a nickname.

Your nickname is used inside the interface and is stored locally in your browser.

You can change it later through:

**Menu → Settings → Profile**

The name is also included in exported Homepage presets.

---

### 🔍 Built-in Search

Homepage includes a built-in search bar.

You can choose your preferred search engine:

* Yandex
* Google
* DuckDuckGo

The selected search engine is remembered automatically.

Search results are opened in a new browser tab.

---

### 🎨 Themes

Homepage includes multiple visual themes that can be selected from Settings.

Available themes include:

* Dark
* Red
* Orange
* Yellow
* Green
* Cyan
* Blue
* Purple
* Pink
* Rainbow
* Light
* Black
* Gray
* Nordic

The selected theme is saved locally and restored automatically on the next visit.

---

### 🌌 Animated Backgrounds

Homepage supports several animated background modes:

* **Ghost Fibers** — animated glowing fibers
* **Topography** — animated topographic-style lines
* **Color Bends** — animated color shapes and bends
* **None** — static background

The animated backgrounds are rendered directly in the browser and adapt to the selected visual theme.

---

### 🪟 Glass UI

Homepage includes an optional **Glass UI** effect.

It gives interface elements a translucent glass-like appearance.

You can enable or disable it from:

**Menu → Settings → Interface**

The selected state is saved automatically.

---

## 📦 Presets

One of the most important Homepage features is the ability to save and transfer your dashboard configuration.

### Export

You can export your current Homepage configuration as a JSON file:

**Menu → Presets → Export JSON**

The filename is based on your nickname.

For example:

```text
Alex.json
```

A preset contains information such as:

* Homepage name
* Categories
* Website links
* Category order
* Link order

This makes JSON files useful as personal backups or portable dashboard configurations.

### Import

You can restore a previously exported preset through:

**Menu → Presets → Import JSON**

Before replacing your current collection, Homepage asks for confirmation.

If the imported preset contains a different valid nickname, Homepage can also ask whether you want to replace your current name with the name stored in the preset.

### Share

Homepage also provides a **Share Link** option from the Presets menu for sharing the current configuration.

---

## ⏳ Exams & Deadlines

Homepage includes a built-in countdown system for exams and deadlines.

You can:

* Add an exam or deadline
* Specify its title
* Set its date and time
* View upcoming deadlines
* See the remaining time

This can be especially useful for students who want their important dates available directly from their start page.

---

## 📊 Statistics

Homepage can track website activity locally.

The statistics section provides information such as:

* Total visits for a selected day
* Number of unique websites visited
* Most visited websites
* Peak activity hour
* Hourly activity visualization

A date selector allows you to inspect statistics for a particular day.

The data is stored locally in the browser.

---

## 📝 Mini-Notion

Homepage contains a lightweight notes and knowledge-base system.

You can:

* Create notes
* Give notes titles
* Assign categories
* Add tags
* Search through notes
* Pin important notes
* Add notes to favorites
* Edit note content
* Delete notes
* Copy note content
* Export notes as Markdown
* Export notes as TXT
* Import Markdown and TXT files

Available note categories include areas such as:

* General
* Study
* Projects
* Ideas

This makes Homepage useful not only as a website launcher, but also as a lightweight personal workspace.

---

## ✅ Todo Manager

Homepage includes a built-in task manager.

It provides a dedicated space for managing tasks and tracking progress.

The interface includes task controls, filters, statistics, and a progress indicator, allowing you to keep everyday tasks alongside your websites and notes.

---

## 🕸️ Website Graph

Homepage includes a visual **Website Graph** that represents relationships between your categories and websites.

The graph provides:

* Visual category and website nodes
* Node search
* Zoom controls
* Centering
* Node dragging
* Website opening directly from the graph

This gives you another way to explore a large collection of websites.

---

## 🛠️ Mini Utilities

Homepage also includes a collection of small everyday utilities.

### 💱 Currency Converter

The dashboard contains a currency converter with rates from the **Central Bank of Russia**.

It supports:

* RUB
* USD
* EUR
* CNY

Rates can be refreshed, and the converter can calculate values between supported currencies.

### 🎲 Random Number Generator

Generate a random number within a custom range.

For example:

```text
1 — 100
```

### 🔐 Password Generator

Generate a random password with a configurable length.

The generated password is displayed directly inside the utility panel.

### ⏱️ Stopwatch

Homepage also provides a simple stopwatch for measuring elapsed time.

---

## 💾 Local Storage

Homepage is designed to keep your personal dashboard data in the browser.

Settings and personal data such as:

* Nickname
* Theme
* Background
* Glass UI state
* Search engine
* Website collection
* Statistics
* Notes
* Tasks
* Exams and deadlines

can be stored locally.

This allows Homepage to remember your configuration between visits without requiring a traditional account system.

For portability and backup, use the **JSON Presets** feature.

---

## ⌨️ Navigation

Homepage uses modal windows for many of its additional features.

The **ESC** key can be used to navigate back through opened interface layers, making it possible to quickly return from a feature to its parent menu.

---

## 🚀 Getting Started

Homepage is designed as a simple web application.

Open the HTML file in a modern web browser and start customizing your dashboard.

### Basic workflow

1. Open Homepage.
2. Choose your nickname.
3. Create your first category.
4. Add your favorite websites.
5. Arrange categories and links using drag and drop.
6. Choose a theme and background.
7. Enable or disable Glass UI.
8. Use the built-in tools when needed.
9. Export your Homepage as JSON to keep a backup.

---

## 🎯 Use Cases

Homepage can be used as:

* 🎓 Student start page
* 💼 Work dashboard
* 🧑‍💻 Developer start page
* 🎮 Gaming dashboard
* 📚 Study workspace
* 📋 Personal task manager
* 📝 Lightweight knowledge base
* 🔗 Website launcher
* 🛠️ Everyday utility dashboard

---

## 🔒 Privacy

Homepage is designed around local browser storage rather than requiring a user account.

Your personal dashboard configuration is kept on the device/browser where you use Homepage.

If you need to move your setup to another browser or device, export it using the JSON Preset system.

---

## 🧩 Project Structure

Homepage is implemented as a self-contained web page.

The main application is contained in:

```text
index.html
```

The project does not require a traditional multi-file frontend structure to run the dashboard.

---

## 📌 Project Philosophy

Homepage is built around a simple idea:

> **Your browser's start page should work for you, not against you.**

Instead of opening dozens of tabs or keeping bookmarks scattered across different places, Homepage provides one customizable workspace for the websites and tools you use every day.

---

## 📄 License

Add your preferred open-source license here, for example:

```text
MIT License
```

if the project is intended to be distributed under the MIT license.
