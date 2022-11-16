![](../images/Deployment_Config.png)

**Create an SAP Fiori Application with "Start from template"**

1. Click on <strong>Start from template</strong> in the Welcome tab to create the project.
Alternative: Open the menu in the top left corner and go to **View > Command Palette ...** and search for ">new project". Select the command **SAP Business Application Studio: New Project from Template**

![](../images/BAS_start.png)

2. In the New Project Wizard select **SAP Fiori Application**.

Click **Start**.

![](../images/Template_Fiori_app.png)

3. In the <strong>Floorplan Selection</strong> choose the following:

For the field <strong>Application Type</strong> choose **SAPUI5 freestyle** from the drop-down.
Select **SAPUI5 Application** as floorplan.

Choose **Next**.

![](../images/Template_UI5.png)


4. In the **Data Source and Service Selection** choose **None** for Data source, because we just create a "Hello World" without data binding.

5. Choose **Next**.

![](../images/Data_Source.png)


6. Under **Entity Selection** name your SAPUI5 view. This name will appear in the launchpad service for the app. We keep <code>"View1"</code> for now

Choose **Next**

![](../images/View1.png")

7. In the next step, <strong>Project Attributes</strong> choose names and a description for your "Hello World" app (examples see figure):

- Module name <code>helloworldui5 </code>
- Application title <code>Hello World App Title </code>
- Application namespace <code>sap.btp </code>
- Description: <code>A Fiori Hello World application</code>

<strong>Project folder path</strong> and <strong>Minimum SAPUI5 version</strong> should not be changed

- Add deployment configuration to MTA project <code>Yes </code>
- Add FLP configuration <code>Yes</code>
- Configure advanced options <code>No</code>

Choose **Next**.

![](../images/Template_Project_Attributes.png)

8. In the next step, **Deployment Configuration** choose **Cloud Foundry** as a target.

Choose **None** for Destination name.

Choose Add application to managed application router?: <code>Yes</code>.

This is the standard html5 repository from launchpad service and eases deployment.

Choose **Next**.

![](../images/Deployment_Config.png)

9. The launchpad service needs some Fiori Launchpad Configuration data about the app. Choose names for the entries Semantic Object, Action, and Title (examples see figure)
(Optional: For more information about these data and features, see Intent-Based Navigation in a Nutshell).

Semantic Object: <code>helloworld </code>
Action: <code>show </code>
Title: <code>showhelloworld </code> 

![](../images/Fiori_Launchpad_config.png)

10. Choose <strong>Finish</strong>

*Note*, that it may take some time until all dependencies are installed.

11. Click on <strong>Add Project to Workspace</strong>

![](../images/Workspace.png)

12. After your App is generated, you should see this page and in the Explorer a new folder "helloworldui5".

![](../images/BAS_Project_App_Info.png)

13. Open your Projects folder via menu: File > Open Folder ... and enter "/home/user/projects".

![](../images/Open_Projects_folder.png)
 
14. Click <strong>OK</strong>.

