<div align="center">
    <img src="img/logo.jpg" height="320" width="830" alt="Odoo Certification">
    <h1>Odoo Certification Preparation</h1>
    <strong> Preparation for Odoo Certification</strong>
</div>

- [1. Introduction](#1-introduction)
- [2. CRM](#2-crm)
- [3. Inventory](#3-inventory)
- [4. MRP](#4-mrp)
- [5. Website \& E-Commerce](#5-website--e-commerce)
- [6. Human Resources](#6-human-resources)
- [7. Timesheets](#7-timesheets)
- [8. Projects](#8-projects)
- [9. Purchase](#9-purchase)
- [10. Accounting](#10-accounting)
- [11. Sale](#11-sale)
- [12. Survey](#12-survey)
- [13. Helpdesk](#13-helpdesk)
- [14. Event](#14-event)
- [15. Odoo Studio](#15-odoo-studio)
- [References](#references)

# 1. Introduction

**Question 1**: When Printing a quote, how does Odoo determine which language to use?

1. Use the language defined in the current user's preferences  
2. Use the language defined on the customer record  
3. Use the language defined by the company of the users

> **Explanation**: In customer, there is a field named language which will effected when printing a customer order, by default this language will select for printing. So the answer is b.

**Question 2**: In a multi-company environment, how do you ensure whether or not the customer is visible for all companies?  

1. This is not possible since every customer belongs to one company  
2. Leave the Company field empty  
3. Check the box "Accessible for Everyone"  
4. I don't know  

 > **Explanation**: In customer record, there is a field named company in Sale and Purchase tab, if you keep this empty for a customer then it will show for all company, and if you select a specific company then this customer will show in that country. So the answer is b.

**Question 3**: If you were on any list, view, how would you display 1000 records at once? 

1. All records are always displayed  
2. By clicking on the page indicator and entering 1-1000  
3. It's not possible, Odoo only display a maximum of 80 records per page  

> **Explanation**: In every tree/list view, there is pagination option where default value is 80, but you can change it whatever value you want to set. So the answer is b.

**Question 4**: How do you access this popup in inventory app? 

1. Start typing the name of the menu you want to access  
2. Control-K  
3. Click the 9-button menu  

> **Explanation**: To see details of the shortcut keys please follow https://www.odoo.com/documentation/17.0/applications/essentials/keyboard_shortcuts.html

**Question 5**: When editing a record in form view, how are mandatory fields distinguished from the non-mandoary field?  

1. The input zone is yellow  
2. The label as a star   
3. The line below the input zone is bold    

> **Explanation**: After click the button save, different version show different message and color change on the mandatory field, some version show red color and some other shows bold line under field. So the answer is C.

**Question 6**: Why are you able to sort by some fields and not others?  

1. You can only sort simple fields, not relational fields   
2. You can only sort on fields that are not computed   
3. You can only sort on fields stored in the database  

> **Explanation**: If some fields value saved in database then that filed will sort on the

**Question 7**: Are building blocks shared across al the themes or specific to each one?  

1. Building blocks are specific to each theme, that's why you start with the theme selection  
2. No, all the themes have the same building block and features  

> **Explanation**: All theme have same building blocks, they are not depends on theme.

**Question 8**: The colors of the shape are dynamic. If your change the presets, will the shape adapt?   

1. Yes, shape adapt automatically  
2. No  
3. Yes, but you have to remove the shape the re-apply it  

> **Explanation**: Color Presets option are available in theme changing blocks, if you change the color from preset then it automatically change the color it affects.  

**Question 9**: Is it possible to hide a building block for a specific language?  

1. Yes, by adding block conditional visibility  
2. No, you can only customize text between languages  

> **Explanation**:  Yes, in building block there is a option named visibility, you can set condition for visibility. So the answer is a.

**Question 10**: How can you add the "customizable cookie bar"  for your website visitor?  

1. By clicking on "customize" white visiting home page  
2. In the website settings  
3. It is not possible to add a cookie bar for visitors  

> **Explanation**: Go to Settings -> Website and configure website and it will appear a cookie option below. Select it and save. So when a user browser on this page it will ask for cookie acceptance. So the answer is b.  

**Question 11**: How can you optimize your title & description for SEO purposes?  

1. Odoo will generate a Titile and Description automatically for SEO bases on the content of your page. You can see the preview in Promote > Optimize SEO and change it if needed   
2. You have to do it manually on each page you create. By going on Promote > Optimize SEO and edit the title and Description of your page preview    

> **Explanation**: Go Website -> Site -> This Page -> Optimize SEO it will show SEO Title and Description option, you can change if default is not suitable for you. So answer is a.  

**Question 12**: Is it possible to animate just a part of a text string  

1. Yes, you can animate any text string, but the text all be the same text type, size and located in the same block/column.    
2. No, you can only animate entire building blocks   

> **Explanation**: yes, it's possible. In theme block option, just click the text you want to edit, and add animation to it from customize. So the answer is a.  

**Question 13**: If you've added the "Newsletter popup" on your website and wish to edit it, how can you find it?  

1. By going into edit mode on your website and waiting a few seconds for the pop-up to appear.  
2. By clicking on "Newsletter Popup" in the "invisible Elements" section at the bottom of the toolbar (in Edit mode)  

> **Explanation**: By clicking on visible property of "Newsletter Popup", as it is not visible by default. So the answer is a.

**Question 14**: Are keyboard shortcuts only available in the backend?

1. Yes  
2. No, they're available in the frontend (ex. Esc to hide top bar)  

> **Explanation**: Shortcuts also available in frontend but they have a limited feature, in frontend you can only use "ESC" and that will show and hide the top bar. So the answer is b.  

**Question 15**: The "Insert in Spreadsheet" button allows the user to:

1. Create a new spreadsheet with the pivot table in it  
2. Insert the pivot table in an existing spreadsheet, as a new sheet  
3. All of the Above  

> **Explanation**: the answer will be both a and b.  

**Question 16**: Where are the spreadsheets saved?  

1. As a file in the Document app  
2. Under the reporting menu of the corresponding app  
3. They are not saved  

> **Explanation**: It will saved under documents apps.  

**Question 17**: How can you manually refresh the values of pivot cells? 

1. Close and re-open the spreadsheet  
2. From the pivot properties panel  
3. All of the above  

> **Explanation**: So both option a and option b is correct.

**Question 18**: Setting up a spreadsheet filter allows you to  

1. Show/hide specific pivots in the spreadsheet  
2. Set a filter on every pivot cell of the spreadsheet  
3. Set formatting rules on pivot cells  

> **Explanation**: So the option will be b and it's correct answer.

**Question 19**: Who can have access to a new spreadsheet?  
a. Its author and the administrator  
b. Anyone who has access to the application from which it originates  
c. Anyone who has access to the workspace the spreadsheet is in  

> **Explanation**: So the option will be C.

# 2. CRM
**Question 1**: How many quotations and orders can you generate from one opportunity?  

1. Several quotations, but only one order  
2. Several quotations, several orders  
3. Only one quotation or order active at the same time  
4. I don't know  

> **Explanation**: An opportunity has option to create several quotation and from every quotation you can create sale order, so option b will be right answer.

**Question 2**: In general, which is more likely to be won, a lead or an opportunity?  

1. Lead  
2. Opportunity  
3. I don't know  

> **Explanation**: Lead is the first option so it comes first then it converted to an opportunity, so everything goes  well then it will converted to quotation and leads. so the option will be B.

**Question 3**: What happens when you click on the little "+" button?

1. It creates a stage that will come after this one.
2. You'll be able to configure the stage
3. It creates an opportunity in this stage
4. I don't know

> **Explanation**:  So creating a new opportunity you have to click on the "+" button. So option will be C.

**Question 4**: Which of the below you cannot use as a Trigger option on Marketing Automation Activity?

1. One day after another activity
2. One hour after a WhatsApp message is opened
3. One day after the email is Opened

> **Explanation**: Option b and it not implemented either.

**Question 5**: Can you add several Mail Templates per Activity on the campaign?

1. Yes, the activity can have multiple Mail Templates
2. No, the activity can have one Mail Template, but I can add another activity with a different Mail Template
3. No, the activity can have one Mail Template, and this Mail Template will be the only one allowed in the whole campaign.

> **Explanation**: Yes, for a campaign you can add several activity and for each activity you can add different single email template. So you can add multiple email template for a campaign but with different activity. So option B is right.

**Question 6**: Can you create more CRM Pipeline Stages?

1. No, Pipeline Stages are fixed per company
2. Yes, the user can create more stages as needed

> **Explanation**: Yes, we can create multiple stages in CRM apps. So option will be B.

**Question 7**: Which of the following statements is FALSE?

1. The user can edit the stage directly from the Pipeline, by choosing Edit Stage From the Setting gear button
2. The user can edit the stage from the Configuration menu, with Developer Mode activated
3. The stages are not editable if there are opportunities on it, they should be moved first then edited.

> **Explanation**: User can edit stages either in developer mode or not in developer mode, so both option will be available, so the answer is option C.

**Question 8**: What is the difference between Leads & Opportunity?

1. A Lead is an initial data gathering without any actions, while an opportunity is a Lead that actions are being taken with it to win it as a customer.
2. No difference, a Lead is an opportunity that didn't received a quotation yet.
3. A lead will become an opportunity once the first meeting is with it.

> **Explanation**: Lead is a data without any action being taken, if you take any action then it will an opportunity. So option A will be the right answer.

**Question 9**: What happens when the user Marks an opportunity as Lost?

1. The opportunity is archived
2. The opportunity is returned to a Lead

> **Explanation**: When an user marks an opportunity lost then it will be archived. So option will be a.

**Question 10**: How many Quotations and Sales Orders could be created for an opportunity?

1. Multiple Quotations, and Single Sales Order
2. Multiple Quotations, and Multiple Sales Orders

> **Explanation**: User can create multiple quotation and sales order from a opportunity. So option will be A.

**Question 11**: What is the below is FALSE regarding the colors on the Stage par?

1. When the user clicks on a color, the opportunities related to it will be the only listed
2. The colors represent the activities planned on these stage opportunities, the Green is future Activities, Orgnge is Today Activities, and Red is Overdue Activities.
3. The colors represent the Expiration of the Quotations on the opportunities, the Green is Unexpired Question, Orange is Quotations expiring Today, and Red is Expired Quotations

> **Explanation**: So the option will be B.

**Question 12**: What are the Opportunities that will appear on the Contact form smart button of the Customer? 

1. The Won and Active opportunities only
2. The Won, Active, and Lost opportunites

> **Explanation**: Option will be B.

**Question 13**: What happens when you click one of the colored bar at the top of the Kanban stage?

1. It highlights opportunities with a specific activity status (Planned, Today, Overdue) in this stage only.
2. Odoo only displays opportunities in that stage that share the same color code which represents its current Activity Status.
3. It only displays opportunities with a specific activity status (Planned, Today, Overdue) for all stages

> **Explanation**: Option will be B

**Question 14:** You want to add a new contact to a company. The company already has an address, and you want to set a different address for its new contact, What do you do? 

1. Starting at the company, add a new contact with the "Other Address" type before entering the new desired address
2.  Starting at the company record, add a new contact with the "Contact" type before entering the new desired address.
3. Create a new contact record with the new desired address filled  in before linking it to the parent company record.

> **Explanation**: Option will be A.

**Question 15**: The little "+" button in kanban is used to?

1. Create a stage that will come after the current one
2. Configure the stage
3. Create an opportunity in this stage

> **Explanation**: It used for creating new opportunity in stages.

**Question 16**: Which of the following is FALSE about the relationship between an opportunity and a customer?

1. You can create a customer after you have won the opportunity
2. Once a record is created, you can no longer create new opportunities for the customer
3.  Opportunities (even won) can exist in the database without a customer.

> **Explanation**: you can create a lead without customer but an opportunity need a customer, so option B is correct.

**Question 17**: The expected revenue  

1. Is computed based on the taxes amount of the sales orders linked to that opportunity  
2. Can only be set when creating the opportunity  
3. Can be set manually at any point  

> **Explanation**: User can set expected revenue at any time whenever needed, so the option C is correct.

**Question 18**: Duplicating an opportunity  

1. Will create an exact copy of the opportunity  
2. Will create an exact copy of the opportunity, and bring it back to the first stage of the pipeline  
3. Will create a copy of this opportunity but it will be set as a lead  

> **Explanation**: It will create a new opportunity with default stage "New". So option B is correct.

**Question 19**: Clicking on this button will:

1. Set the expected closing date in 7 days
2. Add 7 days to the activity deadline
3. Set the activity deadline in 7 days from now

> **Explanation**: If deadline already passed then it set the deadline in 7 days, otherwise it add current deadline value with 7 days and set that value as deadline.

**Question 20**: A user assigned to the access group "Own documents Only" can only work with

1. The leads they are assigned to, in general
2. Only the leads assigned to them by a manager
3. The leads that are either unassigned or assigned to them

> **Explanation**: The leads that are either unassigned or assigned to them, so option C is correct.

**Question 21**: What happens if I click here? 

1. It reloads the page so that I can see new options
2. It manually triggers the auction
3. It switches the assignation mode to automatic

> **Explanation**: User can find this action in settings, it manually triggers action so option B is correct.

**Question 22**: Reporting is access  

1. Only for database admins
2. Only for Managers
3. For all CRM users, but the data is filtered based on their access rights.

> **Explanation**: For all CRM users, but the data is filtered based on their access rights.

**Question 23**: Stages in the pipeline  

1. Can be configured by a user with enough access rights  
2. Can never be changed once Opportunities are created  
3. Can only be changed with the help of a developer  

> **Explanation**: Can be configured with enough access permission. So option a is correct

# 3. Inventory

Question 1: How many stock moves happen when you validate an inventory adjustment?

1. One stock move for the whole inventory
2. One stock move per adjustment line with an undated quantity
3. One stock move per product included the inventory
4. One stock move per location used in the inventory
5. I don't know

> Explanation: It will add a stock move record with an updated value in system, so 1 stock move will count. So option 2 is correct.

Question 2: Where can you define the costing method?

1. On the product
2. On the product category
3. On the company (all products have the same costing method)
4. I don't know

> Explanation: Costing method are define in Product Category. So option 2 is correct.

Question 3: Can you define several reordering rules for the same product?

1. Yes
2. No
3. I don't know

> Explanation: Several reordering rules is not apply for same products. So option 2 is correct.

Question 4: According to the below screenshot, how many variants will be generated for this product?

1. 23 variants
2.  No variant will  be generated, as no stock yet added for the item
3. 192 variants, assuming all attributes Variants Creation Model is instantly

> Explanation: Variant will be multiplied, so if you have 4 attribute and 3 attribute has 4 variant and 1 attribute has 3 variant then their multiplication will be 192. So option 3 is correct.

Question 5: When you have multiple variants available for the product, how can you get the option on the above screenshot on the purchase order?

1. It's automatically available for the attributes with Dynamically creation mode.
2. It's automatically available for the attributes with Instantly creation mode
3. By Activating the Variant Grid Entry on Purchase Setting

> Explanation: There is option available in Sale and Purchase where you can set "Activating the Variant Grid Entry". So option 3 is correct.

Question 6: Is it possible to purchase a Product using different Unit of Measurement?

1. No, each product will have a single Unit of Measure per company
2. Yes, any product can be purchased with any Unit of Measure
3. Yes, but only if it is in the same UOM category

> Explanation: Yes, you can change the UOM only within the same category. So option 3 is correct.

Question 7: Assuming this Product Category configuration, if you increase the stock level on one of its products that has cost on its form, what is the journal entry generated?

1. Debit, Stock Valuation Account, Credit: Stock Input Account
2. Debit: Stock Output Account, Credit: Stock Valuation Account
3. Debit: Stock Input Account, Credit: Stock Valuation Account

> Explanation: So option 1 is correct.

Question 8: If the product (Wood Polish) has an expiration date, how can you control it in the stock?

1. By define a Tracking option on the product and set the Expiration Time, Odoo will count the time based on the current date and it could be changed then stored.
2.  By adding the Expiration Date on the stored units from On Hand quantitties
3. By define a Tracking option on the product and set the Expiration Time, Odoo will count the time based on the current date only then store it.

> Explanation: User can set Expiration Time from individual product and set the expiration duration, and it will effect on product receiving when purchase a product. So option 1 is correct.

Question 9: Can you allocate the Landed Cost based on the Product Weight?
1. No, it could be allocated only equally or by cost
2.  Yes, be select the option and add the weight on the weight field on the Landed Cost line
3. Yes, by selecting the option on the Landed Cost line, and define the product weight on the inventory tab on the Product form

> Explanation: Yes, user can allocate landed cost depending on product weight, so option 3 is correct.

Question 10: If you confirmed a Sales Order with a Product, will it affect the Forecasted quantity of this product?

1. yes, once the Sale is confirmed
2.  Yes, but only if the quantity is Reserved from the stock
3. No, the Forecasted quantity will be updated only when the ordered quantity is moved the stock

> Explanation: yes, it will affect the forecasted quantity when confirm a order. So 2 is correct

Question 11: Which of the below transactions will not affect the Product Forecasted quantity?

1. Confirming a Sales Order with enough quantity on Hand
2. Confirming a Purchase for this product
3. Validating a delivery fro a confirmed Sales Order for this product

> Explanation: Forecasted quantity will affect when confirm a sales order or purchase order but it not affected by validating a sales order or purchase order, So option 3 is correct. 

Question 12: What does it mean if the forecasted quantity of a storable  product is less than a quantity on Hand?

1. Nothing as we don't know the complete history of each product
2. New products are planned to arrive in stock
3. There are probably more outgoing products planned than incoming products

> Explanation: If Quantity on Hand is bigger then Forecasted Quantity then some sale order already confirmed but Quantity on Hand is smaller than Forecasted Quantity then purchased order already confirmed. So option 3 is correct.

Question 13: You have a customer interested in a product of yours that has a supplier deliver lead time that is less than your customer delivery lead time. This is a product that you do not sell often because it is rather expensive. With that in mind, what is the best procurement method for you to manage this product effectively.

1. Use the Master Production Schedule tool
2. You should configure this product as a consumable type
3. You should set this product route to "Make to Order"

> Explanation: User should make this product Make to Order. So option 3 is correct.

Question 14: When should you use "Consumable" as a product type?
1. When managing inventory is not necessary
2. When managing inventory is necessary
3. When selling services

> Explanation: When product don't need to manage stock. So option 2 is correct.

Question 15: What is the "Customer lead time" field used for on the product form?
1. It computes the order date based on the quotation date
2. It computes the delivery order date when the quotation is confirmed
3. It is displayed in the Terms & Conditions of the quotations

> Explanation: Customer Lead Time used in product configuration for quotation order date setting. So option 2 is correct.

Question 16: Can you define several reordering rules for the same product?

1. Yes
2. No

> Explanation: Odoo will check automatically check multiple reordering rules for same product.

Question 17: In a normal situation, the "Customer" location has a positive stock level or a Negative stock level?

1. Negative stock level
2. Positive stock level
3. Should tend to zero

> Explanation: As customer only purchase product so they should have always positive amount. So option 2 is correct.

Question 18: You have 14 units on hand of the products below. If you run the following reordering rule how many units will be ordered?

1. 0
2. 40
3. 48
4. 56

> Explanation: Correct option is 2.

Question 19: If not specifically defined, stock moves are always managed in FIFO?

1. Yes
2. No

> Explanation: Stock removal strategy set on location, from Inventory. Depending on removal strategy product are removed from stock. By default removal strategy is FIFO. So option 1 is correct.


Question 20: When buying a product, when is the quantity on hand of that product increased?

1. When the purchase order is validated
2. When the receipt is validated
3. When the vendor bill is posted

> Explanation: When you buy product it will create a receipt after validating a purchase order and it updates Forecast Quantity and if you validate the receipt then it will update On-Hand Quantity. So option 2 is correct.

Question 21: Is it possible to make conversion between two units of measure from different categories?

1. Yes
2. No

> Explanation: Not actually, basic rules is you can't convert values for two different categories. So option 2 is correct.

Question 22: You have 14 units on hand of the products below. If you run the following reordering rule how many units will be manufactured?

1. 0
2. 40
3. 48
4. 50

> Explanation: As manufacturing depends on Routes and there is not routes set on here, so nothing will create. So option 1 is correct.

Question 23: When performing an inventory adjustment, if you want to apply the counted quantity for several inventory lines at the same time, what will be created?

1. One stock move for the whole inventory adjustment
2. One stock move per adjustment line with an updated quantity
3. One stock move per product included in the adjustment

> Explanation: For every updated quantity it will create an individual stock move. So option 2 is correct.

Question 24: You have a product with a reordering rule of min 5, max 10, to be triggered manually. How can you launch this rule?

1. By clicking on replenish in the product view
2. By clicking on Run Scheduler from the inventory operation menu
3. By clicking order once on the replenishment report
4. All answer are correct

> Explanation: As manual replenishment can done using several ways so all answer is correct. So option 4 is correct.

Question 25: In Odoo is it possible that a company using locations has two products with the same serial number?

1. Yes
2.  No

> Explanation: Odoo has composite unique key with serial no and product, so same product with same serial no is not possible but different product with same serial no is possible in odoo. So option 1 is correct.

Question 26: Regarding inventory adjustment, which of these propositions is FALSE?

1. A transfer with 0 quantity is created when on hand and counted quantity are the same
2. You can set the frequency of counts on product categories
3. The barcode app displays all the counts assigned to you, with a date earlier or equal to today's date
4. None of above is correct

> Explanation: Option 2 is correct.

Question 27: Where can you set up stock valuation accounts?

1. On the product category level and on certain types of locations
2. Only on the product level
3. On the product and product category level
4. Only on the stock locations

> Explanation: User can set stock valuation accounts in Product Category with automated feature and Location where location_type either Inventory loss or production. So option 1 is correct.


Question 28: you have 20 units of a table in stock. 10 of those units belongs to you, and the others 10 belong to their owner, Azure interior. What is your inventory value for those tables if they cost you $500 units?

1. 5000
2. 10000
3. 500

> Explanation: 5000, so option 1 is correct.


Question 29: User have Woodshield as a product that you track by lot, in order to follow expiration dates. Its removal strategy is set to FIFO. You have 40 units in stock, divided into the 4 following lot numbers (10 units of each). If you have to deliver 15 units, which lot number will be automatically reserved by Odoo?

1. 10 units of LOT-001 & 5 units of LOT-002
2. 10 units of LOT-003 & 5 units of LOT-002
3. 10 units of LOT-003 & 5 units of LOT-004

> Explanation: As in FIFO strategy Oldest one will remove first. So option 2 is correct

Question 30: With which costing method can the landed costs be used?

1. AVCO
2. FIFO
3. Both FIFO and AVCO

> Explanation: Product Category must contain costing method either AVCO or FIFO. So option 2 is correct.

Question 31: Regarding this forecast report, assuming none of these sales orders have priority, what will happen if you set your priority on S00113.

1. The most recent sales order will be unreserved, and S00113 will move to the list
2. All reserved deliveries will be unreserved, and 10 units will be reserved for S00113
3. Nothing will happen until reserved quantities are unreserved manually

> Explanation: Nothing will happen until reserved quantities are manually unreserved. So option 3 is correct.

Question 32: I want to move all items that should be picked in WH/stock/shelf1 for internal transfer. What should I do?

1. A batch picking
2. A cluster picking
3. A Wave picking

> Explanation: A batch picking is used for batch transfer. So option 1 is correct.

Question 33: What happens when you validate a delivery order for a customer?

1. It decrements your available stock for this product, but not in any other location
2. It decrements your available stock for this product and increments a customer location.
3. It decrements your stock on hand for this product and increments a customer location

> Explanation: When validate a delivery order it decrements On-hand quantity and increments customer location quantity. So option 3 is correct.

Question 34: When you manually update the quantity on hand of a product via the "Update Quantity" button on the product form view, does it generate a stock move?

1. Yes
2. No

> Explanation: Yes it creates a stock move. So option 1 is correct.

Question 35: Your warehouse is configures to deliver in 3 steps (pick-pack-ship). You have to pick 10 chairs and 5 desks in first step, but you accidentally picked 15 chairs and 2 desks. What will be the result in the pack operation?

1. 15 chars, 2 desks
2. 10 chairs and 5 desk (if no backorder is selected when confirming the picking)
3. 10 chairs, 2 desks
4. 15 chairs, 5 desks

> Explanation: Option 3 is correct.

Question 36: I can't set the capacity on a location by

1. Product
2. Package type 
3. Volume
4. Weight

> Explanation: So option 3 is correct.

Question 37: When inventory move will be created when you do an inventory adjustment to a product from 5 units to 4 units?

1. A move of 4 units from an internal location to an inventory loss location
2. A move of 1 unit from an internal location to an inventory loss location
3. A move of a unit from an inventory loss location to an internal location
4. A move of 4 units from an inventory loss location to an internal location

> Explanation: It create a move which move 1 counted quantity from stock location to inventory adjustment location. So option 2 is correct.

Question 38: You have 20 Drawer Desk on hand, which are configured to be purchased when a client places the order (MTO). If you were to sell 50 units to a customer, how many units will be set on the automatically generated RFQ?

1. 20 units
2. 30 units
3. None of the previous answer

> Explanation: Check Again. So option 3 is correct.

Question 39: I have 5 units of a product in my warehouse, but those 5 units need to be delivered in 6 months. I've just confirmed a sales order for 3 units but can't deliver it now since everything is reserved. Which of these propositions can avoid this situation? 
A. Star the picking of 3 units 
B. Don't set the reservation method to "At Confirmation"
C. Unreserve picking of 5, star picking 3

1. A & B
2. A & C
3. B & C
4. A, B & C

> Explanation: As Delivery picking is set At Confirmation just remove it first then Unreserve the picking. So option 3 is correct.

# 4. MRP
Question 1: Can I continue a manufacturing operation without having to validate a quality check if one is requested?

1. Yes
2. No
3. I don't know

> Explanation: As we can bias the quality check without proper configuration in odoo 17 so, answer may conflict. So option 1/2 both will be correct.

Question 2: Can you define several bill of materials for the same product?

1. Yes
2. No
3. I don't know

> Explanation: We can have multiple BOM for same product, so we can manufacture various types of product. So option 1 is correct.

Question 3: Is it possible to create a routing operation without a work center? 

1. Yes
2. No	
3. I don't know

> Explanation: As routing operation depends on bill of material and work centre so you can't create it without routing operation. So option 2 is correct.

Question 4: Can you define several bill of materials for the same product?

1. Yes
2. No
3. I don't know

> Explanation: We can have multiple BOM for same product, so we can manufacture various types of product. So option 1 is correct.

Question 5: The company (Wood Art) is manufacturing a product (Office Desk), this product consumes wood layers and after it's production, it produces also a (Sawdust), which is sold later to another customer. What option you could use to record this produced (Sawdust)?

1. It will be added manually after the close of the Manufacturing Order
2. It will be defined as a By-Product on the Bill of Material and it will be added automatically with the related Work Order.

> Explanation: First enable by-product features from settings, and after selection configure By-product from Bill of Material and it will create by product from after finish a product in Manufacturing order. So option 2 is correct.

Question 6: If you have a Bill of Material for the product (Desk K12), and you use the Work Center (Assembly Station 1) with this setting in its operation. Assuming no other Work Orders on the Assembly Work Center, what will happen when you confirm MO with 10 units?*

1. Two Work Order will be  created on this Work Center
2. The Expected Duration for the Work Order on this Work Center will be multiplied
3. The Manufacturing Order will not be Planned 

> Explanation: As the operation depends on Work Center capacity and in current work center has only 8 capacity. So option 2 is correct.

Question 7: What is the effect of this defined time on the Work Center?

1. Any Operation on this Work Center will have an extra 30 minutes added to its Expected Duration.
2. The Operation on this Work Center will have an extra 19 minutes added to its Expected Duration.
3. The Operation on this Work Center will have an extra 10 minutes added to its Expected Duration, and the next Operation on the MO will have an extra 20 minutes added to its Expected Duration.

> Explanation: As every work center has startup time and cleanup time so extra time will be startup time + cleanup time. So option 1 is correct.

Question 8: Can you change the Quantity to Produce after the Manufacturing Order is confirmed?

1. No, one confirmed, the MO Quantity can't be changed
2. Yes, by click on the number on the field update the (Quantity to Produce), and Approve
3. Only before the MO is planned, the use can update the quantity

> Explanation: Yes user can change the quantity of the MO after confirm. So option 2 is correct.

Question 9: What is the (CHECK AVAILABILITY) button on the Manufacturing Order will do?

1. It will check the Availability of the Work Centers
2. It will Reserve the Components from the Stock

> Explanation: Check Availability button reserve the component amount from stock. So option 2 is correct.

Question 10: How can you scrap a broken component during the manufacturing process?

1. From the Scrap option on the Manufacturing Order
2. From the Scrap option on the Work Order
3. From the Strap option on the Manufacturing Order or the Work Order

> Explanation: As Scrap option available in both Manufacturing Order and Work Order, so option 3 is correct.

Question 11: When is the MO status is changed to (TO CLOSE)?

1. Only when the Components are consumed
2. Only when the Components are consumed and all Operations are Finished
3. Only when the Quantity Produced is equal to the Quantity to Produce

> Explanation: Only when the component are consumed and all operation are finished. So option 2 is correct.

Question 12: If you produce a product which its Bill of Material has a By-Product, when is the By-Product will be produced?

1. When the Manufacturing Order is Marked as Done
2. Always after the first Work Order is finished
3. After the first Work Order is finished, unless the Operation for the By-Product is configured on BOM, then it will be produced when this operation is Finished


> Explanation: When manufacturing is done then By-Product will generate. So option 1 is correct.

Question 13: If you consumed components more than planned in BOM, is this extra component cost will be added to the finished product cost?

1. Yes, the extra consumption will be added to the finished product cost, and will appear on the MO Cost Analysis
2. No, the extra consumption will be considered as an adjustment loss, but will appear on the MO Cost Analysis

> Explanation: Option 1 is correct.


Question 14: If you have this BOM for the product (Modern Desk). The components cost per unit is $10 for Wood Layer, $70 for Metal Leg, and $120 for Woodshield, and the cost per hour for the Work Centers is $30 for Wood Station, $25 for Assembly Station 1, and $45 for Painting Station. Assuming Automated Inventory Valuation, if you produced 1 unit of Modern Desk with the exact material consumption, and the Real Duration as Expected, what is the cost of this finished unit?*

1. 300
2. 200
3. 260

> Explanation: So equation is (10*3+70*1+120*.5)‎ = 160, (30+25+45)‎ = 100, sum is 160+100‎ = 260. So option 3 is correct.

Question 15: What will happen when you confirm a Sales Order with a product that has a BOM Type "Kit"?

1. A Delivery Order will be created with the components of this BOM
2. A Manufacturing Order will be created to produce this product
3. A Manufacturing Order will be created to product this product, and a Purchase Order will be created to purchase the components of its BOM

> Explanation: It will create a delivery order with BOM component when try to create a sales order. So option 1 is correct.

Question 16: Can you use a Bill of Material with type "Kit" on the Manufacturing Order?

1. Yes
2. No

> Explanation: No, Kit type is not used in Manufacturing Order. So option 2 is correct.


Question 17: What is the (Indirect Demand Forecast) for the Master Desk?*

1. The demand coming from a validated a validated Sales Order with this Product
2. The demand coming from a validated Manufacturing Order for a product where the Master Desk is one of its components
3. The demand needed to fulfill the Forecasted Schedule where the Master Desk is one of its components.

> Explanation: Option 3 is correct.


Question 18: Can you use the Engineering Change Order to update the manufactured product configurations?

1. No, the ECO is used to update the BOM only
2. Yes, ECO is used either to update the Product or its BOM

> Explanation: First install PLM apps. ECO can be used to update Product and its related BOM. So option 2 is correct.

Question 19: Can you apply approvals on the ECO document?

1. Yes, manually add the user and approval type on the ECO Type
2. Yes, manually add the user and approval type on the ECO Stage
3. Yes, manually add the user and approval type on the ECO Document

> Explanation: Yes, it can be manually add user approval in ECO Stage. So option 2 is correct.

Question 20: Once a manufacturing order is validated can you produce more than initially expected?

1. Yes
2. No

> Explanation: Yes, you can add more amount initially expected. So option 1 is correct.

Question 21: What is the purpose of Engineering Change Order?

1. Create customized products based on SOS
2. Manage BOM Versions
3. Modify a manufacturing order

> Explanation: ECO is used to modify Product Configuration and BOM with certain level of approvals. So option 2 is correct.

Question 22: How is the Mean Time to Repair (MTTR) calculated?

1. Total downtime (in days)/ number of breakdowns
2. Total uptime (in days)/number of breakdowns
3. Total time (in days)/number of breakdowns

> Explanation: Total Downtime (in days)/Number of Breakdowns. So option 1 is correct.

Question 23: What type of quality check should I perform if during the same operation, various lots of the same product have to be tested separately?

1. Operation quality check
2. Product type quality check
3. Quantity type quality check

> Explanation: 

Question 24: How can you configure Odoo to automate the creation of preventive maintenance requests?

1. Setup preventive maintenance frequency on the equipment (machine tools)
2. Setup preventive maintenance frequency on the work center
3. Create a meeting type "MRP maintenance" and setup recurring meetings

> Explanation: 

Question 25: In an OEE calculation, whats included in the fully productive time?

1. The recorded working time that does not exceed the expected working time
2. All recorded time on a work order, until it is marked as done
3. All time recorded on the work order during the working schedule of the work center

> Explanation: 
# 5. Website & E-Commerce
# 6. Human Resources

# 7. Timesheets
# 8. Projects
# 9. Purchase
# 10. Accounting

Question 1: Will Odoo allow to create an invoice (with a tax) in a closed tax period?

1. Yes
2. No
3. I don't know

> Explanation: User can find Lock Dates in Accounting -> Actions -> Lock Dates, and user can set Tax Return Lock Date in here. So option 1 is correct.

Question 2: How is the total due by a customer computed?

1. The sum of all unpaid invoices from this customer
2. The balance related to this customer in receivable accounts
3. The sum of invoices minus the sum of payments of this customer

> Explanation: Customer balance may  calculate in different places like invoices, credit notes, and journal entry. So customer balance calculated in receivable account. So option 2 is correct.

Question 3: How many journal items will be create for a customer invoice having 2 lines, and the same 15% tax on each line?

1. 2 journal items
2. 3 journal items
3. 4 journal items
4. 5 journal items
5. I don't know

> Explanation: As for every product sales it will create individual sales line and for tax it will create another line and there is a payable account for all summation. So 4 journal items will be applied. So option 3 is correct.

Question 4: How can you add a Hierarchy for a accounts on the financial reports?

1. By configuring the Group of each account in the Chart of Accounts
2. By using the comparison tools on the reports
3. The Hierarchy is available by default based on the Account Type Hierarchy

> Explanation: By configuring group of each account in the Chart of Account, so option 1 is correct.

Question 5: How can you add an Account Group for the Accounts?

1. Manually select the Group on each account
2. If the account Code is within a Group Prefix it will populate automatically
3. The group is auto-added based on the company localization

> Explanation: Option 2 is correct.

Question 6: When you set the (Outstanding Receipts/Payment Account) on a Bank/Cash journal, should it be configured as Allow (Reconciliation)?

1. No, it will be reconciled any way
2. Yes, so the user will be able to reconcile the Receipt and Payments on the statement

> Explanation: Option 2 is correct.

Question 7: If you want to sell to a client another currency, how you can define the Exchange Rate?

1. The currency will be added to the system first, then the exchange rate will be added on the currency form
2. The currency will be added to the system first, then the exchange rate will be added on the invoice form
3. Multi-currencies option should be activated first, the the exchange rate could be added manually to the current form or generate automatically from the setting

> Explanation: User can set exchange rate from currency option. So option 3 is correct.

Question 8: What is the purpose of the (Not Depreciable Value) on the Asset?

1. It acts as the estimated Salvage Value for the asset, and it will be include in the depreciation schedule
2. It is the extra cost could be spent on the asset life.

> Explanation:  Option 2 is correct.

Question 9: Based on this configuration, what is the value of the first Depreciation that will be computed?*

1. 77.41
2. 77.99
3. 200

> Explanation: Option 1 is correct.

Question 10: Based on this configuration, what is the journal entry generated for the depreciation lines? *

1. Debit: Expense Account, Credit: Fixed Account
2. Debit: Expense Account, Credit: Depreciation Account
3. Debit: Depreciation Account, Credit: Fixed Asset Account

> Explanation: Depreciation journal will be Depreciation will be credited and Expense will be debited. So option 2 is correct.

Question 11: If you have a Computer in your assets and you want to add extra RAM to it, how should you do this action?

1. Be creating a new Asset, and define its parent asset as the Computer
2. Through Modify Depreciation, be define the Reason as new RAM, and add its extra cost to the Depreciation Amount

> Explanation: Option 2 is correct.

Question 12: If you have an asset that will not be used currently, and it will return to service after a while. What option you may use to do this action?

1. Archive the asset when it's out or service, the Unarchive it when it is used again
2. Use the (Pause Depreciation) option to set the asset on Hold, then Resume Depreciation when it's back to service
4. Reset the Asset to Draft when it's out or service, then Confirm it back when it is used again

> Explanation: Select Asset pause option. Option 2 is correct.

Question 13: Can you add an asset using the Declining Depreciation method?

1. No
2. Yes

> Explanation: User can add asset using Declining Depreciation Method. So option 2 is correct.

Question 14: What is the purpose of the Fiscal Position on the customer form?

1. If defined on a customer, you can apply another Tax mapping and Income account for this customer invoices
2. To define the customer Credit Limit

> Explanation: 

Question 15: Based on this approved budget, the Theoretical amount of $97,808.22 means what? *

1. It's actual amount spent for this budget, but its entries are not posted yet
2. It's the amount that was supposed to be spent till now, considering the budget's period and the current date
3. It's the amount of the bills issued for this budget, but it was not paid yet.

> Explanation: Option 2 is correct.

Question 16: When your accounting period is ended, and you have totally finished all your adjustment and reconciliation, how can you prevent anyone from doing any changes including yourself?

1. By using the Lock Dates option and set (lock Date for All Users) to close the period
2. By using the Lock Dates option and set (Lock Date for Non-Advisers) to close the period

> Explanation: Option 1 is correct.

Question 17: When you reconcile a statement, what does this blue line means? *

1. It's a registered payment
2. It's an open Invoice
3. It's a payment with foreign currency

> Explanation: Option 1 is correct.

Question 18: If an Invoice is created in a Tax Locked period, what will happen?

1. The user can't confirm the invoice, and he must change the date to a non-tax locked period
2. The invoice will be posted, but the Accounting Date will be changed to the next available date after the locked period

> Explanation: Option 2 is correct.

Question 19: Assuming this Product Category configuration, if you increase the stock level on one of its products that has cost on its form, what is the journal entry generated?

1. Debit: Stock Valuation Account, Credit: Stock Input Account
2. Debit: Stock Output Account, Credit: Stock Valuation Account
3. Debit: Stock Input Account, Credit: Stock Valuation Account

> Explanation: Option 1 is correct.

Question 20: If a product unit cost is $15, its product category Costing is AVCO, and you want to add 230 units to the stock. What is the Debit value on the Journal Entry generated on that move?

1. No journal entry will be generated
2. It the Product Category has Automated inventory valuation, the value will be $3450
3. If the Product Category has Manual inventory valuation, he value will be $3450

> Explanation: Debit value will be 15*230 = 3,450, and it will insert journal if Automated journal valuation. So option 2 is correct.

Question 21: Where can you define the Stock Valuation Account?

1. On the Product level only
2. On the Product Category Only
3. On the Product level or the Product Category level

> Explanation: Stock valuation account can be define inside product category not individual product. So option 2 is correct.

Question 22: If you change the Cost on the product form, what will occur?

1. A journal entry will be generate to reduce the product cost, assuming Automated inventory valuation
2. A journal entry will be generated to reduce the product cost, assuming Manual inventory valuation
3. A stock move will be generate to reduce the value

> Explanation: If you increase or decrease product cost and product category has automated journal option then it will set stock valuation account. So option 1 is correct.

Question 23: You have 100 units of the Product (Fabric Chair) in your stock, with a unit cost as $120. If you purchased 50 units for $115, which of the below statement is FALSE regarding the unit cost after the receiving?

1. Assuming Automated inventory valuation and Average costing method, the Unit cost will be $118.33
2. Assuming Automated inventory valuation and FIFO costing method, the Unit cost will be $118.33
3. Assuming Automated inventory valuation and Standard costing method, the Unit cost will be $120

> Explanation: 

Question 24: If you sold 30 units from the product (Fabric Chair), will the delivery change the product unit cost?

1. No
2. Yes

> Explanation: Option 1 is correct.

Question 25: Assuming the above configuration, what is the journal entry generated from the stock receipt move? *

1. Debit: Stock Valuation Account, Credit: Stock Input Account
2. Debit: Stock Input Account, Credit: Stock Valuation Account
3. No entry will be generated

> Explanation: No entry will be generated as its has Inventory Valuation manual. So option 3 is correct.

Question 26: How can you prevent the creation or modification of journal entries up to a specific accounting date?

1. By closing a period
2. By setting lock date to lock a fiscal period
3. By posting all journal entries

> Explanation: By setting a lock date to a fiscal period. So option 2 is correct.

Question 27: When editing a new customer invoice, is it possible to automatically define the fiscal position to use based on the customer's country?

1. Yes
2. No

> Explanation: Yes it is possible to define it. So option 1 is correct.


Question 28: Is it possible to configure a declining depreciation of assets?

1. Yes
2. No

> Explanation: Yes user can configure declining depreciation method in individual asset. So option 1 is correct.

Question 29: What happens if an account is managed in a different currency than the company's currency?

1. Odoo stores the debit/credit of all journal items in the account currency only
2. Odoo automatically converts amounts and stores them in the company currency
3. Odoo stores the foreign currency amounts, then stores the converted

> Explanation: Option 3 is correct.

Question 30: What happens if a currency is not set on an account

1. The account can be used for transactions in any currency
2. The account can only be used for transactions in the main company currency
3. It's not possible. A currency is required for each account

> Explanation: Option 1 is correct answer.

Question 31: When using the bank reconciliation tool, what happens if you match a bank statement line with an existing payment?

1. It creates a new journal entry
2. It updates the suspense account of the payment and links the entry to the bank transaction
3. It does nothing as the payment already exists

> Explanation: Option 2 is correct.

Question 32: What will be the result on the next depreciation calculation?

1. Answer A
2. Answer B
3. Answer C

> Explanation: Option 1 is correct.

Reference:  
- https://www.udemy.com/course/odoo-16-certification-preparation/learn/lecture/41070678#overview
  
Question 33: Is it possible to change the reference of a posted journal entry

1. Yes
2. No

> Explanation: Yes, user can change reference of a posted journal entry. So option 1 is correct.

Question 34: What feature should you use to ensure that the right taxes are applied on an invoice based on the customer country?

1. Tax groups
2. Journal groups Account groups
3. Fiscal Positions
4. Incoterms

> Explanation: User can use fiscal position to configure country with customer. So option 3 is correct.

Question 35: In Odoo Accounting, how can you create a new customer invoice or vendor bill?

1. Manuallly
2. By uploading a document
3. By sending an email to an email gateway
4. All of the above

> Explanation: User can create vendor bills using manually, by uploading documents, and by send emails to specific email address. So option 4 is correct.

Question 36: How many charts of accounts can you have?

1. As many as you'd like
2. One per company
3. One per year

> Explanation: If user activate multi company feature, then each company must have one chart of account per company. So option 2 is correct.

Question 37: In which order should lock dates be set for optimal use of Odoo?

1. First, the lock date for non-advisors, then the tax lock date, and eventually, the lock date for all users
2. First, the tax lock date, then the lock date for non-advisors, and eventually, the lock date for all users

> Explanation: First lock tax, then journal entries and lastly for all users. So option 2 is correct.

Question 38: A customer invoice with two different invoice line is posted, both invoices lines are recorded on the same account and are subject to the same 15% tax. How many journal items will be in this invoice?

1. 2 journal iems
2. 3 journal items
3. 4 journal items
4. 5 journal items

> Explanation: 2 journal for 2 product, 1 for tax and 1 for account receivable. So option 3 is correct.

Question 39: What kind of actions can you define when using the payment follow-up levels?

1. Send email
2. Print and send letter
3. Send SMS
4. Only email and letter are possible
5. All are possible

> Explanation: All are possible, so option 5 is correct.

Question 40: What does it mean when you see a blue line item on the bank reconciliation screen?

1. It is showing a registered payment
2. A payment is registered in another currency than the default currency
3. It represents an invoice

> Explanation: Option 1 is correct.

Question 41: How are the total tax amount rounded on an invoice?

1. "Globally" based on the untaxed amount of the invoice
2. "Per line" on each invoice line
3. Either "globally" or "per line" as defined in the app's settings
4. Either "globally" or "per line" as defined in the invoice's options

> Explanation: Option 3 is correct.

Question 42: When are the follow-up actions triggered?

1. A given number of days after the invoice date defined on an invoice
2. A given number of days after the due date defined on an invoice
3. Once a month on a specific day, if the due date defined on the invoice has passed for at least seven days

> Explanation: So option 2 is correct.

Question 43: What happens when you post a vendor bill with an accounting date prior to a locked fiscal period?

1. Odoo does not let you post the vendor bill preventing from creating a journal entry during a locked fiscal period
2. Odoo automatically changes the accounting date to the first applicable date following the lock date and posts the vendor bill
3. The locked fiscal mechanism does not apply here
4. None of the above

> Explanation: Option 2 is correct

Question 44: How is the default income account of a product line determined?

1. It's determined by the journal if none is defined by the product itself
2. It's determined by the product only 
3. It's determined by the journal only
4. It's determined by the fiscal position only

> Explanation: Option 1 is correct.

Question 45: In a normal situation, the "Customer" location has a positive stock level or a Negative stock level?

1. Negative stock level
2. Positive stock level
3. Should tend to zero

> Explanation: When we send product on customer location then it will be positive. So option 2 is correct.
# 11. Sale
# 12. Survey
# 13. Helpdesk
# 14. Event

# 15. Odoo Studio

# References
- 
