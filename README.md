# SAP Fiori: Order-to-Cash (O2C) Management Dashboard

## 🎓 Project Overview
This repository contains my final Capstone Project for the SAP Fiori Frontend Development program at KIIT. 

The application is a **Sales Order Management Dashboard** that demonstrates the frontend visualization of the Order-to-Cash (O2C) business process. It was developed using **SAP Fiori Elements** and follows a strictly metadata-driven architecture. To allow for offline development and decoupled testing, the application utilizes a local JSON-based mock server to simulate an OData V2 backend service.

## ✨ Key Features
* **List Report Page:** Displays all incoming sales orders with a responsive data table.
* **Smart Filter Bar:** Allows users to dynamically filter orders by `OrderID`, `CustomerName`, and `Status`.
* **Object Page Navigation:** Users can drill down into specific sales orders to view detailed, entity-level order information via UI Facets.
* **Metadata-Driven UI:** The user interface is generated entirely through OData XML Annotations (`UI.LineItem`, `UI.SelectionFields`, `UI.Facets`), ensuring strict adherence to SAP Fiori Design Guidelines.

## 🛠️ Tech Stack
* **Frontend Framework:** SAPUI5 (Fiori Elements)
* **Design Pattern:** List Report & Object Page Floorplan
* **Data Protocol:** OData V2
* **Backend Simulation:** Local UI5 Mock Server (`SalesOrderSet.json`)
* **Environment:** Visual Studio Code with SAP Fiori Tools
* **Runtime:** Node.js (v24.15.0+)

## 🚀 How to Run the Project Locally
Because the `node_modules` folder is excluded to save space, please follow these steps to run the application on your local machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ashmit-sinha-30/Capstone_O2C_Dashboard.git
