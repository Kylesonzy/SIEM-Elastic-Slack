# SIEM-Elastic-Slack
Integrated Elastic Stack SIEM with a Kali Linux VM to demonstrate hands-on security monitoring, including log collection, event analysis, and alert creation. This project showcases skills in configuring security agents, generating security events, and building custom visual dashboards.

# How It's Built
**Technologies Used:** Elastic Stack (Elasticsearch, Kibana), Kali Linux VM, Nmap, Elastic Agent

This project leverages a Kali Linux virtual machine to collect security events and send them to an Elastic Stack SIEM deployment for analysis. The SIEM setup includes collecting and analyzing logs, visualizing security data using dashboards, and configuring alerts to detect anomalous activity. Nmap is used to generate security events, which are then captured by the Elastic agent installed on the Kali VM.

Key steps:
- Created an Elastic Cloud account and deployed an Elasticsearch instance.
- Set up a Kali Linux VM using VirtualBox and configured it for network access.
- Installed the Elastic Agent on Kali to forward logs and security events to the SIEM.
- Generated security events on Kali using Nmap to scan the network for vulnerabilities.
- Used Kibana to query and visualize logs, creating a dashboard to monitor events.
- Set up custom alerts to detect and notify about network activity such as Nmap scans.

# SIEM Usage
The Elastic Stack plays a crucial role in this project, providing real-time monitoring and event management capabilities. By deploying the SIEM, security events generated on the Kali VM can be analyzed, visualized, and logged.

The SIEM setup includes:
- Collecting logs from the Kali VM using the Elastic Agent.
- Analyzing security events, such as network scans, by querying logs in Kibana.
- Creating a custom dashboard to visualize the frequency and types of network events.
- Setting up alerts to notify when specific security events, such as Nmap scans, occur.

# API Usage
The Elastic Agent is used to securely forward logs and data to the Elastic SIEM, making real-time event collection and monitoring possible. Kibana's powerful query engine is used to analyze and display logs, while alerts help ensure timely responses to security events.

Through the SIEM API:
- Logs from the Kali VM are continuously sent to the Elastic platform for analysis.
- Event queries are made to filter specific security events like Nmap scans.
- Dashboards and alerts are configured to monitor network activity in real time.

# Optimizations
Several optimizations were implemented to improve the performance and accuracy of the Elastic SIEM:
- Used advanced Nmap scan types (e.g., `-sS` for stealth scanning) to generate meaningful security events.
- Tuned the Elastic Agent for minimal resource usage on the Kali VM, ensuring efficient log forwarding.
- Created targeted queries and visualizations to filter and display specific event types, reducing noise in the SIEM.

# Lessons Learned
SIEM Configuration: Setting up the Elastic Stack SIEM helped refine my understanding of security monitoring systems. The ability to configure real-time log collection, alerts, and visualizations was invaluable for hands-on learning.

Security Event Generation: Using tools like Nmap to generate real-world security events provided insights into how attackers scan for vulnerabilities and how SIEM systems detect these activities.

Monitoring and Alerts: Creating visual dashboards and custom alerts deepened my understanding of how real-time monitoring and incident response can be managed effectively using SIEM technologies.

# Acknowledgements
Special thanks to the Elastic team for their excellent documentation and open-source tools that made this project possible. Thanks also to the creators of Kali Linux and Nmap for providing the necessary tools to simulate and monitor network security events. The Elastic Agent and Kibana dashboards were critical in demonstrating effective log management and alerting.



