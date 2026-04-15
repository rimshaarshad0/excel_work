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

---# excel_work
