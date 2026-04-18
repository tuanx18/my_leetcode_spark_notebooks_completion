# My Database Practice Solutions – tuanx18

Collection of my **Accepted Database problem solutions** using **PySpark** and **SparkSQL**.

LeetCode profile: https://leetcode.com/u/tuanx18/

> All solutions are written as **Jupyter Notebooks (.ipynb)**.
> Each problem typically includes **both PySpark and SparkSQL approaches** when applicable.
> I aim for **clean, readable logic** and **efficient query design**.
> Some problems may include multiple approaches if I revisit them.

---

## Stats (as of March 2026)

(You can update these numbers manually or add badges later)

* Total AC (Database): ___ Problems
* PySpark Solutions: ___
* SparkSQL Solutions: ___
* Last updated: April 2026

---

## Folder & File Naming

All solutions are stored as **Jupyter Notebook files (.ipynb)**.

Files follow this naming pattern:

```
<problem_number>_<problem_slug_in_snake_case>.ipynb
```

Examples:

* `175_combine_two_tables.ipynb`
* `181_employees_earning_more_than_their_managers.ipynb`
* `184_department_highest_salary.ipynb`
* `550_game_play_analysis_iv.ipynb`

Naming convention remains consistent with my previous Python solutions repo.

---

## Solution Structure

Each notebook typically contains:

1. **Problem Description**
2. **PySpark Solution**
3. **SparkSQL Solution**
4. *(Optional)* Alternative Approach / Optimization Notes

This helps compare **DataFrame API vs SQL-based approaches** side-by-side.

---

## How to Run / Test Locally

You can run the notebooks using:

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

Make sure you have:

* Python 3.x
* PySpark installed
* Jupyter Notebook or JupyterLab

Example environment setup:

```bash
pip install pyspark notebook
```

Then open any `.ipynb` file and run the cells sequentially.

---

## Notes

* All problems are focused on **Database-related tasks**.

* Solutions emphasize **real-world data engineering patterns**, such as:

  * Joins
  * Aggregations
  * Window functions
  * Filtering and grouping
  * Query optimization patterns

* Some notebooks may include **performance notes** or **alternative query designs**.

---

## Future Improvements

* Add difficulty breakdown (Easy / Medium / Hard)
* Add solution complexity notes
* Add execution benchmarks
* Add badges (problem count, language usage, etc.)
* Possibly include **dbt-style modeling examples** later

---
