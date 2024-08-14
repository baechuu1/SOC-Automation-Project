# SOC Automation LAB


## PROJECT OBJECTIVE

To gain hands-on experience in implementing various security tools for SOC Automation to detect ongoing threats as a SOC analyst. 


## TOOlS

- Wazuh: An open-source SIEM platform that provides comprehensive security monitoring, log analysis, and threat detection across various systems and environments.
- TheHive: An open-source incident response platform designed for managing, analyzing, and collaborating on security incidents and investigations.
- Shuffle: An automation tool that integrates with various security tools to streamline and automate response actions and workflows.
- Windows VM: A widely used operating system developed by Microsoft, offering a user-friendly interface and extensive compatibility with software applications.
- Mimikatz: A popular open-source tool used for extracting and manipulating authentication credentials on Windows systems, often used in penetration testing and security assessments.
- Digital Ocean: A cloud infrastructure provider offering scalable virtual servers (droplets) and other cloud-based services for deploying and managing applications.
- The VirusTotal: A free online service that analyzes files and URLs for malware and security threats using multiple antivirus engines and other security tools.

## Skills Gained

- SIEM Configuration and Management: Configured and managed Wazuh SIEM for centralized log management and security event analysis.

- Automation of Threat Detection: Set up automated processes using Shuffle to integrate various security tools and workflows.

- Rule Creation and Tuning: Adjusted rule parameters to enhance the effectiveness of automated alerts and responses.

- Incident Analysis and Triage: Developed workflows and procedures for investigating and responding to alerts generated by automated systems.

- Threat Hunting and Detection Strategy: Employed automated detection techniques to identify potential security threats and vulnerabilities.

- Data Correlation and Event Analysis: Correlated security events from multiple sources to gain a comprehensive view of potential threats.




1. ### SOC Automation Lab diagram


<img width="600" alt="SOC Automation lab diagram" src="https://github.com/user-attachments/assets/b9290be3-8f81-4321-b794-3ba75d5fb658">


2. #### Rule defined to detect Mimikatz 


![Screenshot 2024-08-14 094214](https://github.com/user-attachments/assets/2b997627-5d65-4905-8f94-8205ae46ecab)


3. #### Mimikatz detected even if the file name has been changed due to the OriginialFileName rule


![Screenshot 2024-08-14 094437](https://github.com/user-attachments/assets/f336f35a-f50b-46dc-9075-4cce26cc623e)


4. #### Shuffle Workflow


![Screenshot 2024-08-14 143532](https://github.com/user-attachments/assets/99b60bbf-aa9d-43ad-b168-c06bfde05709)


5. #### Alert is created in The hive



![Screenshot 2024-08-14 113756](https://github.com/user-attachments/assets/4b579c63-9cf4-4dbf-a0ef-4a3b294b9b11)![Screenshot 2024-08-14 113728](https://github.com/user-attachments/assets/3c701b7e-b978-4918-9d5a-cbc054bad189)


6. #### Email is sent to SOC Analyst


![Screenshot 2024-08-14 135820](https://github.com/user-attachments/assets/ed04b02d-2c9b-45f5-9032-766195843413)



