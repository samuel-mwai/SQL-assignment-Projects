# SQL Assignment Project

A collection of advanced SQL scripts solving data analysis, engineering, and reporting challenges. These queries demonstrate mastery of string manipulation, math, dates, multi-table joins, window functions, and set operators using PostgreSQL syntax.

## 🛠️ Core Capabilities Demonstrated
* **String Manipulation:** Complex text formatting, substring extraction, and capitalization adjustments.
* **Statistical Computations:** Aggregations, running averages, and numerical data optimization (rounding/boundaries).
* **Temporal Analysis:** Age calculations, date part extraction, and advanced datetime formatting.
* **Relational Mapping:** Mastered `INNER`, `LEFT`, and `RIGHT` joins, including multi-table connections and orphan data filtering.
* **Analytical Window Functions:** Sequential tracking, partitions, index assignments, data-tier division, and delta computations using lagging variables.
* **Set Theory Operations:** Intersector analysis and non-duplicating or tracking set-unions across schemas.

## 📁 Repository Structure & Core Scripts

* **`Section_A_Strings.sql` (String Functions)**
  * Full name text formatting (uppercase) and city formatting (lowercase).
  * Character length tracking for sorting variations.
  * Substring character extraction (`LEFT`) for short name definitions.
  * String concatenation (`CONCAT`) to generate dynamic text summary sentences.

* **`Section_B_Numbers.sql` (Number Functions)**
  * Precision rounding versus integer ceiling and floor boundary rounding to the nearest 10.
  * Main data aggregations: totals (`COUNT`), averages (`AVG`), limits (`MAX`/`MIN`), and accumulations (`SUM`).
  * Scaling value boosts and modifications rounded to whole numbers.

* **`Section_C_Dates.sql` (Date & Time Functions)**
  * Timestamps part extraction (Year, Month, Day) into isolated string views.
  * Age calculation in complete years using date intervals.
  * Text formatting conversions (`TO_CHAR`) for human-readable calendar dates.

* **`Section_D_Joins.sql` (SQL JOINS)**
  * Multi-table `INNER JOIN` mapping event details, patients, and doctors.
  * Active transaction auditing using a `LEFT JOIN`.
  * Multi-layered `RIGHT JOIN` mapping chain to secure provider rosters.
  * `LEFT JOIN` mixed with null-pointer evaluation (`WHERE ... IS NULL`) to filter zero-engagement profiles.
  * Deep multi-entity linking across tables for prescription inventories.

* **`Section_E_Windows.sql` (Window Functions)**
  * Sequential row ranking allocation (`ROW_NUMBER()`) without dropping rows.
  * Structural variations between gap-leaving (`RANK()`) and gapless (`DENSE_RANK()`) subset ordering tiers.
  * Statistical segment distribution using performance tiles (`NTILE(3)`).
  * Personal score tracking against categorical means using a `PARTITION BY` execution set.
  * Timeline logging variables (`LAG()`) to compute score variations over time.

* **`Section_F_Sets.sql` (SET Operators)**
  * Distinct data compilation across namespaces using non-duplicating `UNION`.
  * Appending non-identical database lists with tracking metadata using `UNION ALL`.
  * Overlapping footprint matching and intersection analysis using `INTERSECT`.
  * Three-schema combined dataset collection and tracking using multi-stacked `UNION ALL`.

---

## 📄 Author & License

**Samuel Mwai** — Data Science & Analytics | Machine Learning  
* **GitHub:** [samuel-mwai](https://github.com/samuel-mwai)  
* **License:** MIT License

