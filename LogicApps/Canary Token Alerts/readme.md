# Canary Alerts to Microsoft Sentinel

Description: Azure Sentinel playbook to ingest alerts from Thinkst Canary Platform into Microsoft Sentinel:

• Receive a trigger via a webhook from Canary platform that has the Logic App's Trigger URL

• Parses the received data from webhook

• The parsed data is composed for ingestion into Log Analytics Workspace

• The above is done as two branches since the Canary port number is sometimes treated as integer and is sometimes treated as string.

First branch of the Logic App will treat the Canary port as an integer, and the second branch will treat the Canary port as a string.

Permissions required:
• Azure Sentinel playbook: Azure Sentinel Contributor

Author: Debac Manikandan

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdark-binary%2FMicrosoftSentinel%2Fmain%2FLogicApps%2FCanary%2520Token%2520Alerts%2FIngest-CanaryAlerts.json)
