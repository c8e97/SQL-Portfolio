SELECT item_name, price FROM superstore ORDER BY price;

--STRUCTURE NOTES--
--SELECT ______
--FROM superstore
--WHERE ______
--ORDER BY _______;

SELECT * FROM superstore ORDER BY price DESC;

SELECT SUM(stock_quantity) FROM superstore;

SELECT AVG(price) FROM superstore 'Electronics';

--What is the store's average rating--

SELECT AVG(average_rating) FROM superstore;
