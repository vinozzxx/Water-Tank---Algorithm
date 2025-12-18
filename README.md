#  Water Tank Problem – Vanilla JavaScript Web App

A simple **frontend web application** that visualizes and calculates how much **rainwater is trapped between blocks** of different heights. This project is built using **HTML, CSS, and Vanilla JavaScript** and follows the classic **Water Tank (Trapping Rain Water) problem**.

---

##  Screenshots

![Water Tank Output](https://github.com/vinozzxx/Water-Tank---Algorithm/blob/e30c166b30128a605762003f75def5fb1b6ce348/image%201%20%20.png)

![Water Tank Output](https://github.com/vinozzxx/Water-Tank---Algorithm/blob/e30c166b30128a605762003f75def5fb1b6ce348/image%202%20.png)

---

##  Project Need / Purpose

In many real‑world and technical interview scenarios, we need to **analyze elevation data** and calculate how much water can be stored between structures.

This project helps to:

* Understand **array-based problem solving**
* Apply **logic and mathematical reasoning** visually
* Practice **DOM manipulation** using Vanilla JavaScript
* Demonstrate frontend skills for **interview assignments**

The app visually represents blocks and trapped water, making the logic **easy to understand**.

---

##  Problem Statement

Given an array of non‑negative integers representing block heights, compute how many **units of water** are trapped between the blocks after raining.

### Example

```
Input  : [0, 4, 0, 0, 0, 6, 0, 6, 4, 0]
Output : 18 Units
```

---

## Technologies Used

* **HTML5** – Structure of the application
* **CSS3** – Styling and layout
* **JavaScript (ES6)** – Core logic & visualization
* **SVG / Div-based blocks** – Water tank representation

---

##  Project File Structure

```
WATER-TANK/
│
├── index.html      # Main HTML file
├── style.css       # Styling for blocks and water
├── script.js       # Water calculation logic
├── README.md       # Project documentation
└── .gitignore      # Git ignored files
```

---

##  How It Works

1. User provides an **array of block heights**
2. JavaScript calculates:

   * Left maximum height
   * Right maximum height
3. Water trapped at each position is calculated using:

```
water = min(leftMax, rightMax) - height[i]
```

4. Total trapped water is displayed
5. Blocks and water are **visually rendered**


##  How to Run the Project

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/water-tank-problem.git
   ```

2. Open the project folder

3. Double‑click `index.html`

4. View the output in your browser

---

##  Output

* Displays **total water units trapped**
* Shows **visual blocks and water levels**

---

##  Learning Outcomes

* Strong understanding of array traversal
* Frontend problem‑solving practice
* Visualization of algorithms
* Clean project structure for GitHub

---

##  Author

**Vinothkumar**
Aspiring Data Scientist 

