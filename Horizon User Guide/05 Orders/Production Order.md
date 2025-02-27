# Production Order

## Create a Production Order

A production order outlines the item to be produced, its required materials, and the production timeframe to ensure resource allocation.

To create a production order, follow these steps:

### 1. Navigate to Supply and Demand
- From the main menu, select **Supply and Demand**. 
- Click **Supply and Demand** from the primary menu bar, then select **Demand List**. 


###  2. Filter Demand Types

- In the demand list, uncheck any irrelevant demand types (e.g., pick demand, purchase demand) until only **build demand** remains checked. Then click **Search**. 
- Alternatively, press **Command + F** (Mac) or **Control + F** (Windows), and type **Build** in the **Source** field. 

### 3. Select Build Demand

- To address a specific **Build Demand** item, click **build** x item (e.g., Lemon Meringue Tart). 
- To address all build demands at once, click **address all x demands.** 

    ⚠️ Note: Notification messages will appear at the beginning and end of batch demand generation. Click **OK** to continue.

### 4. **View Batch Name**

- To view the batch name (set after generating demand), go to **Supply and Demand** from the primary navigation menu and select **Demand Batch List** under your user account.

5. In the **Production Order** layout, under the **Order** tab, the production order will be displayed along with its yield, sources, and the quantity and unit of measure for each selected item.

### 5. **Choose Demand**

- Select the demand you just generated, then click the expand button (>) next to it.  
    💡 **Tip:** The first item in the list should be the demand you just created.

### 6. Create Production Order

- In the **Temporary Order Item** list, production orders are grouped by date and order number. Click **Create Order** next to the desired production order, then click **Add Production Order Item**. 


### 7. View Demand

* Click **View X Demands**, then click the (+) button in the **View Demand X** popover to view the selected demand.

7.1. The **BOM** (Bill of Materials) yield items will be added. 

	7.2. You can now address demands. To address a demand, click **View 1 Demand** next to the line item, then click the **Add** button (+). This will prevent the line item from being deleted in the production order. To unaddress the demand, click the **Remove** button (-).
	
	7.3. The order will receive a serial number and its status will change to **View Order**. Click **View Order** to proceed. <br>

### 8. Proceed to View Order

- Click **View Order** to continue. If you click the i icon of the newly added addressed item, you will see the same details  as those in the **View Demand X** popover. 

- Once the production order is created: <br>

### 9. Assign Employee

* In the the **Order** tab, assign an employee responsible for the order by clicking **Click here to select employee**.

### 10. Enter Production Dates 
* Enter the dates for when you **Started** and **Finished** the production order.

### 11. Select Location
* To select the **Location** for storing the yielded items, click **Options**, select **Feature Flags**, and choose **Production Order**.

### 12. Adjust Product Quantities
* In the **Production Order Items** section, select the product type (**Yield** or **Source**) and adjust the product quantity as needed. 

### 13. Use the Reverse Button 🔄

* Click the **Reverse** button  to revert recent changes and restore previous settings.

	- **Adjusting Quantities:** If you change the quantity of an item (e.g., from 20.16 to 30 ounces), click the **Reverse** button to confirm the update. After confirmation, the system will adjust the BOM with the new quantity.
	
	- **Restore Deleted Items:** - If you accidentally delete an item, clicking the **Reverse** button will restore it with the correct quantity after you confirm the action.
	
	- **Handling Changes:** The **Reverse** button will revert modified quantities to their previous values. Newly added items will not be affected or removed.

### 14. Access Additional Settings:

* Click the gear icon to access additional settings, or click the i icon for more information.

### 15. Delete or Modify Line Items

* To delete or modify a specific line item, click the delete button (x) next to that item.

	⚠️ Note: The deletion will not proceed if there is an addressed line item on the demand, even if all demands were addressed or only a part of it  To unaddress a demand, see step 7.2.

   💡 Tip: Click **Unconfirm** to reverse all actions:

* To delete or modify all line items at once, click the **Delete** button above the list of line items.

### 16. Confirm Actions
 
Click **confirm** to complete the following actions:

- Confirm the Production Order. A successful production will display a **Location** and **Lot Number** in the Location Module. To review, go to **Item Management**, select **Location**, and choose the specific location from the left pane. Verify that the yielded item is displayed.

	⚠️ **Note:** If production is unsuccessful, it may be due to not specifying the **Best By** time for the yielded item. To edit this, go to **Item Management**, select **Products**, choose the product, and update the **Best By** field.
	

11. TO BE UPDATED: Tap the gear icon to access additional settings and  the i icon for more information.
12. To delete or modify a specific line item, click the delete button located next to that item. If you wish to delete or change all line items at once, click the delete button above the list of line items.
13. Click **confirm** to complete the following actions:
- **Confirm the production order.** A successful production will display a location and lot number in the Location Module. To review this, navigate to **Item Management**, select **Location**, and choose the specific location from the left pane. Verify that the yielded item is displayed.
	⚠️ **Note:** An unsuccessful production is often caused by not specifying the **Best By** time for the yielded item. To edit this, go to **Item Management**, select **Products**, choose the product, and update the **Best By** field.

* **Increase the Built inventory count.** To check this, go to **Item Management**, select **All Items**, and use **Find Mode** to locate the source or yield item. The **Built** inventory count should have increased.
- **Assign yielded items to "Built in Inventory" (+).**
- **Assign sourced items to "Consumed in Inventory" (+).**
- **Address demand for line items.**
- **Assign the yielded item to the specified location (+).**
- Assign yield items to **Built** in inventory (+).
- Assign source items to **Consumed** in inventory (+).
- Address demand for line items.
- Assign the yielded item to the specified location (+).

	⚠️ Note: If the item does not exist at the location, a new location will be created. If the item already exists, the quantity will be updated.
	
	 💡 Tip: Click **Unconfirm** to reverse all actions
	- Deduct added items.
	- Delete created locations.
	- Reverse updates.
	- Decrement the inventory.

### 17. Add Production Instructions

* Go to the **Procedure** tab and add step-by-step production instructions. 

### 18. Enter Time and Track Progress

* Enter the estimated time duration for each step and check them off as they are completed.

### 19. Track Production Time

- Click the **Play** button to start or pause the timer.
- Click the **Flag** icon to indicate that the process is complete.

### 20. Copy Production Procedure

To copy a procedure from a Bill of Materials (BOM):

1. Go to **Item Management** and click **BOM**.
    
2. Select a BOM from the left pane.
    
3. In the **Procedure** tab, enter the following details for each step:
    
    - **Step Numbers**: Assign sequential numbers to each step for clarity.
    - **Instructions**: Provide clear, concise instructions for each step.
    - **Duration**: Specify the duration for each step in hh:mm format (e.g., 02:20).
4. To duplicate the entire procedure for reuse or modification, follow these steps:
    
    1. Go back to the **Production Order** you were working on.
    2. Click **Orders** from the primary navigation menu, then select **Production Order**.
    3. Find the desired **Production Order**.
    4. In the **Procedure** tab, click **Copy Procedure**.

The procedure from the BOM is copied, and you can modify it as needed.

### 21. Save Changes

Click **Save Changes** to keep your modifications. 
