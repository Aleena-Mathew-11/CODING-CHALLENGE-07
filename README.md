# 📊 Power BI Coding Challenge 07

## 📖 Overview

This project demonstrates how to use Power BI features such as Conditional Formatting, Data Bars, Hierarchies, Drill-Down, and Drill-Through to create interactive and insightful dashboards.

---

## 🎯 Scenario 1: Conditional Formatting & Data Bars

### Business Requirement
Management wants to quickly identify:

- High-performing products
- Loss-making regions
- Sales trend strength

### Solution

#### ✅ Conditional Formatting

Apply conditional formatting to the **Profit** column:

- Profit > 0 → Green
- Profit < 0 → Red

This helps users instantly distinguish profitable and non-profitable records.

#### ✅ Data Bars

Apply Data Bars to the **Sales** column.

Benefits:

- Visual representation of sales values
- Easy comparison between records
- No need for additional charts

---

## 🎯 Scenario 2: Hierarchies, Drill-Down & Drill-Through

### Business Requirement

Users should be able to:

- Click Year → Quarter → Month
- Right-click a Product and view a detailed Product Report

---

## ✅ Hierarchy Creation

Create a Date Hierarchy:

```
Year
 └── Quarter
      └── Month
```

Use the hierarchy in visual axes to enable multi-level analysis.

---

## ✅ Drill-Down

Drill-Down allows users to:

- Navigate within the same visual
- Move from Year level to Quarter level
- Further explore Month-level details

### Example

```
Year → Quarter → Month
```

---

## ✅ Drill-Through

Drill-Through allows users to:

- Navigate to another report page
- Pass selected filters automatically
- View detailed Product or Customer reports

### Example

```
Sales Summary Page
        ↓
Right-click Product
        ↓
Product Detail Page
```

---

## 🛠 Tools Used

- Microsoft Power BI Desktop
- Conditional Formatting
- Data Bars
- Hierarchies
- Drill-Down
- Drill-Through

---

## 📚 Key Learnings

- Applying Conditional Formatting for quick insights
- Using Data Bars to visualize value magnitude
- Creating Hierarchies for structured navigation
- Using Drill-Down for detailed exploration
- Using Drill-Through for report page navigation

---

## 🚀 Conclusion

This challenge demonstrates how Power BI can enhance reporting through visual indicators, hierarchical navigation, and interactive report exploration, helping users make faster and more informed decisions.

---

### Author

**Aleena Mathew**

Power BI Learning & Dashboard Development Projects
