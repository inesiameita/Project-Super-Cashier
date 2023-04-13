# Project-Super-Cashier


**Background Project**

This program is made as a self service cashier system. Customers can input the items purchased, the quantity, the price based on the store list, as well as several other features. This program is created to make it easier for customers to record what items were purchased without having to come directly to the store, and also make it easier for store owners / managers to prepare what items the customer purchased in more details.   




**Objective / Requirements**


The customers will make an order by inputting the items purchased themself (self service system), then the total payment will appear at the end of the transaction.

1. Create a transaction ID 
2. Display a list of items that can be ordered 
3. Input how many items purchased
4. Add 'item_name' , 'item_qty' , 'item_price' 
5. Display order list as a table
6. Update 'item_name' as 'new_name', if there is a change in the name of the item purchased
7. Update 'item_qty' , if there is a change in the quantity of the item purchased
8. Update 'item_price' , if there is a change in the price of the item purchased
9. Delete 'item_name' , if the item is canceled to be purchased
10. Reset transaction to delete all the items purchased
11. Check order list, wheter it is appropriate or not
12. Calculate the discount from total_transaction:
    * If total_transaction > 200,000 will get discount 5%
    * If total_transaction > 300,000 will get discount 8%
    * If total_transaction > 500,000 will get discount 10%
13. Calculate total_payment the customer have to pay from total_transaction - discount




**Flowchart**

![Flowchart Transaction](https://user-images.githubusercontent.com/128911434/231216024-cbea8391-551c-482c-9347-0d4da667b01a.png)



**Test Case Results**

* Test case 1 : Create a transaction ID with function Transaction

![test case 1](https://user-images.githubusercontent.com/128911434/231819845-62cacfc4-84f5-465a-9655-c622db13663b.png)


* Test case 2 : Add items purchased to order list

![test case 2](https://user-images.githubusercontent.com/128911434/231819889-8b8ebd51-27c4-4781-a8c0-9d709c9f6e90.png)


* Test case 3 : Update new item name on order list

![test case 3](https://user-images.githubusercontent.com/128911434/231820239-74ffd3df-7b38-4e16-b810-cebf9eec5817.png)


* Test case 4 : Update new item quantity on order list

![test case 4](https://user-images.githubusercontent.com/128911434/231820281-0b6743f5-7564-4d48-bf79-3aaaff780ca5.png)


* Test case 5 : Update new item price on order list

![test case 5](https://user-images.githubusercontent.com/128911434/231820787-7c869962-e799-4637-b594-63ed360da9d9.png)


* Test case 6 :  Delete item on order list

![test case 6](https://user-images.githubusercontent.com/128911434/231820829-72a5fb45-69f9-4ab1-a7b1-ae15dd33fa1e.png)


* Test case 7 : Reset transaction and delete all items on order list

![test case 7](https://user-images.githubusercontent.com/128911434/231820885-e1964eb3-cf5d-4c45-9150-863c143845de.png)


* Test case 8 : Check order list

![test case 8](https://user-images.githubusercontent.com/128911434/231820914-2fc409d2-c320-4820-8ac3-7bc0d87f6624.png)


* Test case 9 : Calculate total payment the customer have to pay

![test case 9](https://user-images.githubusercontent.com/128911434/231820953-19e309d5-6194-46ba-b2e0-566aa408c270.png)


**Conclusion and Future Work**
1. For this project, the program is still used a basic calculation program system.
2. Developing program with more complex functions.
3. Providing more communicative program display, with menu options that can be selected by user.
4. Other improvements can be developed further, after the program is used by user.  




