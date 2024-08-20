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
4. Click the **Customer** box to select party. In the pop-up web picker, type the party's name in the search bar and press **Enter**, or scroll down, then click **Add**.
5. Set **Receive** **Date** and **Start At**; **End At** date is auto-scheduled.
6. **Click to select item** to choose a **Sale Order Item**. In the pop-up picker, type the product name in the **search nam**e bar or type a category as shown in the category column in **search category** bar. Click **Select** after choosing the product, adjust **Quantity**, and click **Done**. 

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/01_create_sales_orders.png" width="350" height="300">

### **Manage Line Items**
___

7. **Adjusting Price and Quantity:**
    
    - Modify the price or quantity of a sales order line item by entering new values. The subtotal and total costs will update automatically.
8. **Deleting Items:**
    
    - Remove individual items by clicking the "x" icon. To delete all items, use the **delete all** option.
9. **Editing Customer-Facing Details:**
    
    - Click the hamburger menu button (☰) to access the item picker.
    - Choose the line item to edit its customer-facing name and description, based on default settings. Adjust the name as needed.
10. **Configuring Sales Order Items:**
    
    - Customize a sales order item by clicking the gear icon (⚙️) and then selecting **DONE** to save your changes.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/03_sales_order_manage_line_items.png" width="350" height="300">

### **Apply Taxes, Discounts, and Conditions**
___
#### Taxes

11. **Making Sales Orders Taxable:**

- Click the **tax** box next to each sales order line item until a checkmark (✔️) appears.
- Taxes will be calculated in real-time, and the additional tax value will automatically reflect in the **total cost** calculation.
#### Discounts

12. **Selecting Discounts:**

- Navigate to the **Discounts** section and click **Select Discount**.
- In the pop-up window, choose either a percentage (e.g., 10% off) or a fixed amount (e.g., $20 off) by clicking the add button (✚) and/or Done.
- The discount will automatically adjust the subtotal and total costs.

💡 **Tips:**

- You can add more sales order items after applying discounts, and the discount values will update accordingly.
- To remove a discount, click on the (x) icon next to the discount, and the total cost will adjust automatically.

#### Adding Conditions

13. **Adding Sales Channel, Customer Tier, and Payment Terms:**

- Locate the respective fields labeled **click here to add sales channel**, **click here to add customer tier**, and **click here to add payment terms** within the sales order.

💡 **Tip:** To modify the sales channel, customer tier, and payment terms, click the delete (x) symbol next to the item you want to change. Confirm the deletion by clicking **Yes** in the dialogue box that appears.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/04_sales_orders_apply_taxes_discounts_conditions.png" width="350" height="300">

### **Generate Demand and Invoice**
___
14. **Generating Demand:**

14.1. Navigate to **Demand > Generate Demand** and wait for the process to complete. Click **OK** when finished. Then, click **Save Changes**. 

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/05_sales_orders_generate_demand.png" width="350" height="300">

14.2. 

a. To run demand generation asynchronously, click **Generate Demand 2**. This lets you work in other modules while the process runs.

 💡 Tip: To view running asynchronous tasks, go to **Sales Order** > **Order Tab** and click on **Async Tasks**. You’ll see a list of all processes with their names, start times, and current statuses, which helps in monitoring completion and handling any errors.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/21_async_tasks.png" width="350" height="250">

b. Click OK when you see the notification that the asynchronous process has started.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/19_generate_demand_2.png" width="350" height="300">

c. After demand generation is complete, click **View Order** in the dialog box to see the generated demand in your sales order.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/20_view_order_generate_demand_2.png" width="350" height="300">

 💡 Tip: To delete all demand records at once, select the **delete all** option. Confirm carefully, as this action is irreversible.

15. **Generating Sales Invoice:**

- Return to the **Order** tab and click **confirm** to initiate the sales invoice generation process.

⚠️ **Note**: Once a sales order is confirmed, changes to Sales Channel, Customer Tier, or Payment Terms cannot be made. To revert, click **unconfirm**.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/06_confirm_sales_order.png" width="350" height="300">

- Click **generate invoice** and wait until the status displays **Invoiced: Yes**. Then, click **Save Changes** located at the bottom of the screen.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/07_generate_invoice.png" width="350" height="300">

- Return to the **Main Menu** and select **Invoices**. Use **Find Mode** or **Browse Mode** to locate the customer's name on the left side. The generated sales invoices for the selected customer will be listed.

### **Finalize and Print**
_____
16. Click **Save Changes** to apply updates.
17. For a hard copy of the sales order record, click **Print** (🖨️) at the top right of the screen.

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