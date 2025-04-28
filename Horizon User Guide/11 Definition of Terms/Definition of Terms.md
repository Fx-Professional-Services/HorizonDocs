# **Definition of Terms**

* [Bill of Materials](#bill-of-materials)
* [Configurators](#configurators)
* [Demand](#demand)
	* [Build Demand](#build-demand)
	* [Demand Demand](#demand-demand)
	* [Pick Demand](#pick-demand)
	* [Purchase Demand](#purchase-demand)
* [Equipment](#equipment)
* [Invoices](#invoices)
* [Items](#items)
* [Lead](#lead)
* [Orders](#orders)
	* [Move Order](#move-order)
	* [Pick Order](#pick-order)
	* [Purchase Order](#purchase-order)
	* [Receiving Order](#receiving-order)
	* [Return Order](#return-order)
	* [Sales Order](#sales-order)
* [Parties](#parties)
* [Products](#products)
* [Sales Estimate](#sales-estimate)
* [Services](#services)
### **Bill of Materials**
A Bill of Materials is akin to a detailed recipe for creating a product. It outlines the necessary parts or materials, their quantities, and how they are assembled. BOMs can accommodate different versions or configurations of the product, although typically only one is used at any given time for production.
### **Configurators**
Configurators offer customers a set of predetermined choices for a specific sales order. These choices are defined in the configurator and allow users to select a specific number of items, totaling a specific quantity from a particular category. Each choice results in a specific sales order item being entered, and the configurator also determines the Bill of Materials (BOM) needed to produce the chosen product.
### **Conversion Factor**
A **conversion factor** is a number used to convert between units. You multiply or divide by the factor to switch between units.

**Examples:**

- 1 pound (lb) = 0.453592 kilograms (kg)
- 1 meter (m) = 100 centimeters (cm)

### **Conversion Rate**
A **conversion rate** shows how one unit relates to another. It’s usually expressed as a factor, where you multiply by the rate to convert between units.

**Example:**  
To convert kilograms to pounds, the conversion rate is 2.20462:  
1 kilogram = 2.20462 pounds.  
So, multiply the number of kilograms by 2.20462 to get the equivalent in pounds.

### **Customers**
A **Customer** is a person or organization that purchases or uses the products or services offered by the system.

### **Demand**
Demand represents the quantity of an item required by a specific date or time. It is categorized by types such as purchase, build, or pick, which dictate how the demand should be fulfilled. Sales orders are a primary source of generating demand in this context.

* ###### **Build Demand**  
A quantity needs to be manufactured, assembled, or prepared.
* ###### **Demand Demand**  
A quantity is needed because it is required for use or consumption, indicating that it fulfills an existing demand.
* ###### **Pick Demand**  
A quantity needs to be transferred from one location to another within the organization.
* ###### **Purchase Demand**  
A quantity needs to be procured or bought. The purchase order should be placed 10 days (or 240 hours) before the item is required, accounting for the purchase lead time.

### **Employee**
An **Employee** is a person who works for or is employed by the organization managing or using the system.
### **Equipment**
Equipment refers to essential items used in various aspects of product creation and order fulfillment. This can range from basic kitchen utensils like plates and knives to larger items necessary for catering social events, such as tables, chairs, and cloths. Equipment is also included in the Bill of Materials, which outlines all necessary items for creating products.
### **Invoices**
Invoices are accounting documents issued to customers and clients to record sales transactions and request payment. They specify the agreed-upon prices, quantities, and terms of the sale as detailed in the sales order and include any discounts and taxes applied.
### **Items**
An item is a basic unit that can be added to orders, including products, configurators, equipment, and discounts. Each type has unique attributes and generates different demand records. All items are categorized in the main item database table.
### **Lead**  
A lead is a recorded instance of a potential customer who has shown interest in a product or service, with details including their name, inquiry specifics, and source of contact. Leads are crucial in sales and marketing as they represent prospects that may convert into customers.

### **Opportunities**
An **Opportunity** is a qualified lead with high potential to close, tracking value, status, and probability to help sales teams manage and visualize the full customer journey.

### **Orders**

###### **Move Order**
A **move order** directs the relocation of a specific quantity of items from one location to another within a warehouse. It specifies both the source and destination locations, ensuring items are positioned correctly to fulfill a [pick order](#pick-order) efficiently. 

###### **Pick Order**
A **pick order** is a directive to retrieve specific items from inventory and transport them to a designated location for processing or assembly. It ensures that all necessary components are collected and prepared for the next stage of production or fulfillment. 

###### **Production Order**
A **production order** outlines the item to be produced, its required materials, and the production timeframe to ensure resource allocation.

###### **Purchase Order**
A **purchase order** is used to acquire the necessary items or materials. It tracks the demand, items, and necessary information to complete the order.

###### **Receiving Order**
A **receiving order** is the process of receiving items from a **Purchase Order** and other additional items, ensuring that stock levels are updated to reflect newly-arrived inventory. Follow these steps to create a receiving order:

###### **Return Order**
A **return order** is the process of processing items returned by a customer. This updates the inventory and creates a record of the return. 

###### **Sales Order**
A **sales order** initiates fulfilling a customer's request for [products](#products) or [services](#services). Sales order records capture customer details, transaction specifics, and itemized orders, with options for adjusting pricing, applying discounts, and taxes. They enable [demand](#demand) and [invoice](#invoice) generation and allow for printing the record for documentation.
### **Parties**
A **party** refers to any individual or entity—such as a customer, vendor, or employee—that is associated with the business or organizational record.

### **Products**
**Products** are consumable physical items that can be created or purchased, each with prices (e.g., vendor prices) for picking and selling.

### **Sales Estimate**
A **sales estimate** is a preliminary document outlining potential sales details before converting them into a formal [sales order](#sales-order). It helps forecast and plan future transactions based on customer requirements and estimated costs.
### **Services**
**Services** refer to intangible items offered  to customers and clients. This includes providing food and beverage solutions tailored to the needs of events or gatherings. It encompasses menu planning, food preparation, delivery, setup, and potentially serving guests during the occasion.
### **Units of Measure**
**Units of measure** are standardized quantities used to express and compare different types of measurements, such as weight, length, volume, or time. They provide a consistent way to quantify and communicate physical properties.
### **Vendors**
A **Vendor** is a person or organization that provides goods or services to the organization using the system.


