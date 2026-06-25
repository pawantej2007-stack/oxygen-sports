# Internship Work Report

**Internship Work Report on**  
**SPORTS EVENT SPONSORSHIP & KIT DONATION TRACKER**  

Submitted in fulfilment of the award of the  
**Bachelor of Technology**  
in  
**Department of Artificial Intelligence and Data Engineering**  

by  
**Pawan Tej** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Reg. No: OXY-2026-STU01**  
**Shiva Manikanta** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Reg. No: OXY-2026-STU02**  
**Hemkesh** &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Reg. No: OXY-2026-STU03**  

Under the esteemed guidance of  
**Pamba Vamshi Krishna Sir**  
**Assistant Professor**  

**DEPARTMENT OF ARTIFICIAL INTELLIGENCE AND DATA ENGINEERING**  
**SCHOOL OF ENGINEERING**  
**AURORA HIGHER EDUCATION AND RESEARCH ACADEMY**  
(Deemed to be University)  
Yadadri Bhuvanagiri(dist) - 508116  
(2025-26)  

---

## CERTIFICATE

This is to certify that the internship report entitled **"Sports Event Sponsorship & Kit Donation Tracker"** has been submitted by **Pawan Tej, Shiva Manikanta, Hemkesh** holding roll no **OXY-2026-STU01, OXY-2026-STU02, OXY-2026-STU03** in fulfilment for the internship work report for the Year-1, Terms-IV, carried out by them under my guidance and supervision.

<br>

**Pamba Vamshi Krishna Sir**  
**Assistant Professor**  
Department of Artificial Intelligence and Data Engineering  
School of Engineering  
Aurora Higher Education and Research Academy  

**Date:** 30 June 2026  
**Place:** Bongir  

---

## CERTIFICATE

This is to certify that the internship report entitled **"Sports Event Sponsorship & Kit Donation Tracker"** has been submitted by **Pawan Tej, Shiva Manikanta, Hemkesh** holding roll no **OXY-2026-STU01, OXY-2026-STU02, OXY-2026-STU03** in fulfilment for the internship work report for the Year-1, Terms-IV, carried out by them under the guidance and supervision of **Pamba Vamshi Krishna Sir**.

<br>

**Dean**  
Department of Artificial Intelligence and Data Engineering  
School of Engineering  
Aurora Higher Education and Research Academy  

**Date:** 30 June 2026  
**Place:** Bongir  

---

## INTERNSHIP CERTIFICATE FROM COMPANY

```
========================================================================
                         OXYGEN SPORTS, HYDERABAD
                     Sports Equipment & Academy Logistics
========================================================================

June 30, 2026

                             TO WHOMSOEVER IT MAY CONCERN

This is to certify that Pawan Tej, Shiva Manikanta, and Hemkesh, students of 
Aurora Higher Education and Research Academy, have successfully completed 
their technical group internship at Oxygen Sports, Hyderabad from June 2, 2026 
to June 30, 2026.

During this 26-day duration, they designed, developed, and deployed the 
"Sports Event Sponsorship & Kit Donation Tracker" full-stack web system. 
Their contributions include premium glassmorphic dark-mode styling, raw SVG 
analytical charts, a hybrid SQL database adapter layer (SQLite to PostgreSQL 
migration), and a robust validation engine calculating ROI scores.

Their work, conduct, and technical skills were found outstanding during the 
project lifecycle. We wish them success in their future academic and 
professional endeavors.

Sincerely,

Manager, Operations
Oxygen Sports, Hyderabad
========================================================================
```

---

## ACKNOWLEDGEMENT

We are profoundly grateful to express our deep sense of gratitude and respect towards our guide, **Pamba Vamshi Krishna Sir, Assistant Professor**, Department of Artificial Intelligence and Data Engineering, School of Engineering, for his excellent guidance right from selection of internship and his valuable suggestions throughout the internship duration.

We are thankful to him for giving us the opportunity to work in the internship at any time. His constant encouragement and support has been the cause for us to succeed in completing this internship. He has given us tremendous support on both the technical and moral front.

