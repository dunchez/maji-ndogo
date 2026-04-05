## 1. Project Overview
[cite_start]Maji Ndogo is a data-driven initiative aimed at solving a national water crisis[cite: 1, 16]. [cite_start]Following an extensive survey, a database of 60,000 records was compiled by engineers, field workers, and scientists[cite: 5]. [cite_start]The project's mission is to extract meaningful insights from this data to identify pressing problems and set a course for sustainable, data-driven water solutions[cite: 6, 12].

## 2. Objectives
* [cite_start]**Data Exploration**: Explore the foundational tables and understand the connections between variables[cite: 3, 9].
* [cite_start]**Quality Assessment**: Identify and flag water sources that are contaminated or have low quality scores[cite: 14, 467].
* [cite_start]**Integrity Auditing**: Verify the accuracy of the data and uncover potential tampering or corruption[cite: 1811, 1812].
* [cite_start]**Actionable Planning**: Convert raw data into job lists for engineers and meaningful views for decision-makers to plan budgets and infrastructure repairs[cite: 2397, 2400].

## 3. Database Structure
[cite_start]The project utilizes a MySQL database containing several key tables[cite: 492, 501]:
* [cite_start]**water_source**: Logs information about each source (e.g., tap_in_home, well, river, shared_tap) [cite: 506, 642-645].
* [cite_start]**well_pollution**: Contains scientist notes on biological contamination and chemical pollutants[cite: 220, 221].
* [cite_start]**visits**: A logbook of all trips made to different water sources, including queue times[cite: 50, 554].
* [cite_start]**location**: Records the address, province, town, and type (Urban/Rural) for each site[cite: 84].
* [cite_start]**employee**: Information about the field workers who collected the data[cite: 501].
* [cite_start]**data_dictionary**: An embedded table explaining every column in the database[cite: 606].

## 4. Project Phases
### Phase 1: Beginning the Journey
* [cite_start]Getting to know the data by retrieving initial records and exploring table structures[cite: 43].
* [cite_start]Identifying unique water source types and assessing their general quality[cite: 48, 461].

### Phase 2: Clustering and Cleaning
* [cite_start]**Data Cleaning**: Fixing inconsistencies in pollution records and updating employee data[cite: 901, 263].
* [cite_start]**Pattern Analysis**: Clustering data to find broader narratives and analyzing queue times to understand citizen needs[cite: 903, 912].

### Phase 3: Weaving the Narrative
* [cite_start]**Auditing**: Integrating an independent auditor's report to assess data integrity[cite: 1807, 1810].
* [cite_start]**Evidence Gathering**: Building complex queries to identify "corrupt" records where data was tampered with[cite: 1808, 2002].

### Phase 4: Charting the Future
* [cite_start]**Final Insights**: Joining data across multiple tables to find final actionable insights[cite: 2403].
* [cite_start]**Practical Plan**: Creating a `Project_progress` table to track engineering tasks and providing summary reports to President Naledi[cite: 2393, 2634].

## 5. Key Findings
* [cite_start]**Contamination Risks**: Open water sources like rivers carry a high risk of biological pollution[cite: 121].
* [cite_start]**Infrastructure Issues**: Many home taps are recorded as "broken," serving large numbers of people through a single record[cite: 642, 163].
* [cite_start]**Corruption**: Four officials (Zuriel Matembo, Malachi Mavuso, Bello Azibo, and Lalitha Kaburi) were flagged for making significantly more mistakes and having incriminating statements made against them[cite: 2405].

***
[cite_start]*Developed by EXPLORE AI ACADEMY, 2023.* [cite: 1, 2392]
