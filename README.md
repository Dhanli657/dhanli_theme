# Dhanli Theme

A lightweight brand theme for the Frappe / ERPNext **desk**.
It only injects one CSS file — no doctypes, no server code — so it is
safe, easy to review, and easy to remove.

- Brand (navy): `#0E1C63`
- Accent (royal blue): `#2547E6`

## Install (Frappe Cloud, private bench)
1. Push this app to a GitHub repo.
2. Bench → Apps → Add App → from your GitHub URL.
3. Install on a **test site first**, verify forms/print/reports, then your live site.
4. After install, clear cache (bench build runs automatically on Cloud).

## Refine the colours
Open the desk, inspect an element in the browser (DevTools), confirm the CSS
variable names for your Frappe version, and adjust `public/css/dhanli_theme.css`.
This file ships as a starting point.

## License
MIT
