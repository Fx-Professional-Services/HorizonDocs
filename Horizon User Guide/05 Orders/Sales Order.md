# Sales Orders

A sales order initiates fulfilling a customer's request for [products](#products) or [services](#services). Sales order records capture customer details, transaction specifics, and itemized orders, with options for adjusting pricing, applying discounts, and taxes. They enable [demand](#demand) and [invoice](#invoice) generation and allow for printing the record for documentation. Follow these streamlined steps for efficient sales order management:

[Create a Sales Order](#create-a-sales-order) <br>
[Manage Line Items](#manage-line-items) <br>
[Apply Taxes, Discounts, and Conditions](#apply-taxes-discounts-and-conditions) <br>
[Finalize and Print](#finalize-and-print) <br>
[Definition of Terms](#definition-of-terms)
### **Create a Sales Order**
___
1. Ensure the customer's record exists. If not, [create a new customer record](https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/03%20Customers/Create%20and%20Manage%20Customer%20and%20Payment%20Records.md).
2. Navigate to **Sales Orders** in the main menu. 
3. Click **New Record**. 
4. Click the **Customer** box to select party. In the picker, type the party's name in the search bar and press **Enter**, or scroll down, then click **Add**.
5. Set **Receive** **Date** and **Start At**; **End At** date is auto-scheduled.
6. **Click to select item** to choose a **Sale Order Item**. In the picker, type the product name in the **search nam**e bar or type a category as shown in the category column in **search category** bar. Click **Select** after choosing the product, adjust **Quantity**, and click **Done**. 

**💡 Tip:** Refine your item search by entering a category name in the **Category** field in the item picker.

**⚠️ Note:** When you add a line item in sales order, the customer-facing name and description will be automatically displayed if available. 

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/01_create_sales_orders.png" width="350" height="300">

### **Manage Line Items**
___

7. **Adjusting Price and Quantity:**
    
    - Modify the price or quantity of a sales order line item by entering new values. The subtotal and total costs will update automatically.
8. **Deleting Items:**
    
    - Remove individual items by clicking the "x" icon. To delete all items, use the **delete all** option.

	 💡 Tip: To delete a product from a sales order, click **Item Management** and then **Products**. Find the product in the left pane, click **Delete Record**, and confirm with **Delete**.
	
9. **Editing Customer-Facing Details:**
    
    - Click the hamburger menu button (☰) to access the item picker.
    - Choose the line item to edit its customer-facing name and description, based on default settings. Adjust the name as needed.
    
10. **Configuring Sales Order Items:**
    
    - **Customize a Sales Order Item**: Click the gear icon (⚙️) and then selecting **DONE** to save your changes.
    
	  💡 Tip: To search for items by category in the item picker, cick on the order line items to open the item picker viewer. In the category column, enter keywords found in the category. This search will return results based on the entered keywords within the category.
    

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/03_sales_order_manage_line_items.png" width="350" height="300">

### **Apply Taxes, Discounts, and Conditions**
___
#### Taxes

11. **Making Sales Orders Taxable:**

A. Click the expand button (**>**) next to the customer’s name.  
B. In the customer layout, go to the **Customers** tab.  
C. Enter the tax rate.  
D. Return to your sales order and click the **Tax** box next to each line item until a checkmark (✔️) appears.  
E. Taxes will be calculated in real time, and the additional tax value will automatically update the **total cost**.

#### Discounts

12. **Selecting Discounts:**

- Navigate to the **Discounts** section and click **Select Discount**.

- In the pop-up window, choose either a percentage (e.g., 10% off) or a fixed amount (e.g., $20 off) by clicking the add button (✚) and/or Done.

- The discount will automatically adjust the subtotal and total costs.

💡 **Tips:**

- 
- To remove a discount, click the (x) icon next to the discount. The total cost updates automatically.

#### Adding Conditions

13. **Adding Sales Channel, Customer Tier, and Payment Terms:**

- Locate the respective fields labeled **click here to add sales channel**, **click here to add customer tier**, and **click here to add payment terms** within the sales order.

💡 **Tip:** To modify the sales channel, customer tier, and payment terms, click the delete (x) symbol next to the item you want to change. Confirm the deletion by clicking **Yes** in the dialogue box that appears.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/04_sales_orders_apply_taxes_discounts_conditions.png" width="350" height="300">

#### Adding Custom Attributes

14. Adding Custom Attributes

* **Navigate to the Custom Attributes Tab**.
    
- **Enter Values**: For each custom attribute, input the corresponding value (e.g., **Event Date:** 8/15/2025).

💡 **Tip**: To add a new custom attribute:
    - Click **Options** in the navigation menu.
    - Select **Custom Attribute**.
    - Click **New Record** and enter the name of your custom attribute.
    - Add details, such as the variable and, optionally, the default value.

The new custom attribute will appear in the list thereafter.


### **Generate Demand and Invoice**
___
14. **Generating Demand:**

14.1. Navigate to **Demand > Generate Demand** and wait for the process to complete. Click **OK** when finished. Then, click **Save Changes**. 

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/05_sales_orders_generate_demand.png" width="350" height="300">

14.2. 

a. To run demand generation asynchronously, click **Generate Demand 2**. This lets you work in other modules while the process runs.

 💡 Tip: To view running asynchronous tasks, go to Sales Order > Order Tab. In the Options button at the far right of the layout, select Async Tasks. A list of processes will appear, showing their names, start times, and current statuses. This helps you monitor progress and address any errors.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/21_async_tasks.png" width="350" height="250">

b. Click OK when you see the notification that the asynchronous process has started.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/19_generate_demand_2.png" width="350" height="300">

c. Once demand generation is complete, click **View Order** in the dialog box to see the generated demand in your sales order.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/20_view_order_generate_demand_2.png" width="350" height="300">

 💡 Tip: To delete all demand records at once, select the **delete all** option. Confirm carefully, as this action is irreversible.

15. **Generating Sales Invoice:**

To generate a sales invoice, return to the **Order** tab and click **Confirm**.
    
⚠️ **Notes**:
    
- A sales invoice cannot be generated unless the sales order is confirmed.
- Once a sales order is confirmed, you cannot change the Sales Channel, Customer Tier, or Payment Terms. To revert the confirmation, click **Unconfirm**.
- After confirmation, the **Delete All** button will no longer be available for removing line items.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/06_confirm_sales_order.png" width="350" height="300">


- If the sales order is confirmed, click **Generate Invoice** and wait for the status to update to **Invoiced: Yes**. Then, click **Save Changes** at the bottom of the screen.

⚠️ **Important**:

- Only one invoice can be generated per sales order. Once generated, no additional invoices can be created for that order.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/07_generate_invoice.png" width="350" height="300">

- Return to the **Main Menu** and select **Invoices**. Use **Find Mode** or **Browse Mode** to locate the customer's name on the left. The sales invoices for the selected customer will be listed.

### **Finalize and Print**
_____
16. Click **Save Changes** to apply updates.
17. To print a hard copy of the sales order record, click **Print** (🖨️) in the top right corner of the screen.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/08_finalize_and_print_sales_order.png" width="350" height="300">

Following these steps ensures efficient management and accurate processing of sales orders.

## Definition of Terms

#### Demand

Demand represents the quantity of an item required by a specific date or time. It is categorized by types such as purchase, build, or pick, which dictate how the demand should be fulfilled. Sales orders are a primary source of generating demand in this context.

#### Invoice

Invoices are accounting documents issued to customers and clients to record sales transactions and request payment. They specify the agreed-upon prices, quantities, and terms of the sale as detailed in the sales order and include any discounts and taxes applied.

#### Products

Products are consumable physical items that can be created or purchased, each with prices (e.g., vendor prices) for picking and selling.

#### Services

Services refer to intangible items the company offers its customers and clients. This includes providing food and beverage solutions tailored to the needs of events or gatherings. It encompasses menu planning, food preparation, delivery, setup, and potentially serving guests during the occasion.
