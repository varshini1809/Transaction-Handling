POST Request

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

PRODUCT DB SQL

<!-- start:code block -->
INSERT INTO Product (name,price,stockQuantity) VALUES
	 ('Laptop',25000.0,10),
	 ('Samrtphone',5000.0,12);
<!-- end:code block -->
