# 📊 Data Visualization using Matplotlib and Seaborn

A hands-on Python repository for learning **Data Visualization using Matplotlib and Seaborn** through practical Jupyter Notebook examples.

This project covers fundamental visualization techniques including **bar charts, histograms, pie charts, scatter plots, subplots, and Seaborn visualizations**. It is designed for students and beginners who want to develop practical data visualization skills for **Data Science and Data Analysis**.

---

## 🚀 About the Project

Data visualization is an important part of Data Science because it helps transform raw data into meaningful visual insights.

This repository provides practical examples of creating and customizing different types of plots using:

* 📈 **Matplotlib**
* 📊 **Seaborn**
* 🐍 **Python**
* 📓 **Jupyter Notebook**

The notebooks progress from basic Matplotlib concepts to different visualization techniques and Seaborn-based plots.

---

## 📚 Topics Covered

| # | Topic                      | Notebook                        |
| - | -------------------------- | ------------------------------- |
| 1 | Introduction to Matplotlib | `Introduction_Matplotlib.ipynb` |
| 2 | Bar Plots                  | `BarPlot.ipynb`                 |
| 3 | Histograms                 | `Histogram.ipynb`               |
| 4 | Pie Charts                 | `PieCharts.ipynb`               |
| 5 | Scatter Plots              | `ScatterPlots.ipynb`            |
| 6 | Seaborn Visualization      | `Seaborn_Plots.ipynb`           |
| 7 | Subplots                   | `Subplots.ipynb`                |

---

## 🗂️ Repository Structure

```text
Data-Visualization-using-Matplotlib-and-Seaborn/
│
├── Introduction_Matplotlib.ipynb
├── BarPlot.ipynb
├── Histogram.ipynb
├── PieCharts.ipynb
├── ScatterPlots.ipynb
├── Seaborn_Plots.ipynb
├── Subplots.ipynb
│
├── analysis1.pdf
├── output.png
│
└── README.md
```

---

## 🛠️ Technologies Used

* 🐍 **Python**
* 📊 **Matplotlib**
* 🎨 **Seaborn**
* 📓 **Jupyter Notebook**
* 🧮 **NumPy**
* 🐼 **Pandas**

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/sarhan-003/Data-Visualization-using-Matplotlib-and-Seaborn.git
```

### 2. Navigate to the Project

```bash
cd Data-Visualization-using-Matplotlib-and-Seaborn
```

### 3. Install Required Libraries are initial to download

```bash
pip install matplotlib seaborn pandas numpy jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open any `.ipynb` file and execute the cells.

---

## 📈 Visualization Techniques

### 📊 Bar Plot

Bar plots are useful for comparing values across different categories.

```python
import matplotlib.pyplot as plt

categories = ["A", "B", "C", "D"]
values = [20, 35, 30, 45]

plt.bar(categories, values)
plt.xlabel("Category")
plt.ylabel("Value")
plt.title("Bar Plot")
plt.show()
```

---

### 📉 Histogram

Histograms are useful for understanding the **distribution of numerical data**.

```python
import matplotlib.pyplot as plt

data = [10, 12, 15, 15, 18, 20, 21, 22, 25, 25, 30]

plt.hist(data, bins=5)
plt.xlabel("Value")
plt.ylabel("Frequency")
plt.title("Histogram")
plt.show()
```

---

### 🥧 Pie Chart

Pie charts represent the proportion of different categories within a whole.

```python
import matplotlib.pyplot as plt

labels = ["Python", "Java", "C++", "JavaScript"]
values = [40, 25, 20, 15]

plt.pie(values, labels=labels, autopct="%1.1f%%")
plt.title("Programming Language Distribution")
plt.show()
```

---

### 🔵 Scatter Plot

Scatter plots help visualize relationships between two numerical variables.

```python
import matplotlib.pyplot as plt

x = [1, 2, 3, 4, 5]
y = [2, 4, 5, 8, 10]

plt.scatter(x, y)
plt.xlabel("X")
plt.ylabel("Y")
plt.title("Scatter Plot")
plt.show()
```

---

### 🎨 Seaborn Plots

Seaborn provides a high-level interface for creating attractive statistical visualizations.

```python
import seaborn as sns
import matplotlib.pyplot as plt

sns.set_theme()

data = sns.load_dataset("tips")

sns.scatterplot(
    data=data,
    x="total_bill",
    y="tip"
)

plt.title("Total Bill vs Tip")
plt.show()
```

---

### 🧩 Subplots

Subplots allow multiple visualizations to be displayed within a single figure.

```python
import matplotlib.pyplot as plt

fig, axes = plt.subplots(1, 2)

axes[0].plot([1, 2, 3, 4])
axes[0].set_title("Line Plot")

axes[1].bar(["A", "B", "C"], [10, 20, 15])
axes[1].set_title("Bar Plot")

plt.tight_layout()
plt.show()
```

---

## 🧠 What You Will Learn

By working through this repository, you will learn how to:

* Create basic plots using Matplotlib
* Customize plot titles and labels
* Create bar charts
* Create and interpret histograms
* Build pie charts
* Create scatter plots
* Work with Seaborn
* Create statistical visualizations
* Display multiple plots using subplots
* Compare variables visually
* Present data in an understandable format

---

## 📖 Recommended Learning Path

For beginners, follow the notebooks in this order:

```text
Introduction to Matplotlib
          ↓
       Bar Plot
          ↓
      Histogram
          ↓
      Pie Chart
          ↓
    Scatter Plot
          ↓
    Seaborn Plots
          ↓
       Subplots
```

This provides a gradual progression from basic plotting to more advanced visualization techniques.

---

## 🎯 Who Is This Repository For?

This project is useful for:

* 👨‍🎓 Students learning Python
* 📊 Aspiring Data Analysts
* 🤖 Beginners in Data Science
* 🐍 Python learners
* 📈 Data visualization enthusiasts
* 💼 Students building a Data Science portfolio

---

## 🔮 Future Improvements

The repository can be expanded with:

* [ ] Line plots
* [ ] Box plots
* [ ] Violin plots
* [ ] Heatmaps
* [ ] Pair plots
* [ ] Count plots
* [ ] Distribution plots
* [ ] Time-series visualization
* [ ] Interactive visualizations
* [ ] Real-world datasets
* [ ] Exploratory Data Analysis projects
* [ ] Complete Data Visualization projects

---

## 🤝 Contributing

Contributions are welcome!

### Steps to contribute

**1. Fork this repository**

**2. Clone your fork**

```bash
git clone https://github.com/YOUR-USERNAME/Data-Visualization-using-Matplotlib-and-Seaborn.git
```

**3. Create a new branch**

```bash
git checkout -b feature/new-visualization
```

**4. Make your changes**

**5. Commit your changes**

```bash
git add .
git commit -m "Add new visualization example"
```

**6. Push your branch**

```bash
git push origin feature/new-visualization
```

**7. Create a Pull Request**

---

## ⭐ Support

If this repository helped you learn **Matplotlib and Seaborn**, consider giving it a ⭐ on GitHub.

---

## 👨‍💻 Author

### Sarhan Bakarman

GitHub: **[@sarhan-003](https://github.com/sarhan-003)**

---

## 🔗 Repository

**Data Visualization using Matplotlib and Seaborn**

https://github.com/sarhan-003/Data-Visualization-using-Matplotlib-and-Seaborn

---

## 📜 License

This project is created for **educational and learning purposes**.

---

### 📊 Keep Learning. Keep Visualizing. Keep Building. 🚀
