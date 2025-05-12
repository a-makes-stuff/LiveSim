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
<img src="1.png" height="80%" width="80%" alt="loading"/>
<br />
<br />
Setup Analytics Worspace :  <br/>
<img src="2.png" height="80%" width="80%" alt="loading"/>
<br />
<br />
Setup Azure Defender: <br/>
<img src="3.png" height="80%" width="80%" alt="loading"/>
<br />
<br />
Disable Firewall in Virtual Machine<br/>
<img src="4.png" height="80%" width="80%" alt="loading"/>
<br />
<br />
Run powershell Script in the VM to Simulate Attack <br/>
<img src="5.png" height="80%" width="80%" alt="loading"/>
<br />
<br />
Configure Custom logs in Azure <br/>
<img src="6.png" height="80%" width="80%" alt="loading"/>
<br />
<br />
Create Custom Fields in Map <br/>
<img src="7.png" height="80%" width="80%" alt="loading"/>
<br />
<br />
Setup Map with Latitude and Longitude <br/>
<img src="8.png" height="80%" width="80%" alt="loading"/>
<br />
<br />
Observe the simulated breach attempts on VM <br/>
<img src="9.png" height="80%" width="80%" alt="loading"/>
<br />
<br />
