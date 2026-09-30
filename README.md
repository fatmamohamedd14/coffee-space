# ☕ Coffee Space

**Café Operations Platform — Business Analysis Case Study & Working Prototype**

Coffee Space is a working prototype designed to connect the main daily operations of a café in one workflow.

Instead of managing sales, inventory, purchases, costs, and reports separately, Coffee Space brings them together so every confirmed sale can immediately affect stock, cost, and same-day performance.

---

## 🎯 The Business Problem

Many cafés manage:

- Sales through a POS
- Inventory separately
- Purchases in spreadsheets
- Expenses manually
- Profitability only at the end of the month

This creates limited visibility into the actual daily performance of the business.

Coffee Space was designed to connect these operations in one system.

---

## ✨ Key Features

### Point of Sale
- Takeaway and dine-in orders
- Table selection for dine-in
- Product search
- Quantity controls
- Cash, card, and wallet payments
- Digital receipt

### Inventory
- Raw materials
- Packaged products
- Low-stock alerts
- Waste tracking
- Inventory value

### Purchasing
- Supplier management
- Purchase records
- Automatic stock updates
- Weighted-average cost calculation

### Financial Operations
- Operating expenses
- Cash movements
- COGS
- Gross profit
- Net profit
- Profit margin
- Average Order Value

### Access Control

**Manager**
- Full dashboard
- Inventory
- Purchases
- Costs and margins
- Reports
- Product management
- Users and operational controls

**Cashier**
- Simplified dashboard
- POS access
- No visibility into cost or margin data
- No access to management modules

### Operations
- Multi-branch context
- Table management
- Shifts
- Audit trail
- Stock movements
- CSV report export

---

## 🔄 Core Business Logic

**Every confirmed sale should update stock, cost, and same-day business performance.**

For prepared products, ingredients are deducted according to the product recipe.

For packaged products, stock quantity is deducted directly.

The system also separates operational access between managers and cashiers.

---

## 📊 Business Analysis Documentation

The project includes a complete **Business Requirements Document (BRD)** covering:

- Business Problem
- Business Goals
- Stakeholders
- Functional Requirements
- Business Rules
- Non-Functional Requirements
- Acceptance Criteria
- Scope
- Future Phases

**BRD:**  
[View Business Requirements Document](https://github.com/fatmamohamedd14/coffee-space/blob/main/Coffee_Space_BRD.pdf)

**Presentation:**  
[View Case Study Presentation](.Coffee_Space_Presentation.pdf)

---

## 👤 Demo Accounts

### Manager

Username: `manager`  
Password: `Manager@2026`

### Cashier

Username: `cashier`  
Password: `Cashier@2026`

---

## 🛠 Tech

- HTML
- CSS
- JavaScript
- Browser LocalStorage
- Arabic / English interface
- RTL / LTR support
- Light / Dark themes

The current version is designed for **portfolio demonstration and single-device pilot use**.

---

## ⚠️ Current Prototype Scope

Coffee Space is currently a working prototype, not a production ERP.

A production version would require:

- Server-side database
- Secure authentication
- Password hashing
- Multi-device synchronization
- Backend API
- Hardware integrations
- Cloud deployment

---

## 💡 Project Focus

Coffee Space was built as a practical exercise in:

**Business Analysis · Product Thinking · Operations · POS / ERP**

The goal was not only to design screens, but to translate a real operational problem into:

**Business Problem → Requirements → Business Rules → Product Scope → Working Prototype**

---

## 🤝 Feedback

I'm open to feedback from people working in:

- Business Analysis
- Product Management
- POS / ERP Products
- Hospitality Operations
- Business Development
