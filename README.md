Executive Donor Fundraiser Dashboard |
A Tableau dashboard built to help nonprofit leadership monitor fundraising performance, donor engagement, and year-over-year giving trends across a 10-year campaign period (2015–2025).
---

Dashboard Overview
---
This executive-level dashboard provides a high-level summary of philanthropic performance using transactional donor data. It is designed for development officers, philanthropy directors, and senior leadership who need quick, actionable insights without navigating raw data. [Click here to see dashboard](https://public.tableau.com/app/profile/kerristen.brooks/viz/ExecutiveDonorFundraiserDashboard/DonorDashboard)


Key Metrics Displayed
---
Total Donations Raised (2015–2025):	$20,636,208 |
Total Active Donors:	1,987 |
Donor Retention Rate:	97.38%

Visualizations
---
Total Donations Raised (2015–2025) — Headline KPI tile showing cumulative giving over the full 10-year campaign window |
Total Active Donors — Count of unique donors with at least one recorded gift |
Donor Retention Rate — Percentage of donors who gave in more than one period, a critical indicator of donor loyalty |
Year-Over-Year Growth Trend — Line chart showing annual donation totals from 2015 to 2025, with percentage change labels; growth years shown in green, decline years shown in red |
Top 25 Donors — Ranked table of highest cumulative givers by full name and total giving amount

---

Dataset
---
File: `nonprofit_donor_data_V2.csv`
The dataset contains individual-level donation transaction records with the following fields:
Field	Description
`transactionId`	Unique transaction identifier
`donorId`	Unique donor identifier
`firstName` / `lastName`	Donor name
`email` / `phone`	Contact information
`birthdate` / `age`	Donor demographic data
`city` / `state` / `zipCode`	Geographic data
`donationDate` / `donationYear` / `donationMonth`	Temporal donation fields
`donationAmount`	Gift amount in USD
`donationPurpose`	Fund designation (e.g., Annual Fund, Scholarship Fund, Emergency Relief)
`channel`	Giving channel (Online, Direct Mail, Phone, Event, In-Person, Planned Giving)
`donorSegment`	Donor tier (Occasional, Regular, Mid-Level, Major Donor)
`donorType`	Individual, Corporate, or Foundation
`campaignName`	Associated campaign
`isRecurring`	Whether the gift is a recurring donation (Yes/No)
`firstTimeGift`	Whether this is the donor's first gift (Yes/No)
Records: ~10 years of transaction-level data across 1,987+ unique donors and 20 campaigns

---

Tools Used
---
Tableau Desktop / Tableau Public — Dashboard design and visualization |
Microsoft Excel / CSV — Data source preparation |
Python (pandas) (optional preprocessing) — Data cleaning and aggregation

---

Use Cases
---
Monitor overall fundraising health at a glance |
Identify year-over-year trends and flag declining giving periods for leadership review |
Recognize and steward top donors based on cumulative lifetime giving |
Track donor retention as a measure of program effectiveness |
Support board presentations and executive briefings |

---

Notes
---
This dashboard was built using simulated nonprofit donor data for portfolio demonstration purposes.
Donor names and contact information in the dataset are fictional.
The dashboard design uses a dark green and white color scheme consistent with nonprofit/philanthropic branding conventions.
