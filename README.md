# 🧩 Stark Labs – Project JSON Panel

This is a lightweight and responsive admin interface built with **HTML + TailwindCSS** that allows Stark Labs team members to quickly create and export **JSON data for 3D printing projects**.

## ✨ Features

- Generate structured JSON files for each project.
- Auto-pathing for thumbnails, images, and STL files.
- Live JSON preview and copy-to-clipboard support.
- Dark mode ready.
- Built using TailwindCSS.

## 📁 Folder Structure
```
project-json-panel/
├── index.html
├── /gallery/
│ └── project-id/
│ ├── 1.jpg
│ ├── 2.jpg
│ └── model.stl
```

## 🧠 Data Fields

| Field        | Description                      |
|--------------|----------------------------------|
| id           | Project folder name              |
| title        | Project title                    |
| material     | Type of filament used            |
| weight       | Weight in grams                  |
| resolution   | Layer height (e.g., 0.2mm)       |
| price        | Price in EGP                     |
| printTime    | Estimated print duration         |
| designLink   | (Optional) Internal reference    |
| likes        | Like count (default: 125)        |
| description  | Short project description        |
| thumbnail    | Auto-generated from `id`         |
| model        | Auto path to `.stl` file         |
| images       | Array of image paths             |
| tags         | Can be extended (default empty)  |

## 🚀 Getting Started

Just open `index.html` in a browser. No backend or build steps needed.

---

© 2025 Stark Labs. All rights reserved.
