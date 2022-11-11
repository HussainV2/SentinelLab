<h1>Failed RDP with Microsoft Sentinel</h1>

<h2>Description</h2>
<b>Utilized a Powershell script to parse out Windows Event Logs for failed RDP attacks and using a third party API to collect information about the attackers Geographic location.
</b>
<br />
<br />
Configured Microsoft Sentinel (Azure cloud SIEM) workbook to display global attack data (RDP brute force) on world map according to physical location and magnitude of attacks.
<br />
<br />

<p align="center">
<img src="" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Attacks from China coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks</h2>

<p align="center">
<img src="" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
