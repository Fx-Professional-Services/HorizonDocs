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

    A.  **Name**: Enter the product name.
    B. **Replenishment Method**: Choose a restocking method (e.g., **build**, **purchase**, **stock**, **pick**).
    C.  **Preferred Vendor**: Select your vendor from the list.
    D. **Stock to Keep**: Set the desired stock level.
    E. **Unit of Measure**: Specify the unit of measurement.
    F. **Best By (Time):** Specify the product's best by time.
    G. **Active BOM**:
        - Check the **Active BOM** box.
        - In the pop-up, choose an item by:
            - Clicking the **Add** button (✚) or
            - Typing its name in the search box.
        - Click **Done** to return to the main layout.
    H. **Lead Type**: Specify the time needed before fulfilling an order. It will be calculated based on your selections. You can specify lead type in one of the following ways:
        - **Days in Advance**: Enter the number of days before fulfillment.
        - **Day of the Week**: Enter a number (1-7) for the day(s) of the week, where 1 is Sunday. Separate multiple days with commas.
        - **Day of the Month**: Enter a number (1-31) for the day(s) of the month. Separate multiple days with commas.
	💡 Tips for Setting Lead Time
	- To select multiple days, separate the numbers with commas.
	Examples: 
- **Days of the Week**: Selecting "2" for the day and "15:00" sets the lead time to Monday at 3:00 PM.
- **Days of the Month**: Selecting "31" and "15:00" sets the lead time to the 31st of the month at 3:00 PM.
- **Multiple Days**: Selecting “2, 4” and "15:00" sets lead times for both Monday and Wednesday at 3:00 PM. If the best by time is Thursday, the system defaults to Wednesday for freshness.

	I. **Category**: Choose the category of the product by checking the box next to one of the following options:
		- **Need Pick**: Items requiring manual retrieval for orders.
		- **Consumable**: Items used up after use (e.g., food, supplies).
		- **Sale Item**: Products intended for resale to customers.




### Deleting a Product Record

To delete a product record:

- Click **Delete Record**.
- Confirm by selecting **Delete** in the dialogue box.
# Create a New Product in the Upload Vendor Prices

1. **Navigate to Products**: Open the main menu and select **Products**.
2. **Access Upload Vendor Prices**: In the upper left corner, click on **Layout**, choose **User**, then select **Upload Vendor Prices**.
3. **Select Your Party**: Choose your **Party** from the options on the left and click the item field next to it.
4. **Add New Product**: In the upper right corner, tap the add button (✚).
5. **Enter Product Details**: Fill in the product name, description, and replenishment method.
6. **Modify Item Fields**:
    - **Item Quantity**
    - **Item Unit**: Click the add button (✚) next to it, select a unit of measure, then click **Done**.
    - **Vendor Quantity**
    - **Vendor Unit**: Click the add button (✚) next to it, select a unit of measure, then click **Done**.
7. **Save Changes**: Click **Save** to confirm your changes and exit the **Quick Add: Product** window.
8. **Verify New Product**: In the items picker, type the product name in the search box and click the search icon (🔎). Your new product should appear in the results.
9. **Complete Process**: Click **Done** to finish. The newly created product will display in the item column next to the party.

# Set Vendor Prices as Inactive

To manage outdated pricing information and maintain accurate records, follow these steps:

1. **Access Products Menu**: Navigate to the main menu and click on **Products**.
2. **Select Item Management**: Choose **Item Management**, then click on **All Products**.
3. **Choose the Product**: From the list, click on the specific product you want to modify.
4. **Navigate to Costs**: Switch to the **Costs** tab for the selected product.
5. **Set Prices Inactive**: In the **Active** column, enter 0 to set the vendor price as inactive.


