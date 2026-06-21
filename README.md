# 📊 HR Attendance Tracker & Salary Breakdown Dashboard

> **Enterprise-grade HR analytics solution** delivering real-time attendance compliance monitoring and granular payroll decomposition across a full fiscal year workforce cycle.

---

## 🖼️ Dashboard Preview

<p aling="center">
   <img src="Yearly Attendence Tracking.png" alt="Yearly Attendence Tracking" Width="100%"
</p>   



---

## 📋 Executive Summary

This dashboard provides a centralized, data-driven framework for tracking workforce attendance compliance and payroll disbursement for an 11-employee organization across 6 corporate roles throughout the full 2025 fiscal year. It operationalizes HR decision-making by surfacing attendance deviations, leave utilization patterns, and net salary liability — enabling finance and HR leadership to act on facts, not estimates.

---

## 🗂️ Table of Contents

- [Key Performance Indicators](#-key-performance-indicators)
- [Key Analytical Insights](#-key-analytical-insights)
- [Dashboard Features](#-dashboard-features)
- [Financial Salary Breakdown](#-financial-salary-breakdown)
- [Full-Year Benchmark Metrics](#-full-year-benchmark-metrics)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Data Scope & Report Period](#-data-scope--report-period)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📌 Key Performance Indicators

### 🏆 Attendance & Workforce KPIs

| KPI | Value |
|---|---|
| **Overall Attendance Rate** | 97% |
| **Employee of the Year** | Emp004 |
| **Top Performer Attendance** | 98.6% |
| **Top Performer Presence Days** | 281 Days |
| **Top Performer Absences** | 5 Days |
| **Total Headcount Tracked** | 11 Employees |
| **Roles Covered** | 6 Corporate Roles |

### 💰 Payroll & Financial KPIs

| KPI | Value |
|---|---|
| **Total Monthly Salary Pool** | ₹4,24,000.00 |
| **Per Day Average Salary** | ₹15,142.86 |
| **Total Aggregated Payable Days** | 3,894 Days |
| **Earned Basic Salary (YTD)** | ₹53,56,285.71 |
| **Total Gross Salary (YTD)** | ₹54,39,605.76 |
| **Net In-Hand Salary (YTD)** | ₹50,32,585.76 |

---

## 🔍 Key Analytical Insights

**Attendance & Compliance**

- **97% aggregate attendance compliance** indicates a highly disciplined workforce with minimal operational disruption from unplanned absences across the full fiscal year.
- **Emp004** leads organizational performance at **98.6% attendance** with only 5 recorded absences — a benchmark for internal recognition and incentive programs.
- With an average of **275 presence days** against a **286-day working calendar**, the workforce collectively sustains near-maximum productivity coverage.
- An average of **11 absence days per employee** falls well within the **27-day leave allocation**, signaling healthy leave under-utilization — an indicator of either strong engagement or potential leave encashment liability.

**Leave & Calendar Analysis**

- The annual work calendar is structured across **286 total working days**, with **52 planned week-offs**, **24 public holidays**, and **27 days of leave allocation** — a standard corporate scheduling architecture.
- Month-over-month combo chart trends reveal cyclical absence spikes (potentially aligned with public holiday clusters or annual leave concentrations), enabling proactive resource planning.

**Payroll & Compensation**

- The spread between **Gross Salary (₹54,39,605.76)** and **Net In-Hand (₹50,32,585.76)** reflects a total deduction of approximately **₹4,07,020** (primarily driven by Provident Fund contributions), representing a ~7.5% effective deduction rate.
- **HRA** as a salary component buffers taxable income and is reflected distinctly in the salary funnel visualization.
- A **per-day average cost of ₹15,142.86** provides a precise basis for absenteeism-loss quantification and contract staffing cost benchmarking.

---

## ⚙️ Dashboard Features

### 🎛️ Interactive Slicers (Multi-Dimensional Filtering)

| Slicer Dimension | Options Available |
|---|---|
| **Time (Monthly)** | January – December (12 months) |
| **Role** | Accountant, Analyst, HR, Manager, Stuff, Team Leader |
| **Employee ID** | Emp001 – Emp011 (11 individuals) |

All three slicer axes operate in conjunction — enabling cross-filtered views such as "Analyst attendance in Q3" or "Manager payroll for a specific month."

### 📈 Visualization Components

**1. Overall Attendance Gauge**
A single-metric radial/dial gauge displaying the aggregate attendance rate (97%) — designed for instant executive-level comprehension.

**2. Employee of the Year Highlight Card**
A dynamic KPI card that surfaces the top-performing employee by attendance percentage, with supporting day-count breakdown (Presence, Absence).

**3. Monthly Combo Chart (Line + Bar)**
A dual-axis time-series visualization tracking three parallel metrics across January–December:
- Presence Days (Bar)
- Absence Days (Line)
- Leave Cycles (Line)

Enables trend identification, seasonal pattern detection, and YoY benchmarking.

**4. Employee Performance Bar Chart**
A side-by-side horizontal or vertical bar chart rendering individual presence vs. absence counts for all 11 employee IDs simultaneously — enabling at-a-glance rank ordering and outlier detection.

**5. Salary Breakdown Funnel / Horizontal Bar**
A progressive decomposition visualization displaying:
- Earned Basic Salary → HRA Addition → Total Gross Salary → PF Deduction → **Net In-Hand Salary**

Provides complete payroll audit transparency from gross entitlement to liquid take-home.

---

## 💵 Financial Salary Breakdown

```
Earned Basic Salary        ₹53,56,285.71
        +  HRA              ──────────────►
Total Gross Salary         ₹54,39,605.76
        -  PF Deductions    ──────────────►
Net In-Hand Salary         ₹50,32,585.76
```

| Component | Amount (₹) |
|---|---|
| Earned Basic Salary | 53,56,285.71 |
| HRA (House Rent Allowance) | — *(derived)* |
| **Total Gross Salary** | **54,39,605.76** |
| PF Deduction | *(54,39,605.76 − 50,32,585.76)* |
| **Net In-Hand Salary** | **50,32,585.76** |
| Net Deduction Total | ~4,07,020.00 |

---

## 📅 Full-Year Benchmark Metrics

| Metric | Value |
|---|---|
| **Total Working Days (Calendar)** | 286 Days |
| **Average Presence Days** | 275 Days |
| **Average Absence Days** | 11 Days |
| **Leave Allocation** | 27 Days |
| **Planned Week-Offs** | 52 Days |
| **Public Holidays** | 24 Days |

---

## 🛠️ Tech Stack

```
[ PLACEHOLDER — Update with your actual tools ]
```

| Layer | Technology |
|---|---|
| **Data Source** | Microsoft Excel (.xlsx) / CSV |
| **Dashboard & Visualization** | Microsoft Power BI Desktop / Microsoft Excel |
| **Data Modeling** | Power Query (M Language) / Excel Data Model |
| **Calculated Measures** | DAX (Data Analysis Expressions) / Excel Formulas |
| **Version Control** | Git + GitHub |
| **Report Format** | .pbix (Power BI) / .xlsx (Excel) |

> ⚠️ *Replace placeholder entries above with confirmed tools from your build environment.*

### 🧮 DAX Measures / Excel Formulas Used

```
[ PLACEHOLDER — Document your key formulas here ]

Examples:
- Attendance % = DIVIDE([Total Presence Days], [Total Working Days], 0)
- Net Salary = [Total Gross Salary] - [PF Deduction]
- Per Day Salary = DIVIDE([Monthly Salary Pool], [Working Days in Month], 0)
- Earned Basic = Basic Salary Rate × (Payable Days / Total Calendar Days)
```

---

## 📁 Project Structure

```
hr-attendance-tracker/
│
├── 📊 dashboard/
│   ├── HR_Attendance_Dashboard.pbix       # Power BI source file
│   └── HR_Attendance_Dashboard.xlsx       # Excel source file (if applicable)
│
├── 📂 data/
│   ├── raw/
│   │   └── attendance_raw_2025.csv        # Source attendance records
│   └── processed/
│       └── salary_computed_2025.xlsx      # Processed payroll data
│
├── 🖼️ assets/
│   └── dashboard_preview.png             # Dashboard screenshot for README
│
├── 📝 docs/
│   └── data_dictionary.md               # Field definitions and schema
│
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

```
[ PLACEHOLDER — Confirm your tool and version requirements ]
```

- Microsoft Power BI Desktop (v2.x or later) **OR** Microsoft Excel 2019 / Microsoft 365
- Minimum 4 GB RAM recommended for full dataset rendering
- Windows 10/11 (Power BI Desktop is Windows-only natively)

### Opening the Dashboard

**For Power BI (.pbix):**

```bash
# 1. Clone this repository
git clone https://github.com/<your-username>/<your-repo-name>.git

# 2. Navigate to the dashboard directory
cd hr-attendance-tracker/dashboard/

# 3. Open the .pbix file in Power BI Desktop
# Double-click HR_Attendance_Dashboard.pbix
# OR: File → Open → Select .pbix file
```

**For Excel (.xlsx):**

```bash
# 1. Clone or download the repository
# 2. Open HR_Attendance_Dashboard.xlsx in Excel 2019 / Microsoft 365
# 3. Enable macros/content if prompted
# 4. Navigate to the Dashboard tab
```

### Interacting with Filters

1. Use the **Month Slicer** to isolate any calendar month (Jan–Dec).
2. Use the **Role Slicer** to filter by department: Accountant, Analyst, HR, Manager, Stuff, or Team Leader.
3. Use the **Employee ID Slicer** to drill into any individual (Emp001–Emp011).
4. All visuals respond dynamically to multi-slicer combinations.
5. To reset filters: click the **Clear Filters** icon or press `Ctrl+Alt+C` in Power BI.

---

## 📆 Data Scope & Report Period

| Parameter | Detail |
|---|---|
| **Report Period** | Full Year — Financial/Calendar Year 2025 |
| **Last Updated** | June 12, 2026 |
| **Headcount** | 11 Employees |
| **Role Coverage** | 6 Corporate Roles |
| **Time Granularity** | Daily records aggregated to monthly and annual views |
| **Employee ID Range** | Emp001 – Emp011 |

---

## 🤝 Contributing

Contributions, issue reports, and enhancement requests are welcome.

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-enhancement`
3. Commit changes: `git commit -m "Add: description of change"`
4. Push to branch: `git push origin feature/your-enhancement`
5. Open a Pull Request with a clear description of changes

---

## 📄 License

```
[ PLACEHOLDER — Specify your license ]
```

This project is licensed under the [MIT License](./LICENSE) — or replace with your organization's licensing terms.

---

## 👤 Author

```
[ PLACEHOLDER — Add your details ]
```

**Maintainer:** `<Your Name>`
**GitHub:** [@your-username](https://github.com/your-username)
**Report Issues:** [Open an Issue](https://github.com/your-username/your-repo-name/issues)

---

*Report Period: FY 2025 | Last Updated: June 12, 2026 | Data Scope: 11 Employees × 6 Roles × 12 Months*
