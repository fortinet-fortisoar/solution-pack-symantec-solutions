| [Home](https://github.com/fortinet-fortisoar/solution-pack-symantec-solutions/tree/release/1.0.2/README.md) | 
|--------------------------------------------|

# Installation

1. To install a solution pack, click **Content Hub** > **Discover**.
2. From the list of solution packs that appears, search for and select **Symantec Solutions**.
3. Click the **Symantec Solutions** solution pack card.
4. Click **Install** on the bottom to begin installation.

## Prerequisites

|Solution Pack|Purpose|
| :- | :- |
|SOAR Framework|Required for Incident Response modules|
|SOC Simulator|Required for Scenario Module and SOC Simulator connector|

# Configuration

For optimal performance of **Symantec Solutions** solution pack, you must configure:

- Symantec Email Security.cloud as a threat intelligence connector to enrich context of a given indicator
    - To configure and use the Symantec Email Security.cloud connector as a source of threat intelligence, refer to [Configuring Symantec Email Security.cloud](https://docs.fortinet.com/document/fortisoar/2.0.1/symantec-email-security-cloud/1/symantec-email-security-cloud-v2-0-1#Configuration_parameters)
- An email ingestion process to periodically read email from a designated inbox and convert them into alerts in FortiSOAR
    - To configure and use the Microsoft Exchange connector for email ingestion, refer to [Configuring Exchange Connector](https://docs.fortinet.com/document/fortisoar/3.4.0/exchange/1/exchange-v3-4-0#Configuring_the_connector)