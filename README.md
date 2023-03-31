# Business-Cases-for-Data-Science-BC2
📖 Introduction<br>
Within the scope of Business Cases for Data Science, it was proposed a project, where the groups' ability to deliver a market basket analysis in accordance with the different features included in a dataset containing 84.109 records would be tested. However, the company C that ownes this restaurant realized that they are not having enough profits and therefore, wishes to better understand their customers and its preferences.

Therefore, the business goal determined for this project was to develop a market basket analysis. C expects to gain insights in terms of creation of menus, introduction of new products, understand substitute products, recommending/promoting cross-selling, customer segmentation and other possible results depending on the findings.

C has several questions that it hopes to get answers to:

- Are there any differences between dine-inn customers and delivery customers?<br>
- Is the product offering adequate (e.g., do customers make strange combination of products) ?<br>
- Are there any patterns in consumption that may indicate tendencies?<br>

📖Dataset description<br>
This notebook uses the Case2_AsianRestaurant_Cyprus_2018.txt. The Dataset is related with all sales transactions of a restaurant located in Nicosia, the capital of Cyprus. This asian food restaurant is inserted in a company C, with restaurants spread all over the this country. This restaurant is struggling to maintain its profit margin and continuous growth due to increasing competition and customers’ changes in habits. To try to revert this process, C wants to take advantage of its sales data to understand customers’ patterns of consumption and preferences.

The dataset is composed of the following columns:

- DocNumber: number of the document. The document number repeats in as many rows as the rows in the original document (invoice)<br>
- ProductDesignation: product designation<br>
- ProductFamily: name of the family of the product. A product can only be member of one only family<br>
- Qty: quantity<br>
- TotalAmount: sale price of the total quantity<br>
- InvoiceDateHour: date and hour when the document was issued<br>
- EmployeeID: ID of the employee who issued the document<br>
- IsDelivery: indication if sale was a delivery or a dine-inn (1: delivery, 0: dine-inn)<br>
- Pax: number of persons at the table<br>
- CustomerID: ID of the customer (if a customer record was assigned to the sale)<br>
- CustomerCity: city of the customer (usually only employed in delivery)<br>
- CustomerSince: date of creation of the customer<br>

Note: Each row in the dataset represents a document line (invoice line).
