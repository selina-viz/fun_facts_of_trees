# 🌲 Vancouver Trees & Urban Landscape: A Fun Data Journey

Vancouver is a beautiful city, known for its perfect balance between urban life and nature. Trees play a key role in maintaining this harmony. In this exploratory data analysis project, we dive into fun facts and insightful patterns behind tree distribution across Vancouver, with a future goal of connecting it to **real estate values**.

This report is based on four main questions of interest, and each section reveals some fascinating truths about the city's green life!

---

## 🔍 Highlights of the Analysis

### 🌳 1. Trees Over Time

In **Figure 1**, we explore how many trees were planted each year. Then, in **Figure 2**, we highlight the **top 5 and bottom 5** planting years.

- **1991 Fun Fact**: Only 15 trees were planted that year, ranking in the bottom 5. However, the **average height of trees planted in 1991 is the tallest**!
  - Nearly **one-third** of the trees planted that year were **giants** — a surprising outlier.
- Neighborhoods with the **most newly planted trees (1989–2019)** are all located on the **east side** — possibly indicating urban development in those areas.

### 🛣️ 2. Tree Distribution by Street Side

In **Figure 5**, we compare tree size and quantity based on where they're planted on the street:

- **Trees planted on both sides of the street** are **taller and more numerous** than those in the middle or near bike lanes.
- **Bike areas** have the **smallest and fewest** trees.
- This reflects a balance and contrast in urban planning — symmetry offers aesthetic balance, while asymmetry offers contrast and variety.

### 🏡 3. Trees and Real Estate

Using maps and benchmark home price data (April 2022), we uncovered some intriguing patterns:

- **Westside neighborhoods**, known for mansions and higher land values, are also where **many of the biggest and oldest trees** are located.
- **Fairview** stands out with its **evenly distributed mid-sized trees** — living up to its name with a truly “fair view”!
- **Shaughnessy**, with an average home price of **$5.5M**, has the **largest concentration of giant trees**, especially with **diameter > 60 inches** — a true champion in both **real estate and tree size**!

### 📏 4. Tree Size Exploration

- The **most common tree sizes** have diameters under **5 inches** and heights between **1–1.5 meters**.
- As tree size increases, the count decreases.
- Among top 5 genus groups, all follow this trend except for **Prunus** (cherries, plums, peaches), where the dominant diameter is **10–20 inches**. These trees are known for their beautiful blossoms and rapid growth.

---

## 📌 Key Visualizations

> You can view the full HTML report here:  
**🔗 [EDA Report](https://www.upccn.com/report/project_report_20230314_170249.html)**

Screenshots or sample visuals can also be added here.

---

## 📁 Project Structure

```bash
vancouver-trees-and-realestate/
├── eda_notebook.ipynb       # EDA notebook (optional)
├── eda_report.html          # Final report (HTML)
├── data/                    # Sample dataset (if shareable)
├── images/                  # Visuals for README (optional)
├── README.md                # Project summary
└── requirements.txt         # Python dependencies (optional)
