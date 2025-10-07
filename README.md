# 🎨 **FillAlgorithmsDemo.java – Interactive Graphics Fill Algorithms**

## 🧭 Overview

**FillAlgorithmsDemo** is a fun and educational Java AWT project that visually demonstrates **three classic fill algorithms** used in computer graphics — **Flood Fill**, **Boundary Fill**, and **Scanline Fill**.
It provides an **interactive GUI** where users can draw shapes, click to fill areas, and instantly see how each algorithm behaves.

Whether you're a student learning graphics or just curious about how paint programs work under the hood, this project makes the concept come alive!

---

## 🚀 **Key Highlights**

✅ **Three Algorithms in One App:** Switch between *Flood Fill*, *Boundary Fill*, and *Scanline Fill* easily from the menu.
🖱️ **Interactive GUI:** Click to fill or draw directly on the canvas.
🎨 **Real-Time Visualization:** Watch how each fill algorithm operates visually.
⌨️ **Keyboard + Mouse Controls:** Simple and intuitive interaction.
🧠 **Educational Purpose:** Perfect for understanding pixel-based fill logic and scanline techniques.

---

## 🧩 **How It Works**

### 🟢 **1. Flood Fill**

* Select **Flood Fill** from the menu.
* Click **inside the rectangle**.
* The algorithm fills connected pixels until boundaries are reached.
* (Fills shown in **red**)

### 🔵 **2. Boundary Fill**

* Select **Boundary Fill** from the menu.
* Click **inside the boundary** area.
* The fill continues until it reaches boundary pixels.
* (Fills shown in **blue**)

### 🟠 **3. Scanline Fill**

* Select **Scanline Fill** from the menu.
* Click multiple points to draw a polygon.
* Press **F** to fill the shape line-by-line.
* (Fills shown in **orange**)

---

## ⚙️ **Setup & Execution**

### 🪶 Requirements

* Java JDK 8 or higher
* Any IDE (Eclipse, IntelliJ, NetBeans) or command line

### 🧱 Steps to Run

1. Save the file as **`FillAlgorithmsDemo.java`**
2. Compile it:

   ```bash
   javac FillAlgorithmsDemo.java
   ```
3. Run the program:

   ```bash
   java FillAlgorithmsDemo
   ```
4. The window will appear — select an algorithm from the **Algorithms menu** and interact using your mouse and keyboard.

---

## 🧠 **Concepts Demonstrated**

* Recursive **Flood Fill & Boundary Fill** logic
* Polygon filling using the **Scanline Algorithm**
* **AWT Event Handling:** `MouseListener`, `KeyListener`, and `ActionListener`
* Real-time **graphics rendering** with `paint()` and pixel arrays
* Dynamic GUI creation with **Java AWT**

---

## 🕹️ **Controls Summary**

| Action                   | Description                              |
| ------------------------ | ---------------------------------------- |
| **Menu → Flood Fill**    | Activates flood fill mode                |
| **Menu → Boundary Fill** | Activates boundary fill mode             |
| **Menu → Scanline Fill** | Enables polygon mode                     |
| **Mouse Click**          | Selects fill area or adds polygon points |
| **F Key**                | Fills polygon (only in Scanline mode)    |
| **Close Window**         | Exits the program                        |

---

## 🌈 **Why This Project Is Awesome**

* Turns abstract graphics concepts into **visual, interactive learning**
* Simple code structure — easy to understand and extend
* Great for **computer graphics assignments** and **demos**
* Helps visualize how **painting tools** fill areas in real applications

---

## 📄 **License**

This project is **open-source** and available for **educational and personal use**.
You may freely use, modify, and share it — just give proper credit.

---