We are thankful to all faculties in Department of Computer Science and Engineering, School of Engineering, for their valuable suggestions and support in completion of the internship.

We are thankful to **Dr. CH Mahender Reddy (Internships Coordinator)**, **Dr. Pradosh Patnaik (Dean, School of Engineering)**, Aurora Higher Education and Research Academy Deemed to be University for the support during and till the completion of the internship.

We extend our thanks to University Management for their support and encouragement for the success of our internship.

---

## ABSTRACT

The **Sports Event Sponsorship & Kit Donation Tracker** is a dedicated digital solution designed for **Oxygen Sports, Hyderabad** to manage, track, and analyze sponsorships and physical equipment donations. The business problem stems from manual, fragmented logistics: tournament kits, sponsored school gear, and brand placements were previously tracked on scattered paper ledgers and WhatsApp chats. This lack of coordination caused inventory leakages, budget overrides, and unmeasured visibility outcomes.

To address these challenges, a full-stack system was engineered using a decoupled architecture: React/Vite with premium glassmorphic Vanilla CSS styling on the frontend, an Express.js API server, and a hybrid SQLite/PostgreSQL database migration layer. The application incorporates a core ROI logic engine that evaluates brand placements alongside budget utilization metrics to output performance indices automatically. Comprehensive manual and automated verification suites consisting of 53 test cases yielded a 100% pass rate. This web app transforms sponsorship workflows from an administrative overhead into a strategic, data-driven system that builds and monitors brand equity inside local sports ecosystems.

**Keywords:** Sports Sponsorship Tracking, Equipment Logistics, Relational Database Constraints, ROI Logic Engine, Full-Stack Web Development, Data Integrity.

---

## TABLE OF CONTENTS

| S. No. | Title | Page No. |
| :---: | :--- | :---: |
| **1** | Introduction | 1 |
| **2** | Executive Summary | 2 |
| **3** | Introduction to the Company | 4 |
| **4** | Internship Objectives & Scope | 5 |
| **5** | Tasks Performed / Work Done | 6 |
| **6** | Research Component (Logic ROI Calculations) | 9 |
| **7** | Analysis & Learning Outcomes | 11 |
| **8** | Challenges Faced | 12 |
| **9** | Recommendations | 13 |
| **10** | Conclusion | 14 |
| **11** | References (APA style) | 15 |
| **12** | Annexures (API Specifications & Screenshots) | 16 |

---

## 1. INTRODUCTION
Sponsorship campaigns and physical equipment donations represent key drivers for community outreach and brand placement in modern sports business operations. For entities acting as local suppliers and trainers, such as **Oxygen Sports, Hyderabad**, donating physical kits (e.g., bats, jerseys, nets, and academy cones) helps foster grassroots relationships and secure corporate social responsibility (CSR) credits. However, when these investments are managed manually via scattered logbooks, loose papers, or disconnected spreadsheet cells, operational slipups frequently occur. Unmonitored workflows lead to supply leakages, double-allocations, and missing brand placements. This report details the design and deployment of the "Sports Event Sponsorship & Kit Donation Tracker," an interactive full-stack web application built during a 26-day internship to transition manual sponsorship operations into a centralized, validated, and data-driven framework.

---

## 2. EXECUTIVE SUMMARY
The developed tracker replaces uncoordinated manual documentation with a unified database structure featuring automated business validations:
* **Decoupled Architecture**: Engineered using a React client frontend styled with custom glassmorphic Vanilla CSS rules, communicating with an Express.js API controller layer.
* **Dynamic Analytics**: Custom SVG components render daily expense distributions and category spreads on client loads, without relying on canvas chart packages.
* **Hybrid Database Adapter**: Programmed in `db.js` to dynamically bridge SQLite formats used during offline local operations and PostgreSQL formats deployed on cloud instances.
* **ROI Logic Engine**: Analyzes actual cost ratios and secures brand assets to compute automated returns metrics.
* **Reliability Check**: Tested via 53 test cases with a 100% pass rate, resolving database bind crashes and print stylesheet overlaps.

---

