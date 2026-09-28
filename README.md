# HMH Finance System

A static, responsive finance command center for HMH Group built with vanilla HTML, CSS, and JavaScript.

## Files
- `index.html` — application UI + client-side data logic
- `style.css` — HMH navy/yellow theme, responsive layout, components

## Hosting
Upload both files to the same folder on GitHub Pages, Netlify, Vercel static hosting, or any static web host. Open `index.html` through your host.

## Data storage
This version stores its data in the browser with `localStorage`. That means:
- data persists after refresh on the same browser/device;
- different devices/browsers do not share the same data;
- this is not a secure multi-user accounting backend.

For production/shared finance data, connect the same front-end to Firebase, Supabase, or another backend with authentication and database rules.

## Included modules
Dashboard, Transactions, Revenue, Expenses, Invoices & AR, Cash Flow, Reports, Projects, Payroll, Assets, Settings, JSON backup/restore, CSV export, light/dark theme.
