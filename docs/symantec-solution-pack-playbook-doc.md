# FortiSOAR Symantec Solutions Solution Pack – Out-of-the box Playbooks Collections

The FortiSOAR™ Symantec Solutions Solution Pack (solution-pack-symantec-solutions). This solution pack enables users to experience the power and capability of FortiSOAR™ incident response for Symantec Solutions. This solution pack provides capabilities that show case the Symantec Cloud SOC use case.

## Ingestion Playbook Collection
You can use the playbooks in the *01 – Ingest* collection to perform various operations such as fetching incident details, using Symantec Could.

Following is a table that lists the playbooks that are part of the “**01 - Ingest**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|Symantec CloudSOC - Fetch Incidents|Fetch Cloud.SOC Alerts|
|2|Symantec CloudSOC - Fetch Incidents - Create Single Alert|Create single alert for Symantec incidents|


## Use Cases Playbook Collection
You can use the playbooks in the *04-Use Cases* collection to understand and perform various tasks or steps needed to deal with an incident, such as a Phishing attack or a Brute Force Attempt.

Following is a table that lists the playbooks that are part of the “**04-Use Cases**” collection in the Solution Pack:


|**Sr. No.**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|Investigate and Escalate Symantec Email.Cloud Phishing Alert|Investigates an alert ingested from Symantec Email.Cloud of type ‘Phishing’, and escalates the alert to an ‘Incident’ if indicators associated with the alert are found to be ‘Malicious’.|
|2|Investigate Data Leakage Alert (Symantec CloudSOC)|Investigates a data leakage alert that is ingested from Symantec CloudSOC and performs containment and remediation tasks if sensitive data is leaked.|
|3|Investigate Symantec EMail.Cloud Alert|Investigate data leakage alert  ingested from Symantec CloudSOC|
|4|Remediate Malware Alert (Symantec EDR / ATP)|Remediate malware alert by blocking malicious entities|
