# OPTIMIZATION-MODEL

"COMPANY": CODETECH IT SOLUTIONS

"NAME": B SIDDU

"INTERN ID": CT04DF448

"DOMAIN": DATA SCIENCE

"DURATION": 4 WEEKS

"MENTOR": NEELA SANTOSH


Delivery Truck Routing Optimization
In today’s fast-paced and highly competitive logistics and supply chain environment, optimizing the delivery process is crucial for reducing operational costs and increasing customer satisfaction. One of the most common problems faced by logistics companies is how to distribute goods from a central warehouse to various destinations in the most cost-efficient manner while fulfilling customer demands accurately and on time.

This project focuses on a classic linear programming (LP) problem: minimizing delivery costs from a warehouse to multiple cities with fixed demand, using Python’s PuLP library. The objective is to develop a mathematical model that helps a logistics company make cost-effective delivery decisions while ensuring all cities receive the exact quantity of goods they require.

Business Scenario
A logistics company operates a central warehouse and needs to deliver goods to three cities: City A, City B, and City C. Each city has a predetermined and non-negotiable demand:

City A requires 30 units
City B requires 50 units
City C requires 20 units

Delivering one unit of product from the warehouse to each city incurs a specific cost:

₹4 per unit to City A
₹6 per unit to City B
₹8 per unit to City C

The company is committed to meeting the full demand of each city — no more, no less. Although the trucks used for delivery have a capacity of 40 units per trip, this model assumes that the number of available trucks is not limited, and delivery quantity per trip is not a constraint (this simplification will be revisited in advanced versions of the model). The primary concern here is cost minimization.

 Optimization Goal
The goal of this optimization is to minimize the total cost of delivering goods from the warehouse to the three cities, while:
Satisfying the demand of each city exactly
Ensuring that no city receives more or less than its required units
Leveraging the delivery cost rates effectively to reduce expenditure

The final output will include:
The minimum delivery cost required to fulfill all demands
The quantity of goods delivered to each city (which should match the exact demand)
Insights into how cost minimization can be achieved using mathematical optimization


output:
Total Delivery Cost = ₹ 620.0
Units to City A: 30.0
Units to City B: 50.0
Units to City C: 20.0

![Image](https://github.com/user-attachments/assets/8c0aa41b-5836-4516-b1e2-c54a33979b27)

