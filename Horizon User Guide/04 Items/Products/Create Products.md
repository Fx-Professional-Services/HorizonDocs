# Create Products

Products are consumable physical items that can be built  or purchased, each with associated prices (e.g., vendor prices) for picking and selling. Use the links below to: 

* [Add a Product](#add-a-product) <br>
* [Create a New Product in the Upload Vendor Prices](#create-a-new-product-in-the-upload-vendor-prices) <br>
## Add a Product

### Steps to Add a New Product

1. **Navigate to Products**
    
    - From the main menu, select **Products**.

2. **Initiate a New Product Record**
    
    - Click **New Record** to begin adding a product.
    
3. **Enter Product Details**
    Complete the following fields:

	A. **Name**: Enter the product name.
	
	B. **Replenishment Method**: Choose a restocking method from the following options: **Build**, **Purchase**, **Stock**, or **Pick**.
    
	C. **Preferred Vendor**:
            1. Click the **Preferred Vendor** field.
            2. In the vendor picker, either scroll to find the vendor's name or use the **Search** field.
            3. Click the **Search** button 🔎 to search for a vendor.<br>
	D. **Stock to Keep**: Set the desired stock level. <br>
	E. **Unit of Measure**: Specify the unit of measurement. <br>
	F. **Best By (Time):** Specify the product's best-by time. <br>
	G. **Active BOM**: Select an active Bill of Materials (BOM) for demand generation.
	* Click the **Active BOM** field.
	- In the pop-up, choose an item by:
	    * Clicking the **Add** button (✚), or
	    * Typing the item's name in the search box.
	    * Click **Done** to return to the main layout.<br>

	H. **Lead Type**: Specify the time required before fulfilling an order. The lead time is calculated based on your selection: <br> 
        - **Days in Advance**: Enter the number of days before fulfillment. <br>
        - **Day of the Week**: Enter a number (1-7) for the day(s) of the wee (1 = Sunday). Separate multiple days with commas. <br>
        - **Day of the Month**: Enter a number (1-31) for the day(s) of the month. Separate multiple days with commas. <br>
	💡 Tips for Setting Lead Time: <br>
	- To select multiple days, separate the numbers with commas. <br>
	- Example 1: For **Days of the Week**: Selecting "2" for the day and "15:00" sets the lead time to Monday at 3:00 PM. <br>
	- Example 2: For **Days of the Month**: Selecting "31" and "15:00" sets the lead time to the 31st of the month at 3:00 PM. <br>
	- Example 3: For **Multiple Days**: Selecting “2, 4” and "15:00" sets lead times for both Monday and Wednesday at 3:00 PM. If the best-by time is Thursday, the system defaults to Wednesday for freshness. <br>

	I. Subtypes: Select the item subtype by checking the box next to one of the following options: <br>
		- **Need Pick**: Items requiring manual retrieval for orders. <br>
		- **Consumable**: Items used up after use (e.g., food, supplies). <br>
		- **Sale Item**: Products intended for resale to customers. <br>
	**⚠️ Note:** To verify if the item subtypes match your selections in the product layout: 
	1. Go to **Item Management** > **All Items**. 
	2. Click **Find Mode** to find the item from the left pane. 
	3. The selected item subtypes should be appear Yes, reflecting your earlier choices. 
	
<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/56_create_products.png" width="350" height="250">

⚠️ **Note:** To delete a product record:

1. Click **Delete Record**.
2. Confirm your action by selecting **Delete** in the dialog box.

⚠️ **Warning**: This action will permanently remove the product from your records, so proceed with caution. To verify the deletion, go to **Item Management**, select **All Items**, click **Find Mode**, and enter the name of the deleted product in the name field. You should see no results.

## Create a New Product in the Upload Vendor Prices

Follow these steps to create a new product in the **Upload Vendor Prices** through the picker window: 

1. **Navigate to Products**  
    From the main menu, select **Products**.
    
2. **Access Upload Vendor Prices**  
    In the upper-left corner, click **Layout**, then select **User**. From the dropdown, choose **Upload Vendor Prices**.
    
<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/57_upload_vendor_prices.png" width="350" height="220">

3. **Select the Party**  
    On the left, choose your **Party**, then click the item field next to it.
4.  **Add a New Product**  
    In the upper-right corner, click the **Add** button (✚).

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/58_add_product_upload_vendor_prices.png" width="350" height="250">

5. **Enter Product Details**  
    Fill in the following fields:
    
    - **Product Name**
    - **Description**
    - **Replenishment Method**
    - **Unit of Measure**  
        Then, specify whether the product is a **Consumable**, **Sales Item**, or **Need Pick** by selecting "Yes" or "No."
6. **Save the Product**  
    Click **Save** to apply your changes and close the **Quick Add: Product** window.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/59_quick_add_products.png" width="300" height="200">

7. **Search for the Product**  
    In the items picker, type the name of the product in the search box and click the search icon **(🔎)**. Your newly added product should appear in the search results.
    
8. **Finalize the Product**  
    Click **Done** when you find the desired product. The newly created product will be displayed in the item column next to the selected party.
# Manage Vendor Prices

Efficient management of vendor prices is essential for accurate records. This guide outlines how to import vendor prices and set them as inactive.


[Import Vendor Prices](import-vendor-prices) <br>
[Set Vendor Prices as Inactive](set-vendor-prices-as-inactive) <br>
[Set Active Vendor Price to Inactive During Import](set-active-vedor-price-to-inactive-during-import) <br>
## Import Vendor Prices

To import vendor prices:

1. Click **Sales Order** on the main menu.
2. In the secondary navigation tabs, click the **Options** button, then select **Vendor Prices**.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/90_vendor_prices.png" width="350" height="250">

3. In the **Upload Vendor Prices** layout, click **Import Vendor Price**.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/91_import_vendor_prices.png" width="350" height="250">

4. Select the file containing the vendor prices, then click **Open**.
5. Specify the import order for the target fields.
6. Click **Import**.
7. Wait for the import to finish. Review the **Import Summary**, then click **OK**.

## Set Vendor Prices as Inactive

To mark outdated prices as inactive, follow these steps:

1. **Access the Products Menu**  
    Click **Products** in the main menu.
    
2. **Select Item Management**  
    Choose **Item Management**, then click **All Products**.
    
3. **Choose the Product**  
    Select the product from the left pane for which you want to modify the price.
    
4. **Navigate to the Costs Tab**  
    Click the **Costs** tab to view the price details.
    
5. **Set the Price as Inactive**  
    In the **Active** column, enter **0** to deactivate the price.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/92_set_vendor_prices_inactive.png" width="350" height="220">

By following these steps, you can keep your vendor pricing information up-to-date and accurate.

## Set Active Vendor Price to Inactive During Import

1. Navigate to **Sales Order** > **Options** > **Vendor Prices**.
2. In the upper right corner, click **Import Vendor Price**.
3. Specify the **Import Order** for the target fields.  
    **Note**: The **Source Fields** should match the **Target Fields**.
4. Click **Import**.
5. In the **Import Summary**, click **OK** to confirm the import.

To display the toolbar:

- Press **Option + Command + S** (on Mac) or **Control + Alt + S** (on Windows).
- Click **Show All**.

This will:

- Automatically set the previously active vendor prices to inactive in the related data of the imported vendor price.
- Update the prices based on the new vendor prices uploaded to the system.

## Enter Details in Upload Vendor Prices

Follow these steps to input product details in the **Upload Vendor Prices**:

1. **Navigate to Products**  
    Open the main menu and select **Products**.
    
2.  **Access Upload Vendor Prices**  
    In the upper-left corner, click **Layout**, select **User**, then choose **Upload Vendor Prices**.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/93_access_upload_vendor_prices.png" width="350" height="200">

3. **Select Your Party**  
    Choose your **Party** from the options on the left.
    
4. **Enter Product Details**  
    Input the following details:
    
    - **Item Quantity**
    - **Item Unit**
    - **Vendor Quantity**
    - **Vendor Unit**

5. **Verify the New Product**  
    In the item picker, type the product name in the search box and click the search icon (🔎). The new product should appear in the results.
    
6. **Complete the Process**  
    Click **Done** to finish. The newly created product will appear in the item column next to the **Party**.

#### Definition of Terms

##### Need Pick

An item flagged as "Need Pick" is retrieved from inventory based on a pick order and transported to a designated location for processing or assembly.
##### Consumable

An item flagged as "Consumable" is intended to be used up or depleted over time.

##### Sale Item

An item flagged as a sale item is available for purchase, distinguishing it from items not intended for sale.