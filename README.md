# SaaS-Companies-Analysis 📊🌐

🔗 **[View Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMGI4MDk2MTUtMjcwMC00MTYzLWFiN2UtYzY1MzA3MzNhYTZlIiwidCI6IjEwNGQ4MDQ4LWZkMGMtNDNkNS1hNjMwLWZjNjI5ZTVkYWI1OSJ9)**

![SaaS Dashboard](https://github.com/Boateng-Yaw-Edmund/Top-100-SaaS-Companies---Analysis/blob/main/SaaS/WhatsApp%20Image%202025-06-28%20at%2015.07.30_32694f05.jpg)

An interactive Power BI dashboard that analyzes the top 100 SaaS companies in 2025 across revenue, valuation, and user satisfaction. This project uncovers trends, benchmarks, outliers, and potential opportunities within the global SaaS ecosystem.

---

## 🔍 Project Objective

To explore and visualize SaaS industry data using Power BI with the goal of:
- Uncovering high-performing companies based on valuation and ARR
- Identifying trends in G2 ratings across companies
- Detecting valuation outliers and their impact on visuals
- Providing strategic insights through interactive KPIs

---

## 🧮 Main KPIs

- **Average ARR**: $5.83 Billion  
- **Total Valuation**: $6.02 Trillion  
- **Average G2 Rating**: 4.43  
- **% of Companies Rated 4.5+**: 41%

---

## 🛠️ Project Process

1. **Explored the raw SaaS dataset**
   - Reviewed dataset structure and completeness
   - Identified key metrics: ARR, valuation, G2 rating, employee count, etc.

2. **Cleaned and transformed data using Power BI and SQL**
   - Converted financial fields (ARR, Valuation, Funding) from text with suffixes (e.g. $1.5B) to numeric values
   - Standardized text, fixed inconsistent entries, and handled nulls
   - Flagged and excluded extreme outliers in some visuals (e.g., Microsoft, SAP)

3. **Created calculated fields and KPIs**
   - Designed custom DAX measures like Valuation-to-ARR ratio and Rating Categories
   - Grouped companies by rating tiers for deeper segmentation

4. **Designed an interactive dashboard**
   - Implemented slicers, cards, bar and scatter plots
   - Applied custom background from PowerPoint to enhance visual styling
   - Filtered visuals to clarify insights and avoid skewing by extreme outliers

---

## 📸 Dashboard Visualizations

![Dashboard Overview](https://github.com/Boateng-Yaw-Edmund/Top-100-SaaS-Companies---Analysis/blob/main/SaaS/Screenshot%20(86).png)  
![Cleaned Table](https://github.com/Boateng-Yaw-Edmund/Top-100-SaaS-Companies---Analysis/blob/main/SaaS/WhatsApp%20Image%202025-06-27%20at%2020.28.08_07f208dd.jpg)

---

### 🚀 Skills / Concepts Demonstrated

- **Data Cleaning & Transformation** – Parsing suffixes (M, B, T), fixing types, removing duplicates, handling nulls
- **SQL Querying** – Used to inspect null values, apply filters, and prep before Power BI load
- **DAX for KPI Design** – Created calculated columns and custom measures
- **Outlier Management** – Identified and excluded high-valuation giants from charts to enhance pattern visibility
- **Dashboard Interactivity** – Applied slicers, tooltips, and dynamic visuals for drill-downs
- **Custom UI/UX** – Used a branded canvas background from PowerPoint to polish the look
- **Insight Generation** – Delivered business-focused conclusions based on quantitative metrics

---

## 🧠 Key Insights

- **Valuation outliers like Microsoft and SAP** significantly stretch visuals — excluding them improves trend visibility for mid-tier firms.
- **41% of SaaS companies** are rated above 4.5 on G2, showing strong customer satisfaction.
- A healthy **valuation-to-ARR multiple (~10x)** indicates investor confidence in long-term profitability.
- Several **highly rated but low-valued companies** may be underpriced and represent opportunities for disruption or investment.

---

## 📌 Conclusion & Recommendations

### ✅ Conclusion

The SaaS industry shows strong financial performance and high user satisfaction, with an average ARR of $5.83B and 41% of companies rated 4.5+ on G2. While a few outliers skew valuation trends, filtering them reveals clearer patterns and opportunities. This dashboard provides a solid foundation for ongoing analysis, strategic benchmarking, and informed decision-making in the evolving SaaS landscape.

### 💡 Recommendations

- **Benchmark low-rated companies** against top performers to identify user experience gaps.
- **Prioritize undervalued but highly rated companies** for deeper market research and potential investment.
- **Use filtered visuals and ratio metrics** to uncover patterns obscured by megacap outliers.
- **Update the dataset periodically** to track valuation, ARR, and G2 trends over time.

---

## 💡 Inspiration

Inspired by a curiosity to uncover macro trends in the SaaS space, sharpen Power BI skills, and tell data stories using real-world metrics and clean visual design.

> _"From raw valuation data to strategic business signals — this dashboard maps the SaaS landscape with clarity and insight."_

---

## 📬 Connect with Me

**[LinkedIn](https://www.linkedin.com/in/edmund-boateng-yaw-4073b620b/)** | **[@ed_mund.csv](https://x.com/ed_mund_csv)**
