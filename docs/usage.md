| [Home](https://github.com/fortinet-fortisoar/solution-pack-symantec-solutions/blob/develop/README.md) | 
|--------------------------------------------|

# Usage

Refer to [Simulate Scenario documentation](https://github.com/fortinet-fortisoar/solution-pack-soc-simulator/blob/develop/docs/usage.md) to understand how to simulate and reset scenarios. 
 
To understand the process FortiSOAR follows to respond to phishing emails using Symantec Solutions, we have included a scenario &mdash; **Symantec Email Cloud** with this solution pack. Refer to the section *Symantec Email Cloud* to understand how this solution pack's automation addresses your needs. 

## Symantec Email Cloud

This scenario generates an example alert of Type *Phishing* in FortiSOAR's **Alerts** module. 

Navigate to the generated alert and note the following:

- Reported Email contains following file information:
    - malware name
    - filename
    - malware category
    - file hash
- Reported Information (sender, email message) is presented for analyzing the case.

**Investigate Symantec EMail.Cloud Alert** : Users can launch **Investigate Symantec EMail.Cloud Alert** playbook from an alert. This playbook performs following automated tasks:

- Creating indicators for File MD5
- Creating indicators for URL
- Creating indicators for Email

**Investigate and Escalate Symantec Email.Cloud Phishing Alert**: Users can launch **Investigate and Escalate Symantec Email.Cloud Phishing Alert** playbook from an alert. This playbook performs following automated tasks:

- Lookup for malicious indicators
- Escalate an alert to an incident
- Find similar alerts
- Mark an incident as a campaign
