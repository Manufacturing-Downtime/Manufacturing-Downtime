## Beverage Bottling Line Downtime Analysis

**Program:** Digital Egypt Pioneers Initiative (DEPI), MCIT  
**Track:** Junior Data Analysis  

##  Project Overview
This project investigates production delays in a bottling facility where batches frequently exceed target runtimes. Baseline cycle times are 60 minutes for 600 ml bottles and 98 minutes for 2-liter bottles. Using a Power BI dashboard, the analysis tracks 12 downtime categories to isolate mechanical failures from operator errors and guide daily batch scheduling.

## Team Members
| Name | Project Role |
| :--- | :--- |
| **Talha Wessam Mahmoud** | Business Analysis Lead |
| **Mohamed Refat Mohamed Elamary** | Data Cleaning and Modeling Lead |
| **Omar Ahmed Mostafa Fakhry** | DAX Calculations Lead |
| **Marwa Ahmed Abdelaziz Mohamed** | Dashboard Designer |
| **Mariam Mohamed Abdel Rasheed Abdel Hameed** | Dashboard Designer |
| **Hager Osama Marzouk** | Documentation and Presentation Lead |


## Instructor
* Eng. Amir Shehata (DEPI Data Analysis Track)


The project follows a four-week schedule:
* **Week 1: Data Cleaning and Preprocessing**
  * Clean raw batch logs and compute actual run durations, including runs that cross midnight.
  * Reshape the 12 downtime factor columns into a normalized format suitable for Power BI relationships.
  * Build a Star Schema linking the batch records to product and downtime factor lookup tables.
  * *Deliverable:* Cleaned data model and documented Power Query steps.
* **Week 2: Analysis Questions Phase**
  * Formulate specific operational questions about failure rates, line bottlenecks, and operator error frequencies.
  * Compare actual batch completion times to the baseline targets.
  * *Deliverable:* Written analytical framework and business questions.
* **Week 3: Dashboard Phase**
  * Write DAX measures for total downtime minutes, percentage of operator-related errors, and batch cycle variance.
  * Build a Power BI report with dedicated views for high-level line performance, downtime breakdowns, and operator comparisons.
  * *Deliverable:* Completed `.pbix` dashboard file.
* **Week 4: Final Presentation**
  * Assemble project findings, practical maintenance observations, and visual summaries into a slide deck.
  * *Deliverable:* Final report and presentation deck.

## Roles and Responsibilities
* **Data Preparation (Mohamed Refat):** Fixes invalid timestamps, normalizes factor data, and sets up data model relationships.
* **Business Analysis (Talha Wessam):** Identifies patterns in stoppage data, such as runs with excessive delays, and frames questions for reporting.
* **Calculations and Metrics (Omar Ahmed):** Writes DAX measures for cycle variance, failure frequencies, and downtime duration totals.
* **Interface and Visuals (Marwa Ahmed and Mariam Mohamed):** Structures report pages, selects charts, and ensures clear navigation and filtering.
* **Presentation and Reporting (Hager Osama):** Prepares the final slide deck and organizes project documentation for review.
