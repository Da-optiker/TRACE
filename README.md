# TRACE — Tracking Revenue And Canadian Expenditures

Team: Nyemazi Armand Landry, Abdulrahman Abdulle, Louis Omini
Supervisor: Andreas Maniatis
University of Windsor

Interactive Power BI dashboard of Canadian government revenue, spending, and budget balance, built from public Statistics Canada tables.

## File to review

[TRACE.pbix](TRACE.pbix)

Open it in Power BI Desktop. The figures are already stored in the file, so the report can be reviewed as saved.

The dashboard has five pages:

1. Overview — 2025 consolidated revenue, expense, and budget balance, with the 2024 comparison
2. Trends — revenue, expense, and balance over time, by level of government
3. Compare — federal, provincial and territorial, and local government side by side
4. Functions — spending by function (CCOFOG) as a bar chart and a treemap
5. Deficits — deficit and surplus years, including the years around COVID

## Data

Both tables are public.

- Statement of government operations and balance sheet, quarterly: [table 10-10-0015-01](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1010001501)
- Canadian Classification of Functions of Government, annual: [table 10-10-0005-01](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1010000501)

The cleaned tables used to build the report are in `data/`. Values in those files are millions of dollars. The dashboard shows them in billions.
