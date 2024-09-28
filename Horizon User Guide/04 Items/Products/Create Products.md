# Create Products

Products are consumable physical items that can be created or purchased, each with associated prices (e.g., vendor prices) for picking and selling. Clink on the links below to: 

[Add a Product](add-a-product) <br>
[Create a New Product in the Upload Vendor Prices](create-a-new-product-in-the-upload-vendor-services) <br>
[Set Vendor Prices as Inactive](set-vendor-prices-as-inactive) <br>
## Add a Product

### Steps to Add a New Product

1. **Navigate to Products**
    
    - Go to the main menu and select **Products**.
2. **Initiate New Record**
    
    - Click on **New Record**.
3. **Fill in Product Details**
    
    Complete the following fields:

    A.  **Name**: Enter the product name. <br>
    B. **Replenishment Method**: Choose a restocking method (e.g., **build**, **purchase**, **stock**, **pick**). <br>
    C.  **Preferred Vendor**: Select your vendor from the list. <br>
    D. **Stock to Keep**: Set the desired stock level. <br>
    E. **Unit of Measure**: Specify the unit of measurement. <br>
    F. **Best By (Time):** Specify the product's best by time. <br>
    G. **Active BOM**: <br>
        - Check the **Active BOM** box. <br>
        - In the pop-up, choose an item by: <br> 
            - Clicking the **Add** button (✚) or <br>
            - Typing its name in the search box. <br>
        - Click **Done** to return to the main layout. <br>
    H. **Lead Type**: Specify the time needed before fulfilling an order. It will be calculated based on your selections. You can specify lead type in one of the following ways: <br> 
        - **Days in Advance**: Enter the number of days before fulfillment. <br>
        - **Day of the Week**: Enter a number (1-7) for the day(s) of the week, where 1 is Sunday. Separate multiple days with commas. <br>
        - **Day of the Month**: Enter a number (1-31) for the day(s) of the month. Separate multiple days with commas. <br>
	💡 Tips for Setting Lead Time <br>
	- To select multiple days, separate the numbers with commas. <br>
	Examples: 
- **Days of the Week**: Selecting "2" for the day and "15:00" sets the lead time to Monday at 3:00 PM. <br>
- **Days of the Month**: Selecting "31" and "15:00" sets the lead time to the 31st of the month at 3:00 PM. <br>
- **Multiple Days**: Selecting “2, 4” and "15:00" sets lead times for both Monday and Wednesday at 3:00 PM. If the best by time is Thursday, the system defaults to Wednesday for freshness. <br>

	I. **Category**: Choose the category of the product by checking the box next to one of the following options: <br>
		- **Need Pick**: Items requiring manual retrieval for orders. <br>
		- **Consumable**: Items used up after use (e.g., food, supplies). <br>
		- **Sale Item**: Products intended for resale to customers. <br>

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/56_create_products.png" width="350" height="250">

⚠️ Note: If you need to delete a product record: <br>

1. Click **Delete Record**. <br>
2. Confirm your action by selecting **Delete** in the dialogue box. <br>

This will permanently remove the product from your records, so proceed with caution.
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

# Set Vendor Prices as Inactive

To manage outdated pricing information and maintain accurate records, follow these steps:

1. **Access Products Menu**: Navigate to the main menu and click on **Products**.
2. **Select Item Management**: Choose **Item Management**, then click on **All Products**.
3. **Choose the Product**: From the list, click on the specific product you want to modify.
4. **Navigate to Costs**: Switch to the **Costs** tab for the selected product.
5. **Set Prices Inactive**: In the **Active** column, enter 0 to set the vendor price as inactive.


