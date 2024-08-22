# Production Order

## Create a Production Order

A production order details the item to be produced, its required materials, and the timeframe for production to ensure proper resource allocation. To create a production order based on demand, follow these steps:

1. [Address a build demand.](https://github.com/Fx-Professional-Services/HorizonDocs/blob/sales_order/Horizon%20User%20Guide/05%20Orders/Address%20Demand.md#build-demand) 
2. Select **Demand Batch List** under **Supply and Demand**.
3. Find your user account. Choose the demand you just generated, then click the expand button (>) next to the item. <br>
 💡 Tip: The first item in the list under your account should be the demand you just generated.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/25_demand_batch_list.png" width="350" height="250">

4. In the Production Orders window, click **Create Order** for the desired production order.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/30_create_order.png" width="350" height="250">

5. Once created, the order will have: <br>
	5.1. a serial number and <br> 
	5.2. its status will change to **View Order**—click it to proceed. <br>
<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/29_view_order.png" width="350" height="250">

6. In the Production Order under the **Order** tab, assign an employee responsible for the order by clicking on 'click here to select employee.'

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/24_production_order_tab.png" width="350" height="250">

7. Enter the dates for when you **Started** and **Finished** the production order.
8.  To select the **Location** where the yielded items will be stored, go to **Sales Order**, click **Options**, then select **Feature Flags** and choose Production Order.  
9. TO BE UPDATED: LOT #. 
10. In the **Production Order Items** section, you can select the product type (yield or source) and adjust the product quantity. 
11. Tap the reverse button 🔄 to revert recent changes and restore previous settings.

	- **Adjusting Quantities:** If you change the quantity of an item (e.g., from 20.16 to 30 ounces), clicking the reverse button will prompt you to confirm the update. Once you proceed, the system will adjust the BOM to reflect the specified quantity.
	
	- **Restoring Deleted Items:** If you accidentally delete an item, the reverse button will restore it with the correct quantity when you confirm the action.
	
	- **Handling Changes:** The reverse button will adjust any modified quantities to their previous values. However, newly added items will not be affected or removed.
	
12. TO BE UPDATED: Tap the gear icon to access additional settings and  the i icon for more information.
13. To delete or modify a specific line item, click the delete button located next to that item. If you wish to delete or change all line items at once, click the delete button above the list of line items.
14. Click **confirm** to complete the following actions:
- Confirm the production order.
- Assign yielded items to "Built in Inventory" (+).
- Assign sourced items to "Consumed in Inventory" (+).
- Address demand for line items.
- Assign the yielded item to the specified location (+).

	⚠️ Note: If the item does not exist at the location, a new location will be created. If the item already exists, the quantity will be updated.

	 💡 Tip: Click **Unconfirm** to reverse all actions:

	- Deduct added items.
	- Delete created locations.
	- Reverse updates.

15. Go to the **Procedure** tab, add step-by-step production instructions. 

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/26_procedure_tab.png" width="350" height="250">

16. You can input the estimated time duration for each step and check them off as they are completed.
17. Track the production time by using the **play button** to start and pause the timer, and click the flag icon to mark the process as finished.
18. Click **Copy Procedure** to duplicate the entire production order procedure for reuse or modification.
19. Click **Save Changes** to keep your modifications. 






