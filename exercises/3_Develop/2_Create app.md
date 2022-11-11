
**Create an SAP Fiori Application with "Start from template"**


<ol> 
<li>Click on **Start from template** in the Welcome tab to create the project.</li>
Alternative: Open the menu in the top left corner and go to **View > Command Palette ...** and search for ">new project". Select the command **SAP Business Application Studio: New Project from Template**

<img src="/exercises/images/BAS_start.png" width="750">

 <li>In the New Project Wizard select **SAP Fiori Application**.</li>

Click <strong>Start</strong>.

<img src="/exercises/images/Template_Fiori_app.png" width="750">


<li>In the **Floorplan Selection**, choose the following:</li>

For the field **Application Type** choose **SAPUI5 freestyle** from the drop-down.
Select **SAPUI5 Application** as floorplan.

Choose <strong>Next</strong>.

<img src="/exercises/images/Template_UI5.png" width="750">


<li>In the **Data Source and Service Selection** choose **None** for Data source, because we just create a "Hello World" without data binding.</li>

<li>Choose <strong>Next</strong>.</li>

<img src="/exercises/images/Data_Source.png" width="750">


<li>6. Under **Entity Selection** name your SAPUI5 view. This name will appear in the launchpad service for the app. We keep "View1" for now</li>

Choose **Next**.

<img src="/exercises/images/View1.png" width="750">

<li>In the next step, **Project Attributes** choose names and a description for your "Hello World" app (examples see figure):</li>

**Module name**: <code>helloworldui5 </code><br>
**Application title**: <code>Hello World App Title </code><br>
**Application namespace**: <code>sap.btp </code><br>
**Description**: <code>A Fiori Hello World application  </code><br>

**Project folder path** and **Minimum SAPUI5 version** should not be changed

**Add deployment configuration to MTA project**: <code>Yes </code><br>
**Add FLP configuration**: <code>Yes</code><br>
**Configure advanced options**: <code>No</code><br>

Choose **Next**.

<img src="/exercises/images/Template_Project_Attributes.png" width="750">


<li>In the next step, **Deployment Configuration** choose **Cloud Foundry** as a target.</li>

Choose **None** for Destination name.

Choose **Add application to managed application router**?: Yes.
This is the standard html5 repository from launchpad service and eases deployment.

Choose **Next**.

<img src="/exercises/images/Deployment_Config.png" width="750">

<li>The launchpad service needs some Fiori Launchpad Configuration data about the app. Choose names for the entries Semantic Object, Action, and Title (examples see figure)</li
(Optional: For more information about these data and features, see Intent-Based Navigation in a Nutshell).

**Semantic Object**: <code>helloworld </code><br>
**Action**: <code>show </code><br>
**Title**: <code>showhelloworld </code> <br>

<img src="/exercises/images/Fiori_Launchpad_config.png" width="750">

<li>Choose **Finish**.</li

*Note*, that it may take some time until all dependencies are installed.

<li>Click on **Add Project to Workspace**</li>

<img src="/exercises/images/Workspace.png" width="750">

<li>After your App is generated, you should see this page and in the Explorer a new folder "helloworldui5" under HOME.</li>

<img src="/exercises/images/BAS_Project_App_Info.png" width="750">

<li>Open your Projects folder via menu: File > Open Folder ... and enter "/home/user/projects".</li>

<img src="/exercises/images/Open_Projects_folder.png" width="750">
 
<li>Click <strong>OK</strong>.</li>

</ol> 
