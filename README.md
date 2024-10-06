<h1>World Maps Construction</h1>
<b>This tutorial outlines the configuration world maps for Windows, Linux, MSSQL, and Network Security Groups using Microsoft Sentinel</b>

<h2>Environments and Technologies Used</h2>

- <b>Microsoft Azure</b> 
- <b>Microsoft Sentinel</b>


<h2>Operating Systems</h2>

- <b>Windows 10</b>

<h2>Configuration Steps</h2>

- <b>Download the windows, linux, mssql, and nsg json files from this link: https://github.com/joshmadakor1/Cyber-Course-V2/tree/main/Sentinel-Maps(JSON)</b>

![image](https://github.com/user-attachments/assets/b5f5a966-b00c-4f1c-8818-1ecab9b63479)
- <b>Navigate to Microsoft Sentinel and click add workbook</b>
- <b>Click edit and remove the text and query</b>
- <b>Click add query and advanced editor</b>
- <b>Delete the default query and paste the linux query from the json file</b>
- <b>Click done editing</b>

![image](https://github.com/user-attachments/assets/7b516904-f7ba-4fdb-b944-ad1c118156cc)
- <b>Linux world map creation</b>

![image](https://github.com/user-attachments/assets/aa75d53b-af87-4934-81c5-4c60e2dad54b)
- <b>Click save</b>
- <b>Title: linux-ssh-auth-fail</b>
- <b>Subscription: Azure Subscription 1</b>
- <b>Resource Group: RG-Cyber-Lab</b>
- <b>Location (US) East US 2</b>
- <b>Click apply</b>
- <b>Repeat the same process for windows, mssql, and nsg world maps</b>

![image](https://github.com/user-attachments/assets/9fef866d-7f1a-4964-b005-8a532b74b80e)
- <b>Windows-rdp-auth-fail world map creation</b>

![image](https://github.com/user-attachments/assets/974915ae-f6c5-44ea-ad8f-6083f74175b8)
- <b>Nsg-malicious-allowed-in world map creation</b>

![image](https://github.com/user-attachments/assets/a7d517b3-a7a5-48fc-a41d-e575b6703513)
- </b>Mssql-auth-fail world map creation</b>






