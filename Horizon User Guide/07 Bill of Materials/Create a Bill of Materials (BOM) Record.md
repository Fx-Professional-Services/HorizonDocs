# Create a Bill of Materials (BOM) Record

A Bill of Materials (BOM) serves as a detailed guide for creating a product. It specifies the required parts or materials, their quantities, and the assembly process. BOMs can support various versions or configurations of a product, although only one is typically used for production at any given time.

  Follow these simple steps to create a new Bill of Materials (BOM) record:

### 1. Access the BOM Section

   - Open the **Bill of Materials** file from the main menu. <br>
2. **Initiate New Record**:

   - Click **New Record** to start a blank record.

💡 **Tip:** When using other modules, such as Products, Sales Orders, or Supply and Demand, access the BOM module by clicking **Item Management > BOM**.

3. **Add Yield or Source Item**:

#### 3.1 Navigate to the Sources/Yields Tab

- Click the **Add Yield Item** and/or **Add Source Item** field.
- **Search**: Type the item name and click the search icon **(**🔎**)**.
- **Browse**: Scroll through the list and click on the item.
- Click **Done** to return.

	3.2.**Select Items**:
	
💡 **Tips**
- **Add New Item:** Click the add button (✚) at the top right of the picker window. Enter the product details (name, description, replenishment method, etc.) and click **Save**.
- **Delete Item:** Click the delete button (✖︎) next to the item and confirm by selecting **Delete** in the dialog box.

### 4. Confirm the Unit of Measure

- The unit of measure for each item is automatically set. To change it, click the **Unit** type box, select the new unit of measure, and click **Done**.

### 5. Set the BOM Name

- The BOM name is automatically generated based on the list of item names. You can customize it in the details tab.

	💡**Tips:** 

	1. **Quickly Add a Source and/or Yield Item:**  
		Click the **Add** button (✚) in the top-right corner of the picker. Enter the product details, including the name, description, replenishment method, and unit of measure. Indicate whether the product is a Sale Item, Need Pick, or Consumable by entering **1** for Yes or **0** for No. When finished, click **Save**.

- Click the **Add** button (✚) at the top right corner.
- Enter the product details, including:
    - **Name**
    - **Description**
    - **Replenishment Method**
    - **Unit of Measure**
- In the **Consumable** and **Need Pick** fields, enter `1` for Yes and `0` for No to indicate whether the product is consumable or needs to be picked.
- Click **Save**.

**⚠️ Note**: If the same item appears in both the yield and source portals, an error will be shown when you attempt to commit. To resolve this, remove the item from one of the portals.

 2. **To delete a BOM yield or source item**:
    
    - Click the **Delete** button (✖︎) next to the item.
    - A confirmation dialog will appear. Click **Delete** to confirm.
    - When a BOM yield item is deleted, the BOM name in the left pane will update automatically.

4. **Set BOM Name and Type**:

   - The BOM name is automatically set based on the list of item names in the yield. To assign a descriptive name to the BOM, go to the **Details** tab and edit the name.

- Click the **Quantity** type box and enter the quantity for each source/yield item.

   - Select the appropriate type for the BOM: **substitution** or **standard**.

5. **Confirm Unit of Measure**:

   - The unit of measure for each yield and source item is set automatically. To change it, click the **Unit** field. In the picker, select a new unit of measure by clicking the **Add** button (+), then click **Done**.

6. **Input the Quantity**:

7. **Add Procedural Steps**: 

7.1. Go to the **Procedure** tab located next to the **Sources/Yields** tab.

   💡 **Tip**: Use the up and down arrow keys to easily navigate between fields. <br>
   
7.2. In the Procedure tab, input the following details for each step. 

A. **Step Number**: Assign a sequential number to each step for clarity.    

B. **Instructions**: Provide clear and concise instructions for completing each step.

C. **Duration**: Specify the duration for each step in the hh:mm format (e.g., 02:20).

D. **Create a Task**: To use the procedure in the Bill of Materials as ad-hoc tasks for a project in **Horizon Project Management**:

1. Click **Create Task** in the upper-right corner of the module.
2. In the window that appears, enter the task name or title.
3. Click **OK** to create the task.
4. To review the newly created ad-hoc task, go to the **Main Menu**, select **My Tasks**, and choose **Projects**.
5. You should see the ad-hoc task listed there.

  ⚠️ **Note**: Should you wish to delete the BOM record, click on the **Delete Record** in the navigation buttons. Then, in the dialogue box, select **Delete** to proceed with the deletion of the BOM record.

8. **Update BOM Cost**:

In the **Sources/Yields** tab, click **Update Cost** in the secondary navigation tabs to update BOM cost. This will update the **Subtotal** and **Total** costs. 

To resolve issues that may arise when updating the BOM costs, follow these steps:

1. **Missing Unit of Measure for BOM Cost Update**

If a dialog appears stating that the unit cost cannot be calculated due to a missing unit of measure:

1. Click the **Expand** button (>) next to the line item to open the **Products > Details** page.
2. Click the **Costs** tab.
3. Enter the unit of measure for the item. 
___
2. **Missing BOM Unit of Measure Conversion**

If no BOM unit of measure conversion exists, you cannot update the BOM cost. To resolve this:

1. Go to **Horizon Order > Units and Categories > Conversion Factors**.
2. Click **New Record**.
3. Add the conversion factor between the units of measure.
4. In the **Specific** field, add the source item to apply the conversion to that product only.
___
3. **Updating BOM Cost After Source Item Quantity Change**

After updating the quantity for each source item, you will be prompted to update the BOM cost:

1. Click **OK** in the dialog box.
2. Click **Update Cost**.
3. The **Subtotal** and **Total Cost** will be updated.
___
4. **No BOM Set for Source Item**

If no BOM is set for the source item and its replenishment method is **Build**, follow these steps:

1. Click the **Expand** button (>) next to the line item to open the **Products > Details** page.
2. In the **Details** tab, update the **Active BOM**.
3. Return to the BOM page and click **Update Cost** to update the BOM price and total cost.
