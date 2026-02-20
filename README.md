#!/bin/bash

# Define the filename
README_FILE="README.md"

# Write content to README.md
cat <<EOF > $README_FILE
# 🎓 Higher Education Analytics Dashboard

> **Note:** GitHub cannot preview .pbix files directly. Please refer to the screenshots below for a visual overview of the dashboard.

## 📊 Dashboard Previews
![Main Dashboard](https://github.com/YOUR_USERNAME/YOUR_REPO/blob/main/Screenshot%202026-02-20%20191436.png?raw=true)
*Main Dashboard: Overview of KPIs and Regional distribution.*

![Geographical Overview](https://github.com/YOUR_USERNAME/YOUR_REPO/blob/main/Screenshot%202026-02-20%20191512.jpg?raw=true)
*Geographical Overview: Mapping college density across states.*

## 📌 Project Overview
This Power BI project provides a deep dive into the higher education sector, analyzing over **4 Million students** across **609 colleges**[cite: 4, 5].

## 🚀 Key Insights
* **Total Colleges:** 609 institutions analyzed[cite: 4].
* **Total Courses:** 11,754 diverse programs[cite: 4].
* **Student Enrollment:** 4 Million total students[cite: 4].
* **Regional Leader:** The North region holds the highest count with 424 colleges[cite: 4].
* **Management Split:** The institutions are distributed between Government (209), Private (191), and Management (209) sectors[cite: 11].

## 🛠️ Technical Setup
* **Core Model:** student management.pbix[cite: 1].
* **Themes Used:** CY25SU11.json and Storm.json for visual styling[cite: 3, 4].
* **Primary Features:** DAX-driven KPIs, interactive map visuals, and city-wise student strength analysis[cite: 4, 11].

---
### 📂 How to Open
1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Clone this repository.
3. Open \`student management.pbix\` to interact with the data.
EOF

echo "$README_FILE has been generated with image links!"
