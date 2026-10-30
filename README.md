Greenfield School Results Analysis

An Excel data-cleaning and analysis project using student results from Greenfield Secondary School. The workbook helps the school compare class and subject performance, track progress across three terms, and identify students who may need extra support.

Project objectives

Clean inconsistent class and gender labels.

Convert text-formatted scores to numbers and correct scores above 100 caused by an extra zero.

Remove duplicate student-term records while keeping blank subject scores blank.

Calculate each student's total, average, grade, and rank within their class and term.

Compare class averages and pass rates across terms.

Find the hardest and easiest subjects, measure student improvement, and list students with a Third Term average below 50.

Present the findings in a summary dashboard with charts and class-by-subject comparisons.

Data cleaning

The original dataset contained 726 rows. After standardising the data and removing six duplicate Student ID and Term records, the cleaned dataset contains 720 student-term records for 240 students across six classes. Thirty text-formatted scores were converted to numbers, three scores with an extra zero were corrected, and 12 blank scores were retained as missing rather than changed to zero.

Key findings

Average performance increased from 60.10 in First Term to 64.43 in Third Term.

JSS3B had the highest Third Term class average (66.73) and the greatest improvement from First to Third Term (+6.05 points).

JSS3A had the lowest Third Term average (62.65) and pass rate (80%), so it may need the most class-level support.

Maths was the hardest subject, with an average of 55.41 across all terms. Civic Education had the highest average at 67.32.

Thirty-two students had a Third Term average below 50 and were listed for follow-up support.

Workbook contents

The Excel workbook contains the original Results sheet and these analysis sheets:

Clean Data - standardised records, totals, averages, grades, ranks, cleaning report, and top student rankings.

Class Summary - class size, average score, and pass rate by term, plus class improvement.

Subjects - subject averages by term and class.

Improvement - First-to-Third-Term changes for each student and the five largest gains.

At Risk - students with a Third Term average below 50.

Summary - key findings, charts, a message to the principal, and Class/Term dropdown filters.

Notes

The Summary sheet uses dropdown filters for Class and Term to show a selected class-term average. These controls are formula-driven and are not native PivotTable slicers.

<img width="1180" height="541" alt="image" src="https://github.com/user-attachments/assets/0ab9d4d4-ab35-4a5e-b0ca-56414c42d9c6" />
<img width="1710" height="332" alt="image" src="https://github.com/user-attachments/assets/2c49b976-f3a1-4481-a20b-5bcaa3e4f4b6" />
<img width="1270" height="522" alt="image" src="https://github.com/user-attachments/assets/7042ecb6-4ed4-46a2-b741-abf0b4d3d0b8" />

