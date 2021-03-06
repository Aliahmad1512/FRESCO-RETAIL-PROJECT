# FRESCO | RETAIL | PROJECT
### Problem description: The data analysis Fresco Retail’s customers’ transaction data to predict return decision using various data points like customer background, payment modes, store types, product nature, etc. 
### The objective is to study the influence of different transaction data points and their impact on a customer’s final decision to return the product(s) bought in a transaction.

![2018-seg-fresco-y-mas-tampa-032a-deremer-studios-llc_1200xx5531-3111-0-288](https://user-images.githubusercontent.com/88396377/137611468-c4da65b8-1407-439a-ad86-91bc12b0794a.jpg)

#### Variable Description:
* transaction_id: Unique transaction number for each sale
* Month_code: The month of transaction
* prod_cat_code: Product category code. A product may have multiple sub-categories
* prod_cat: Product category name mapped to prod_cat_code.
* prod_subcat_code: Product sub-category code
* prod_subcat: Product sub-category name mapped to product_subcat_code
* Qty: Quantity of products bought / returned
* Rate: Price per unit of a product in local currency
* Amount: Total amount (Qty * Rate) without the taxes
* Tax: Tax amount by local government
* Delivery_chrgs: Delivery charges to deliver the products ordered
* Payment_mode: Mode of payment used by the customer to pay for a transaction
* Store_type: Type of store where the transaction took place. eShop means online commerce. MBR means Multi branded retail store. Flagship store means standalone fully owned shop by the retailer. Teleshop means orders received on retailer phone numbers.
* Reviews: Review left by the customer on the product or transaction
* Cust_id: Customer identification number
* DOB: Customer’s date of birth
* Gender: Customer’s gender
* Education_Level_Code: Code assigned to different education levels of a customer
* Level_Education: Education level mapped to Education_Level_Code
* Profession_Code: Customer’s profession code
* Profession Type: Type of profession (Salaried, Self Employed, Others)
* City_code: City identification code assigned to each city RETURN: This is our target variable that stores the response of whether the transaction was finally returned by the customer.
* RETURN: This is our target variable that stores the response of whether the transaction was finally returned by the customer.
