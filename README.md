# StockWise — Interactive Product Inventory & Analytics Dashboard

A responsive, front-end capstone project built with HTML, CSS and JavaScript. It demonstrates arrays/objects, functions, conditionals, loops, array methods, DOM manipulation, form validation, localStorage and analytics charts.

## Features
- Dashboard KPIs: product count, inventory value, units in stock and low-stock alerts
- Add, edit and delete products
- Search by product, category or ID
- Filter by category and stock status
- Low-stock / out-of-stock badges and automated insights
- Category inventory value doughnut chart and stock quantity bar chart
- Export inventory to CSV
- Data persistence with browser `localStorage`
- Responsive desktop and mobile layout
- Input validation and duplicate product-name check

## Run in VS Code
1. Extract the ZIP.
2. In VS Code choose **File → Open Folder** and select the `interactive_product_inventory_dashboard` folder (the one containing `index.html`, `styles.css`, and `app.js`).
3. Install the **Live Server** extension if you do not already have it.
4. Right-click `index.html` → **Open with Live Server**.
5. Your browser should open a local address such as `http://127.0.0.1:5500`.

You can also double-click `index.html`, but Live Server is recommended.

## Important
- Chart.js and Google Fonts are loaded from online CDNs, so analytics charts and fonts need an internet connection. Core inventory functions work locally.
- This is a front-end educational demo. Data is stored in the current browser only; it does not have a shared database, user login, or server-side security.
- If you want a reset, click **Reset demo data** at the bottom of the inventory table.
- Exported CSV opens in spreadsheet software such as Excel.

## Suggested demonstration for a teacher
1. Show the KPI cards and explain that they are calculated from product data.
2. Add a product with name `Monitor`, category `Electronics`, price `15000`, quantity `6`, reorder level `5`.
3. Search for `Monitor`, then filter by category and stock status.
4. Edit the quantity to `3` and show how the stock status and low-stock insights update.
5. Delete the test product, then export the inventory as CSV.
6. Explain that `map`/`filter`/`reduce`, objects, functions, conditionals and localStorage power the application.

## Project structure
- `index.html` — layout and forms
- `styles.css` — responsive UI
- `app.js` — inventory logic, persistence and charts
