# Remove-Unattached-Managed-Disks
Remove Unattached Managed Disks in Azure using PowerShell Script and a list of Disks in a CSV file

Navigate to the customer's Cost Optimization Workbook in Azure Advisor.

Within the workbook, go to the Storage tab and look for Unattached Managed Disks.

Export data to Excel by clicking the download button.

If needed, adapt the exported data. The PowerShell scripts will delete all disks in the exported excel sheet by default, so if you want to keep certain disks, delete the corresponding lines in the excel sheet.

Save the Excel sheet as CSV file. The CSV file will be used as source to the PowerShell script.

Execute/run DeleteIdleDisk.ps1

The script requires the CSV as input and the customer's tenant ID



**Disclaimer**

- This is not official Microsoft documentation or software.
- This is not an endorsement or a sign-off of an architecture or a design.
- This code sample is provided "AS IT IS" without warranty of any kind, either expressed or implied, including but not limited to the implied warranties of merchantability and/or fitness for a particular purpose.
- This sample is not supported under any Microsoft standard support program or service.
- Microsoft further disclaims all implied warranties, including, without limitation, any implied warranties of merchantability or fitness for a particular purpose.
- The entire risk arising out of the use or performance of the sample and documentation remains with you.
- In no event shall Microsoft, its authors, or anyone else involved in the creation, production, or delivery of the script be liable for any damages whatsoever (including, without limitation, damages for loss of business profits, business interruption, loss of business information, or other pecuniary loss) arising out of the use of or inability to use the sample or documentation, even if Microsoft has been advised of the possibility of such damages
