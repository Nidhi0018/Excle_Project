# Excel Data Cleaning Project – Sales Dataset Standardization

## 📌 Objective
This project simulates a **real-world business scenario** where raw sales data collected from regional teams is inconsistent, messy, and not analysis-ready. Using Excel, I performed full data cleaning and standardization to ensure it's ready for downstream tasks like reporting, dashboarding, and decision-making.

---

## 🧩 Business Problem
Raw datasets often contain:
- Duplicate entries causing inflated metrics
- Inconsistent region and gender labels that break reports
- Messy formatting that complicates integration with tools like Power BI
- Missing calculations (like Total Sales Value)

In a real company, this would lead to **incorrect KPIs, misinformed decisions, and lost trust in data**. My job here was to fix that.

---

## 🛠️ Tasks Performed

| Task                          | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| ✅ Removed Duplicates         | Eliminated duplicate order entries to ensure accurate revenue reporting    |
| ✅ Cleaned Blank Rows         | Deleted empty or incomplete rows                                            |
| ✅ Fixed Region Inconsistencies | Standardized region values (`"north"`, `" SOUTH "` → `"North"`, `"South"`) |
| ✅ Cleaned Gender Values      | Transformed `"FEMALE"`, `"F"` to `"Female"`, etc. for analysis consistency |
| ✅ Applied Text Functions     | Used `PROPER()`, `TRIM()` to clean names and text fields                    |
| ✅ Split Full Names           | Extracted `First_Name` and `Last_Name` from `Customer_Name`                |
| ✅ Formatted Dates & Numbers | Proper formatting of date, currency, and phone number columns              |
| ✅ Added Total Value Column   | Created `Total_Value = Quantity × Unit Price` for revenue tracking         |

---

## 🔍 Summary Table – Before vs After

| Issue              | Before Example     | After Fix        |
|-------------------|--------------------|------------------|
| Region             | `" SOUTH "`         | `South`          |
| Gender             | `"F"`, `"male"`     | `Female`, `Male` |
| Customer Name      | `john DOE`          | `John Doe`       |
| Phone Format       | Mixed               | Standardized     |
| Duplicates         | Present             | Removed          |
| Total Value Column | Not Present         | Added            |

---

## 📊 Tools & Skills Used

- **Microsoft Excel**
  - Conditional formatting
  - Data cleaning functions: `PROPER()`, `TRIM()`, `IFERROR()`, etc.
  - Data transformation
  - Formula-based logic: `LEFT()`, `FIND()`, etc.
- **Data Cleaning Principles**
  - Consistency
  - Completeness
  - Accuracy

---



