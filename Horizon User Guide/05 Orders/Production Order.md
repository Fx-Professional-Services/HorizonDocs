# Production Order

## Create a Production Order

A production order details the item to be produced, its required materials, and the timeframe for production to ensure proper resource allocation. To create a production order based on demand, follow these steps:

1. **Navigate to Supply and Demand**

- From the main menu, select **Supply and Demand**. Click **Supply and Demand** from the primary navigation tabs, then select **Demand List**. 

2. **Filter Demand Types**

- In the demand list, uncheck any irrelevant demand types (e.g., pick demand, purchase demand) until only **build demand** remains checked. Click **Search**. Alternatively, you can also press Command + F (Mac) or Control + F (Windows), then type in **build** in the **source** field. 

	💡 **Tip:** To find demand from a specific customer, click **enter the customer’s name** or **order number** in the search fields.

3. **Select Build Demand**

- To address a specific build demand item, click **build** x item (e.g., Lemon Meringue Tart). To address all build demands at once, click **address all x demands.** 
    ⚠️ Note:** Notification messages will appear at the beginning and end of batch demand generation. Click **OK** to continue.
    
4. **View Batch Name**

- To view the batch name (initially set after generating demand), go to **Supply and Demand** from the primary navigation buttons and select **Demand Batch List** under your user account.

5. **Choose Demand**

- Select the demand you just generated, then click the expand button (>) next to it.  
    💡 **Tip:** The first item in the list should be the demand you just generated.

6. **Create Production Order**

- In the Temporary Order Item list, you will find production orders grouped by date and order number. Click **Create Order** for the desired production order.

7. **Order Status**

- Once created, the order will have: <br>
	7.1. a serial number and <br> 
	7.2. its status will change to **View Order**—click it to proceed. <br>
8. In the Production Order under the **Order** tab, assign an employee responsible for the order by clicking on 'click here to select employee.'

9. Enter the dates for when you **Started** and **Finished** the production order.
10.   To select the **Location** for storing the yielded items, click **Options**, then select **Feature Flags**, and choose **Production Order**.
11. In the **Production Order Items** section, you can select the product type (yield or source) and adjust the product quantity. 
12. Tap the reverse button 🔄 to revert recent changes and restore previous settings.

	- **Adjusting Quantities:** If you change the quantity of an item (e.g., from 20.16 to 30 ounces), clicking the reverse button will prompt you to confirm the update. Once you proceed, the system will adjust the BOM to reflect the specified quantity.
	
	- **Restoring Deleted Items:** If you accidentally delete an item, the reverse button will restore it with the correct quantity when you confirm the action.
	
	- **Handling Changes:** The reverse button will adjust any modified quantities to their previous values. However, newly added items will not be affected or removed.
	
13. TO BE UPDATED: Tap the gear icon to access additional settings and  the i icon for more information.
14. To delete or modify a specific line item, click the delete button located next to that item. If you wish to delete or change all line items at once, click the delete button above the list of line items.
15. Click **confirm** to complete the following actions:
- **Confirm the production order.** A successful production will display a location and lot number in the Location Module. To review this, navigate to **Item Management**, select **Location**, and choose the specific location from the left pane. Verify that the yielded item is displayed.
	⚠️ **Note:** An unsuccessful production is often caused by not specifying the **Best By** time for the yielded item. To edit this, go to **Item Management**, select **Products**, choose the product, and update the **Best By** field.
- **Assign yielded items to "Built in Inventory" (+).**
- **Assign sourced items to "Consumed in Inventory" (+).**
- **Address demand for line items.**
- **Assign the yielded item to the specified location (+).**

	⚠️ Note: If the item does not exist at the location, a new location will be created. If the item already exists, the quantity will be updated.

	 💡 Tip: Click **Unconfirm** to reverse all actions:

	- Deduct added items.
	- Delete created locations.
	- Reverse updates.

16. Go to the **Procedure** tab, add step-by-step production instructions. 

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/26_procedure_tab.png" width="350" height="250">

17. You can input the estimated time duration for each step and check them off as they are completed.
18. Track the production time by using the **play button** to start and pause the timer, and click the flag icon to mark the process as finished.
19. Click **Copy Procedure** to duplicate the entire production order procedure for reuse or modification.
20. Click **Save Changes** to keep your modifications. 






