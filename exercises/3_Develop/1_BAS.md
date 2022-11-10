
**Open SAP Business Application Studio**

1. Click Instances and Subscriptions under Services 

2. Select the tab Subscriptions, and click on SAP Business Application Studio. You will be forwarded to your SAP Business Application Studio Home Page with automatic login to the application.



3. Please, accept the Privacy Statement



4. Browse the SAP Business Application Studio home page.


 

**Create a Dev Space in SAP Business Application Studio**

1. Click on Create Dev Space on the SAP Business Application Studio home page (or select "My Dev Spaces" if you already have one).



2. Enter a name of your choice for the space (for example, "devdemo") in the upper left corner and choose the application type SAP Fiori (Choosing SAP Fiori eases the creation of a deployable application compared to application type "Basics"). You don't have to select any additional SAP Extensions here. 

3. Click again Create Dev Space in the lower right corner. 

 

You will be forwarded to an overview of your dev space(s).

It may take some time until the newly created dev space is started. Once started the status changes from "STARTING" to "RUNNING” and the dev space name (in this case "devdemo") will turn into a blue hyperlink.

4. Click on the dev space link (e.g. "devdemo") to enter the space.


After a few seconds ...



... you will see the Welcome Page of your dev space:



**Connect your SAP Business Application Studio with your Cloud Foundry Environment**

A connection of your SAP Business Application Studio to your Cloud Foundry subaccount is necessary if you want to deploy your application into your SAP BTP subaccount and make it available. 

**Preparation Steps** 

1. Switch to the SAP BTP cockpit and click on Overview of your subaccount (top left).
2. Check the **API Endpoint** and **Org Name** and your **Space**.


 

**Keep this information in mind** for the next steps (this is especially important if you want to use multiple subaccounts for your SAP Business Application Studio).

 

**Procedure for Connecting**

1. Switch to the tab where you have opened SAP Business Application Studio. In the tabs, click on View in the menu and select Command Palette ... .



2. Search or Select CF: Login to Cloud Foundry.


3. Ensure that the right cloud foundry API endpoint is entered (attention: when you copy&paste the API endpoint from the cockpit, make sure to remove spaces at the beginning or end of the URL).

4. Enter your SAP BTP account Email and Password when prompted. 



5. Select your Cloud Foundry Org (predefined).

6. Select the Space name (predefined).




**Now we have successfully created a connection between your SAP Business Application dev space and your SAP BTP Cloud Foundry space.**
 

 