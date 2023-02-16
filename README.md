# Pharmacy System Entity-Relationship Diagram (ERD)
This ERD represents a system for managing a pharmacy that contains drugs and connecting with a company to get information to produce a package that contains the drugs with their information such as name, expiry date, production date, quantity, selling price, and other details. The system also keeps track of who receives the drugs and the customers who purchase them.

## ERD Overview
The ERD contains the following entities:

1. Company: The company that produces the drugs.
2. Drug: The drug that is produced by the company.
3. Package: The package that contains the drug and its information such as name, expiry date, production date, quantity, and selling price.

4. Pharmacy: The pharmacy that stocks the drugs and sells them to customers.

5. Customer: The customer who purchases the drug from the pharmacy.

6. Transaction: The transaction that occurs when the customer purchases the drug from the pharmacy.

### The entities are connected with the following relationships:

* A company produces many drugs.
* A drug is produced by one company.
* A drug can be contained in many packages.
* A package contains one drug.
* A pharmacy stocks many packages.
* A package is stocked by one pharmacy.
* A pharmacy can serve many customers.
* A customer can purchase drugs from many pharmacies.
* A transaction is made by one customer.
* A customer makes many transactions.
* A transaction involves one package.
* A package is involved in many transactions.

## Entity Descriptions
Here is a brief description of each entity in the ERD:

Company
The Company entity represents a pharmaceutical company that produces drugs.

 Attributes:

Company ID: A unique identifier for the company.
Company Name: The name of the company.
Drug

 The Drug entity represents a drug that is produced by a company.

Attributes:

Drug ID: A unique identifier for the drug.
Drug Name: The name of the drug.
Package
The Package entity represents a package that contains the drug and its information such as name, expiry date, production date, quantity, and selling price.

Attributes:

Package ID: A unique identifier for the package.
Expiry Date: The date on which the package expires.
Production Date: The date on which the package was produced.
Quantity: The quantity of drugs in the package.
Selling Price: The price at which the package is sold.
Pharmacy

The Pharmacy entity represents a pharmacy that stocks the drugs and sells them to customers.

Attributes:

Pharmacy ID: A unique identifier for the pharmacy.
Pharmacy Name: The name of the pharmacy.
Customer
The Customer entity represents a customer who purchases the drug from the pharmacy.

Attributes:

Customer ID: A unique identifier for the customer.
Customer Name: The name of the customer.
Transaction
The Transaction entity represents a transaction that occurs when the customer purchases the drug from the pharmacy.

Attributes:

Transaction ID: A unique identifier for the transaction.
Transaction Date: The date on which the transaction occurred.

# Conclusion

This ERD provides a foundation for creating a pharmacy system that contains drugs and connects with a company to get information to produce packages that contain the drugs with their information such as name, expiry date, production date, quantity, selling price, and other details. The system also keeps track of who receives the drugs and the customers who purchase them. By using this ERD as a guide, developers can create a robust and efficient pharmacy system.