## Brain Tumor Distribution Analysis (Power BI)
An interactive Power BI dashboard that explores brain tumor cases by tumor type, grade, brain region, age group and diagnosis year.

## The question
How are brain tumor cases distributed across tumor types, grades, regions of the brain and age groups, and how has the number of diagnoses changed over time?

## The data
- A practice dataset of **20,000 patients** and 20 columns ( BTD1.csv ).
- Fields include age, gender, tumor type (malignant or benign), tumor size, brain region, histology, stage, treatments, survival rate and diagnosis date.
- There are no missing values and no duplicate patient IDs.
- The values are spread very evenly across groups, which suggests the dataset is simulated rather than real patient records. This project is about dashboard design and analysis skills, not medical conclusions.

## What I built
- **KPI cards with trend lines: Total Patients, Average Age and Tumor Size, each with a supporting figure underneath
- **Tumor Type Distribution: malignant vs benign
- **Top Affected Brain Region
- **Top Affected Age Group
- **Annual Patients Diagnosed: a line chart over time
- **Tumor type buttons: Astrocytoma, Glioblastoma, Medulloblastoma and Meningioma
- **Grade buttons (Grade I to IV): filter the whole dashboard by tumor grade. They are linked to the data through a relationship between a grade-image table and the patient table.
- ** Brain MRI image as the visual centrepiece

## Key numbers (all 20,000 patients)
|Measure | Value |
|---|---|
| Total patients	| 20,000 |
| Average age	| 49.43 |
| Average tumor size	| 5.24 |
| Malignant	| 50.15% |
| Average survival rate	| 70.1% |

## My Findings
- The Temporal region has the most cases overall (5,118), followed by Parietal (4,990), Occipital (4,967) and Frontal (4,925).
- The 60+ age group is the largest overall (6,299 patients, about 31.5%). In this dashboard, 60+ means patients aged over 60.
- Cases are spread almost evenly across the four tumor types, the four grades and the four brain regions. Average survival rate is about 70% in every group, whatever the tumor type, grade or treatment.
- The last point on the line chart is lower because 2024 data only runs to October.
- The youngest patient is 20, so the 11-20 age group only contains 20-year-olds.

## How I built it
1.	Loaded BTD1.csv into Power BI and checked for missing values and duplicates.
2.	Grouped ages into bands: 11-20, 21-30, 31-40, 41-50, 51-60 and 60+.
3.  Built the KPI cards, charts and tumor type buttons.
4.	Connected the Grade buttons to the data by creating a Grade column and a relationship between the two tables.

## Tools
Power BI, DAX, CSV

## Files
my brain tumor dashboard!!.pbix: the Power BI report
BTD1.csv: the dataset
Dashboard screenshot

 ## About me
Osavibie Deborah Edoruyi, aspiring data analyst.
[LinkedIn](https://www.linkedin.com/in/osavibie-edoruyi-1131a6329)

