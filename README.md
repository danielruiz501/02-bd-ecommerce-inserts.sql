# Bd ecommerce inserts

USE ecommerce;

INSERT INTO customers (name, email)
VALUES 
('Carlos López','carlos@example.com'),
('Ana Torres','ana@example.com');

INSERT INTO products (name, price, stock)
VALUES
('Laptop', 15000, 10),
('Mouse Gamer', 500, 40);

INSERT INTO orders (customer_id, order_date)
VALUES
(1,'2024-01-01'),
(2,'2024-01-05');
