# Inventory Management System

A responsive inventory management web application for managing stock, suppliers, purchase orders, stock movements, and inventory analytics from a centralized dashboard.

## Features

* Dashboard with inventory overview and key metrics
* Inventory and stock management
* Supplier management
* Purchase order tracking
* Stock-in and stock-out tracking
* Wastage management
* Inventory analytics and charts
* User management and activity logs
* Notifications and application settings
* Responsive UI with light and dark themes

## Tech Stack

* **React.js**
* **TypeScript**
* **Vite**
* **Tailwind CSS**
* **React Router**
* **React Context API**
* **React Hook Form**
* **Recharts**
* **Radix UI**
* **Lucide React**

## Project Structure

```text
inventory-management-system/
│
├── src/
│   ├── app/
│   │   ├── components/
│   │   │   ├── pages/
│   │   │   ├── ui/
│   │   │   ├── figma/
│   │   │   ├── DashboardLayout.tsx
│   │   │   ├── NotificationCenter.tsx
│   │   │   ├── LoadingScreen.tsx
│   │   │   └── CustomCursor.tsx
│   │   │
│   │   ├── store/
│   │   │   ├── AppStore.tsx
│   │   │   └── ThemeStore.tsx
│   │   │
│   │   ├── App.tsx
│   │   └── Attributions.md
│   │
│   ├── styles/
│   │   ├── globals.css
│   │   ├── index.css
│   │   └── default_theme.css
│   │
│   └── main.tsx
│
├── guidelines/
│   └── Guidelines.md
│
├── index.html
├── package.json
├── postcss.config.mjs
├── vite.config.ts
└── README.md
```

## Getting Started

### Prerequisites

* Node.js 18+
* npm

### Installation

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd YOUR-REPOSITORY
npm install
```

### Run Locally

```bash
npm run dev
```

Open `http://localhost:5173` in your browser.

### Production Build

```bash
npm run build
```

## Future Improvements

* Backend and database integration
* REST API implementation
* JWT authentication and role-based access control
* Real-time inventory updates
* Barcode and QR code support
* Automated low-stock alerts
* Reporting and data export

## Author

**Aditya A**
Computer Science Engineering Student

---

If you find this project useful, consider giving it a star.
