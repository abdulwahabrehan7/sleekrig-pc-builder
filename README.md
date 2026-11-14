# SleekRig - Custom PC Architect 🖥️⚡

**SleekRig** is a high-performance, minimalist PC component builder and hardware cost estimator web application. Built with a modern monochrome aesthetic, it features a massive 850+ component catalog, real-time multi-currency conversion, an intelligent compatibility diagnostics engine, and off-screen vector PDF specification exports.

---

## ✨ Key Features

* **Massive Hardware Database:** 100+ components per category spanning CPUs, GPUs, Motherboards, RAM, Storage, PSUs, Cases, and Coolers.
* **Multi-Currency Engine:** Seamlessly toggle between **USD ($)**, **AED (د.إ)**, and **INR (₹)** with automatic local exchange rate conversions and custom part price normalization.
* **Intelligent Diagnostics & Compatibility Engine:** Automatically checks socket matching (Intel/AMD), form-factor sizing (ATX vs. Micro-ATX), memory generation (DDR4 vs. DDR5), and power supply (PSU) wattage headroom.
* **Custom Component Creator:** Allows users to add and price custom components on the fly within any category.
* **Vector PDF Exports:** Generates clean, aligned system spec sheets instantly via `html2pdf.js` with off-screen viewport rendering to prevent blank-page bugs.
* **Local Storage Persistency:** Remembers your custom-built rig across sessions.
* **Responsive Dark/Light Mode:** Built with a clean, single-page monochrome design system using Tailwind CSS.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, Tailwind CSS (v3 with custom configuration)
* **Scripting:** Vanilla JavaScript (ES6+ Modules, IIFE Database Architecture)
* **Icons & Fonts:** Font Awesome 6, Inter, JetBrains Mono
* **Export Engine:** `html2pdf.js` (`html2canvas` + `jsPDF`)

---

## 🚀 Getting Started

To run this project locally, simply clone the repository and open the index file:

```bash
# Clone the repository
git clone [https://github.com/abdulwahabrehan7/sleekrig-pc-builder.git](https://github.com/abdulwahabrehan7/sleekrig-pc-builder.git)

# Navigate to the project directory
cd sleekrig-pc-builder

# Open index.html in your preferred browser
# (Or use a live server extension in VS Code)
