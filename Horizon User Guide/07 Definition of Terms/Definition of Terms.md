# **Definition of Terms**

### **Bill of Materials**
A Bill of Materials is akin to a detailed recipe for creating a product. It outlines the necessary parts or materials, their quantities, and how they are assembled. BOMs can accommodate different versions or configurations of the product, although typically only one is used at any given time for production.
### **Configurators**
Configurators offer customers a set of predetermined choices for a specific sales order. These choices are defined in the configurator and allow users to select a specific number of items, totaling a specific quantity from a particular category. Each choice results in a specific sales order item being entered, and the configurator also determines the Bill of Materials (BOM) needed to produce the chosen product.
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
### **Equipment**
Equipment refers to essential items used in various aspects of product creation and order fulfillment. This can range from basic kitchen utensils like plates and knives to larger items necessary for catering social events, such as tables, chairs, and cloths. Equipment is also included in the Bill of Materials, which outlines all necessary items for creating products.
### **Invoices**
Invoices are accounting documents issued to customers and clients to record sales transactions and request payment. They specify the agreed-upon prices, quantities, and terms of the sale as detailed in the sales order and include any discounts and taxes applied.
### **Items**
An item is a basic unit that can be added to orders, including products, configurators, equipment, and discounts. Each type has unique attributes and generates different demand records. All items are categorized in the main item database table.
### **Lead**  
A lead is a recorded instance of a potential customer who has shown interest in a product or service, with details including their name, inquiry specifics, and source of contact. Leads are crucial in sales and marketing as they represent prospects that may convert into customers.

### **Orders**

###### **Pick Order**
A pick order is a directive to retrieve specific items from inventory and transport them to a designated location for processing or assembly. It ensures that all necessary components are collected and prepared for the next stage of production or fulfillment. 
###### **Production Order**
A production order outlines the item to be produced, its required materials, and the production timeframe to ensure resource allocation.
###### **Sales Order**
A sales order initiates fulfilling a customer's request for [products](#products) or [services](#services). Sales order records capture customer details, transaction specifics, and itemized orders, with options for adjusting pricing, applying discounts, and taxes. They enable [demand](#demand) and [invoice](#invoice) generation and allow for printing the record for documentation.
### **Parties**
A party refers to any individual or entity—such as a customer, vendor, or employee—that is associated with the business or organizational record.

### **Products**
Products are consumable physical items that can be created or purchased, each with prices (e.g., vendor prices) for picking and selling.
### **Services**
Services refer to intangible items offered  to customers and clients. This includes providing food and beverage solutions tailored to the needs of events or gatherings. It encompasses menu planning, food preparation, delivery, setup, and potentially serving guests during the occasion.


