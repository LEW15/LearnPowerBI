# Incidents by severity count

Learn to pull Log Analytic Workspave queried data and display it within Power BI.
At least read access to a Microsoft Sentinel workspace.
An Organizational account BI account that has read access to your Microsoft Sentinel workspace.
Power BI desktop app.

Detailed steps as follows:

From Sentinel
1) Browse to Microsoft Sentinel > Logs
2) Write the KQL query as per your requirements and run it.
    SecurityIncident
    | summarize count() by Severity
3) Click on Export > Power BI (as an M query).

The exported Power Query Formula Language (M Language ) can be used with Power Query in Power BI Desktop.
For Power BI Desktop follow the instructions below: 
1) Download Power BI Desktop from https://powerbi.microsoft.com/desktop/
2) In Power BI Desktop select: 'Get Data' -> 'Blank Query'->'Advanced Query Editor'
3) Paste the M Language script into the Advanced Query Editor and select 'Done
