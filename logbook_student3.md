# Oxygen Sports - Sports Event Sponsorship & Kit Donation Tracker
## Student 3 (Testing & Deployment) - Internship Logbook

### Day 1: 02 June 2026
* **Tasks Undertaken**:
  * Read the introduction section twice to align on project objectives.
  * Researched basic testing definitions (test cases, test trackers, regression testing) and planned validation strategies.
  * Checked GitHub configuration and established folder structures.

### Day 2: 03 June 2026
* **Tasks Undertaken**:
  * Set up root folder structure (`/frontend`, `/backend`, `/testing_deployment`, `/docs`, `/tests`).
  * Created the main root project `README.md` defining team structure, objectives, directory mappings, and stack.
  * Organised the repository folders and placeholders.
* **Key Decisions**:
  * Organized standard sub-folders to ensure isolated development environments for each role.

### Day 3: 04 June 2026
* **Tasks Undertaken**:
  * Outlined 5 testable objectives for system checks, validation ranges, deployment success, and logic checks.
  * Run curl health-checks simulating Postman execution for the Express `/health` API.
  * Documented the first test case and actual output in [health_check_test.md](file:///C:/Users/Shiva/.gemini/antigravity/scratch/oxygen-sports-tracker/tests/health_check_test.md).
* **Key Decisions**:
  * Recorded detailed parameters of testing configurations (e.g., ports, response keys) to prevent confusion during automated setup stages.

### Day 4: 05 June 2026
* **Tasks Undertaken**:
  * Reviewed Student 1 wireframes for domain requirement coverage.
  * Authored a 15-item system testing suite covering forms, dashboards, analytics, and api integrations.
  * Saved the test cases suite to [test_cases.md](file:///C:/Users/Shiva/.gemini/antigravity/scratch/oxygen-sports-tracker/docs/test_cases.md).
* **Key Decisions**:
  * Categorized test cases strictly by screen panel and type (Happy Path, Error, Edge Case) to ensure balanced coverage of edge cases.

### Day 5: 06 June 2026
* **Tasks Undertaken**:
  * Built final presentation slides outlining test case coverage maps, Git environment status, and project objectives.
  * Organised a mock team walkthrough timing each role to complete Review 1 presentation in 9 minutes.
  * Assured all documentation folders are clean and correctly mapped.

### Day 6: 06 June 2026
* **Tasks Undertaken**:
  * Delivered the QA sections of the Review 1 presentation covering testing objectives and the 15-item test suite to **Pamba Vamshi Krishna Sir**.
  * Gathered and compiled comments from all three student reviews into a single, cohesive team report.
  * Saved and pushed the final team evaluation notes to [review1_feedback.md](file:///C:/Users/Shiva/.gemini/antigravity/scratch/oxygen-sports-tracker/docs/review1_feedback.md).
* **Key Decisions**:
  * Scheduled explicit boundary case tests to ensure budget validation queries operate correctly at upper range limits.

### Day 7: 08 June 2026
* **Tasks Undertaken**:
  * Appended boundary condition tests (exact limits and limit + ₹1 deviations) to [test_cases.md](file:///C:/Users/Shiva/.gemini/antigravity/scratch/oxygen-sports-tracker/docs/test_cases.md).
  * Built the initial execution test log sheet at [test_tracker.md](file:///C:/Users/Shiva/.gemini/antigravity/scratch/oxygen-sports-tracker/docs/test_tracker.md) to log manual validations.
  * Collected 3 literature review references and logged details inside [literature_survey.md](file:///C:/Users/Shiva/.gemini/antigravity/scratch/oxygen-sports-tracker/docs/literature_survey.md).
* **Key Decisions**:
  * Chose a tabular tracking structure for test executions to simplify status checks during development builds.

### Day 8: 09 June 2026
* **Tasks Undertaken**:
  * Summarised the 3 research references in 5-bullet detail points covering methodology, findings, and project relevance.
  * Updated [literature_survey.md](file:///C:/Users/Shiva/.gemini/antigravity/scratch/oxygen-sports-tracker/docs/literature_survey.md) compiling academic evidence of logging importance.
  * Verified that reference data logically connects to the local equipment donation problem.
* **Key Decisions**:
  * Formulated citations strictly matching standard reference logging guidelines to prevent validation queries during review.

### Day 9: 10 June 2026
* **Tasks Undertaken**:
  * Reviewed Student 2 ER diagram layouts confirming inclusion of all frontend input attributes.
  * Expanded the test scope to formulate a comprehensive 24-item test plan covering form validations, dashboard filtering, details views, and API calls.
  * Saved the expanded logs list to [comprehensive_test_plan.md](file:///C:/Users/Shiva/.gemini/antigravity/scratch/oxygen-sports-tracker/docs/comprehensive_test_plan.md).
* **Key Decisions**:
  * Grouped the 24 test cases under 6 modular clusters (Data Entry, Budget, Visibility, Dashboard, Details/Audits, System API) for neat readability.

### Day 10: 11 June 2026
* **Tasks Undertaken**:
  * Tested the backend APIs by sending 5 complete records to verify successful inserts and index ordering.
  * Tested validation edge cases including missing parameters, negative inputs, and budget limit overrides.
  * Documented all 10 verification outcomes inside the execution log tracker sheet [test_tracker.md](file:///C:/Users/Shiva/.gemini/antigravity/scratch/oxygen-sports-tracker/docs/test_tracker.md).
* **Key Decisions**:
  * Added detailed API response keys to the test logs to easily debug interface payload fields in upcoming integration work.

### Day 11: 12 June 2026
* **Tasks Undertaken**:
  * Executed API integration validation checking details retrieval for active vs non-existent IDs.
  * Verified pagination offsets (fetching page 1 vs page 2) and tested filters and wildcard search criteria.
  * Updated [test_tracker.md](file:///C:/Users/Shiva/.gemini/antigravity/scratch/oxygen-sports-tracker/docs/test_tracker.md) documenting 6 new results.
* **Key Decisions**:
  * Documented both positive (200 OK) and negative (404 NOT FOUND) details checks to ensure error handling coverage.

### Day 12: 13 June 2026
* **Tasks Undertaken**:
  * Reviewed PR merges verifying code style consistency, comment checks, and proper path formats.
  * Executed comprehensive E2E validation: filled entry form, verified POST payloads, and checked details drawer activations.
  * Overwrote the root [README.md](file:///C:/Users/Shiva/.gemini/antigravity/scratch/oxygen-sports-tracker/README.md) with step-by-step installation instructions.
  * Documented the end-to-end integration check in [test_tracker.md](file:///C:/Users/Shiva/.gemini/antigravity/scratch/oxygen-sports-tracker/docs/test_tracker.md).
* **Key Decisions**:
  * Focused setup instructions on clear database migration details to prevent table missing crashes during user installations.

### Day 13: 15 June 2026
* **Tasks Undertaken**:
  * Formulated and executed 10 target checks for the business logic engine checking standard utilization scores, extreme values (zero budgets), and error inputs.
  * Updated [test_tracker.md](file:///C:/Users/Shiva/.gemini/antigravity/scratch/oxygen-sports-tracker/docs/test_tracker.md) documenting all 10 logic results.
* **Key Decisions**:
  * Placed explicit checks verifying that empty note inputs or negative values correctly reject during logic runs without bypassing constraint modules.

### Day 14: 16 June 2026
* **Tasks Undertaken**:
  * Expanded literature survey records compiling a total of 5 detailed references with summaries to [literature_survey.md](file:///C:/Users/Shiva/.gemini/antigravity/scratch/oxygen-sports-tracker/docs/literature_survey.md).
  * Outlined presentation summaries mapping literature inputs, benchmark comparisons, testing statistics, and Git folder counts.
  * Organized a complete team rehearsal timing Review 2 delivery to exactly 11 minutes.

### Day 15: 17 June 2026
* **Tasks Undertaken**:
  * Reviewed architecture diagram mappings for data gaps.
  * Formulated a detailed integration test plan defining 8 end-to-end user scenarios and 3 specific engine edge cases.
  * Saved the plans to [integration_test_plan.md](file:///C:/Users/Shiva/.gemini/antigravity/scratch/oxygen-sports-tracker/docs/integration_test_plan.md).
* **Key Decisions**:
  * Scheduled integration tests using precise inputs (like ₹1 and max limit costs) to verify budget checker thresholds explicitly.

### Day 16: 18 June 2026
* **Tasks Undertaken**:
  * Ran verification checks confirming validation error catches and status transitions (Approved -> Disbursed -> Completed).
  * Audited PUT requests with invalid/missing IDs.
  * Documented 8 CRUD integration tests inside [test_tracker.md](file:///C:/Users/Shiva/.gemini/antigravity/scratch/oxygen-sports-tracker/docs/test_tracker.md).
* **Key Decisions**:
  * Verified that completed sponsorships successfully block editing overrides to maintain historical audit stability.
Underside.
