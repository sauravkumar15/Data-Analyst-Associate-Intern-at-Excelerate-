# Data-Analyst-Associate-Intern-at-Excelerate-
As a Data Analyst Associate Intern at Excelerate, I improved data accuracy by 20%, automated reporting to cut turnaround time by 30%, and built dashboards in Excel, Power BI, and Tableau. I collaborated with teams to optimize workflows, enhance data quality, and deliver actionable insights, strengthening my analytical and visualization skills.

# Internship Overview

This internship provided hands-on experience in building end-to-end data processing pipelines, validating large-scale datasets, and delivering impactful visual analytic dashboards for university admissions and outreach. The program emphasized teamwork, global collaboration, and continuous learning within a multinational setting involving Excelerate and Saint Louis University.


# Week 1: Project Initiation and Exploratory Data Analysis (EDA)

## Team Setup & Roles

* Defined roles: Project Lead (Saurav Kumar), Decision Maker, Communication Facilitator, and Members.

* Established communication protocols via weekly TCM calls and regular group meetings connecting team members across different time zones.

* Set project milestones, documentation standards, and continuous learning goals.


  ## Data Overview & Initial Inspection

* Handled three distinct datasets: ApplicantData (37,882 entries), CampaignData (23 entries), OutreachData (37,881 entries).

* Performed data type checks, missing value audits, and preliminary outlier detection.

* Developed scalable Python helper functions for cleaning phone numbers, standardizing outcomes, and name/email sanitization.

# Key Technical Tasks

* Removed duplicates reducing ApplicantData to 19,997 records.

* Normalized campaign names and outcomes using regex and mapping tables.

* Addressed missing and invalid phone numbers by filtering entries with insufficient digit lengths.

* Loaded cleaned datasets into PostgreSQL for query-based validation and initial analysis.

# Collaboration Highlights

* Coordinated effectively with global members via joint Google Docs and cloud repositories.

* Fostered a culture of accountability through shared revision logs and progress tracking.

* Held reflection meetings twice a week to discuss blockers and solutions.

# Week 2: Data Cleaning Advancement and Dashboard Development

## Advanced Cleaning & Validation

* Dropped high-null and redundant columns (e.g., PhoneNumber, BatchCode) to streamline datasets.

* Enforced business rules such as 6-digit AppID validation and timestamp completeness.

* Created new metrics - ConnectedCalls, DisconnectedCalls, ConnectivityRate, AgentPerformance - to quantify outreach effectiveness.


## Dashboard Construction

* Exported cleaned datasets as CSV and linked them to Looker Studio for interactive dashboard creation.

* Built geo-distribution maps showing applicant concentrations in India, Ghana, Bangladesh, and other regions.

* Designed KPIs including total applicants, unique campaigns, outreach volume, and call connectivity rates.

* Created funnel visualizations tracking applicant progress through admission stages.


## Global Team Interaction

* Participated in weekly review calls with Excelerate mentors and Saint Louis University collaborators.

* Shared knowledge on Looker Studio dashboard filtering and linking CSV-based reports.

* Addressed feedback loops on data quality and presentation effectiveness.



# Week 3: Comprehensive Data Validation and KPI Enrichment

## Dataset Refinement


* Deleted invalid AppIDs and incomplete timestamp records to improve dataset integrity.

* Iteratively pruned unused columns to maintain a lean master table.

* Systematically removed duplicate records, ensuring single latest encounters per applicant.
  

## KPI Calculation and Validation

* Defined formulas for connectivity rate and agent performance categories (Good, Average, Poor, Not Evaluated).

* Applied SQL queries to audit metrics against raw data for consistency.

* Validated stage outcomes ensuring alignment with campaign categories and intake statuses.


## Results & Insights

* Achieved a connectivity rate of approximately 92% from 29,210 calls.

* Identified high dropout rates at No Information and Not Enrolled stages prompting process review.

* Highlighted key campaign performance trends spotlighting GR GS Call and SP25 campaigns.



## Teamwork & Communication

* Conducted technical walkthroughs to explain validation logic to peers.

* Documented all SQL scripts and validation procedures collaboratively.

* Enabled asynchronous knowledge transfer via recorded sessions and shared slide decks.


# Week 4: Final Presentation and Reflective Evaluation

## Final Deliverables

* Presented a comprehensive EDA, data validation, and visualization report incorporating before-after comparisons showing improved data quality.

* Delivered polished Looker Studio dashboards with interpreted insights for stakeholder decision-making.


## Presentation Videos

* Self-presentation video summarizing individual contributions, technical achievements, and overall learning.

* Peer presentation video showcasing team collaboration dynamics, problem-solving approaches, and collective outcomes.

## 360-Degree Peer Evaluations

* Facilitated multi-dimensional peer feedback assessing technical skill, teamwork, communication, and leadership.

* Synthesized evaluations into a transparent feedback report fostering professional development.


## Continuous Learning & Team Synergy

* Reflected on challenges faced such as duplicate detection complexities, timestamp inconsistencies, and cleaning workflow automation.

* Emphasized the importance of agile processes and global teamwork in delivering timely, high-quality outcomes.



# Technology Stack

 *  Python: Pandas, NumPy for data cleaning and manipulation.

 * PostgreSQL: Data loading, querying, and validation.

 * Looker Studio: Interactive dashboarding with CSV data sources.

 * SQL: Complex joins, aggregation, and KPI calculations.


# Acknowledgements

* Excelerate and Saint Louis University mentors for project guidance.

* Team members for collaboration across continents ensuring smooth coordination.

* Continuous peer support and constructive feedback fostering skill growth.

# Credits

* Intern: SAURAV KUMAR
  
* Collaborators: Farhan Hussain, M. Nouman Arshad, Shivansh Rajput, Dia Agarwal, Yuva Mirsha, Ajay Kumar Kasaudhan, Naheed Akhtar, and others

* Special thanks for feedback and guidance to mentors and peer reviewers at Excelerate and SLU.




