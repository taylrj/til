For keep the referential integrity of data, the foreign key has been used to point to other table's primary key.

For example:
We have two tables, CUSTOMER and ORDERS.
The CUSTOMER table has all the records of our customer, and the ORDERS keeps all the data of oders.
Here, we'd like to add a constraint that the customers in ORDERS must exist in CUSTOMER.
Therefore, we can set a `foreign key` in ORDERS which points to the primary key in CUSTOMER.

