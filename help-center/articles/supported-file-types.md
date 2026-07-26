# Which file types can I upload?

Relay works with comma-separated (`.csv`) and tab-separated (`.tsv`) text files.

Excel workbooks (`.xlsx`) aren't supported, and that's a deliberate choice
rather than a gap: workbooks can hide formulas and multiple sheets, which don't
fit Relay's "exactly what you uploaded is exactly what's analyzed" promise.
Export a single sheet to CSV first.
