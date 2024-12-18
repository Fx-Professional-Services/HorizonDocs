# Create Products

Products are consumable physical items that can be built  or purchased, each with associated prices (e.g., vendor prices) for picking and selling. Use the links below to: 

* [Add a Product](add-a-product) <br>
* [Create a New Product in the Upload Vendor Prices](create-a-new-product-in-the-upload-vendor-services) <br>
# Manage Vendor Prices

* [Import Vendor Prices](import-vendor-prices)
* [Set Vendor Prices as Inactive](set-vendor-prices-as-inactive) <br>
## Add a Product

### Steps to Add a New Product

1. **Navigate to Products**
    
    - From the main menu, select **Products**.
2. **Initiate a New Record**
    
    - Click **New Record**.
3. **Enter Product Details**
    
    Complete the following fields:

    A.  **Name**: Enter the product name. <br>
    B. **Replenishment Method**: Select a restocking method (e.g., **build**, **purchase**, **stock**, **pick**). <br>
    C.  **Preferred Vendor**: Select the vendor from the list. <br>
    D. **Stock to Keep**: Set the desired stock level. <br>
    E. **Unit of Measure**: Specify the unit of measurement. <br>
    F. **Best By (Time):** Specify the product's best by time. <br>
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

This action will permanently remove the product from your records, so proceed with caution. To verify the deletion, go to **Item Management**, select **All Items**, click **Find Mode**, and enter the name of the deleted product in the name field. You should see no results.
# Create a New Product in the Upload Vendor Prices

1. **Navigate to Products**: Open the main menu and select **Products**.
2. **Access Upload Vendor Prices**: In the upper left corner, click on **Layout**, choose **User**, then select **Upload Vendor Prices**.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/57_upload_vendor_prices.png" width="350" height="250">

3. **Select Your Party**: Choose your **Party** from the options on the left and click the item field next to it.
4. **Add New Product**: In the upper right corner, tap the add button (✚).

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/58_add_product_upload_vendor_prices.png" width="350" height="250">

5. **Enter Product Details**: Provide the product name, description, replenishment method, and unit of measure. Indicate the product type and select "Yes" or "No" for the following: consumable, sale item, or need pick.
6. **Save Changes**: Click **Save** to confirm your changes and exit the **Quick Add: Product** window.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/59_quick_add_products.png" width="350" height="250">

7. **Verify New Product**: In the items picker, type the product name in the search box and click the search icon (🔎). Your new product should appear in the results.
8. **Complete Process**: Click **Done** to finish. The newly created product will display in the item column next to the party.


# **Manage Vendor Prices**

Efficient management of vendor prices is essential for accurate records. This guide outlines how to import vendor prices and set them as inactive.

## Import Vendor Prices

1. Click **Sales Order** on the main menu.
2. In the top left corner, click the **Options** button, then select **Vendor Prices**.
3. In the **Upload Vendor Prices** layout, click **Import Vendor Price**.
4. Select the file containing the vendor prices, then click **Open**.
5. Specify the import order for the target fields.
6. Click **Import**.
7. Wait for the import to finish. Review the **Import Summary**, then click **OK**.

## Set Vendor Prices as Inactive

To mark outdated prices as inactive:

1. **Access Products Menu**: Click **Products** in the main menu.
2. **Select Item Management**: Choose **Item Management** and click **All Products**.
3. **Choose the Product**: Select the product to modify.
4. **Navigate to Costs**: Click the **Costs** tab.
5. **Set Prices Inactive**: Enter 0 in the **Active** column to deactivate the price.

By following these steps, you can maintain accurate vendor pricing information.


