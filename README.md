# Ctse.XrmToolbox.CopyFlow

With this plugin for XrmToolBox you can easily copy (unmanaged and managed) PowerAutomate/Cloud flows inside an unmanaged solution.

## Usage instructions:
* Click on the button "Load solutions", then all unmanaged solutions with a cloud flow will be displayed.
* Select a solution, then all cloud flows inside the solution will be displayed.
* Click on the button "Copy flow", a popup will be shown where you have to fill in the new flow name and if the copied flow should be turned on. The flow will be copied into the same solution with the given name and status.
* Click on the button "Open flow" to open the selected flow inside PowerAutomate.

Note: the user must have the privileges Import Customizations and Export Customizations

Note: Currently you may notice an issue when updating CopyFlow to a newer version. After updating the old version of CopyFlow is still active.
The workaround for now for updating to a new version of CopyFlow is from the Tool Library uninstall the CopyFlow tool and after that install the CopyFlow tool again.
