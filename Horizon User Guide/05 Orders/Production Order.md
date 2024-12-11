# Production Order

## Create a Production Order

A production order details the item to be produced, its required materials, and the production timeframe, ensuring proper resource allocation. To create a production order based on demand, follow these steps:

1. **Navigate to Supply and Demand**

- From the main menu, select **Supply and Demand**. 
- Click **Supply and Demand** from the primary navigation tabs, then select **Demand List**. 

2. **Filter Demand Types**

- In the demand list, uncheck any irrelevant demand types (e.g., pick demand, purchase demand) until only **build demand** remains checked. Then click **Search**. 
- Alternatively, press Command + F (Mac) or Control + F (Windows), and type **Build** in the **Source** field. 

	💡 **Tip:** To find demand from a specific customer, **enter the customer’s name** or **order number** in the search fields.

3. **Select Build Demand**

- To address a specific **Build Demand** item, click **build** x item (e.g., Lemon Meringue Tart). 
- To address all build demands at once, click **address all x demands.** 

    ⚠️ Note: Notification messages will appear at the beginning and end of batch demand generation. Click **OK** to continue.
    
4. **View Batch Name**

- To view the batch name (set after generating demand), go to **Supply and Demand** from the primary navigation menu and select **Demand Batch List** under your user account.

5. **Choose Demand**

- Select the demand you just generated, then click the expand button (>) next to it.  
    💡 **Tip:** The first item in the list should be the demand you just generated.

6. **Create Production Order**

- In the Temporary Order Item list, production orders are grouped by date and order number. Click **Create Order** for the desired production order.

7. **Order Status**

- Once the production order is created: <br>
	7.1. The BOM yield items will be added. 
	
	7.2. The order will receive a serial number and its status will change to **View Order**. Click **View Order** to proceed. <br>


9. **Assign Employee**

* In the the **Order** tab, assign an employee responsible for the order by clicking **Click here to select employee**.

10. **Enter Production Dates** 
* Enter the dates for when you **Started** and **Finished** the production order.

11. **Select Location**
* To select the **Location** for storing the yielded items, click **Options**, then select **Feature Flags**, and choose **Production Order**.

12. **Adjust Product Quantities**
* In the **Production Order Items** section, select the product type (**Yield** or **Source**) and adjust the product quantity as needed. 

13. **Use the Reverse Button** 🔄
	Click the **Reverse** button  to revert recent changes and restore previous settings.

	- **Adjusting Quantities:** If you change the quantity of an item (e.g., from 20.16 to 30 ounces), click the **Reverse** button to confirm the update. After confirmation, the system will adjust the BOM with the new quantity.
	
	- **Restoring Deleted Items:** If you accidentally delete an item, the **Reverse** button will restore it with the correct quantity once you confirm the action.
	
	- **Handling Changes:** The **Reverse** button will revert modified quantities to their previous values. Newly added items will not be affected or removed.
	
14. **Access Additional Settings:**

* Click the gear icon to access additional settings or click the i icon for more information.

15. **Delete or Modify Line Items**

* To delete or modify a specific line item, click the delete button (x) next to that item.

* To delete or modify all line items at once, click the **Delete** button above the list of line items.
 
 16. **Confirm Actions**
 
Click **confirm** to complete the following actions:

- Confirm the Production Order. A successful production will display a **Location** and **Lot Number** in the Location Module. To review, go to **Item Management**, select **Location**, and choose the specific location from the left pane. Verify that the yielded item is displayed.

	⚠️ **Note:** An unsuccessful production is often due to not specifying the **Best By** time for the yielded item. To edit this, go to **Item Management**, select **Products**, choose the product, and update the **Best By** field.
	
- Assign yield items to **Built** in inventory (+).
- Assign source items to **Consumed** in inventory (+).
- Address demand for line items.
- Assign the yielded item to the specified location (+).

	⚠️ Note: If the item does not exist at the location, a new location will be created. If the item already exists, the quantity will be updated.

	 💡 Tip: Click **Unconfirm** to reverse all actions:

	- Deduct added items.
	- Delete created locations.
	- Reverse updates.

17. **Add Production Instructions**

* Go to the **Procedure** tab and add step-by-step production instructions. 

18. **Enter Time and Track Progress

* Enter the estimated time duration for each step and check them off as they are completed.

19. **Track Production Time**

* Use the **Play button** to start and pause the timer. Click the **Flag icon** to mark the process as finished.

20. **Copy Production Procedure**

* Click **Copy Procedure** to duplicate the entire production order procedure for reuse or modification.

21. **Save Changes**
* Click **Save Changes** to keep your modifications. 






