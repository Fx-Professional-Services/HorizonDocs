# Start Using Horizon

Welcome to _Horizon_. *Horizon* is designed for tracking [demand](#demand) for all our [products](#products) and [items](#items), enabling us to forecast resource availability accurately. It's important to configure each item correctly before adding it to [sales orders](#sales-orders) to ensure precise demand tracking and effective resource planning.


[Launch Horizon File](#launch-horizon-file)

[Create a Horizon Account](#create-a-horizon-account)

[Log In and Out of Horizon](#log-in-and-out-of-horizon)

[Navigate the Main Menu](#navigate-the-main-menu)

[Reset Your Password](#reset-your-password)

[Delete Your Account](#delete-your-account)

## Launch Horizon File

Follow these steps will launch the Horizon file in FileMaker Pro.

1.  Start the FileMaker Pro application.
2. **Access Hosts Menu**:
    - **Mac**: Go to the top menu bar, select **File**, then **Hosts**.
3. Choose the server hosting your database from the list.
4. Find and click the Horizon file, then confirm by clicking OK.
## Create a Horizon Account

With your Horizon account, you can access all Horizon files, including Parties, [Products](#products), [Sales Orders](#4-sales-orders), [Invoices](#invoices), [Bill of Materials](#6-bill-of-materials), and [Leads](#7-leads). You can create sales orders, generate [demand](#demand), generate invoices, create Bills of Materials, and more.

[Create Your Own Horizon Account](#create-your-own-horizon-account)

[Create an Account for Another User in Horizon](#create-an-account-for-another-user-in-horizon)

### Create Your Own Horizon Account

1. **Open Horizon**: [Follow the steps to launch the Horizon file](#launch-horizon-file).
2. **Add Account**: Click **Add Account** on the login page.
3. **Enter Email**:
    - Type your email username and select your domain.
    - Click **Send Request** to validate.
4. **Confirm Email Sent**: Click **OK**.
5. **Validate Email**:
    - Open the **Request for Horizon Access** email.
    - Copy and paste the link into your browser. <br>
    ⚠️ Link expires in 15 minutes.

6. **Select Privilege**: Choose your privilege (e.g., manager, chef), or your role in the system. <br>

7. **Set Password**: Enter your password and click **Continue**.  <br>
<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/32_create_your_own_horizon_account.png" width="300" height="500">

8. **Enter Details**: Fill in your name and contact info. Select a preferred contact method.  <br>
9. **Save Contact Method:** Tick the **Primary** box and click **Save**.  <br>
10. **Account Created**: Click **OK**. 

### Create an Account for Another User in Horizon
___
##### To create an account for another user if you're logged in to Horizon:

1. **Navigate to Employees:**
    
    - Go to **All Parties** > **Employees** > **New Record**.
2. **Enter Employee Details:**
    
    - Fill in the required fields, including the first name and primary contact method. Click **Save**.
3. **Edit Employee Record:**
    
    - Click on the new record and enter a valid email under **FileMaker user name**.
4. **Assign Privilege:**
    
    - Select a **FileMaker privilege** based on the user's role (e.g., manager, chef). 

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/33_create_account_for_another_user.png" width="350" height="300">
5. **Add Account**:
	* Click **Add Account**.

6. **Email Confirmation**:
    
    - Click **OK** when the **Email Sent** notification appears.
7. **Activate Account:**
    
    - Open the **Request for Horizon Access** email, use the provided link to open FileMaker Pro within 15 minutes, set a new password, and click **Continue**.
8. **Finalize:**
    
    - Click **OK** on the **Account Created** notification.

This process efficiently sets up a new user account in Horizon.
## Log In and Out of Horizon

[Log into Your Horizon Account](#log-into-your-horizon-account)

[Log Out of Horizon](#log-out-of-horizon)
### Log into Your Horizon Account
___
1. **[Launch Horizon file](#launch-horizon-file).**
2. **Open Login Page:**
    - Go to the Horizon login page.
3. **Enter Credentials:**
    - **Account Name:** Enter the email associated with your Horizon account (e.g., xxx@gmail.com).
    - **Password:** Enter your password.

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/34_log_in.png" width="300" height="500">

4. **Log In:**
- Click **Log In** or press **Enter** (Windows) / **Return** (Mac).
##### Troubleshooting Login Issues
- If you have trouble with your password, [reset your password](#reset-your-password).
### Log Out of Horizon
___
#### From the Main Menu:
- Click **Log Out** at the bottom of the main menu.
#### From Other Pages:
- Click **Main Menu** at the top left.
- Then, click **Log Out** at the bottom of the main menu.
## Navigate the Main Menu

The first thing you see when you're logged into Horizon is the _main menu_. Use the menus on the left side to choose commands and perform tasks in the application. 

<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/staging/Horizon%20User%20Guide/00%20Assets/09_main_menu.png" width="400" height="300">

### 1 **All Parties**
Use this menu to navigate through customer, vendor, and employee records, and more.

### 2 **Customers**
Use this menu to manage payment transaction records.

### 3 **Products**
Use this menu to manage all [items](#items) in the system, including [products](#products), [services](#services), [configurators](#configurators), and [equipment](#equipment).

---
#### Items

An item is a basic unit that can be added to orders, including products, configurators, equipment, and discounts. Each type has unique attributes and generates different demand records. All items are categorized in the main item database table.


---
#### Products
Products are consumable physical items that can be created or purchased, each with prices (e.g., vendor prices) for picking and selling.

---

#### Services
Services refer to intangible items offered  to customers and clients. This includes providing food and beverage solutions tailored to the needs of events or gatherings. It encompasses menu planning, food preparation, delivery, setup, and potentially serving guests during the occasion.

---

#### Configurators  
Configurators offer customers a set of predetermined choices for a specific sales order. These choices are defined in the configurator and allow users to select a specific number of items, totaling a specific quantity from a particular category. Each choice results in a specific sales order item being entered, and the configurator also determines the Bill of Materials (BOM) needed to produce the chosen product.

---

#### Equipment
Equipment refers to essential items used in various aspects of product creation and order fulfillment. This can range from basic kitchen utensils like plates and knives to larger items necessary for catering social events, such as tables, chairs, and cloths. Equipment is also included in the Bill of Materials, which outlines all necessary items for creating products.

---
### 4 **Sales Orders**
Select this menu when recording the sale of products or services to a customer. Sales Order records specify the transaction time, specific details of the ordered goods or services, and a comprehensive list of items sold, including any configurations.

### 5 **Invoices**  
Invoices are accounting documents issued to customers and clients to record sales transactions and request payment. They specify the agreed-upon prices, quantities, and terms of the sale as detailed in the sales order and include any discounts and taxes applied.

### 6 **Bill of Materials**
A Bill of Materials is akin to a detailed recipe for creating a product. It outlines the necessary parts or materials, their quantities, and how they are assembled. BOMs can accommodate different versions or configurations of the product, although typically only one is used at any given time for production.
### 7 **Leads**
A lead is a recorded instance of a potential customer expressing interest in a product, service, or opportunity. It includes the individual's name, details of their inquiry (e.g., inquiring for a wedding party), and the source of the lead (e.g., phone call). Additional information such as contact details and specifics about the opportunity they are interested in (e.g., planning a wedding) are also typically included. Leads are pivotal in sales and marketing, representing prospects that may convert into customers with further engagement.

---
#### Demand
Demand represents the quantity of an item required by a specific date or time. It is categorized by types such as purchase, build, or pick, which dictate how the demand should be fulfilled. Sales orders are a primary source of generating demand in this context.

---
### 8 **Re-Login**  
Select this menu if you're asked to log in again due to inactivity or an expired session. This button ensures that only authorized users can access the system and facilitates switching between multiple accounts, maintaining security and convenience.

---

### 9 **Settings**  
Select this option to reset data and display the installed plug-ins when the app starts up.

## Reset Your Password

**To reset your password if you're not logged in to Horizon:** 

1. [Launch Horizon file.](#launch-horizon-file)

2. Enter your **account name** (email) on the Horizon login page.

3. Click **Reset Password**.

4. Click **OK** after receiving the **Email Sent** notification.

5. Open the Horizon email titled **Request for Password Reset**, copy the link, paste it into your browser's address bar, and press Return (Mac) to **Open FileMaker Pro**.

   ⚠️ Note: The link expires in 15 minutes.

6. Enter your new password, deleting any system-generated one if necessary.

   💡 Tip: Use the tab key to move to the next field easily.

7. Click **Change Password**.

8. Click **OK** upon seeing the successful **Password Reset** notification.

**To reset your password if you're logged in to Horizon**:

1. Go to the main menu, and click on **All Parties.**

2.  Click **Employees** tab. 

3. Find your employee record by using **Find Mode** or **Browse Mode** option — scrolling through the list of employees in the left pane. Click on the record to open it. 

4. Click on **Reset Password**.


<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/main/assets/4_reset_password.png" width="350" height="300">
5. Click OK after receiving the email-sent notification.

6. Open the Horizon email titled **Request for Password Reset**, copy the link, paste it into your browser's address bar, and press Return (Mac) to **Open FileMaker Pro**.

	⚠️ Note: The link expires in 15 minutes.

7. Enter your **new password**, if needed, delete any system-generated one.

8. Click **Change Password**.

9. Click **OK** upon receiving the successful **Password Reset** notification.
## Delete Your Account

#### What happens if I permanently delete my Horizon account? 

• You won't be able to reactivate your account. 

• Your employee record and everything else you've added will be permanently deleted. You won't be able to retrieve anything you've added. 
#### Learn how to permanently delete your Horizon account.

⚠️ Note: You cannot delete your Horizon account using your own account. Log in using another user's account to delete yours.

To permanently delete your account:

1. [Log into your account.](#log-into-your-horizon-account)

2. Go to **All Parties** on the main menu.

3. Navigate to the **Employees** tab.

4. Locate and click on the Employee record of the person whose account you want to delete. You can find it by searching their name in **Find Mode** or scrolling through the list in Browse Mode.

5. Click **Delete Account** to remove the employee's account from all Horizon files.
<img src="https://github.com/Fx-Professional-Services/HorizonDocs/blob/main/assets/5_delete_account.png" width="400" height="300">


