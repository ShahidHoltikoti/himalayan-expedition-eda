# himalayan-expedition-eda-1900-2020-
# 🏔️ Himalayan Expedition Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project explores decades of Himalayan climbing data to uncover the statistical realities of high-altitude mountaineering. By analyzing thousands of expedition records, this EDA breaks down success, failure, and fatality rates based on critical factors such as supplemental oxygen usage, hired support, seasonality, and the specific peak being scaled.

**View the full analysis in the [Jupyter Notebook](Final_Report.ipynb)

## 🛠️ Tools & Technologies Used
* **Python:** Core programming language.
* **Pandas:** Data cleaning, conditional aggregations, custom mapping, and rate calculations.
* **Matplotlib:** Building custom subplots, multi-axis grouped bar charts, and container label formatting.
* **Jupyter Notebook:** Interactive development and reporting environment.

## 📊 Key Analytical Highlights & Techniques
This project demonstrates advanced data manipulation and visualization techniques, including:
* **The "Long Tail" Grouping Method:** Cleaned categorical clutter by dynamically isolating the top 4 most attempted peaks (Everest, Ama Dablam, Cho Oyu, Manaslu) and mathematically aggregating all remaining peaks into a custom "Others" category without distorting percentage rates.
* **Boolean Mapping:** Translated raw True/False values into professional, readable labels (e.g., "Fully Supported", "Unaided/Purist") for dynamic axis indexing.
* **Dual-Axis Subplots:** Created side-by-side comparative Matplotlib grids to visualize raw climber counts next to actual percentage rates to prevent skewed interpretations of danger levels.
* **Automated Data Labeling:** Built looping structures through Matplotlib containers to automatically extract and format height values as floating-point percentages directly above graph bars.

## 📈 Core Visualizations Included
1. **Peak-Specific Risk Assessment:** Success and fatality rates across major Himalayan peaks.
2. **Seasonal Safety Profiles:** Outcome distributions across Winter, Summer, Spring, and Autumn climbing seasons.
3. **Historical Climbing Trends:** Generational shifts in expedition outcomes and volumes by decade.
4. **Equipment and Support Impact:** A matrix analysis of outcomes based on the 4 key climbing styles: Fully Supported, Oxygen Only, Support Only, and Unaided.

## 📁 Repository Structure
* `Final_Report.ipynb` - The primary Jupyter Notebook containing all Python code, logic, and visual outputs.
* `Mountain_result.csv` - The cleanly exported, aggregated dataset highlighting the final mountain risk metrics.
* 
## 🚀 How to Run Locally
1. Clone the repository: `git clone https://github.com/ShahidHoltikoti/himalayan-expedition-eda.git`
2. Ensure you have Python installed along with `pandas` and `matplotlib`.
3. Open the `.ipynb` file in Jupyter Notebook, Jupyter Lab, or VS Code and run the cells sequentially.

---
*Created by [Shahid Holtikoti](https://github.com/ShahidHoltikoti) - Feel free to reach out on LinkedIn for discussions regarding data science and analytics!*
