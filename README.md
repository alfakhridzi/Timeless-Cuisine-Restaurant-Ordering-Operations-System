# Timeless-Cuisine-Restaurant-Ordering-Operations-System
Timeless Cuisine is an information system and app mockup for a restaurant where customers order from a tablet at their table, and the staff behind the scenes (cashier, warehouse, purchasing, and admin) are connected through one system covering payment, ingredient stock, purchasing, menu management, and financial reports.

Overview
A restaurant has two connected sides: the **dining room**, where customers order and pay, and the **back office**, where ingredients are tracked, bought, and turned into menu items and reports. Timeless Cuisine models both sides in one system.

Customer experience
- A waiter guides the customer to a table that has an ordering tablet.
- The customer browses the menu, orders food and drinks, and can add preferences such as *not spicy* or *no shrimp*.
- If a requested preference is unavailable, the system shows a "choice not available right now" notification.
- After the meal, the customer pays at the cashier by giving the order code. The system shows the order details and total, and accepts cash, debit card, credit card, or QRIS. After payment the order is marked as paid and a receipt is printed.

Back-office experience
- Warehouse staff monitor ingredient stock, request new ingredients when stock is low, record ingredients received from suppliers, and record ingredient usage.
- The purchasing team receives the requests and confirms purchases.
- The admin manages the menu (based on the available ingredients) and generates sales and profit and loss reports.

Actors
- Customer (Pelanggan) | Orders from the table tablet and pays
- Cashier (Kasir) | Confirms the order and processes the payment
- Warehouse (Gudang) | Manages ingredient requests, usage, and receipts
- Purchasing (Pembelian) | Buys ingredients based on warehouse requests
- Admin | Manages the menu and creates reports

Use Cases

Each use case is documented with a scenario, triggering event, preconditions, postconditions, flow of activities, and exception conditions.
- Place an order | Customer
- Make a payment | Customer
- Process the payment | Cashier
- Request raw ingredients | Warehouse
- Record raw ingredient usage | Warehouse
- Record raw ingredient receipt | Warehouse
- Purchase raw ingredients | Purchasing
- Manage the menu | Admin
- Create a profit and loss report | Admin
- Create a sales report | Admin
  
Examples of exception handling designed into the system
- Menu entries must be based on available ingredients, otherwise the system shows an error.
- If revenue data can't be retrieved for a period, the P&L report shows total revenue as Rp 0.
- If no sales exist for the chosen period, the sales report asks the user to change the date range.
- If sales data isn't fully synchronized, the report is shown with a disclaimer that it may not be real-time or final.

System Analysis & Design
- Fishbone Diagram | Root causes of the problems the system addresses
- Context Diagram | The system and its data exchange with each actor
- DFD Level 0 | The main processes and data stores
- Use Case Diagram and Descriptions | The 10 use cases above in full detail
- Class Diagram | The data entities, their attributes, and relationships
- Sequence Diagrams| Ordering, payment, ingredient usage, sales report, and P&L report
- State Transition Diagrams | The lifecycle of the main objects
- Activity Diagrams | Step-by-step flows for the main processes
- System Input and Output | Screen designs for inputs and report outputs


My Contribution

- Created the Use Case Diagram, Class Diagram, and Activity Diagrams
- Designed the app screens in Figma
