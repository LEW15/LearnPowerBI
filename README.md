# Incidents by severity count

Learn to pull Log Analytic Workspave queried data and display it within Power BI.

At least read access to a Microsoft Sentinel workspace.
An Organizational account BI account that has read access to your Microsoft Sentinel workspace.
Download Power BI Desktop from https://powerbi.microsoft.com/desktop/

Detailed steps as follows:

From Sentinel
1) Browse to Microsoft Sentinel > Logs
2) Write the KQL query as per your requirements and run it. For example;
    SecurityIncident
    | summarize count() by Severity
3) Click on Export > Power BI (as an M query).

From Power Bi Desktop
1) In Power BI Desktop select: 'Get Data' -> 'Blank Query'->'Advanced Query Editor'
2) Paste the M Language script into the Advanced Query Editor and select 'Done
3) Build visual
