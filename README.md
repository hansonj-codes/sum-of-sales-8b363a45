# Sales Summary 374959384

This is a single-page static website that sums the "sales" column from data.csv and displays the total.

Features
- Loads Bootstrap 5 from jsdelivr.
- Reads data.csv from the site root, sums the `sales` column, and displays the total in the element with id `total-sales`.
- Sets the page title to "Sales Summary 374959384".

Deployment
1. Push this repository to GitHub.
2. Enable GitHub Pages for the repository (use the main branch and root folder).
3. Ensure `data.csv` is present at the repository root (it is provided in the attachments).

Usage
- Open the published GitHub Pages URL.
- The page will fetch `data.csv`, compute the sum of the `sales` column, and display it.

Notes
- The script expects a CSV with a header row containing a `sales` column.
- Non-numeric or empty sales entries are ignored.

Commit message included in repository as `commit_message`.