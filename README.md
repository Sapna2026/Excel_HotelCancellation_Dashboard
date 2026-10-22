#  Hotel Booking Cancellation Analysis | Excel Dashboard

<p align="center">
  <strong>Exploring Hotel Booking Trends and Cancellation Patterns with Microsoft Excel</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Microsoft-Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Microsoft Excel"/>
  <img src="https://img.shields.io/badge/Domain-Hospitality%20Analytics-1565C0?style=for-the-badge" alt="Hospitality Analytics"/>
  <img src="https://img.shields.io/badge/Project-Data%20Analytics-7B1FA2?style=for-the-badge" alt="Data Analytics"/>
  <img src="https://img.shields.io/badge/Focus-Cancellation%20Analysis-E67E22?style=for-the-badge" alt="Cancellation Analysis"/>
</p>

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)
- [Dataset](#-dataset)
- [Project Structure](#-project-structure)
- [Technologies Used](#-technologies-used)
- [Project Workflow](#-project-workflow)
- [Pipeline Steps](#-pipeline-steps)
- [Data Cleaning Summary](#-data-cleaning-summary)
- [Exploratory Data Analysis](#-exploratory-data-analysis)
- [Dashboard Features](#-dashboard-features)
- [Key Performance Indicators](#-key-performance-indicators)
- [Models Compared](#-models-compared)
- [Evaluation Metrics](#-evaluation-metrics)
- [Key Findings](#-key-findings)
- [Business Recommendations](#-business-recommendations)
- [Installation](#-installation)
- [How to Run](#-how-to-run)
- [Challenges and Learnings](#-challenges-and-learnings)
- [Future Improvements](#-future-improvements)
- [Skills Demonstrated](#-skills-demonstrated)
- [License](#-license)
- [Author](#-author)

---

## 📊 Project Overview

The **Hotel Booking Cancellation Analysis** project focuses on understanding hotel reservation patterns and examining booking cancellations through data analytics and visualization using Microsoft Excel.

Hotel booking cancellations can affect room occupancy, revenue planning, staffing, and operational efficiency. Analyzing historical reservation data helps identify patterns across hotel types, booking periods, customer segments, and reservation characteristics.

The goal of this project is to organize booking information into a structured analytical workflow and present relevant insights through an Excel dashboard.

### Project Details

| Category | Details |
|---|---|
| Project Name | Hotel Booking Cancellation Analysis |
| Domain | Hospitality Analytics |
| Primary Tool | Microsoft Excel |
| Analysis Type | Exploratory and Descriptive Data Analysis |
| Business Focus | Hotel Bookings and Cancellations |
| Main Deliverable | Excel Dashboard and Analysis |
| GitHub Profile | https://github.com/Sapna2026/Excel_HotelCancellation_Dashboard|

## 💼 Business Problem

Hotel cancellations create uncertainty in occupancy planning and can affect expected revenue. Understanding the patterns associated with cancellations helps hotel management make better-informed operational decisions.

Without clear reporting, it can be difficult to identify how cancellation behavior varies across different booking characteristics and customer groups.

This project explores questions such as:

- What proportion of hotel bookings are canceled?
- How do cancellation patterns vary across hotel types?
- Are cancellations different across booking periods?
- Which customer segments demonstrate different booking patterns?
- How do reservation characteristics relate to cancellation behavior?
- How can hotel booking data support operational planning?

These questions provide a framework for examining cancellation trends and identifying opportunities for further analysis.

## 🎯 Project Objectives

The main objectives are to:

- Analyze hotel booking and cancellation data.
- Prepare data for consistent and reliable analysis.
- Examine booking status and cancellation patterns.
- Compare trends across available hotel and customer categories.
- Explore time-based booking behavior.
- Develop meaningful business KPIs.
- Present findings through clear charts and dashboard visualizations.
- Support evidence-based decisions related to reservation management.

## 🗂️ Dataset

The analysis requires hotel booking data containing reservation records and relevant booking attributes.

Depending on the source dataset, useful fields may include:

| Data Category | Example Fields |
|---|---|
| Hotel Information | Hotel type |
| Booking Status | Cancellation status |
| Arrival Information | Arrival date, month, year |
| Reservation Details | Lead time, stay duration |
| Customer Information | Customer type, guest counts |
| Booking Conditions | Deposit type, distribution channel |
| Room Information | Reserved and assigned room types |
| Financial Information | Average daily rate (ADR) |
| Guest Preferences | Special requests, parking requirements |

These are examples of common hotel booking fields, not a verified inventory of columns in this repository.

### Dataset Source

The exact dataset filename, source URL, license, date range, and record count should be documented after verifying the repository files.

If the data originates from a public dataset, its original source and usage conditions should be credited appropriately.

## 📁 Project Structure

The repository-specific file structure could not be verified because the repository URL currently returns 404.

The following is a suggested organization for this project, not a claim about the files currently present:

```text
Excel_HotelCancellation_D/
│
├── data/
│   └── hotel_booking.csv
│
├── dashboard/
│   └── hotel_cancellation_dashboard.xlsx
│
├── reports/
│   └── analysis_report.pdf
│
├── images/
│   └── dashboard_preview.png
│
├── README.md
└── LICENSE
```

Use the actual filenames and folders in your repository when updating this section. Remove any example paths that do not exist.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Microsoft Excel | Data analysis and dashboard development |
| Excel Formulas | Calculations and KPI development |
| PivotTables | Summarizing booking and cancellation data |
| PivotCharts | Visualizing patterns and comparisons |
| Conditional Formatting | Highlighting relevant values and trends |
| Excel Filters and Slicers | Interactive exploration, where implemented |
| GitHub | Project hosting and documentation |

Power Query or Power Pivot may also be used if they are part of the actual workbook.

## 🔄 Project Workflow

The analytical workflow follows these stages:

```text
Hotel Booking Dataset
         |
         v
Data Inspection
         |
         v
Data Cleaning and Preparation
         |
         v
Exploratory Data Analysis
         |
         v
KPI Calculation
         |
         v
Excel Charts and Dashboard
         |
         v
Interpretation of Findings
         |
         v
Business Recommendations
```

## ⚙️ Pipeline Steps

### Step 1: Data Collection

Load the hotel booking dataset and review its structure, fields, and intended analytical purpose.

### Step 2: Data Inspection

Examine the data types, missing values, duplicate records, categorical variables, and booking status fields.

### Step 3: Data Cleaning

Resolve relevant data quality issues and ensure that fields used in calculations are consistent.

### Step 4: Data Preparation

Prepare dates, categories, booking status, and numerical fields for analysis.

### Step 5: Exploratory Data Analysis

Explore cancellation patterns across available dimensions such as hotel type, booking period, and customer category.

### Step 6: KPI Development

Define and calculate relevant measures, including booking totals and cancellation rates, when supported by the dataset.

### Step 7: Dashboard Development

Present the selected metrics using Excel charts, summary tables, and interactive controls where implemented.

### Step 8: Validation

Reconcile dashboard calculations against the underlying data and check that filters and visualizations produce consistent results.

### Step 9: Reporting

Summarize validated findings and translate them into practical recommendations for hotel operations.

## 🧹 Data Cleaning Summary

Reliable analysis begins with consistent and accurate source data.

The following checks are relevant to hotel booking cancellation analysis:

| Cleaning Area | Purpose |
|---|---|
| Missing Values | Identify incomplete fields and assess their impact |
| Duplicate Records | Check for repeated booking records |
| Data Types | Ensure dates and numeric fields use appropriate types |
| Category Standardization | Normalize inconsistent category labels |
| Date Validation | Check date fields and chronological consistency |
| Guest Counts | Identify invalid or inconsistent guest information |
| Cancellation Status | Ensure booking outcomes are consistently represented |
| Data Validation | Check totals and derived calculations |

The actual transformations performed should be documented after reviewing the workbook or data preparation steps. No specific cleaning operation is claimed without verification.

## 🔎 Exploratory Data Analysis

Exploratory Data Analysis (EDA) helps uncover patterns, relationships, and potential operational issues in booking data.

### Areas of Analysis

- **Cancellation Analysis:** Examine canceled versus non-canceled reservations.
- **Hotel Type Analysis:** Compare cancellation behavior between available hotel categories.
- **Time-Based Analysis:** Investigate monthly or seasonal booking patterns.
- **Customer Analysis:** Explore differences across customer types.
- **Booking Behavior:** Examine relationships involving lead time, deposit type, and other available booking attributes.
- **Room Analysis:** Explore reservation and room-assignment information where available.
- **Financial Analysis:** Investigate relevant revenue-related measures if the dataset supports them.

The objective is to turn raw reservation records into understandable comparisons and business insights.

## 📈 Dashboard Features

The Excel dashboard should provide a convenient way to review important booking and cancellation measures.

Potential features include:

- Booking and cancellation summaries.
- Cancellation rate visualization.
- Hotel-type comparisons.
- Monthly booking and cancellation trends.
- Customer-segment comparisons.
- Booking characteristic analysis.
- KPI cards and summary charts.
- Interactive filters and slicers, if implemented.

The exact dashboard elements should match the actual workbook.

### Dashboard Preview
open the [dashboard screenshot directly](https://github.com/Sapna2026/Excel_HotelCancellation_Dashboard/blob/main/Screenshot%202026-10-21%20104219.png)
To explore the full dashboard, download and open `Book1.xlsx` in Microsoft Excel.
## 📌 Key Performance Indicators

The following KPIs are useful for hotel booking cancellation analysis.

| KPI | Definition |
|---|---|
| Total Bookings | Count of valid booking records, using the appropriate counting method |
| Canceled Bookings | Count of bookings marked as canceled |
| Non-Canceled Bookings | Count of bookings that were not canceled |
| Cancellation Rate | Canceled bookings divided by total eligible bookings |
| Non-Cancellation Rate | Non-canceled bookings divided by total eligible bookings |
| Average Daily Rate (ADR) | Average daily rate, using the dataset's defined ADR field |
| Hotel-wise Cancellation Rate | Cancellation rate calculated separately for each hotel category |
| Period-wise Cancellation Rate | Cancellation rate calculated for a selected period |

### Example KPI Formula

\[
\text{Cancellation Rate} =
\frac{\text{Canceled Bookings}}{\text{Total Eligible Bookings}}
\times 100
\]

The numerator and denominator should use the same reporting scope. The cancellation rate should be calculated from booking counts rather than by simply averaging individual row-level indicators.

## 🤖 Models Compared

This project is presented as an Excel-based descriptive analytics and dashboard project.

It does not claim to train or compare machine-learning models.

Instead, the analysis focuses on:

- Descriptive statistics.
- Category-wise comparisons.
- Trend analysis.
- KPI calculations.
- Visual exploration of cancellation behavior.

If a predictive modeling component is added in the future, classification algorithms such as Logistic Regression, Decision Trees, or Random Forest could be evaluated separately.

## 📏 Evaluation Metrics

Because this is a descriptive analytics project, traditional machine-learning metrics such as accuracy, precision, recall, F1-score, and ROC-AUC are not applicable unless predictive modeling is implemented.

The dashboard and analysis can instead be evaluated using:

- **Calculation Accuracy:** Whether totals and rates reconcile with source records.
- **Data Quality:** Whether incomplete or inconsistent data is handled appropriately.
- **Aggregation Consistency:** Whether grouped metrics match the underlying data.
- **Metric Definitions:** Whether KPIs use appropriate denominators and reporting periods.
- **Visualization Clarity:** Whether the dashboard makes comparisons easy to interpret.
- **Usability:** Whether users can navigate and understand the reporting interface.

No numerical evaluation results are reported here because verified project results were not available.

## 💡 Key Findings

The analysis is intended to identify evidence-based patterns in hotel reservation cancellations.

Potential questions to investigate include:

- Which hotel categories have higher cancellation rates?
- During which periods do cancellations increase or decrease?
- How does cancellation behavior differ by customer type?
- Are cancellation patterns associated with booking lead time?
- How do deposit policies relate to booking outcomes?
- Which booking characteristics deserve additional investigation?

**Important:** These are analysis questions, not confirmed findings. Add actual findings only after calculating and validating the results from the project dataset.

A useful finding should include the observed pattern, the relevant comparison, and the business implication.

## 🧠 Business Recommendations

After validating the analysis, findings may support recommendations such as:

1. **Improve Reservation Monitoring:** Review cancellation patterns to help inform occupancy planning.
2. **Review Booking Policies:** Examine whether cancellation behavior differs across deposit and booking conditions.
3. **Plan for Seasonal Demand:** Use verified time-based patterns to improve staffing and capacity planning.
4. **Improve Customer Communication:** Consider suitable confirmation and reminder processes based on observed booking patterns.
5. **Monitor Key Metrics:** Review cancellation rates consistently across relevant hotel categories and periods.
6. **Support Revenue Planning:** Use booking and cancellation trends as inputs to operational planning.

These are potential actions to investigate, not claims of measured business improvements.

## 💻 Installation

This project can be explored using Microsoft Excel if the deliverable is an Excel workbook.

### Requirements

- Microsoft Excel or a compatible spreadsheet application.
- Access to the project files.
- The original booking dataset if it is needed to refresh the workbook.

### Clone the Repository

```bash
git clone https://github.com/Sapna2026/Excel_HotelCancellation_D.git
```

Navigate to the repository folder:

```bash
cd Excel_HotelCancellation_D
```

Alternatively, use **Code → Download ZIP** on the GitHub repository page.

> The repository URL must be accessible and the project files must be present for these instructions to work.

## ▶️ How to Run

1. Clone or download the repository.
2. Open the project directory.
3. Locate the actual Excel workbook.
4. Open it in Microsoft Excel.
5. Review the available worksheets, analysis, and dashboard.
6. Apply available filters or slicers if they are implemented.
7. Review the cancellation metrics and visualizations.
8. Compare relevant results with the source dataset.
9. Consult any included reports or documentation.

### Troubleshooting

- If external data connections are used, ensure that the source files remain available at the expected paths.
- If PivotTables or PivotCharts appear outdated, inspect the workbook's refresh settings.
- If a formula returns unexpected results, verify the source fields and calculation logic.
- If dashboard filters are unavailable, check whether the workbook implements interactive controls.
- If a file cannot be found, confirm its exact name and location in the repository.

## 📦 Project Deliverables

Depending on the files included in the repository, project deliverables may include:

- An Excel workbook containing analysis and dashboard visualizations.
- A source dataset for hotel bookings.
- A dashboard screenshot or preview.
- A report or executive summary documenting findings.
- A README explaining the project workflow and usage.

Update this section to list only the deliverables actually included in the repository.

## 🎓 Challenges and Learnings

This project offers an opportunity to develop practical skills in:

- Preparing structured data for analysis.
- Identifying and resolving data quality issues.
- Defining meaningful business KPIs.
- Comparing booking patterns across categories.
- Analyzing cancellation trends.
- Building clear, user-friendly dashboards.
- Communicating analytical results to business stakeholders.
- Documenting an end-to-end analytics workflow.

## 🚀 Future Improvements

Potential improvements include:

- Document the dataset source and column definitions.
- Add a detailed data cleaning log.
- Include validated KPIs and numerical findings.
- Improve dashboard interactivity and navigation.
- Add clear visualizations for important cancellation patterns.
- Introduce a repeatable data refresh process.
- Build a complementary Power BI dashboard.
- Use SQL to explore larger booking datasets.
- Develop and evaluate cancellation prediction models as a separate extension.

## 🧩 Skills Demonstrated

- Microsoft Excel
- Data Cleaning and Preparation
- Exploratory Data Analysis
- Hospitality Analytics
- Cancellation Analysis
- KPI Development
- Data Visualization
- Dashboard Design
- Business Problem Solving
- Data Documentation
- GitHub

## 📄 License

The repository do not have license.
## 👩‍💻 Author

**Sapana Yadav**

Aspiring Data Analyst | Excel | SQL | Python | Power BI

- **GitHub Profile:** [Sapna2026](https://github.com/Sapna2026)
- **Project Repository:** [Excel_HotelCancellation_D](https://github.com/Sapna2026/Excel_HotelCancellation_D)

I'm developing my data analytics portfolio through projects that combine data preparation, business analysis, and visualization to communicate insights clearly.

---

⭐ If you find this project useful, explore the repository and share your feedback.

**Thank you for visiting my project!**
