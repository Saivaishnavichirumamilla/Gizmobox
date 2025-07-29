# Gizmobox
### Set-up project environment - Gizmobox
- Created external location for gizmobox container
- Created gizombox catalog
- Created schemas bronze, silver and gold 
- Created volume
### Extract Customers data which is a JSON file
- Extract data
- Create view i.e.v_customers 
### Extract Orders data which is a complex JSON file that means it has some missing or null vales
- Extract data as text to keep the data raw at bronze layer
- Create view i.e. v_orders
### Extract Memberships data which is in binary format
- Extract using pyspark and create view for it