ClipTable allows for quick conversion of tables copied from Numbers (or Wiki) inside clipboard to other formats:
- HTML
- Wiki markdown
- Tex/Latex
- SQL INSERT/UPDATE

Just copy table from numbers, select output format and click "Convert>" button, then paste converted output. Program handles most of simple texts formats between HTML and Wiki markdown. Some formatting is retained in tex output.

Some notes for effective usage:
- Program uses html as input from numbers. There is no sensible way to detect headers in numbers clipboard. Cell is considered as header when it has background and is all bold.
- SQL INSERT looks for first row that has all cells as headers. That row will be used as column names (for INSERT ... VALUES ... command).
- SQL UPDATE needs column headers, they will be used as for WHERE conditions, other columns are used in SET clause.

This program is in active development. Planned addition of markdown tables and JSON output.
