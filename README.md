# Restaurio

A full-featured Restaurant Point of Sale (POS) and management system built with ASP.NET Core MVC. Restaurio handles everything a small-to-medium restaurant needs day-to-day: taking orders at the counter, managing tables, tracking stock and suppliers, and reviewing sales — all through a clean, fast, shadcn-inspired UI with light/dark themes.

🌐 Live Demo: http://restaurio.runasp.net/

## Features

**Point of Sale**
- Category-filtered item grid with live search, built for speed at the counter
- Supports Dine In, Take Away, Home Delivery, and Food Panda orders (with platform order reference tracking)
- Live cart with quantity steppers, discount %, tax %, delivery and service charges
- Automatic cash-tendered / change calculation
- One-click Kitchen Slip and Customer Bill printing
- Hold orders on a table and resume them later

**Management**
- Menu items and categories, with drag-and-drop image uploads and live previews
- Table management with real-time occupancy status
- Stock inventory tracking linked to suppliers
- Supplier and user (staff) management
- Role-based access control — Admin and Cashier roles

**Orders & Reporting**
- Full order history with status (Completed / Running / Cancelled)
- Excel-style multi-select column filtering and CSV export on every data table
- Analytical dashboard — revenue, order counts, due amounts — with a sales trend chart (Today / Last 7 Days / This Month / This Year)

**UI/UX**
- Tailwind CSS, shadcn-style components (dialogs, dropdowns, custom selects and date pickers)
- Light and dark mode, plus selectable accent colors
- Responsive layout with a collapsible sidebar

## Screenshots

### Login
<img width="1440" height="900" alt="login" src="https://github.com/user-attachments/assets/d07ffa7d-3873-413a-9035-24431028d4db" />

### Analytical Dashboard
<img width="1440" height="900" alt="dashboard" src="https://github.com/user-attachments/assets/b1cade78-346a-4d5d-affb-c4aa7e16d9f9" />

### Point of Sale
<img width="1440" height="900" alt="pos" src="https://github.com/user-attachments/assets/c371c58c-7fe6-4bdd-b872-20622657580a" />

### Point of Sale — Dark Mode
<img width="1440" height="900" alt="pos-dark" src="https://github.com/user-attachments/assets/218f7168-c4d6-4a4d-af1d-29595469ea93" />

### Slips & Invoices
<img width="1400" height="1000" alt="slips-and-invoice" src="https://github.com/user-attachments/assets/eb1b4f58-e934-48cb-a41c-f0ae5eeef088" />

### Order History
<img width="1440" height="900" alt="orders" src="https://github.com/user-attachments/assets/bbb2eacc-7a9a-4c77-bf35-26cb869e6d51" />

### Menu Items
<img width="1440" height="900" alt="menu-items" src="https://github.com/user-attachments/assets/3b2be1da-26d5-4f23-ade0-5bdf8eb690da" />

### Categories
<img width="1440" height="900" alt="categories" src="https://github.com/user-attachments/assets/5d66b349-3f23-465c-a806-22656328afa3" />

### Table Management
<img width="1440" height="900" alt="tables" src="https://github.com/user-attachments/assets/74e3791f-8abf-491e-8e20-2c91fe90c890" />

### Settings — Accent Themes
<img width="1440" height="900" alt="settings" src="https://github.com/user-attachments/assets/d57f2ce7-b978-4633-8cf6-192fe2e10e6b" />


## Tech Stack

| Layer | Technology |
|---|---|
| Backend | ASP.NET Core MVC (.NET 10) |
| Data access | Entity Framework Core (Database First) |
| Database | Microsoft SQL Server |
| Auth | Cookie-based authentication, role-based authorization |
| Frontend | Tailwind CSS, vanilla JS + jQuery, SweetAlert2 |

## Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/download)
- SQL Server (LocalDB, Express, or full) with the `RestaurantPOS` database restored/created
- Node.js + npm (optional — only needed if you plan to modify and rebuild the Tailwind CSS)

## Roles

| Role | Access |
|---|---|
| Admin | Full access — manage users, suppliers, stock, categories, items, tables |
| Cashier | POS and order operations |

## License

This project does not currently specify a license.

## Contact

This repository shows the project's structure and feature set. For the full source code, licensing, or custom deployment inquiries, get in touch:

- **Email:** [musaimran932@gmail.com](mailto:musaimran932@gmail.com)
- **WhatsApp:** [+92 306 3239877](https://wa.me/923063239877)
