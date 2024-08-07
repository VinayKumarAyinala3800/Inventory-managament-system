**Inventory Management System README**
**Overview**
This Inventory Management System (IMS) offers two approaches for managing inventory data: one using JSON and the other without JSON. The system helps in tracking stock levels, orders, and product details efficiently.

**Features**
Product catalog management
Real-time inventory updates
Order processing and tracking
Reporting and analytics

**System Requirements**
Python 3.x
Required libraries: json, csv (if using CSV files)

**Setup
With JSON
Install dependencies:**
pip install -r requirements.txt
**Configuration:**
Ensure you have a JSON file (inventory.json) for storing inventory data.
**Run the application:**
python inventory_json.py


**Without JSON (Using CSV)
Install dependencies:**

pip install -r requirements.txt

**Configuration:**

Ensure you have a CSV file (inventory.csv) for storing inventory data.
**Run the application:**
python inventory_csv.py

**Usage
With JSON**
Add a product:
add_product(name, quantity, price)
Update inventory:
update_inventory(product_id, quantity)
View inventory:
view_inventory()

**Without JSON (Using CSV)**
Add a product:
add_product_csv(name, quantity, price)
Update inventory:
update_inventory_csv(product_id, quantity)
View inventory:
view_inventory_csv()

**File Structure**

├── inventory_json.py         # JSON-based inventory management
├── inventory_csv.py          # CSV-based inventory management
├── inventory.json            # JSON data file (example)
├── inventory.csv             # CSV data file (example)
├── requirements.txt          # Dependencies
├── README.md                 # This file


**Contributing**
Fork the repository.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a Pull Request.

**License**
This project is licensed under the MIT License. See the LICENSE file for details.

**Contact**
For any questions or feedback, please contact **A Vinay Kumar** at **vjssl3800@gmail.com**.

