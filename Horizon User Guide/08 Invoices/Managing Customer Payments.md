# Managing Customer Payments

This guide explains how to process customer payments in the Payment module of Horizon Accounting. It covers the creation and management of payment records for different payment types, including checks, credit cards, ACH transfers, and payment plans. You'll also learn how to define payment terms for invoices. 

* [Payments](#payments)
* [Payment ACH](#payment-ach)
* [Payment Cards](payment-cards)
* [Payment Plan](#payment-plan)
* [Payment Terms](payment-terms)

# Payments

### Create a Payment

1. **Access the Invoice Module**
    
    - In the **Main Menu**, click **Invoices** to open the Invoice module in Horizon Accounting.
2. **Navigate to the Payment Module**
    
    - Click **Payments** to open the Payment module.
3. **Create a New Payment Record**
    
    - In the Payment module, click the **New Record** button.
4. **Select a Customer**
    
    - Click **Party Display Name** to select a customer.
    - In the customer picker, scroll to find the customer's name or enter it in the search field and click the **Search** button 🔎. 
5. **Enter Payment Details**
    
    - Enter the payment details, including the **amount** and **payment type** (choose from Check, Card, or ACH).
        
    - Depending on the selected payment type, provide the following details:
        
        - **For Check:**
            
            - Enter the **Check Number**.
        - **For Card:**
            
            - Select the **Card Type** (choose from Visa, MasterCard, American Express, Discover, Diners Club, or JCB).
            - Enter the **Expiration Date** in MM/YY format.
            - Enter the **Card Number**.
            - Optionally, enter a **Memo**.
        - **For ACH:**
            
            - Select the **Account Type** (Checking or Savings).
            - Enter the **Routing Number** and **Account Number**.
            - Optionally, enter a **Memo**.
### Delete a Payment

6. In the left pane, select the payment record you want to delete.
7. Click **Delete Record**.
8.  In the confirmation dialog, click **Delete** to proceed.

# Payment ACH

### Create an ACH Payment Record

1. In the **Main Menu**, click **Invoices** to open the **Invoice module** in Horizon Accounting.
2. Click **Payments**, then click **Options**, then select **Payment ACH**.
3. Click the **New Record** button.
4. Click **Party Display Name** to select a customer.
5. Enter the ACH details:
    - **Account Type** (Checking or Savings)
    - **Account Number**
    - **Routing Number**
    - **Bank Name**
    - **Memo** (optional)
    - **Last 4 digits** of the account number

### Delete an ACH Payment Record

6. In the left pane, select the ACH payment record you want to delete.
7. Click **Delete Record**.
8.  In the confirmation dialog, click **Delete** to proceed.
# Payment Cards

### Create a Payment Card

1. **Access the Payment Cards Module**

	- From the **Main Menu**, click **Invoices** to open the Invoice module.

2. **Create a New Payment Card**

	- In the **Invoices module**, click **Options** in the secondary navigation menu, then select **Payment Cards.**

3. Click **New Record**.

4. **Select a Customer**

	- Click **Party Display Name** to choose a customer.
	- In the customer picker, either scroll to find the customer’s name or use the **Search** field and click the **Search** button 🔎.

5. **Select a Payment Card Type**

	- Click the **Type** field and choose from the following options:
	    - Visa
	    - MasterCard
	    - American Express
	    - Discover
	    - Diners Club
	    - JCB

6. Enter Payment Card Details

	- Enter the **Card Number**.
	- Enter the **Code** (CVV).
	- Enter the **Expiration Date** in MM/YY format.
	- Enter the **Zip Code**.
	- Enter the **Last 4 digits** of the card number.
### Delete a Payment Card

7. In the left pane, select the payment card you want to delete.
8. Click **Delete Record**.
9.  In the confirmation dialog, click **Delete** to proceed.
# Payment Plan

### Create a Payment Plan

1. **Access the Payment Plans Module**
    
    - In the **Main Menu**, click **Invoices** to open the Invoice module.
    - Click **Payment Plans** to navigate to the Payment Plans module.
2. **Create a New Payment Plan**
    
    - In the Payment Plans module, click the **New Record** button.
3. **Select a Customer**
    
    - Click **Party Display Name** to choose a customer.
    - In the customer picker, scroll to find the customer's name or enter it in the search field and click the **Search** button 🔎.
4. **Select a Sales Order**
    
    - Click the dropdown in the **Sales Order Number** field to select a confirmed order from the list.
5. **Enter Payment Plan Details**
    
    - Enter the **Plan Amount**. Note: The amount cannot exceed the customer’s account balance.
    - Enter the **Number of Payments**.
    - Set the **First Payment Date** and **Last Payment Date**.
6. **Define the Payment Schedule**
    
    - In the **Payment Schedule** section, either manually enter the schedule or click **Generate Schedule** to auto-generate the payment dates and amounts.
    - You can adjust individual schedule dates and amounts as needed.
    - To remove a payment from the schedule, click the **Delete** icon.

### Delete a Payment Plan

7. In the left pane, select the payment plan you want to delete.
8. Click **Delete Record**.
9. In the confirmation dialog, click **Delete** to proceed.

# Payment Terms

The **Payment Terms** section in Horizon Accounting allows you to define and manage the terms for invoice payments. This feature helps set clear expectations for payment deadlines and conditions, ensuring a streamlined billing process and consistent cash flow.

### Create Payment Terms

1. From the **Main Menu**, select **Invoices** to open Horizon Accounting.
2. In the secondary menu bar, click **Options**, then select **Payment Terms**.
3. Click **New Record**. 
4. Enter the following details: 
	*  Terms
	* Description
	* Minimum order amount
	* Due Days
	* Sales Tax
### Delete Payment Terms

5. In the left pane, select the payment term you want to delete.
6. Click **Delete Record**.
7. In the confirmation dialog, click **Delete** to proceed.


