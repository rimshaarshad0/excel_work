# Excel Work

## 📊 Annual Examination Result 2026

This Excel file contains a student mark sheet designed to calculate results automatically using formulas.

---

## 📌 Features

- Student result management
- Automatic total calculation
- Percentage calculation
- Grade assignment
- Pass/Fail status

---

## 📋 Columns Description

### 1. Roll No
Each student is assigned a unique roll number.

### 2. Name
Student name.

### 3. Subjects
Marks obtained in:
- Math
- Science
- English
- Computer

---

## 🧮 Calculations Used

### ✅ Total Marks
=SUM(D6:G6)
Adds marks from all subjects.

---

### ✅ Percentage
=(H6/400)*100
Calculates percentage based on total marks (out of 400).

---

### ✅ Grade Formula
=IF(I6>=90,"A+",IF(I6>=80,"A",IF(I6>=70,"B",IF(I6>=60,"C",IF(I6>=50,"D","F")))))

#### Grading Criteria:
- A+ → 90% and above  
- A → 80% to 89%  
- B → 70% to 79%  
- C → 60% to 69%  
- D → 50% to 59%  
- F → Below 50%  

---

### ✅ Status (Pass/Fail)
=IF(I6>=40,"PASS","FAIL")

- PASS → Percentage ≥ 40%
- FAIL → Percentage < 40%

---

## 📈 Example Students

- Ahmed Raza  
- Muhammad Ali  
- Hassan Khan  
- Usman Tariq  
- Bilal Ahmed  

---

## 💡 Purpose

This sheet is useful for:
- Schools & teachers
- Result management systems
- Excel practice for beginners

---

## 🛠️ Tools Used

- Microsoft Excel
- Built-in formulas (SUM, IF)

---

## 📌 Notes

- All calculations are automated
- You can add more students by dragging formulas down
- Make sure total marks remain consistent (400)

## 📊 Sales Dashboard Dataset

This dataset contains structured sales data used for building interactive dashboards and performing business analysis. It provides insights into revenue and profit trends over time.

## 📂 Dataset Description

The data is organized in a tabular format and represents daily sales records along with key performance indicators.

### 🔑 Key Columns

* **Date** — Represents the sales transaction date
* **Revenue** — Total income generated from sales
* **Profit** — Net earnings after deducting costs
* **Additional Fields** — May include product categories, regions, or other business-related attributes

## 📈 Summary

* **Total Revenue:** 69,095
* **Total Profit:** 20,728.5

## 🧮 Excel Formulas Used

The following formulas are typically used in the dataset:

### ➤ Total Revenue Calculation

```excel
=SUM(Revenue_Column)
```

Example:

```excel
=SUM(C2:C100)
```

### ➤ Total Profit Calculation

```excel
=SUM(Profit_Column)
```

Example:

```excel
=SUM(D2:D100)
```

### ➤ Profit Calculation (if derived)

```excel
=Revenue - (Revenue*Cost)
```

Example:

```excel
=C2 - (C2*70%)
```

### ➤ Running Total (Cumulative Revenue)

```excel
=(C2*C100)
```

Example:

```excel
=(Unit sold * Price)
```

### ➤ Average Revenue

```excel
=AVERAGE(C2:C100)
```

## 🎯 Purpose

This dataset is intended for:

* Sales performance tracking
* Dashboard creation
* Trend analysis over time
* Business decision support

## ⚙️ Usage

This dataset can be used with various tools, such as:

* **Microsoft Excel** for analysis
* **Power BI / Tableau** for dashboards
* **Python (Pandas)** for data processing

## 📝 Data Notes

* Clean empty or unnamed columns before analysis
* Ensure correct date formatting
* Verify totals for accuracy

## 👨‍💻 Applications

* Sales dashboards
* Business reports
* Data visualization projects

## 📄 License

This dataset is intended for educational and analytical use.

---

