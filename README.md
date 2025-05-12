<h1>Azure sentinel - Attack Simulation</h1>

<h2>Description</h2>
This simulation consists of using the Azure sentinel SIEM to visualize simulated attacks on a vm configured as a honeypot. I used custom logs to translate the location data fetched from the geo location api to map them onto 
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>App.ipgeolocation</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Azure Sentinel</b> (21H2)

<h2>Simulation walk-through:</h2>


<p align="center">


Setup Virtual Machine in Azure: <br/>
<img src="1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setup Analytics Worspace :  <br/>
<img src="2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setup Azure Defender: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Run powershell Script in the VM to ingest logs <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create custom log in Azure log analytics workspace to bring in the custom log <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Extract fields from raw data <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setup Map in Sentinel with data <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the simulated breach attempts on VM <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