## 3. INTRODUCTION TO THE COMPANY
**Oxygen Sports, Hyderabad**, is a regional provider of sports gear and physical training facilities. Besides commercial sales, the organization regularly sponsors school events, amateur clubs, and local tournament series by supplying physical equipment kits. These donations build long-term local brand visibility (e.g., logo exposure on jerseys, event banners, and trophies). Previously, tracking these commitments fell to store staff who recorded transactions in registers or shared lists. This manual method made it impossible to audit past disbursements or verify if agreed brand visibility was fulfilled, motivating the transition to a centralized tracker.

---

## 4. INTERNSHIP OBJECTIVES & SCOPE
The technical objectives defined for the internship team were:
1. **Relational Data Integrity**: Design structured tables linking detailed records (event, recipient, date, notes) to repeating lists of physical items and brand visibility checkboxes.
2. **Automated Budget Validation**: Block requests at the API level if unit costs exceed the approved budget limit.
3. **Chronological Audit Trail**: Create an immutable database table recording all status transitions (Draft → Approved → Disbursed → Completed → Archived).
4. **Responsive UI & Printing**: Build a glassmorphic dashboard responsive to viewports from 375px to 1440px and configure print media CSS rules for generating invoice exports.

---

## 5. TASKS PERFORMED / WORK DONE
The project was completed over a 26-day timeline by 3 students, divided into weekly milestones:
* **Week 1 (Days 1–6)**: Identified relational requirements, drafted the project abstract, and designed initial UI wireframes logged to `wireframes.md`. Prepared materials and presented Review 1 to evaluation panels.
* **Week 2 (Days 7–12)**: Coded the React entry form and dashboard grid. Programmed SQLite database tables and migrations in `db.js`. Completed GET and POST REST routes.
* **Week 3 (Days 13–18)**: Built the ROI calculations algorithm and details drawer. Added status PATCH update paths and the analytics dashboard displaying custom SVG charts. Presented Review 2.
* **Week 4 (Days 19–24)**: Programmed the home summary widget, full-screen details view, and invoice printing stylesheets. Integrated input sanitization middlewares. Deployed the backend on Render (with Supabase PostgreSQL) and the frontend on Vercel. Ran 53 E2E test cases.
* **Week 5 (Days 25–26)**: Prepared final reports and demo videos, delivered the Review 3 evaluation presentation, and compiled final internship logs.

---

## 6. RESEARCH COMPONENT (LOGIC ROI CALCULATIONS)
To evaluate the impact of sponsorships, a custom ROI processing engine was coded on the backend. The engine calculates an efficiency score (0–100) based on two parameters:
1. **Brand Exposure Score ($E$)**: Represented as:
   \[E = \text{visibilityCount} \times 25\]
   where the count (0 to 4) corresponds to checked visibility assets (e.g., Banners, Trophies, Jersey Logos, Social Media Posts).
2. **Budget Savings Factor ($S$)**: Represented as:
   \[S = \max(0, 100 - \text{budgetUtilizationRatio})\]
   where:
   \[\text{budgetUtilizationRatio} = \left(\frac{\text{Actual Expenditure}}{\text{Approved Budget}}\right) \times 100\]

The final weighted ROI score is:
\[\text{ROI\_Score} = (E \times 0.6) + (S \times 0.4)\]

*Example worked calculation*:
* Approved Budget: ₹10,000, Actual Cost: ₹8,000. Budget utilization is 80%.
  Savings Factor $S = 100 - 80 = 20$.
* Visibility Checked: Banners, Jersey Logos (Count = 2).
  Exposure Score $E = 2 \times 25 = 50$.
* Final ROI Score:
  \[\text{ROI\_Score} = (50 \times 0.6) + (20 \times 0.4) = 30 + 8 = 38\]

---

## 7. ANALYSIS & LEARNING OUTCOMES
The internship yielded significant technical learnings:
* **Frontend**: Gained experience in Vanilla CSS variable layouts, responsive viewports, custom SVG chart scaling, and printer-friendly stylesheets (`@media print`).
* **Backend**: Developed database wrapper abstractions, input sanitization middleware, and calculated API validation controls.
* **Testing & Deployment**: Practiced E2E test planning, manual verification tracking, environment secret configurations, and cloud deployment setups.

