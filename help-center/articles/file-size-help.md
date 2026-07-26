# My file is too large — what now?

A few practical ways to get under the limit:

1. **Split by time**: export one month or quarter at a time.
2. **Drop unused columns**: narrower files are dramatically smaller.
3. **Trim precision**: long decimal tails inflate file size without helping analysis.

Relay checks the size before reading the data, so an oversized upload fails
fast rather than hanging.
