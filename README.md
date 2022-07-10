<h2>Getting Oracle VirtualBox up and running, installing and configuring Windows Server 2019, and  Exchange on Oracle VM VirtualBox</h2>


<h2>Description</h2>

In this lab, I will be installing and configuring oracle VirtualBox which is a cross-platform virtualization software, Windows Server 2019 Datacenter edition as the operating system, and Microsoft Exchange as a mail and calendaring server.
<br />


<h4>The hash of any file I am downloading will be checked using Windows PowerShell before I install it, so I can guarantee it has not been compromised.</h4>

<p align="center">
Oracle VM VirtualBox Hardware Requirements: <br/>
<img src="https://i.imgur.com/8KKA78G.jpg" height="80%" width="80%" alt="Oracle Virtualbox hardware requirement"/>
<br />
<br />
System Information:  <br/>
<img src="https://i.imgur.com/vbRdqyV.jpg" height="80%" width="80%" alt="System Information"/>
<br />
 
Check Virtualization Firmware Enabled (Command Line):  <br/>
<img src="https://i.imgur.com/55rLyYB.jpg" height="80%" width="80%" alt="check virtualization firmware enabled cmd"/>
<br />
 
Compare SHA256 checksums to verify Oracle VirtualBox download integrity:  <br/>
<img src="https://i.imgur.com/6BzaqRl.jpg" height="80%" width="80%" alt="code to see SHA256 in downloads"/>
<br />
 
 Compare SHA256 checksums to verify Oracle VirtualBox download integrity:  <br/>
<img src="https://i.imgur.com/D6seHTy.jpg" height="80%" width="80%" alt="SHA256 checksum from Oracle Virtualbox download"/>
<br />
 
  SHA256 checksums from Oracle VirtualBox:  <br/>
<img src="https://i.imgur.com/wO2WlLW.jpg" height="80%" width="80%" alt="SHA256 checksum from Oracle Virtualbox download"/>
<br />
 
Enable Virtualization in UEFI(Recovery):  <br/>
<img src="https://i.imgur.com/Q6jwTr6.jpg" height="80%" width="80%" alt="Choose Option but no UEFI"/>
<br />
 
 Enable Virtualization in UEFI(Startup Menu F10) :  <br/>
<img src="https://i.imgur.com/0hu3l6r.jpg" height="80%" width="80%" alt="Startup Menu"/>
<br />

  Enable Virtualization in UEFI(System Security) :  <br/>
<img src="https://i.imgur.com/MOx4ZvQ.jpg" height="80%" width="80%" alt="Computer Setup"/>
<br />
 
  Enable Virtualization in UEFI(Virtualization Technology (VTx) :  <br/>
<img src="https://i.imgur.com/aaSI9pF.jpg" height="80%" width="80%" alt="System Security"/>
<br />
 
  Oracle VM VirtualBox Installed(Complete):  <br/>
<img src="https://i.imgur.com/ODg9ioX.jpg" height="80%" width="80%" alt="VM VirtualBox installation Complete"/>
<br />
 
   Enable Virtualization in UEFI(BIOS KEY F10) :  <br/>
<img src="https://i.imgur.com/Q6jwTr6.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 
   Enable Virtualization in UEFI(BIOS KEY F10) :  <br/>
<img src="https://i.imgur.com/Q6jwTr6.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 
 
<h2>Hardware Requirements and Supporting Operating System  </h2>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL95125Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71ya122M2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkv87FQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
