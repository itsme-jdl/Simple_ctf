<h1>Simple CTF</h1>

<h2>Description</h2>

- <b> Project consists of ubuntu based virtual machine which is intentionally configured vulnerable in order to practise the pentesting methedology.</b><br/>
- <b> Actual Virtual Machine is located in Google Drive, which can be easily accessed from <a href="https://drive.google.com/drive/folders/1Tc9_bJLo-6UevsyyShogm8xHJJnVbD2G?usp=share_link">here.</a>. Instructions to setup the machine is mentioned below.<br />

<h2>Environment Used</h2>

- <b> Virtualisation (VM Ware/ Virtual Box) </b>
- <b> Ubuntu (Victim) </b> 
- <b> Kali Linux (Attacker) </b>


<h2> Skills Used</h2>

- <b> Networking Concepts
- <b> Pentesting Methedology</b>
- <b> OSINT</b>

<h2> Instructions to setup on your local system </h2>

- <b> Ensure that your system have atleast 8 Gb RAM and 50 GB disk space, in order to set up both, attacker and victim machines.</b></br>
- <b> Download and install any virtualisation software (<a href="https://www.vmware.com/in/products/workstation-player/workstation-player-evaluation.html">VM Ware</a> for Windows. (I configured this only for VM Ware)</b></br>
- <b> After this we need to setup our attacker system for which I am using <a href="https://www.kali.org/get-kali/">Kali Linux</a>, you can also use <a href="https://www.parrotsec.org/download/>Parrot OS</a></b></br>
- <b>There are plenty of videos and documentations available to set up both the OS, kindly follow them.</b></br>
- <b>Now, lets setup our victim.</b></br>
- <b> Download the victim from <a href="https://drive.google.com/drive/folders/1Tc9_bJLo-6UevsyyShogm8xHJJnVbD2G?usp=share_link">here.</a></b></br>
- <b> Once downloaded, unzip it using Winrar/7zip and double click on the <i><b>.ovf</b></i> file.</b></br>
- <b> It will promt to give the name. You can name it anything, I gave ctf_machine</b></br></br> <img src="https://github.com/itsme-jdl/Simple_ctf/blob/main/Ctf_walkthroughs/vm%20setup.jpg" height="80%" width="80%" alt="VM Setup"/><br /><br /><br />
 
- <b> Then click on import. It will start importing...</b></br><br /><br /> <img src="https://github.com/itsme-jdl/Simple_ctf/blob/main/Ctf_walkthroughs/importing.jpg" height="80%" width="80%" alt="VM Setup"/><br /><br /><br />

- <b> Once the import is complete, one can power on the machine...</b></br>
- <b> Now, download kali/parrot OS and set it up in similar faishon as done above.</b></br>
- <b> Make sure to set same Network option for both the systems i.e. (either NAT or NAT Network)</b></br>
- <b> Once the setup of both the system is done, now you are good to go. Start hunting the flag...</b></br></br>
- <b> If you are stuck somewhere, I have created a writeup, demonstrating each steps to pwn the system. It is in the same folder of the VM <a href="https://drive.google.com/drive/folders/1Tc9_bJLo-6UevsyyShogm8xHJJnVbD2G?usp=share_link">here.</a>. </b></br>




<h2> CTF Insights:</h2>

<p align="center"> Nmap Scan results: 
<br/>
<br/>
<img src="https://github.com/itsme-jdl/Simple_ctf/blob/main/Ctf_walkthroughs/nmap_scan.jpg" height="80%" width="80%" alt="Website Walkthrough"/>
<br />
<br />
<p align="center"> Connecting to ftp:
<br/>
<br/>
<img src="https://github.com/itsme-jdl/Simple_ctf/blob/main/Ctf_walkthroughs/connecting_ftp.jpg" height="80%" width="80%" alt="Website Walkthrough"/>
<br />
<br />
<p align="center"> Connecting to ssh: 
<br/>
<br/>
<img src="https://github.com/itsme-jdl/Simple_ctf/blob/main/Ctf_walkthroughs/ssh_connect.jpg" height="80%" width="80%" alt="Website Walkthrough"/>
<br />
<br />
<p align="center"> Esclating privileges and getting root: 
<br/>
<br/>
<img src="https://github.com/itsme-jdl/Simple_ctf/blob/main/Ctf_walkthroughs/getting_root.jpg" height="80%" width="80%" alt="Website Walkthrough"/>
<br />
<br />
</p>
