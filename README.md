
- Implemented transaction management within the Spring framework to handle product purchase workflows.  
- Designed processes to persist orders to the database, update stock levels in the inventory system, and record payment details efficiently.  
- Incorporated failure handling mechanisms with transaction rollback to prevent data inconsistencies and ensure system integrity.  


# POST Request

<!-- start:code block -->
curl -X 'POST' \
  'http://localhost:9191/api/orders' \
  -H 'accept: */*' \
  -H 'Content-Type: application/json' \
  -d '{
  "id": 103,
  "productId": 1,
  "quantity": 5
}'
<!-- end:code block -->

# PRODUCT DB SQL

<!-- start:code block -->
INSERT INTO Product (name,price,stockQuantity) VALUES
	 ('Laptop',25000.0,10),
	 ('Samrtphone',5000.0,12);
<!-- end:code block -->
