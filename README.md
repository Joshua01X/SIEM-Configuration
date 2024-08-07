# SIEM-Configuration

## Objective
The objective of this lab project is to set up Microsoft Sentinel, a cloud-native Security Information and Event Management (SIEM) tool, within the Microsoft Azure platform. The goal is to create a comprehensive security monitoring and incident response system that can collect, analyze, and respond to security events in real time.

## Technologies Employed
Microsoft Azure: Cloud computing platform for hosting and managing resources.
Microsoft Sentinel: SIEM tool used for threat detection, investigation, and response.
Log Analytics Workspace (LAW): Central repository for collecting and analyzing log data.
Kusto Query Language (KQL): Query language used in Log Analytics for data analysis.
JSON: Used for configuring workbooks and defining querying conditions.
Geodata Files: Used to enrich data and provide geographic context to incidents.

## Methodologies Followed
### Create the Log Analytics Workspace (LAW):

![image](https://github.com/user-attachments/assets/a1b34751-1393-48d1-93f4-9869a228a051)

- Set up a new Log Analytics Workspace in Azure, which will act as the central repository for all log data collected by Sentinel.
- Ensure proper configuration and resource allocation for efficient data collection and processing.
- Gather required geodata files and JSON configurations.

### Add Sentinel to the Created LAW:

![image](https://github.com/user-attachments/assets/befe9461-0647-404f-be5b-3bdbe63578c7)

- Integrate Microsoft Sentinel with the created Log Analytics Workspace.
- Configure Sentinel to start collecting data from various sources and ensure seamless integration.

### Prepare a Geodata File to Enrich Data:

![image](https://github.com/user-attachments/assets/8c24eb02-eb98-45cd-9171-978d0f0ff6db)

- Download a geodata file containing relevant geographic information.
- Add this geodata file to the Watchlists in LAW to enhance future KQL queries with geographic context.

### Configure Workbooks for Real-Time Incident Mapping:

![image](https://github.com/user-attachments/assets/e8e32b4a-eb27-4c3c-b202-111840bd9b95)

- Prepare a JSON file with the necessary code and querying conditions to visualize incident alert locations in real time.
- Configure workbooks in LAW using the JSON file to present data effectively and enable quick incident response.

### Generate or Import Analytics Rules:

![image](https://github.com/user-attachments/assets/a6131288-824f-45fa-b6fc-b30869cbe49a)

- Create or import pre-defined analytics rules into Sentinel.
- Configure these rules to trigger incident alerts based on specific criteria, ensuring timely detection and response to security events.

## Conclusion
The setup of Microsoft Sentinel in Azure provided key insights and findings: the Log Analytics Workspace centralized log data efficiently, the geodata file enriched log data for detailed geographic analysis, and configured workbooks enabled real-time incident mapping. Predefined analytics rules triggered timely incident alerts, significantly improving threat detection and response. This setup enhanced the overall security posture by making it easier to identify and mitigate threats. The project also provided valuable hands-on experience with cloud-based SIEM tools, log management, security analytics, KQL queries, and the configuration of analytics rules, thereby enhancing practical skills in these areas.
