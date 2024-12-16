# SQL Query Bug: Unexpected Results with '>' Operator

This repository demonstrates a common SQL query error where using the '>' operator can lead to unexpected results.  The query aims to select employees from the 'Sales' department with salaries greater than 100000. However, it incorrectly excludes employees with salaries exactly equal to 100000.

The `bug.sql` file contains the erroneous query, while `bugSolution.sql` shows the corrected version.