# 🐍 Python Capstone Project – Data Cleaning & Transformation

Data preparation and transformation project using **Pandas** and **NumPy** to simulate an end-to-end data wrangling pipeline involving employee and project records.

---

## 📁 Project Structure

| Folder       | Contents                                                  |
|--------------|-----------------------------------------------------------|
| `notebooks/` | Jupyter notebook with full cleaning and transformation steps |
| `data/`      | Excel/CSV files used at each stage of transformation      |
| `docs/`      | Final PDF report (if any)                                 |
| `images/`    | Visuals/snapshots of output (optional)                    |

---

## 📂 Project Files

### Notebook

| File Name                                       | Description                     |
|------------------------------------------------|---------------------------------|
| `Capstone Project DFs- Abhishek Akunuru.ipynb` | Main Python notebook with ETL logic |

### Data Files

| File Name                  | Description                               |
|---------------------------|-------------------------------------------|
| `employee.xls`            | Raw employee details                      |
| `project.xls`             | Raw project data                          |
| `project_cleaned.xls`     | Cleaned project data                      |
| `employee_name_split.xls` | First name & last name extracted          |
| `final.xls`               | Merged employee and project datasets      |
| `final_cleaned.xls`       | Cleaned and deduplicated version          |
| `final_with_bonus.xls`    | Bonus column added                        |
| `Final_named.xls`         | Name prefixed for designation             |
| `final_promoted.xls`      | Designation levels promoted               |
| `seniority.xls`           | Based on age group for seniority          |
| `Total_proj_cost.xls`     | Project costs aggregated                  |
| `city_with_o_csv.csv`     | Filtered records with 'o' in city name    |

### Documentation

| File Name                    | Description         |
|-----------------------------|---------------------|
| `Capstone project - Python.pdf`| Data & Tasks to perform |

---

## 🧹 Key Highlights

- Cleaned and joined multiple datasets using **Pandas**
- Split names, removed duplicates, and handled missing values
- Applied conditional column creation (bonus, promotions, etc.)
- Aggregated and grouped data for insights (total project cost)
- Used **NumPy** for numerical operations and age calculations

---

## 🏷️ Tags

`python`, `pandas`, `numpy`, `data-cleaning`, `data-transformation`, `etl`, `capstone-project`

