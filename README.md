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
# 4. MRP
# 5. Website & E-Commerce
# 6. Human Resources

# 7. Timesheets
# 8. Projects
# 9. Purchase
# 10. Accounting
# 11. Sale
# 12. Survey
# 13. Helpdesk
# 14. Event

# 15. Odoo Studio

# References
- 
