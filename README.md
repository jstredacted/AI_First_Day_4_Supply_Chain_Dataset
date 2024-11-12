README: Synthetic Orders Dataset for Logistics Group Delivery
Overview
This dataset represents orders for a logistics system designed to optimize batch deliveries using a group order model. The dataset includes orders from three areas in Metro Manila: Makati, Quezon City, and Taguig, each divided into three sub-groups (A, B, and C). The goal is to simulate how products are grouped to fill up cargo space efficiently and enable users to progress through discount levels based on the quantity and dimensions of the products.

Key Features:
Area & Sub-group: The location of the delivery, with each area (Makati, Quezon City, Taguig) divided into three sub-groups (e.g., Makati A, Makati B, Makati C).
Product: A unique identifier for the product (e.g., Product-1, Product-2, etc.).
Product Price: The price of the product in PHP.
Order Time: The timestamp when the order was placed.
Dimensions: The physical attributes of the product (length, width, height in centimeters, and weight in kilograms).
Dataset Columns:
Area & Sub-group: The area and corresponding sub-group for each order. This field is a combination of the area (Makati, Quezon City, Taguig) and one of its sub-groups (A, B, or C).

Example: "Makati A", "Taguig B", "Quezon City C".

Product: A unique product identifier, such as "Product-1", "Product-2", etc.

Product Price: The price of the product in Philippine Peso (PHP), randomly generated within a range of 100 to 500 PHP.

Order Time: The timestamp when the order was placed, randomly assigned to a date within the past 30 days.

Length (cm): The length of the product in centimeters, randomly generated within the range of 5 to 50 cm.

Width (cm): The width of the product in centimeters, randomly generated within the range of 5 to 50 cm.

Height (cm): The height of the product in centimeters, randomly generated within the range of 5 to 50 cm.

Weight (kg): The weight of the product in kilograms, randomly generated between 0.5 kg and 10 kg.

Usage
This dataset is ideal for testing logistics systems that need to optimize group deliveries by tracking product dimensions and allowing users to jump between sub-groups within areas to speed up the discount process.

Example Use Cases:
Testing group order logistics: Simulate how products are grouped based on area and dimensions to maximize truck space.
Discount system validation: Use the product dimensions and area/sub-group assignments to calculate how discount levels progress based on the size and number of products added.
Data Format
The dataset is provided in CSV format and contains the following columns:

Area & Sub-group	Product	Product Price	Order Time	Length (cm)	Width (cm)	Height (cm)	Weight (kg)
Makati A	Product-1	200.50	2024-11-01	20.3	10.5	5.7	2.3
Taguig B	Product-2	150.75	2024-10-25	30.4	12.1	9.2	3.5
Quezon City C	Product-3	300.00	2024-10-18	15.7	14.8	10.0	4.2
...	...	...	...	...	...	...	...
How to Use
Data Analysis: Load the dataset into a data analysis tool (e.g., Pandas in Python) to analyze the distribution of orders across areas, sub-groups, and product dimensions.
Logistics Optimization: Use the product dimensions and area/sub-group data to model logistics optimization problems, such as grouping products to maximize cargo space and track discount progress.
License
This dataset is synthetic and intended for testing and simulation purposes. There are no usage restrictions, but it should not be used for commercial purposes without further modification.
