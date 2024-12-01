Retrieve customerName, email, and PhoneNumber from the customer table:

SELECT customerName, email, PhoneNumber
FROM customer;
Retrieve customerName, email, and PhoneNumber from the customer table where customerAddress is equal to "Kisii":


SELECT customerName, email, PhoneNumber
FROM customer
WHERE customerAddress = 'Kisii';
Retrieve customerID and TotalAmount from the bills table where status is equal to "unpaid":


SELECT customerID, TotalAmount
FROM bills
WHERE status = 'unpaid';

Retrieve customerID, TotalAmount, and CategoryID from the bills table where status is equal to "paid":

SELECT customerID, TotalAmount, CategoryID
FROM bills
WHERE status = 'paid'


Retrieve customerID and Status from the bills table where BillDate is between "2024-11-01" and "2024-11-30":

SELECT customerID, Status
FROM bills
WHERE BillDate BETWEEN '2024-11-01' AND '2024-11-30';


Retrieve billID, itemDescription, and LineTotal from the bill_items table ordered by LineTotal in descending order:
SELECT billID, itemDescription, LineTotal
FROM bill_items
ORDER BY LineTotal DESC;


Retrieve billID, itemDescription, and LineTotal from the bill_items table ordered by LineTotal in ascending order:
SELECT billID, itemDescription, LineTotal
FROM bill_items
ORDER BY LineTotal ASC;


Retrieve billID, itemDescription, and LineTotal from the bill_items table where LineTotal is greater than 100 and results are in descending order using billID:
SELECT billID, itemDescription, LineTotal
FROM bill_items
WHERE LineTotal > 100
ORDER BY billID DESC



Retrieve PaymentAmount and PaymentMethod from the payments table where PaymentMethod contains "esa":
SELECT PaymentAmount, PaymentMethod
FROM payments
WHERE PaymentMethod LIKE '%esa';



Retrieve CustomerName and CustomerAddress from the customer table where CustomerAddress starts with "Ki":
SELECT CustomerName, CustomerAddress
FROM customer
WHERE CustomerAddress LIKE 'Ki%';





