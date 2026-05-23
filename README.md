# Home-SOC-Lab
Built a Home SOC Lab using VirtualBox, Windows 11, Sysmon, and Event Viewer to generate and analyze endpoint telemetry.
# Home SOC Lab

## Objective
Built a Home SOC Lab to gain hands-on experience with endpoint monitoring, event logging, and security analysis using VirtualBox, Windows 11, Sysmon, and Event Viewer.
## Tools Used
- VirtualBox
- Windows 11
- Sysinternals Sysmon
- Windows Event Viewer
- Command Prompt
- PowerShell
## Lab Setup
- Created a Windows 11 virtual machine
- Installed Sysmon for endpoint telemetry
- Verified Sysmon logs in Event Viewer
- Generated endpoint activity for analysis
## Activity Generated
Commands executed:
- whoami
- ipconfig
- ping google.com
- netstat -ano
- tasklist
- nslookup google.com
## Events Reviewed
- Event ID 1 — Process Creation
- Event ID 3 — Network Connection
- Event ID 22 — DNS Query

## Screenshots

<img width="1038" height="771" alt="Screenshot 2026-05-23 170104" src="https://github.com/user-attachments/assets/962dabc0-87f0-4b24-86db-e5be817c7423" />
<img width="1019" height="741" alt="Screenshot 2026-05-23 170237" src="https://github.com/user-attachments/assets/44124296-7885-4f92-9a60-aa74c3bc4e6d" />
<img width="1055" height="764" alt="Screenshot 2026-05-23 170331" src="https://github.com/user-attachments/assets/e702fe9a-4525-4e29-8745-bcbc88a52e68" />
<img width="1134" height="821" alt="image" src="https://github.com/user-attachments/assets/d981affa-ab8a-422d-82ad-83a9f54e7d7a" />
<img width="1139" height="800" alt="image" src="https://github.com/user-attachments/assets/8c9c67bc-200d-4a8e-9e6a-766beafd14be" />
<img width="1056" height="786" alt="image" src="https://github.com/user-attachments/assets/761e4960-ee06-45a8-8932-df6c02a6c739" />
<img width="795" height="527" alt="Screenshot 2026-05-23 170253" src="https://github.com/user-attachments/assets/7e8fbcfc-ff64-470a-b133-67ce5929a31b" />



## Lessons Learned
This project helped me understand how endpoint activity creates logs, how Sysmon enhances telemetry collection, and how analysts investigate process and network activity.
