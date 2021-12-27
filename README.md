# InvoiceGenerator

Run it using main.py (python main.py)



-----------------After running it looks something like this---------------



Following products are avilable in our Store
--------------------------------------------
PRODUCT         PRICE           QUANTITY    
--------------------------------------------
Phone            200             35
laptop           900             40
HDD              200             16
--------------------------------------------
Please enter your name:Sachin 

---------------Firstly we have to Enter the Name as in mine case Sachin and press Enter-----------------


Following products are avilable in our Store
--------------------------------------------
PRODUCT         PRICE           QUANTITY    
--------------------------------------------
Phone            200             35
laptop           900             40
HDD              200             16
--------------------------------------------
Please enter your name: sachin

Hello sachin! Welcome to our Electronic Store.  
Look at above and select product as your choice.

What product do you want to buy?hdd

-------After that screen looks something like this , here We have to pass the item which we have to buy fromm the given products ( phone , laptop and HDD) I choosed hdd ------


Following products are avilable in our Store
--------------------------------------------
PRODUCT         PRICE           QUANTITY    
--------------------------------------------
Phone            200             35
laptop           900             40
HDD              200             16
--------------------------------------------
Please enter your name: sachin

Hello sachin! Welcome to our Electronic Store.  
Look at above and select product as your choice.

What product do you want to buy? hdd
How many hdd do you want to buy: 4

----------------After choosing product , choose quantity of products (In my case I choosed 4)------------------------


Following products are avilable in our Store
--------------------------------------------
PRODUCT         PRICE           QUANTITY    
--------------------------------------------
Phone            200             35
laptop           900             40
HDD              200             16
--------------------------------------------
Please enter your name: sachin

Hello sachin! Welcome to our Electronic Store.  
Look at above and select product as your choice.

What product do you want to buy? hdd
How many hdd do you want to buy: 4
sachin do you want buy more products?(Y/N)y


----Then it going to ask us whether we have to buy something else or not , if yes press y ,if no press n(In my case I want to buy phone too)---------





Following products are avilable in our Store
--------------------------------------------
PRODUCT         PRICE           QUANTITY    
--------------------------------------------
Phone            200             35
laptop           900             40
HDD              200             16
--------------------------------------------
Please enter your name: sachin

Hello sachin! Welcome to our Electronic Store.  
Look at above and select product as your choice.

What product do you want to buy? hdd
How many hdd do you want to buy: 4
sachin do you want buy more products?(Y/N)y

What product do you want to buy? phone
How many phone do you want to buy: 3
sachin do you want buy more products?(Y/N)n

You Choosed Items and it's Quantity respectively:
 {'HDD': 4, 'PHONE': 3}

Total cost for HDD:  800

Total cost for phone:  600

Your discountable total amount is:  1400
Please enter your expected discount (%):5


-----------------------After buying phone and the quantity of phone it again ask for further shopping ,if yes type y, else n(In my case I don't want ) so it gives the total amount and ask for discount in %  -------------

 
 Following products are avilable in our Store
--------------------------------------------
PRODUCT         PRICE           QUANTITY    
--------------------------------------------
Phone            200             35
laptop           900             40
HDD              200             16
--------------------------------------------
Please enter your name: sachin

Hello sachin! Welcome to our Electronic Store.  
Look at above and select product as your choice.

What product do you want to buy? hdd
How many hdd do you want to buy: 4
sachin do you want buy more products?(Y/N)y

What product do you want to buy? phone
How many phone do you want to buy: 3
sachin do you want buy more products?(Y/N)n

You Choosed Items and it's Quantity respectively:
 {'HDD': 4, 'PHONE': 3}

Total cost for HDD:  800

Total cost for phone:  600

Your discountable total amount is:  1400
Please enter your expected discount (%): 5
You did not got your expected 5.0% discount
Because, your totel purchase is not meet the minimum criteria for 5.0% discount.
Your payable amount is:  1400.0

Remaining Stock Products:
 [['Phone', '200', '32'], ['laptop', '900', '40'], ['HDD', '200', '12']]        

Does the any new customer waiting to buy product? n

Thank you for shopping from our store!!
Please check your invoice for your shopping details,
Which we created txt file format for you.

--------after eentering discount .if it meets with the sellers then it will be discounted else not and the it again asks for the further shopping for new customer ,if yes type y ,else n--------





