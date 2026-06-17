# select-in-e-or
HT-SIS-01-M-26-10495

-- 1
SELECT * FROM OrderDetails
WHERE Quantity < 10 OR ProductID > 20
ORDER BY OrderDetailID;

-- 2
SELECT * FROM OrderDetails
WHERE OrderID = 100 OR MOD(ProductID,5) = 0
ORDER BY Quantity;

-- 3
SELECT * FROM OrderDetails
WHERE OrderDetailID > 50 OR Quantity < 20
ORDER BY OrderID;

-- 4
SELECT * FROM OrderDetails
WHERE ProductID < 15 OR OrderID LIKE '%0'
ORDER BY Quantity;

-- 5
SELECT * FROM OrderDetails
WHERE Quantity BETWEEN 20 AND 50 OR MOD(OrderDetailID,3) = 0
ORDER BY OrderID;

-- 6
SELECT * FROM OrderDetails
WHERE OrderID > 200 OR ProductID LIKE '%7'
ORDER BY Quantity;

-- 7
SELECT * FROM OrderDetails
WHERE MOD(Quantity,4) = 0 OR OrderID < 50
ORDER BY OrderDetailID;

-- 8
SELECT * FROM OrderDetails
WHERE ProductID = 8 OR Quantity BETWEEN 10 AND 30
ORDER BY OrderID;

-- 9
SELECT * FROM OrderDetails
WHERE OrderDetailID LIKE '%5' OR ProductID > 25
ORDER BY Quantity;

-- 10
SELECT * FROM OrderDetails
WHERE OrderID = 150 OR Quantity < 15
ORDER BY OrderDetailID;

-- 11
SELECT * FROM OrderDetails
WHERE Quantity < 50 OR OrderID = 250
ORDER BY OrderDetailID;

-- 12
SELECT * FROM OrderDetails
WHERE ProductID > 30 OR OrderID BETWEEN 100 AND 300
ORDER BY Quantity;

-- 13
SELECT * FROM OrderDetails
WHERE OrderDetailID < 15 OR MOD(Quantity,5) = 0
ORDER BY ProductID;

-- 14
SELECT * FROM OrderDetails
WHERE ProductID < 12 OR OrderID LIKE '%9'
ORDER BY Quantity;

-- 15
SELECT * FROM OrderDetails
WHERE Quantity > 25 OR MOD(OrderID,4) = 0
ORDER BY OrderDetailID;

-- 16
SELECT * FROM OrderDetails
WHERE ProductID = 45 OR OrderID < 200
ORDER BY Quantity;

-- 17
SELECT * FROM OrderDetails
WHERE OrderDetailID = 50 OR Quantity > 30
ORDER BY OrderID;

-- 18
SELECT * FROM OrderDetails
WHERE Quantity < 5 OR MOD(OrderDetailID,6) = 0
ORDER BY ProductID;

-- 19
SELECT * FROM OrderDetails
WHERE OrderID > 10 OR Quantity BETWEEN 10 AND 20
ORDER BY Quantity;

-- 20
SELECT * FROM OrderDetails
WHERE ProductID > 15 OR OrderDetailID LIKE '%2'
ORDER BY OrderID;

-- 21
SELECT * FROM OrderDetails
WHERE ProductID > 50 OR Quantity < 5
ORDER BY OrderID;

-- 22
SELECT * FROM OrderDetails
WHERE OrderDetailID LIKE '%3' OR Quantity BETWEEN 10 AND 15
ORDER BY ProductID;

-- 23
SELECT * FROM OrderDetails
WHERE MOD(OrderID,7) = 0 OR Quantity = 25
ORDER BY Quantity;

-- 24
SELECT * FROM OrderDetails
WHERE OrderDetailID < 10 OR ProductID BETWEEN 15 AND 20
ORDER BY OrderID;

-- 25
SELECT * FROM OrderDetails
WHERE OrderID > 300 OR MOD(Quantity,2) = 0
ORDER BY OrderDetailID;

-- 26
SELECT * FROM OrderDetails
WHERE MOD(ProductID,9) = 0 OR Quantity BETWEEN 1 AND 10
ORDER BY OrderID;

-- 27
SELECT * FROM OrderDetails
WHERE OrderDetailID = 100 OR ProductID > 25
ORDER BY Quantity;

-- 28
SELECT * FROM OrderDetails
WHERE Quantity = 50 OR OrderID LIKE '%8'
ORDER BY ProductID;

-- 29
SELECT * FROM OrderDetails
WHERE ProductID < 20 OR Quantity > 40
ORDER BY OrderDetailID;

-- 30
SELECT * FROM OrderDetails
WHERE MOD(OrderDetailID,5) = 0 OR MOD(Quantity,2) = 1
ORDER BY OrderID;

-- 31
SELECT * FROM OrderDetails
WHERE Quantity > 10 OR OrderDetailID < 5
ORDER BY ProductID;

-- 32
SELECT * FROM OrderDetails
WHERE MOD(ProductID,2) = 0 OR OrderID > 500
ORDER BY Quantity;

-- 33
SELECT * FROM OrderDetails
WHERE OrderDetailID = 15 OR Quantity < 20
ORDER BY OrderID;

-- 34
SELECT * FROM OrderDetails
WHERE MOD(Quantity,2) = 1 OR ProductID > 50
ORDER BY OrderDetailID;

-- 35
SELECT * FROM OrderDetails
WHERE OrderID LIKE '%0' OR ProductID BETWEEN 30 AND 40
ORDER BY Quantity;

-- 36
SELECT * FROM OrderDetails
WHERE Quantity > 50 OR OrderID < 100
ORDER BY ProductID;

-- 37
SELECT * FROM OrderDetails
WHERE MOD(OrderDetailID,10) = 0 OR Quantity BETWEEN 5 AND 15
ORDER BY OrderID;

