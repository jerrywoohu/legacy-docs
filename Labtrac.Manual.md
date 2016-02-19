#Labtrac Team User Guide.

+ **[Welcome](#0)**

+ **[Getting Started](#1.1)**

	- [Adding Dentists](#1.1)
		- [Delivery Methods](#1.1b)
	- [Adding Products](#1.2)
		- [Product Codes](#1.2b)
	- [Adding Materials](#1.3)
		- [Attaching a Material to a Product](#1.3b)
	- [Adding a Job](#1.4)
		- [Entering a Job](#1.4b)
		- [Completing a Job](#1.4c)
		- [Stage Work](#1.4d)
	- [Technicians and Departments](#1.5) (*only relevant to users with the Production Module*)
	
+ **[System Settings](#2)**

	- [Lab Details](#2.1)
	- [System Options](#2.2)
	- [Sugeon Defaults](#2.3)
	- [Financial](#2.4)
	- [Order Enclosures](#2.5)
	- [Footnotes](#2.6)
	- [User Manager](#2.7)
	
+ **[Invoicing and Statements](#3)**

	- [Invoice List](#3.1)
	- [Invoice Manager](#3.2)
	- [Statement Manager](#3.3)
	- [Account Activity](#3.4)
	- [End of Month Guide](#3.5)

+ **[CRM Studio and Backup](#3.6)**
	
+ **[Payment Entry](#4)**

	- [Posting a Payment](#4.1)
	- [Reversing a Payment](#4.2)
	
+ **[Reports](#5)**

+ **[Financial Manager](#6)**


* * *

#<a name=0></a>Welcome to Labtrac

Congratulations on buying your Labtrac software and welcome to the Labtrac family of over 200 Laboratories, in the UK, who have run their systems successfully over the last 20 years.

This document is to give you a guide to the implementation process so you know the sequence of events and particularly what you will need to prepare for.

Some contact numbers that you will find useful;

#####	Labtrac Support/Sales - 03333 449970
***(all calls charged at local rate)***


These Numbers are available during 9:00 to 5:30 Monday to Thursday and 9:00 to 5:00 on Fridays, excluding Bank Holidays.

If any issue is non-urgent then it is best to contact us using the **support@labtrac.com** email, explaining what the issue is and providing any details that you can, as well as Contact names etc. When we need to carry out any training or need to access your system to resolve any issues we have invested in the TeamViewer software package and this allows us to access your system with your permission.


##### 1. Installation of the Labtrac Software

* Firstly we need to install TeamViewer on all PC's which will have Labtrac on. To do this please follow these instructions.

+ Open an internet browser and go to labtrac.com

* Click on the tap in the top right corner called *Support*.

+ Now in this page you will see *Support* again in the middle of the page. Under this it will say *Labtrac Remote Support Client* click this link and it will start a download which you can say *Run* to.

* This will then open the *TeamViewer* Installer. The first thing you will need to enter in this page is *How do you want to use TeamViewer* to which you should select *Both of the above*.

+ Next it will ask you to agree to the tearms of the license.

+ Once you have agreed it will then ask for a password. This should be a password which you can tell the Labtrac Support team.

+ After you have entered the Password then change the name of the PC to your lab name **eg. Knutsford Dental-PC 1** and click *Finish*

* This Process will take 4 or 5 minutes for each PC.

* Once the TeamViewer link is available, the Labtrac Support Team can then proceed to install the latest Labtrac version on your PC and this will take around 20-30 minutes depending on broadband speeds and the modules that you have taken. Once this has been completed we can then start the Labtrac data build stage.

##### 2. Access to Labtrac

By clicking on the Labtrac icon on your desktop you will be presented with the Labtrac sign on screen. Key in the user name, press tab then enter the password. By default both these fields are set to ‘sys’.


![Adding a Dentist](C:\Users\dannysitunes\SharePoint\Home - Shared Documents\Support\Labtrac Manual\Media\Sign In.PNG)


##### Labtrac - Data Build

There is a one-off requirement to enter your Dentist, Products (and prices), and Materials.
These can be done in any order but, generally, we start with the loading of the Dentists information.

###<a name=1.1></a>Adding Dentists

* To add a dentist first we need to click on *Dentist* in the contents bar.

* Now either click *Add* on the top or F2 to bring up the next screen.

* By now you should have have an idea for your dentist codes. Enter that into the *Dentist Code* section and then the full name under *Dentist Name*.

* Here we are met with a few different options. First off we can enter an address.

* Next we can choose whether or not they are a Principal. If they are not a Principal you can select whoever is from the dropdown menu of Surgeons previously entered.

* Assuming that they are the principal you will see the *Invoiced* box has greyed out. This is because the default for the System Parameters is set to Invoice Monthly if however you would like to invoice on delivery you can check that box now.

* Here is also where we can select the *Run*. This is the delivery method which we set up earlier.

* If there is a *Run* that you forgot to enter earlier you can go back and enter one from the Dentist details screen by clicking on the dotted box next to *Run* and it will prompt you, again, to enter details.

* Here it also gives you a *Default Standard* option. In our example we have set these up as NHS, Independent and Private.

* Next we will go to the *Contacts* tab here we can enter the contact name and contact number.

* Then we click on the *Financial* tab and we need to enter a Invoice Address. If the Invoice address is the same as the one we entered on the Details screen you can click the button next to *Invoice Address* to copy it to here.
<a name=a> </a>
* After entering the address we can go to the email tab. Here we can enter the Dentists email and select some preferences such as whether you email the invoice or statement and if a lab is paper light or paperless if you select all these options there is no need for a hard copy of anything at all.

* Now we can click *OK* and the surgeon is entered.

#####Here is a video showing all the steps above...

![Adding a Dentist](C:\Users\dannysitunes\SharePoint\Home - Shared Documents\Support\Labtrac Manual\Media\Adding a Dentist.mp4)

#####<a name=1.1b></a>Delivery Methods

* To set up our delivery methods (how the dentists recieve the work) we first need to DOUBLE click on *Delivery Details* from the content bar.

* This then opens a new window which will be blank. To set up a delivery method click *Add* in the bottom left of the screen.

* Again, this will open a new window from here we need to select a few parameters. We need to select the *Run* number.

* Next we select the *Days* this is the amount of time you want to allow for the job to arrive in surgery after leavin the Lab.

* Now we will go down and write some details in the *Delivery Method* section(eg Postal, Courier, Hand Delivered etc)

In our example we have created run number 1, allowed for 2 days and have named the method Postal. 

![Delivery Method Video](C:\Users\dannysitunes\SharePoint\Home - Shared Documents\Support\Labtrac Manual\Media\Delivery Method.PNG)


* * *


###<a name=1.2></a>Products

#####<a name=1.2b></a>Product Codes

When setting up product codes in Labtrac there are a few things we have to bear in mind;

+ Something else

+ There needs to be a product code for every standard of work that you do. Meaning if you do NHS,Independent and Private work you will need 3 codes for each product. In the example below we have suffixed the same *PBC* (for a Porcelain Bonded Crown) code with a N,I or P depending on the Standard.

	- **PBC-N** for NHS Porcelain Bonded Crown.
	- **PBC-I** for Independent Porcelain Bonded Crown.
	- **PBC-P** for Private Porcelain Bonded Crown.

###<a name=1.2></a>Adding a Products

To add a product fist click on the *Master Products* section in the contents bar. Then click *Add* or F2 to bring up the *New Item* window.

Now we can enter a Product Code and Description and click *Add*. 

This brings up a new window with a few options. 

If this is the first time adding a product we need to set up our *Standard* and *Category*. This is something we will only need to do the first time. At the moment they will have a dropdown box which says *All*. To add to this do the following;

* First click the dotted box next to the dropdown for *Standard*. This will open a new window.

* Next we can type in the *Standard* we would like to set up, in the example we have used *NHS*, *Independent* and *Private*, then click *Add*.

Now we need to do the same for *Categories* 

* First click the dotted box next to the dropdown for *Categories*. This will open a new window.

* Next we need to type in the *Categories* we would like to set up, in the example we have used *Crown and Bridge*, *Prosthetics*, *Orthodontics* and *Misc*. Then click *Add*.

Now going back to the original *Add Product* window we can fill this out;

* Select relevant boxes.

* Choose your *Standard* and *Category*.

* Set up Prices. Labtrac allows you to have up to 40 different prices for each product. If you have different practices or dentist who have different price schemes you can set this up here by typing into the boxes.

* Click *OK* and the product has been entered.

#####Here is a video showing all the steps above...

![Delivery Method Video](C:\Users\dannysitunes\SharePoint\Home - Shared Documents\Support\Labtrac Manual\Media\Adding a Product.mp4)


###<a name=1.3></a>Adding Materials

Now we are going to go through adding materials. In our example we are adding Gold Alloy.

* First go to Materials in the Contents bar.

* Click *Add* or F2 and this will bring up a new window.

* Enter a *Material Code* and *Description*, You may already have your own material code in the example, however, we have used *PGOLD60* for Private Gold Alloy 60%, then click *Add*.

This will have opened a new window where you can enter more details;

* First we can enter the *Cost Price* of this material. This is for your own reference if you would like to record the price you pay for the material.

* The next thing we move to is *Unit of Measure*. Here we put a 1 this is because we our entering our prices for gold per gram.

* We then move to *Standard* where in our cast we select *Private*.

* Then we have the prices which again go from 1 - 40. We have entered 3 different price structures.

* Click *OK* and the Material has been added.


#####<a name=1.3b></a>Attaching a Material to a Product

In our example we have create a Full Gold Crown as a product. This product will always need our Material we then created, Gold Alloy. Now we will show you how to link the two together.

* Go into Master Products in the content bar and either select an existing product or create a new one.

* When we open the product you will see a unchecked box *Record Material* and a dropdown menu. Check the box and select from the dropdown the Material you want to add to the product.

* Click *OK* and that is now added.

Now when it comes to completing a job Labtrac will not allow you to do so without entering the amount, in our case grams, of material used.


* * *


###<a name=1.4></a>Adding a Job

#####<a name=1.4b></a>Entering a Job

Now we will look at adding a job. To add a new job firstly click on 'Live Jobs' in the contents bar.

* To add a new job click this will then open a new window.

* The first thing to do in this new window is enter the patients details.

* Next, on the right hand side, we have the *Surgeon* details.

* Select the *Order Type* in our case we have selected *Private*.

* Select the surgeon from the dropdown menu and the rest will fill in automatically.

* Next we need to enter our dates. Labtrac assumes the date received is todays date. If this is not the case you can change it here by either typing or selecting from the calendar. Then select the date the work is due in surgery.

* We will then go to the *Product* button or F7. this will open a new window which will have all the products that we have set up. Select the one you need from the list and click *OK*, in our case PFGC (Private Full Gold Crown).

* There are a few more things we can do before making the job *Live*. We can select the *Notepad* tab to add notes for the technician. The *Prescription* tab to add further details about the patient, the *Images* tab to add any images sent through from the dentist or the *Surgeon Notes* to add any notes to go back to the dentist with the work.

* Now the job is ready to *Launch* do this by clicking the Launch button or F11.

#####Completing the Job<a name=1.4c></a>


Now we will work through completing the job.

* Open up a job that is ready to be completed.

*  Click on the *Task* button or F10.

* This is where you can tell Labtrac a few different things. Such as the work being *Out on Approval*, *Surgeon Return*, *Hold Job*, *Sub Contract* a job and *Complete Job*.

* Click *Complete Job* this will bring a new window up confirming you want to complete and once confirmed, in our example, it has brought up the *Material Details* because we had attached the Gold Alloy material to a Private Full Gold Crown.

* Now in the window under quantity we can enter the amount you used, in our case it was per gram and in the example we have used 2.5g. That will then calculate the total cost and we can *Save* and *Continue* and the Job is complete.

#####<a name=1.4d></a>Stage Work

Now we are going to go through staging a job.


* The first thing we need to do is to go into *Live Jobs* and click *Add* or F2 to open a new job.

* We can go through all the normal steps for adding a job here. In our example we have added, under *Product* a Bite and a Special Tray.

* Launch the job.

* When the job is ready to be sent out to the dentist for approval we need to reopen our live job. Then we can click *Task* or F10. This will then bring up a dropdown menu. From this select *Send on Approval*. This now tells Labtrac that the job is out with the dentist and no longer in the lab.

* When we receive the work back from the dentist and we are ready to move onto the next stage we can open the job back up and again go to *Task* or F10 and select *Surgeon Return*. It will now prompt us to change the date the work is due back in surgery.

* Now we can **add the new stage** to do this we need to click on the *stage* tab (left of product button) or F5 this now brings up our products and from here you can select which ones apply for the second stage, in our example it is a Try In.

* Now we are ready to send the work back into the lab which we do by clicking *Launch* or F11.

* Again once the work in the lab is complete and ready to be sent back to the dentist we have to reopen the job and select *Send on Approval*.

* When we receive the work back from the dentist we can go back into the job and into *Task* F10 and click *Surgeon return* then select *Stage* and choose from the product list. In our example we have now entered a 1-3 Tooth Denture.

* We can now launch this job and when work is complete in the lab we can then go through and complete the job as normal.

* * * 

###<a name=1.5></a>Technicians and Departments*
(*Only for users with the Production Module)

#<a name=2></a> System Settings

###<a name=2.1></a>Lab Details

+ **Lab Name** - Maximum of 50 characters - used on screens and optionally on external documents.

+ **Lab Address** - This is used on Delivery Notes and Invoices. When filling out this field remember to use **CTRL** and **ENTER** keys together to create a new line.

+ ***MHRA* Number** - The number provided by MHRA qualified labs. This appears on all documentation.

+ **Last Order Number** - This is a numeric or alpha/numeric field of up to 10 characters. The numeric part will be incremednted each time an order is processed. By default it will start at ***J00001***.

+ **Last Delivery Number** - This is a numeric or alpha/numeric field of up to 10 characters. The numeric part will be incremented each time a delivery note is produced. By Default it will start ***D00001***.

+ **Last Purchase Number** - This is a numeric or alpha/numeric field of up to 10 characters. The numeric part will be incremented each time a purchase order is produced. By Default it will start ***P00001***.



###<a name=2.2></a>System Options

+ Order
	- *Include Bin No* -  if checked Labtrac wont allow you to enter a job without entering a Bin Number (Pan Number).

	- *Check if Patient is Already on the System* -

	- *Price Final Stage Only* - 

	- *Job Ticket by Batch* -

	- *Disable Work Ticket Promt*


###<a name=2.3></a>Dentist

+ **Invoice on Delivery** 
 	- If this is set to **YES** the system will produce a *Single Invoice* with every completed job.
 	- If this is set to **NO** then the completed job will be added to a Consolidated Invoice for preparing and printing at the month end.

+ **Copy of Invoice sent to Principal**

	- If this is set to **YES** this means that, for each Associate Dentist (non Principal) the designated Principal will recieve a copy of the Associate's invoice
	- If this is set to **NO** the system will not produce a copy of the Associate's invoice to be sent to the Principal.

+ **Discount Shown on Invoice** 

	- If this is set to **YES** then the value of of the discount offered will be shown on the invoice.
	- If this is set to **NO** the discount will not be shown on the invoice.

***NOTE***  *The value exported to an external accounts package will be the gross value.*

+ **Nominal Code**

	- This is the default nominal code in the external accounts package to which all sales values are assigned.

+ **Payment Details**

	- The default details entered in this section will be placed on any *new* 
Dentist record automatically. This can then be amended on an individual Dentist record if required.
**Days** - The days to be shown on the invoice by which the payment is due.
**Terms** - The payment terms to be shown on the invoice.

+ **Settlement Details** 

	- The default details entered in this section will be placed on any new Dentist record automatically. They can then be amended on the Dentist Details page as required.
**%** - Dicount percentage to apply if settlement made in the stipulated days.
**Days** - The number of days withinwhich the settlement discount will apply.
**Terms** - The settlement terms to be shown on the invoice.

###<a name=2.4></a>Financial

The Laboratory's bank details can be added here but these details are **not used** by the system. These are purely for your reference.

+ **Bank Name** 

	- Name of Laboratory's bank - up to 50 characters

+ **Bank Address**
	- When entering the bank address details the **CTRL** and **Enter** keys need to be pressed together to start a new line.

+ **Sort Code** 
	- The banks sort code needs to be entered in the format **nn-nn-nn**.

+ **Account Number** 
	- The Labortatory's account number at the bank.

+ **Account Name**

	- The name of the Laboratory's bank accouny.

+ **Export Accounts To**
	- If you use an external accounts package (Sage etc) select from the dropdown list to select the system which the system invoice details are to be exported.

+ **Last Invoice Number**
	- Numeric or aplha/numeric field of up to 10 characters; the numeric part of which will be incremented each time an invoice is produced. **eg. I00001**

+ **Last Credit Number** 

	- Numeric or alpha/numeric field of up to 10 characters, the numeric part of which will be incremented each time a credit is raised. **eg. C00001**

+ **Last Transaction Number**

	- This field cannot be amended, it displays the last financial number.

###<a name=2.5></a>Order Enclosures

###<a name=2.6></a>Footnotes

###<a name=2.7></a>User Manager

User manager is the area within Labtrac in which you can set up individual log-ins for your users.

+ To add a new user double click on *User Manager* in the Contents Bar. That will open a new window in which you will see all the current users listed.

+ Click *Add* and this will bring up a *User Details* Page. Now all we have to do is fill the boxes with the correct infomation and click *OK*.

**NOTE: Security level is on a numerical scale from 1-9. **

+ 1 will only allow a user to input jobs. They wont be able to see prices for anything.

+ 5 allows a user to view and enter jobs, products and dentists as well as see any reports that a user with a higher security level allows. 

+ 9 is full acces.

#<a name=3></a>Invoicing and Statements

###<a name=3.1></a>Invoice List

Once you have clicked on the invoice list you will sere a coprehensive list of every invoice you have ever produced. To open any of these invoices up all you have to do is double click on the left hand side of any of the rows. This will then open the invoice report. From here you can reprint an invocie at any time by clicking on the print icon in the top left - this will send to your default printer.

###<a name=3.2></a>Invoice Manager



###<a name=3.3></a>Statement Manager

To produce your statments double click on *Statment Manager*. This will open a new window in the window select the type of statment you would like to run from the list in the left hand side. Next make sure the correct aged debt reference is set. Now click preview to view all of the statments and you can then print. 

	- Date filter - optional date filter to narrow down results.
	- Surgeon Filter - oprtional filter to  produce a statment for a particular dentist.

###<a name=3.4></a>Account Activity

The *Account Activity* section is the area of Labtrac in which you can see an overview and complete history of any account. 

###<a name=3.5></a>End Of Month Guide

###<a name=3.6></a>CRM Studio and Backup Module

#<a name=4></a>Payment Entry

###<a name=4.1></a>Posting a Payment

+ Once we are in Payment Entry find the dentist who you wish to post a payment against and double click on them. This will open a new window which will show all outstanding invoices for this Dentist. 

+ First we need to select what type of payment this is (BACS, Cheque, Credit Note or a Discount) from the list on the left hand side.

+ Next we can enter the *Amount*.

+ Then we can put in a *Reference* and/or *Details* these fields are not mandatory but can help keep track of payment infomation.

+ Next we can set the date the payment has been made.

+ Finally all we need to then do is select the relevant invoice the payment is against and click the check box on the left hand side of that.

+ Once we have all that we can click post in the top right and that is the payment posted.

![Delivery Method Video](C:\Users\dannysitunes\SharePoint\Home - Shared Documents\Support\Labtrac Manual\Media\Payment Entry.PNG)

###<a name=4.2></a>Reversing a Payment

If you find you have entered a payment incorrectly follow these steps to reverse the payment

+ Double click on *Reverse a Payment*. This will bring up a list of all the payments you have entered. Once you have found the relevant payment infomation double click on the left hand side of the row. This will then bring up another payment screen.

+ Once you have opened this you will see a list of all invoices included in the payment. What you need to do is select (by using the check box) the payment which you want to reverse.

**NOTE: You have to select every invoice that was in the original payment entry. You cannot partially reverse a payment.**

+ Now you have selected the relevant invoice numbers click *Update* in the top right which will then produce a message saying the details have been updated.

#<a name=5></a>Reports

#<a name=6></a>Financial Manager

Financial Manager is an area of Labtrac where you can change/edit completed work. It is used as a last resort and it is best not to rely on this feature too heavily.
