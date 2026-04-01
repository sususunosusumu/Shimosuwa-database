Shimosuwa 2026 Budget Guide CSV package

Files
- budget_guide_2026_projects.csv
  Main machine-readable project list extracted from the budget guide PDF.
  Columns:
  - page: source PDF page
  - chapter / section
  - project_name
  - budget_2026_text / budget_2026_man_yen
  - budget_2025_text / budget_2025_man_yen
  - budget_diff_man_yen / budget_change_rate_pct
  - department
  - account_or_code: business code or special-account label
  - purpose
  - main_actions
  - major_expenses_prev: major expense bullets shown in the page's prior-year budget panel

- budget_guide_2026_account_summary.csv
  Top-level account summary from the "当初予算" table.

- budget_guide_2026_general_revenue.csv
  General account revenue summary.

- budget_guide_2026_general_expenditure.csv
  General account expenditure summary.

Notes
- Text was extracted from the uploaded PDF and normalized into CSV.
- Because the source PDF is a designed booklet with multi-block page layout, a small number of rows may need spot-checking before public release.
- Amount columns in *_man_yen use 万円 as the numeric base for easier sorting and charting.