-- 38
SELECT * FROM OrderDetails
WHERE Quantity = 100 OR ProductID < 5
ORDER BY OrderDetailID;

-- 39
SELECT * FROM OrderDetails
WHERE ProductID > 40 OR MOD(OrderID,6) = 0
ORDER BY Quantity;

-- 40
SELECT * FROM OrderDetails
WHERE OrderDetailID < 20 OR Quantity > 30
ORDER BY OrderID;

-- 41
SELECT * FROM OrderDetails
WHERE OrderID IN (50,100,150)
ORDER BY Quantity;

-- 42
SELECT * FROM OrderDetails
WHERE ProductID IN (2,4,6,8)
ORDER BY OrderDetailID;

-- 43
SELECT * FROM OrderDetails
WHERE Quantity IN (10,20,30)
ORDER BY OrderID;

-- 44
SELECT * FROM OrderDetails
WHERE OrderDetailID IN (5,10,15,20)
ORDER BY Quantity;

-- 45
SELECT * FROM OrderDetails
WHERE OrderID IN (200,300,400)
ORDER BY ProductID;

-- 46
SELECT * FROM OrderDetails
WHERE ProductID IN (12,14,16)
ORDER BY Quantity;

-- 47
SELECT * FROM OrderDetails
WHERE Quantity IN (25,50,75,100)
ORDER BY OrderID;

-- 48
SELECT * FROM OrderDetails
WHERE OrderDetailID IN (100,200,300)
ORDER BY ProductID;

-- 49
SELECT * FROM OrderDetails
WHERE ProductID IN (5,10,15,20)
ORDER BY Quantity;

-- 50
SELECT * FROM OrderDetails
WHERE Quantity IN (1,2,3,4,5)
ORDER BY OrderID;

-- 51
SELECT * FROM OrderDetails
WHERE OrderID IN (250,350,450)
ORDER BY Quantity;

-- 52
SELECT * FROM OrderDetails
WHERE ProductID IN (11,21,31)
ORDER BY OrderDetailID;

-- 53
SELECT * FROM OrderDetails
WHERE Quantity IN (40,50,60)
ORDER BY OrderID;

-- 54
SELECT * FROM OrderDetails
WHERE OrderDetailID IN (150,250,350)
ORDER BY ProductID;

-- 55
SELECT * FROM OrderDetails
WHERE ProductID IN (7,14,21)
ORDER BY Quantity;

-- 56
SELECT * FROM OrderDetails
WHERE OrderID IN (50,100,200)
ORDER BY OrderDetailID;

-- 57
SELECT * FROM OrderDetails
WHERE Quantity IN (20,25,30)
ORDER BY ProductID;

-- 58
SELECT * FROM OrderDetails
WHERE OrderDetailID IN (10,20,30)
ORDER BY Quantity;

-- 59
SELECT * FROM OrderDetails
WHERE OrderID IN (100,200,300)
ORDER BY Quantity;

-- 60
SELECT * FROM OrderDetails
WHERE Quantity IN (5,10,15)
ORDER BY OrderID;

-- 61
SELECT * FROM OrderDetails
WHERE OrderDetailID IN (25,50,75,100)
ORDER BY Quantity;

-- 62
SELECT * FROM OrderDetails
WHERE ProductID IN (9,18,27)
ORDER BY OrderID;

-- 63
SELECT * FROM OrderDetails
WHERE Quantity IN (12,14,16)
ORDER BY ProductID;

-- 64
SELECT * FROM OrderDetails
WHERE OrderID IN (400,500,600)
ORDER BY Quantity;

-- 65
SELECT * FROM OrderDetails
WHERE OrderDetailID IN (20,40,60,80)
ORDER BY OrderID;

-- 66
SELECT * FROM OrderDetails
WHERE ProductID IN (5,10,20)
ORDER BY Quantity;

-- 67
SELECT * FROM OrderDetails
WHERE Quantity IN (8,16,24,32)
ORDER BY OrderDetailID;

-- 68
SELECT * FROM OrderDetails
WHERE OrderID IN (300,400,500)
ORDER BY ProductID;

-- 69
SELECT * FROM OrderDetails
WHERE Quantity IN (15,30,45)
ORDER BY OrderID;

-- 70
SELECT * FROM OrderDetails
WHERE OrderDetailID IN (50,150,250)
ORDER BY Quantity;

-- 71
SELECT * FROM OrderDetails
WHERE OrderDetailID IN (100,200,300,400)
ORDER BY Quantity;

-- 72
SELECT * FROM OrderDetails
WHERE ProductID IN (10,20,30,40)
ORDER BY OrderID;

-- 73
SELECT * FROM OrderDetails
WHERE Quantity IN (5,10,15,20)
ORDER BY ProductID;

-- 74
SELECT * FROM OrderDetails
WHERE OrderID IN (50,150,250,350)
ORDER BY Quantity;

-- 75
SELECT * FROM OrderDetails
WHERE OrderDetailID IN (1,3,5,7)
ORDER BY OrderID;

-- 76
SELECT * FROM OrderDetails
WHERE ProductID IN (13,26,39)
ORDER BY Quantity;

-- 77
SELECT * FROM OrderDetails
WHERE Quantity IN (22,44,66,88)
ORDER BY OrderDetailID;

-- 78
SELECT * FROM OrderDetails
WHERE OrderID IN (90,180,270)
ORDER BY ProductID;

-- 79
SELECT * FROM OrderDetails
WHERE Quantity IN (8,16,24,32)
ORDER BY OrderID;

-- 80
SELECT * FROM OrderDetails
WHERE OrderDetailID IN (101,201,301,401)
ORDER BY Quantity;
