# Sales Orders

A sales order initiates the fulfillment of a customer's request for [products](#products) or [services](#services). Sales order records capture customer details, transaction specifics, and itemized orders. They also allow for  pricing adjustments, applying discounts, and managing taxes. Sales orders enable [demand](#demand) and [invoice](#invoice) generation, and provide an option for printing the record for documentation. Follow these  steps for efficient sales order management:

* [Create a Sales Order](#create-a-sales-order) 
* [Manage Line Items](#manage-line-items) 
* [Apply Taxes, Discounts, and Conditions](#apply-taxes-discounts-and-conditions)
* [Finalize and Print](#finalize-and-print) 
* [Definition of Terms](#definition-of-terms)
### Create a Sales Order
___
1.  **Ensure the Customer Record Exists**:
    
    - Make sure the customer’s record is already created. If not, [create a new customer record](https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/03%20Customers/Create%20and%20Manage%20Customer%20and%20Payment%20Records.md).
2. **Navigate to Sales Orders**:
    
    - In the main menu, go to **Sales Orders**.
3. **Create a New Record**:
    
    - Click **New Record**.
4. **Select the Customer**:
    
    - Click the **Customer** field to select a party.
    - In the picker, type the party’s name in the **Search** field and press **Enter**, or scroll through the list and click **Add**.
5. Set the Dates**:
    
    - Set the **Receive Date** and **Start At** date.
    - The **End At** date will be auto-scheduled based on the system’s settings.
6. **Select Sale Order Items**:
    
    - Click to select an item and choose a **Sale Order Item**.
    - In the picker, type the product name in the **Search Name** field or type a category name in the **Search Category** field.
    - After selecting the product, adjust the **Quantity**, then click **Done** to finalize the item selection.

**💡 Tip:** Refine your item search by entering a category name in the **Category** field in the item picker.

**⚠️ Note:** When you add a line item in sales order, the customer-facing name and description will automatically display, if available. 

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/01_create_sales_orders.png" width="350" height="300">

### Manage Line Items
___

7. **Adjusting Price and Quantity:**

    - Modify the price or quantity of a line item by entering new values. The subtotal and total costs will update automatically.

8. **Deleting Items:**

   To remove items from the list:
  - Click the **"x"** icon next to the item to delete it.
	- To delete all items, click **Delete All**.
	- In the confirmation prompt, click **Yes** to confirm deletion.

	 💡 Tip: To delete a product from a sales order, click **Item Management** and then **Products**. Find the product in the left pane, click **Delete Record**, and confirm with **Delete**.
	
9. **Editing Customer-Facing Name and Details:**
    
    9.1. After selecting a sales order item, stay in the **Details** tab.
    
    9.2. Add a **customer-facing description** in the field below the item you added. You can also modify the customer-facing description for other items as needed.

To edit the **customer-facing name** and **customer-facing description**:

- Go to the **All Items** tab.
- Select the line item.
- In the (i) info popover, update the **customer-facing name** and **customer-facing description**.

**⚠️ Note:** You can also update these details in **Item Management > All Items**. Use **Find Mode** to locate the item in the left pane. Then, go to the **Details** tab to edit the **Customer-facing Name** and **Customer-facing Description**.

After you update the customer-facing name and description, these details appear in the sales order and contract.

10. **Configuring Sales Order Items:**
    
    - To customize a sales order item, click the gear icon (⚙️), make changes, and  click **DONE** to save. 
    
	  💡 Tip: To search by category in the item picker, click on the order line item to open the  picker. In the Category field, enter keywords. The results will filter based on the entered keywords. 
    

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/03_sales_order_manage_line_items.png" width="350" height="300">

### Apply Taxes, Discounts, and Conditions
___
#### Taxes

11. **Making Sales Orders Taxable:**

A. Click the expand button (**>**) next to the customer’s name.  
B. In the customer layout, go to the **Customers** tab.  
C. Enter the tax rate.  
D. Return to your sales order and click the **Tax** box next to each line item until a checkmark (✔️) is displayed. Taxes will be calculated in real time, and the additional tax value will automatically update the **total cost**.

#### Discounts

12. **Applying Discounts:**

- Navigate to the **Discounts** section and click **Select Discount**.

- Select either a percentage discount (e.g., 10% off) or a fixed amount (e.g., $20 off) by clicking the add button (✚) and then **Done**. The discount will automatically adjust the subtotal and total costs.

- In the pop-up, choose either a percentage (e.g., 10% off) or a fixed amount (e.g., $20 off) and click the add button (✚) and/or Done.

- The discount will automatically update the subtotal and total costs.

💡 **Tips:**

- To remove a discount, click the (x) icon next to the discount. The total cost updates automatically.
- You can add more sales order items after applying discounts, and the discount values will update accordingly.
- To remove an applied percentage or fixed amount discount, click the (x) icon next to the discount. The total cost will adjust automatically.

#### Adding Conditions

13. **Adding Sales Channel, Customer Tier, and Payment Terms:**

- Locate the fields labeled **Click here to add Sales Channel**, **Click here to add Customer Tier**, and **Click here to add Payment Terms** within the sales order.
- Use the web picker to select the appropriate sales channel, customer tier, and payment terms.
- Click Add (+) or Done to save your selections.

💡 **Tip:** To modify the sales channel, customer tier, and payment terms, click "x" next to the item. Then, click **Yes** to confirm deletion. 

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/04_sales_orders_apply_taxes_discounts_conditions.png" width="350" height="300">

#### Adding Custom Attributes

14. **Adding Custom Attributes:**

* Navigate to the Custom Attributes Tab.
    
- Enter Values for each attribute (e.g., **Event Date**: 8/15/2025).

💡 **Tip**: To add a new custom attribute:
    - Click **Options** in the navigation menu.
    - Select **Custom Attribute**.
    - Click **New Record** and enter the name of your custom attribute.
    - Add details, such as the variable and, optionally, the default value.

The new custom attribute will appear in the list thereafter.

### Generate Demand and Invoice
___

14.1.  **Generating Demand:**

- Navigate to **Demand > Generate Demand**.
    - A notification will appear when demand generation starts and completes.
- Click **OK** when the notification appears.
- Click **Save Changes** to finalize the process.

15. **Generating Demand:**

15.1. Navigate to **Demand > Generate Demand** and wait for the process to complete. Click **OK** when finished. Then, click **Save Changes**. 

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/05_sales_orders_generate_demand.png" width="350" height="300">

15.2. 

a. To generate demand asynchronously, click **Generate Demand 2**. This allows you to continue working in other modules while the process runs.

 💡 Tip: To view running asynchronous tasks, go to **Sales Order** > **Order Tab**. In the Options menu, select **Async Tasks**. A list of processes will appear, showing their names, start times, and current statuses. This helps you monitor progress and address any errors.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/21_async_tasks.png" width="350" height="250">

b. When notified that the asynchronous process has started, click **OK**. 

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/19_generate_demand_2.png" width="350" height="300">

c. Once demand generation is complete, click **View Order** to see the generated demand in your sales order.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/20_view_order_generate_demand_2.png" width="350" height="300">

 💡 Tip: To delete all demand records, click **delete all**. Confirm carefully, as this action is irreversible.

16. **Generating Sales Invoice:**

To generate a sales invoice, go to the **Order** tab and click **Confirm**.
    
⚠️ **Important:**

- You cannot generate an invoice until the sales order is confirmed.
- Once a sales order is confirmed, you cannot change the Sales Channel, Customer Tier, or Payment Terms. To undo the confirmation, click **Unconfirm**.
- The **Delete All** button will no longer be available once the order is confirmed.
- The value of both confirmed and unconfirmed sales orders affects the **Total Sales Order** field in the **Customer** module.  
	* To access the **Customer** module, click the customer's name.

Inventory Update
Confirming the sales order updates the inventory.

To view the inventory, click Item Management, then select Products.
In the left pane, select the product from your sales order items.
Once the sales order is confirmed, the values in the Sold and Demand fields will automatically update.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/06_confirm_sales_order.png" width="350" height="300">


- Once the sales order is confirmed, click **Generate Invoice**. Wait for the status to update to **Invoiced: Yes**. Then, click **Save Changes**. 

⚠️ **Important**:

- Only one invoice can be generated per sales order. Once generated, no additional invoices can be created for that order.
- After an invoice has been generated for the order, you can no longer unconfirm the sales order. To proceed, first unconfirm the sales invoice.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/07_generate_invoice.png" width="350" height="300">

- To view the invoice, navigate to the **Main Menu** and select **Invoices**. Use **Find Mode** or **Browse Mode** to locate the customer's name  and view the associated invoices. 

### **Finalize and Print**

17. To print a hard copy of the sales order, click **Print** (🖨️) in the top-right corner of the screen.

**⚠️ Note:** The print layout should include the customer-facing name and description for each item, if available.

18. For a hard copy of the sales order record, click **Print** (🖨️) at the top right of the screen.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/08_finalize_and_print_sales_order.png" width="350" height="300">

Following these steps ensures efficient management and accurate processing of sales orders.

## Definition of Terms

#### Demand

**Demand** refers to the quantity of an item required by a specific date or time. It is categorized by types such as purchase, build, or pick, which dictate how the demand should be fulfilled. Sales orders are a primary source of demand generation.

#### Invoice

An **invoice** is an accounting document issued to customers to record sales transactions and request payment. It specifies prices, quantities, and terms as outlined in the sales order, including any discounts or taxes applied.

#### Products

**Products** are consumable physical items that can be built or purchased, each with pricing (e.g., vendor prices) for picking and selling.

#### Services

Services refer to intangible items the company offers its customers and clients. This includes providing food and beverage solutions tailored to the needs of events or gatherings. It encompasses menu planning, food preparation, delivery, setup, and potentially serving guests during the occasion.
These services are customized to meet the specific needs of each event or gathering.

