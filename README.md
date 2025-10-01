#  Drinking Water Supply O&M Backend

This repository contains the **backend of a handheld/mobile-based Operation & Maintenance (O&M) tool** for managing drinking water supply schemes under the **Jal Jeevan Mission (JJM)**. The backend provides APIs and data management functionalities to support **asset tracking, inventory management, financial operations, and bill/payment processing** for rural water supply systems.

---

##  Project Overview

The tool is designed to assist **Gram Panchayats (GP) and PHED personnel** in managing the operation and maintenance of village-level water supply infrastructure. Key functionalities include:

- **Asset Management:** Record all water supply assets (pumps, pipelines, valves, treatment plants) with GIS location, installation date, and historical information.
- **Consumables & Inventory Management:** Track chemicals, filters, spare parts, and other supplies; forecast demand and plan replenishments.
- **Finance Management:** Record receipts, expenditures, and generate cash books for the GP.
- **Consumer Management & Billing:** Maintain a consumer list, generate bills, and support payment collection.
- **Payment Integration:** Support online payment gateways including **UPI, Net Banking, and Credit Cards**.
- **User-Friendly Interface:** Easy-to-use endpoints for GP-level operations; support for local languages.

---

##  Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT / Role-based access control
- **Geolocation:** GIS-based asset tracking
- **Payment Integration:** APIs for UPI, Net Banking, and Credit Card transactions

---

##  Features

1. **Assets Management**
   - Add, update, and view assets with GIS coordinates
   - Maintain asset history and installation metadata

2. **Inventory & Consumables**
   - Track stock of chemicals, filters, and spare parts
   - Forecast requirements and generate replenishment alerts

3. **Financial Records**
   - Record receipts and expenditures
   - Generate cash books and financial reports

4. **Billing & Payments**
   - Manage consumer lists and generate bills
   - Integrate online payment gateways (UPI, Net Banking, Cards)

5. **User Accessibility**
   - User-friendly APIs for GP operations
   - Optional support for local languages

---

##  Getting Started

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/drinking-water-om-backend.git

# Navigate to backend
cd backend

# Install dependencies
npm install

# Start the server
npm run dev

