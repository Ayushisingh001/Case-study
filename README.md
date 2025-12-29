# inventory-management-case-study

Case Study Solutions

---

## Part 1: Code Review & Debugging
**File:** 
- Product creation API (intern-style Python).  
- Handles validation, SKU uniqueness, optional warehouse assignment, and inventory creation.  
- Uses `try-except` for error handling.  

---

## Part 2: Database Design
**Files:** 
- SQL schema for companies, warehouses, products, inventory, suppliers, and bundles.  
- Includes `InventoryHistory` and many-to-many relationships.  
- Constraints: primary keys, foreign keys, unique SKUs.  
- Notes gaps/questions: bundle pricing, stock units, inventory history tracking, warehouse location details.  

---

## Part 3: Low Stock Alerts API
**File:** 
- Generates low-stock alerts per company.  
- Handles multiple warehouses, recent sales, supplier info, and calculates days until stockout.  
- Written in plain Python focusing on logic; database queries are represented as functions. 
