# 📊 Matplotlib — Complete Learning Repository

> A structured, hands-on collection of Jupyter Notebooks for mastering **Matplotlib** — from basic plotting fundamentals to advanced 3D visualizations and customizations.

---

## 📌 About This Repository

This repository is a **beginner-to-advanced guide** to the Matplotlib library in Python. Each notebook is focused on a specific topic, making it easy to learn progressively or jump straight to what you need.

Whether you're just starting your data visualization journey or looking to level up with subplots, 3D plots, and annotations — this repo has you covered with practical, hands-on examples throughout.

---

## 📁 Repository Structure

```
matplotlib/
│
├── 📓 basic_plotting.ipynb        # Core plotting concepts — line plots, scatter, bar, histograms & more
├── 📓 advance_matplotlib.ipynb    # Advanced techniques — 3D plots, subplots, annotations & styling
├── 📂 data/                       # Datasets used across notebooks
├── 📄 requirements.txt            # Required Python libraries
└── 📄 README.md                   # You are here!
```

---

## 📓 Notebooks Overview

### 1. `basic_plotting.ipynb` — Basic Plotting

A comprehensive introduction to Matplotlib covering all essential plot types and customizations:

#### 📈 Line Plots
- Creating 2D line plots with `plt.plot()`
- Customizing with **legends**, **marker sizes**, **line styles**, and **colors**
- Labeling axes and adding titles

#### 🔵 Scatter Plots
- Building scatter plots with `plt.scatter()`
- Customizing point size, color, and transparency (`alpha`)
- Using scatter plots for data distribution and correlation analysis

#### 📊 Bar Charts
- Vertical and horizontal bar charts
- Grouped and stacked bar charts
- Customizing bar colors, widths, and edge styling

#### 📉 Histograms
- Plotting frequency distributions with `plt.hist()`
- Controlling bin size and density
- Overlapping histograms for comparison

#### 🥧 Pie Charts
- Creating pie charts with `plt.pie()`
- Adding labels, percentages, and explode effects
- Customizing colors and shadow effects

#### 🎨 Changing Styles
- Applying built-in Matplotlib styles (`plt.style.use()`)
- Customizing figure sizes, DPI, and backgrounds
- Using Pandas `.plot()` functions directly on DataFrames

---

### 2. `advance_matplotlib.ipynb` — Advanced Matplotlib

Deep-dive into advanced Matplotlib features used in real data science workflows:

#### 🌈 Colored Scatter Plots
- Mapping a third variable to color using `c` and `cmap`
- Adding color bars for scale reference

#### 📐 Plot Size & Layout
- Controlling figure dimensions with `figsize`
- Fine-tuning padding and spacing

#### 🏷️ Annotations
- Adding text annotations with `plt.annotate()`
- Using arrows and callouts to highlight data points
- Placing labels precisely on graphs

#### ➖ Horizontal & Vertical Lines
- Drawing reference lines with `plt.axhline()` and `plt.axvline()`
- Using lines to mark thresholds, means, and critical values for data extraction

#### 🪟 Subplots
- Creating multi-plot layouts with `plt.subplot()` and `plt.subplots()`
- Sharing axes across subplots
- Managing tight layouts and spacing

#### 🧊 3D Plots (using `mpl_toolkits.mplot3d`)
- **3D Scatter Plot** — visualizing 3D data point distributions
- **3D Line Plot** — plotting trajectories and paths in 3D space
- **3D Surface Plot** — rendering smooth mathematical surfaces
- **3D Contour Plot** — displaying level curves over a 3D surface

#### 🔥 Heatmaps
- Creating heatmaps with `plt.imshow()` and color maps
- Adding color bars and axis labels
- Visualizing matrix data and correlations

#### 🐼 Pandas Plot Functions
- Using `.plot()`, `.plot.bar()`, `.plot.hist()` directly on DataFrames
- Combining Pandas and Matplotlib for seamless data visualization

---

## 🗺️ Suggested Learning Path

```
basic_plotting.ipynb
        ↓
  Line Plots → Scatter Plots → Bar Charts → Histograms → Pie Charts → Styles
        ↓
advance_matplotlib.ipynb
        ↓
  Colored Scatter → Annotations → H/V Lines → Subplots → 3D Plots → Heatmaps
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| 🐍 Python 3.x | Programming Language |
| 📊 Matplotlib | Data Visualization |
| 🐼 Pandas | Data Manipulation & Plot Integration |
| 🔢 NumPy | Numerical Operations |
| 📓 Jupyter Notebook | Interactive Python Environment |

---

## 🚀 Getting Started

### Prerequisites

Make sure Python is installed, then install the required libraries:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install matplotlib pandas numpy jupyter
```

### Run the Notebooks

1. **Clone this repository:**
```bash
git clone https://github.com/mohitjaryal/matplotlib.git
cd matplotlib
```

2. **Launch Jupyter Notebook:**
```bash
jupyter notebook
```

3. **Open any notebook** from the browser and start visualizing! 🎉

---

## 💡 Who Is This For?

- 🎓 Students learning Python for Data Science or Data Analysis
- 👩‍💻 Beginners who want to master data visualization from scratch
- 📊 Anyone building a strong Matplotlib foundation step by step

---

## 🤝 Contributing

Contributions, suggestions, and improvements are always welcome!

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add: your feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📬 Connect with Me

| Platform | Link |
|----------|------|
| 🌐 Website | [mohitjaryal.online](https://mohitjaryal.online) |
| 💼 LinkedIn | [in/mohitjaryal](https://www.linkedin.com/in/mohitjaryal) |
| 🐦 Twitter/X | [@mohitjaryal04](https://x.com/mohitjaryal04) |
| 💻 GitHub | [mohitjaryal](https://github.com/mohitjaryal) |
| 🧩 LeetCode | [mohitjaryal](https://leetcode.com/u/mohitjaryal) |
| 🧩 HackerRank | [mohitjaryal](https://hackerrank.com/u/mohitjaryal) |

---

<div align="center">

**⭐ If this repo helped you, consider giving it a star — it motivates me to keep learning and sharing!**

*Made with 💙 by [Mohit Jaryal](https://mohitjaryal.online)*

> *"A picture is worth a thousand data points — and Matplotlib paints them all."* 📊

</div>
