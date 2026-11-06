# Worksheet data

[worksheets.json](worksheets.json) contains the saved cell values from the combined [Minitab project](../minitab/complete-analysis.mpx). The export retains worksheet names, column names, numeric/text types and row order. It includes both input columns and derived columns saved in that project.

Each worksheet contains its own column arrays. Columns can have different lengths: a saved scalar, for example, can contain one value alongside a 24-row measurement column. Read the arrays as separate worksheet columns rather than assuming every column has the same number of rows.

The JSON export copies stored values. It does not execute Minitab commands, recalculate analyses or replace the saved project outputs. Native project files retain the associated analysis commands and charts.

For the worksheet inventory and case-specific files, see the [file guide](../docs/FILES.md).
