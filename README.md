# SQLFinancialReport
Example of written SQL Financial Report

## Code Explanation
This report is a SQL income expense year-to-date report written for a previous client. All identifying information and database specific information has been removed or renamed. This report is written in a way to meet dynamic needs based on having multiple departmental reports without fully rewriting the SQL code. The starting script can pass specific account codes or look for account titles to pass to the report table generator (Income Expense YTD). From there, the table will either insert the selected data per line as data from a year ago or a rolling total total from the previous 12 months based on need. The table can then be passed to a preferred report generation service as needed. Multiple starting scripts with different account codes or account titles can be used without the need to modify the main report writer.
