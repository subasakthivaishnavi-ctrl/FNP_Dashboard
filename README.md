# 💐 Ferns N Petals (FnP) Sales Analysis Dashboard

An interactive **Excel Analytics Dashboard** designed to monitor sales metrics, revenue generation, delivery timelines, customer spending behavior, and order distribution across various occasions and product categories.

---

## 🖼️ Dashboard Preview

![Sales Analysis Dashboard](./FNP%20Dadhboard%20Img.PNG)

---

## 📌 Key Metrics & Highlights

* **Total Orders:** 1,000 orders fulfilled
* **Total Revenue Generated:** ₹3.52M
* **On-Time Delivery Performance:** 5.53 days average delivery turnaround
* **Average Customer Spend:** ₹3.52K per transaction
* **Revenue Drivers by Occasion:** Highest revenue generated across Anniversary, Raksha Bandhan, and Holi occasions.
* **Top Product Categories:** Colors, Soft Toys, and Sweets lead overall sales volume.
* **Geographic Reach:** Top cities by order volume include Bareilly, Ghaziabad, and Bhilai.

---

## 🛠️ Tools & Technologies Used

* **Microsoft Excel:** Dashboard wireframing, pivot tables, dynamic charts, and slicer integration.
* **Excel Formulas & Pivot Tables:** Data aggregation for revenue sums, average customer spending, and order counts.
* **Power Query / Data Modeling:** Multi-table data linking across Orders, Customers, and Product catalogs.
* **Interactive Slicers & Timelines:** Custom dynamic filtering for Order Date, Delivery Date, and Occasions.

---

## ⚙️ How This Dashboard Was Built

1. **Data Structuring & Cleaning:**
   * Linked primary datasets (**Orders**, **Customers**, and **Products**) using unique relational keys (`Customer_ID`, `Product_ID`).
2. **Pivot Table Calculations:**
   * Calculated total orders (`1,000`), total revenue (`₹3.52M`), and average spend (`₹3.52K`).
   * Grouped order timelines across days of the week and months to analyze peak purchasing cycles.
3. **Visualization & UI Layout:**
   * Designed a uniform green-themed dashboard incorporating KPI cards, bar charts, line graphs, and top product lists.
   * Integrated timeline sliders and occasion slicers for interactive data filtering.

---

## 📂 Repository Structure

```text
FnP_Sales_Analysis/
│
├── image_10449f.png       # Dashboard screenshot preview
├── fnp Dashboard.xlsx      # Main Excel workbook containing dataset & dashboard
└── README.md              # Documentation file
