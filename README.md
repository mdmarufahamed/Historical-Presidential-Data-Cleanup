The Dataset: 
A historical list of U.S. Presidents with details on their party, vice president, and salary.

The Problems I Found:
Inconsistent Name Casing: e.g., john adams, JAMES MONROE.
Dirty" Prior Experience Field: The prior column contained messy text with extra spaces and strange characters (â€“ which is an encoding error for a long dash –).
Inconsistent Political Party Names: e.g., Demorcatic (typo for Democratic), Republicans (should probably be Republican).
Duplicate Rows: Woodrow Wilson and Barack Obama appear twice.
Irrelevant Data: The prior column was removed in the cleaned sheet, suggesting it was deemed unnecessary for the final analysis.

My Cleaning Process:
Standardization: Applied PROPER function to President and Vice names.
Deduplication: Identified and removed duplicate entries.
Error Correction: Manually fixed party name typos (Demorcatic -> Democratic).
Column Removal: Decided to remove the overly complex and messy prior column to simplify the dataset for its intended use.
Validation: Ensured the S.No. sequence was correct after deduplication.

The Outcome: 
A clean, accurate, and simplified historical reference table.
