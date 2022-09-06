# Release Information

- **Version**:  1.0.2 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR v7.2.0 and above

# What's New
## Bugfixes
- The playbooks included with this solution pack were added in the collection **02 - Use Cases** instead of **02 - Use Case - Symantec Solutions**. After this fix, installation of this solution pack creates a new collection **02 - Use Case - Symantec Solutions** and adds included playbooks in this collection.
- The solution pack document's contents section now includes a global variable `Demo_mode`.
- The playbook **Generate > Symantec Email.Cloud** now appears as **Generate - Symantec Email.Cloud** and adds more details to alerts.
- Fixed the conditions, for finding similar alerts, in the playbook **Investigate and Escalate Symantec Email.Cloud Phishing Alert**
- Removed the playbook **Investigate Symantec EMail.Cloud Alert** as **Extract Indicator** playbook in **03 - Enrich** collection performed the same task.

# Overview

**Symantec Solutions Solutions Pack** helps leverage Symantec Solutions in FortiSOAR by using an integration with Symantec Email Security.cloud. This solution pack provides a set of investigation playbooks to respond to phishing emails reported by Symantec's Email.Cloud.

You can configure the Symantec Email Security.cloud connector &mdash; included with this solution pack &mdash; to ingest emails of type **Phishing** and trigger the response workflow.

# Next Steps 
 
| [Installation](https://github.com/fortinet-fortisoar/solution-pack-symantec-solutions/tree/release/1.0.2/docs/setup.md#installation) | [Configuration](https://github.com/fortinet-fortisoar/solution-pack-symantec-solutions/tree/release/1.0.2/docs/setup.md#configuration) | [Usage](https://github.com/fortinet-fortisoar/solution-pack-symantec-solutions/tree/release/1.0.2/docs/usage.md) | [Contents](https://github.com/fortinet-fortisoar/solution-pack-symantec-solutions/tree/release/1.0.2/docs/contents.md) | 
