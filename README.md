# Beverage Line Downtime Analysis

**Program:** Digital Egypt Pioneers Initiative (DEPI), MCIT  
**Track:** Junior Data Analysis  
**Instructor:** Amir Ahmed Shehata

## Project Overview
This project investigates production delays in a bottling facility where batches frequently exceed target runtimes. Baseline cycle times are 60 minutes for 600 ml bottles and 98 minutes for 2-liter bottles. Using a Power BI dashboard, the analysis tracks 12 downtime categories to isolate mechanical failures from operator errors and guide daily batch scheduling.

## Team Members, Roles & Responsibilities
| Name | Project Role | Responsibilities |
| :--- | :--- | :--- |
| **Talha Wessam Mahmoud** | Project Coordination & Business Analysis | Coordinate team tasks, write the 10 business questions (Q1-Q10), and verify report numbers |
| **Mohamed Refat Mohamed Elamary** | Data Cleaning & Modeling | Clean raw logs in Power Query (overnight rollover, mL units, unpivot 12 factors) and build the star schema |
| **Omar Ahmed Mostafa Fakhry** | DAX Calculations | Write DAX measures for utilization, Pareto shares, operator rates, and next-day forecasts |
| **Marwa Ahmed Abdelaziz Mohamed** | Dashboard Design | Design page layouts, theme styling, and filter controls across the 4 report pages |
| **Mariam Mohamed Abdul Rashid Abdul Hamid** | Dashboard Design | Build report visuals, page navigation, and the SKU tooltip view |
| **Hager Osama Marzouk** | Documentation & Presentation | Write the cleaning and modeling doc and prepare the final presentation deck |

## Work Plan
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
  * Write DAX measures for line utilization, downtime shares, normalized operator rates, and next-day capacity forecasts.
  * Build a 4-page Power BI report covering line overview, downtime causes, operators and products, and next-day forecasts.
  * *Deliverable:* Completed `.pbix` dashboard file.
* **Week 4: Final Presentation**
  * Assemble project findings, practical maintenance observations, and visual summaries into a slide deck.
  * *Deliverable:* Final report and presentation deck.

## KPIs
* **Line Utilization & Downtime Rate:** Share of total line time spent bottling versus stopped.
* **Lost Batch Capacity:** Equivalent standard batches lost to downtime and the share of batches hit by stops.
* **Operator vs. Non-Operator Split:** Share of downtime caused by operator error versus equipment, supply, and other stops.
* **Stop Frequency & Average Duration:** How often each downtime factor occurs and how long each stop lasts.
* **Operator Error Rate:** Operator-caused downtime per productive hour to compare operators across different workloads.
* **Product Downtime Rate:** Downtime share and average delay per batch across products and bottle sizes (600 ml vs. 2-liter).
* **Next-Day Batch Capacity:** Expected downtime and completed batches for planned shift hours, plus extra batches gained if downtime drops.

## Project Files
* **Power BI Dashboard:** [Manufacturing Downtime.pbix](https://drive.google.com/file/d/1GXvakc7QJ07fZXKJPmV3_M2YBDx_J73e/view?usp=sharing)
* **Cleaning & Modeling Documentation:** [Cleaning & Modeling Doc.pdf](https://drive.google.com/file/d/1hWw6j58ALkrbdq8r21LBNeE6EHhhZyW2/view?usp=sharing)
* **Analysis Questions (Q1-Q10):** [Manufacturing Downtime Analysis Questions.pdf](https://drive.google.com/file/d/1AhNVVFIZDFbtkBJPBGQ-dhVn5wrqayMX/view?usp=drive_link)
* **Original Dataset:** [Manufacturing Line Productivity.xlsx](https://docs.google.com/spreadsheets/d/1vMn7fnoOOgRVKfxzh4CdjM9OyK8ucQRr/edit?usp=sharing&ouid=108723738870898957321&rtpof=true&sd=true)
* **Final Presentation:** Pending Week 4 upload
