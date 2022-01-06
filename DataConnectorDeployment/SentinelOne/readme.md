# SentinelOne to Microsoft Sentinel

Description: Azure Template to automate deployment of a Function App, Application Insights, App Service Plan, and a Storage account.

The default (automated) deployment process ingests the following logs:

- Activities
- Agents (created)
- Agents (updated)
- Groups (updated)
- Threats (created)
- Threats (updated)
- Alerts (created)

The above cannot be customised in the Function App when deployed. </br>
Following deployment is for a custom use case where only the "Threats" (created and updated) and "Alerts" (created) are ingested into Microsoft Sentinel.


Permissions required:
- TBC

Author: Debac Manikandan

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdark-binary%2FMicrosoftSentinel%2Fmain%2FData%2520Connector%2520Deployment%2FSentinelOne%2Ftemplate.json)
