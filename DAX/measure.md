# DAX Measures – Blinkit Sales Analysis

This document contains the DAX measures used in the Blinkit Sales Analysis Dashboard.

---

## 1. Total Sales

Calculates the total sales generated across all items.

```DAX
Total Sales =
SUM('BlinkIT Grocery Data'[Sales])
```

---

## 2. Average Sales

Calculates the average sales value.

```DAX
Avg Sales =
AVERAGE('BlinkIT Grocery Data'[Sales])
```

---

## 3. Number of Items

Calculates the total number of items in the dataset.

```DAX
No of Items =
COUNTROWS('BlinkIT Grocery Data')
```

---

## 4. Average Rating

Calculates the average customer rating.

```DAX
Avg Rating =
AVERAGE('BlinkIT Grocery Data'[Rating])
```

---

## Measure Summary

| Measure     | Purpose                            |
| ----------- | ---------------------------------- |
| Total Sales | Calculates overall sales           |
| Avg Sales   | Calculates average sales           |
| No of Items | Counts total items                 |
| Avg Rating  | Calculates average customer rating |

---

## Tools Used

* Microsoft Power BI
* DAX
* Power Query

These measures are used to create KPI cards and analytical visualizations in the Blinkit Sales Analysis Dashboard.
