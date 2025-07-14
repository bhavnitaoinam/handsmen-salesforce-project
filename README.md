# HandsMen Threads: Elevating the Art of Sophistication in Men's Fashion – Salesforce DX Project

A Salesforce Lightning application designed for **HandsMen Threads**, a premium men's fashion brand. This project streamlines business operations with customized data modeling, Apex automation, and intelligent workflows — enhancing customer experience, order management, and inventory control.

---

## Features Implemented

### Custom Objects
- **HandsMen_Customer__c**: Tracks customer info, loyalty status, and purchase history
- **HandsMen_Product__c**: Manages product catalog, pricing, and stock
- **HandsMen_Order__c**: Stores order data including status and total amount
- **Inventory__c**: Monitors stock levels and warehouse location
- **Marketing_Campaign__c**: Records campaign details with start and end dates

### Automation & Flows
- **Order Confirmation Email Alert**  
  Sends confirmation email to customer upon order approval
- **Low Stock Alert Flow**  
  Triggers an alert email to the inventory manager when stock < 5
- **Loyalty Status Scheduler**  
  A scheduled flow updates customer loyalty tier (Gold/Silver/Bronze) based on total purchases

### Apex Logic
- `InventoryBatchJob` — for scheduled inventory syncing (example async job)
- Validation Rules, Record-Triggered Flows, and Apex Triggers for data integrity

### Email Templates
- **Order Confirmation Email**
- **Low Stock Alert**
- **Loyalty Program Status Update**

---

## Tech Stack

| Tool            | Purpose                                |
|-----------------|----------------------------------------|
| Salesforce DX   | Project structure and metadata management |
| Apex            | Business logic and triggers            |
| Flows           | Declarative automation                 |
| Email Templates | Custom notifications                   |
| Git & GitHub    | Version control and collaboration      |

---

## Author

Bhavnita Oinam  
[GitHub](https://github.com/bhavnitaoinam)
