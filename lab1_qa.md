1.  Find the top three items with the highest average prices for each size.
    -   Which table or tables would contain this?
	   	- **menu** table has `item_size`, `item_price`and even `item_name`.
    -   Which tool would help you answer this question?
		- **Insights** tool is useful. Then after using the query it advises, we can use **Transform SQL with Gemini** and fine tune for what we want.
		
2.  Find all orders from location_id 37.
	-   Which table or tables would contain this information?
		- **order** table has this information as it has `order_id` and `location_id`.
    -   How many orders are there from this location?
	    - 118 orders.
    -   Which tool would you use to find all the orders?
	    - **Insights**, but if that doesn't work and not generate the insight that we need, we can click **Query** in the **Schema**, then use **Transform SQL with Gemini** to generate information we want.

3.  For your use cases, which tool, table explorer or data insights, would help you the most? Why?
		-	Probably all, but currently **Insights** and **Transform SQL with Gemini**.
