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
		
	2. To delete a BOM yield item: Click on the delete button (✖︎) next to the item. A confirmation dialogue will appear; click **Delete** to confirm.
	
	**⚠️ Note:** If the same item appears in both the yield and source portals, an error will be displayed upon commit. To resolve this, remove the item from either portal. 

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

B. **Instructions**: Write clear, concise instructions for performing each step.

C. **Duration**: Specify the duration for each step in the hh:mm format (e.g., 02:20).

  ⚠️ **Note**: Should you wish to delete the BOM record, click on the **Delete Record** in the navigation buttons. Then, in the dialogue box, select **Delete** to proceed with the deletion of the BOM record.