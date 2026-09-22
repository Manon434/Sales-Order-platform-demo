# Sales-Order-platform-demo
Enterprise Sales Order Management Platform with 3-level approvals, production tracking, and end-to-end order lifecycle management.
# 🏭 Sales Order Management Platform

A web-based **Sales Order Management Platform** designed to manage the complete sales lifecycle from enquiry to delivery, with structured approvals and production tracking.

## 🚀 Features

* 🔐 **Signup & Login** — Only registered users can access the platform
* 👥 **Customer Management** — Manage customers and their sales activity
* 📋 **Enquiries** — Track incoming business enquiries
* 💰 **Quotations** — Create and manage customer quotations
* 🧾 **Sales Orders** — Manage orders through their complete lifecycle
* ✅ **3-Level Approval** — Sales Manager → Production → Management
* 🏭 **Production Tracking** — Track production stages, progress, quantities, ETA and blockers
* 📦 **Dispatch & Delivery** — Monitor order fulfillment
* 🧾 **Invoicing** — Track invoices and payment status
* 🔄 **SAP Mock Integration** — Simulates SAP sales order creation after approval
* 💾 **Persistent Data** — Uses browser localStorage for the demo

## 🔄 Workflow

```text
Enquiry
   ↓
Quotation
   ↓
Sales Order
   ↓
Sales Manager Approval
   ↓
Production Approval
   ↓
Management Approval
   ↓
Production
   ↓
Quality Check
   ↓
Dispatch
   ↓
Delivery
   ↓
Invoice
```

## 📊 Demo Data

| Module       | Records |
| ------------ | ------: |
| Customers    |      30 |
| Enquiries    |      40 |
| Quotations   |      35 |
| Sales Orders |      30 |

## 🛠️ Tech Stack

*HTML5 · CSS3 · JavaScript · LocalStorage**

## 🌐 Live Demo

****

## 📌 Project Status

**Front-end demonstration / prototype**

The application demonstrates the complete business workflow. Backend APIs, database integration, authentication security and real SAP integration can be added for production deployment.