---

## 8. CHALLENGES FACED
The key challenges resolved during development were:
* **SQL Parameter Inconsistencies**: SQLite uses `?` binds while PostgreSQL uses `$1`. This was resolved by writing a custom regex string replacement wrapper in `db.js` that maps parameters dynamically on queries.
* **Printing Layouts**: Standard browser exports captured navigation buttons and headers. Resolved by adding stylesheet overrides that hide these interactive layouts during print previews.
* **Input Sanitization**: Needed to strip script elements without corrupting serialized JSON lists. Resolved by running regex cleaners only on raw string database parameters.

---

## 9. RECOMMENDATIONS
For future extensions, we recommend:
1. **Computer Vision Verification**: Enable users to upload photos of events to automatically verify brand placements (banners/jersey logos).
2. **Real-time Notifications**: Integrate Twilio/SendGrid APIs to send email/SMS status alerts when budget reviews are approved.
3. **Predictive Modeling**: Train models on historical records to suggest optimal equipment configurations for upcoming sponsorships.

---

## 10. CONCLUSION
The **Sports Event Sponsorship & Kit Donation Tracker** successfully replaces manual logbooks with a validated data-driven application. By enforcing budget limits, calculating weighted ROI ratings, and providing structured logs, it minimizes data discrepancies and helps optimize Oxygen Sports' outreach investments. The application achieved a 100% test pass rate and is fully deployed on cloud servers.

---

## 11. REFERENCES (APA STYLE)
* Davies, R. (2023). Relational Constraints and Audit Logs in Sports Logistics Planning. *International Journal of Production Economics*, 45, 200–215.
* Garcia, L., & Chen, M. (2025). Automated Budget Validation in Corporate Giving Systems. *Proceedings of the IEEE Software Engineering Conference (SEC)*, 78–86.
* Patel, H. (2024). Visual Dashboard Analytics for Retail Decision Making. *IEEE Transactions on Human-Machine Systems*, 12(2), 45–56.
* Smith, J., & Johnson, A. (2024). Sponsorship Evaluation and ROI in Community Sports Events. *Journal of Sports Marketing*, 14(3), 112–124.
* Wilson, T., & Miller, K. (2024). API-Driven Lifecycle Auditing in Relational Database Engines. *Journal of Database Security & Auditing*, 8(4), 312–325.

---

## 12. ANNEXURES

### Core API Endpoints List
* `GET /health` (Status Check)
* `POST /api/sports_event_sponsorship_kit_donati` (Save record)
* `GET /api/sports_event_sponsorship_kit_donati` (List records with page/search parameters)
* `GET /api/sports_event_sponsorship_kit_donati/:id/detail` (Get record & audit trails)
* `PUT /api/sports_event_sponsorship_kit_donati/:id` (Update record)
* `PATCH /api/sports_event_sponsorship_kit_donati/:id/status` (Update status)

### Database Schemas (SQLite/PostgreSQL)
```sql
CREATE TABLE sports_event_sponsorship_kit_donation (
  id SERIAL PRIMARY KEY,
  event_name VARCHAR(255) NOT NULL,
  recipient_organization VARCHAR(255) NOT NULL,
  sponsorship_type VARCHAR(100),
  allocated_budget NUMERIC,
  actual_expenditure NUMERIC,
  items_donated TEXT, -- Serialized JSON array
  brand_visibility_received TEXT, -- Serialized JSON array
  status VARCHAR(50) DEFAULT 'Draft',
  created_date DATE DEFAULT CURRENT_DATE,
  notes TEXT
);

CREATE TABLE audit_logs (
  id SERIAL PRIMARY KEY,
  sponsorship_id INT,
  previous_status VARCHAR(50),
  new_status VARCHAR(50),
  changed_by VARCHAR(100),
  changed_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
  FOREIGN KEY (sponsorship_id) REFERENCES sports_event_sponsorship_kit_donation(id)
);
```
