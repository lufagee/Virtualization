# $${\color{lightblue}Getting \space Started \space with \space Virtualization \space and \space Linux \space Distributions}$$

<a id="descr"></a>
<h4 align="center"><summary>Description & Requirements</summary></h4>
<details align="center">
<summary></summary>
    <ol>
    <details>
    <summary>Project consists of aquiring <b>Oracle VirtualBox VM</b> and <b>Debian GNU/Linux</b> from their official sources, and installing them, primarily adhering to the default installation settings / minimum resource allocation requirements.</summary>
        <ul>
        <details>
        <summary>VirtualBox's suite of virtualization technologies allows deployment of  <b>operating systems(OS), virtual machines(VM), and applications</b> within a fully equipped virtualized environment.
        </summary> 
            <ul>
            Type 2 hypervisor's, like Oracle VirtualBox VM, run on top of an existing operating system and create/manage virtual machines.
            </ul>
        </details>
        </ul>
    </details>
    </ol>
    <ol>
    <details>
    <summary><b>Debian GNU/Linux</b> 
    will be deployed inside the virtual machine created by Oracle VirtualBox VM's hypervisor.</summary>
        <ul>
        <details>
        <summary>Running a live system like GNOME desktop environment requires additional resource allocation. GNOME can run on lower-end hardware, but performance improves significantly with more RAM</summary>
            <ul><b>Minimum</b>
            <li>
            RAM: 2 GB; 4GB or more is recommended for GNOME.
            </li>
            <li>
            CPU: 1 GHz single-core processor; 2 cores or more for better performance.            
            </li>
            <li>
            Storage: 25 GB of disk space for a full GNOME desktop installation; add more storage if you plan on storing large files.
            </li>
        </details>
        </ul>
    </details>
</details>
<br/>



<h4 align="center"><summary>Table of Contents</summary></h4>
<details align="center">
<summary></summary>
    <ol>
    <a href="#descr">Description & Requirements</a>
    </ol>

<ol>
<a href="#gif1">Oracle VirtualBox Download »</a>
    <ul>
    <a href="#gif2">Installation »</a>
    </ul>
</ol>

<ol>
<a href="#gif3">Debian ISO Download »</a>
    <ul>
    <a href="#gif4">New VM »</a>
        <ul><a href="#gif5">EUFI Settings »</a></ul>
    </ul>
</ol>

<ol>
<a href="#gif6">Debian Installer »</a>
    <ul>
    <a href="#gif7">Gnome | LibreOffice Writer »</a>

</ol>


</details>










<!----------------         ***ORACLE VB***               ------------------>

<a id="gif1"></a>
## Oracle VirtualBox VM Aquisition & Installation


<p align="center">
Launch your browser and head over to the <a href="https://www.virtualbox.org/">Oracle VirtualBox VM official site</a>: 
<br/>
<br/>
<img src="./gifs/1-Oracle-VirtualBoxDownload.gif" height="60%" width="60%" alt="Oracle VirtualBox VM Aquisition"/>
<br/>
<br/><a id="gif2"></a>
<br/>
Run the <b>.exe</b> file we just <a href="https://www.virtualbox.org/wiki/Downloads">downloaded</a> to install Oracle VirtualBox VM:
<br/>
<br/>
<img src="./gifs/1.1-Oracle-VirtualBoxInstall.gif" height="60%" width="60%" alt="Oracle VB Installation"/>
<br/>
</p>

<h1 align="center">🎉🎉🎉 <b>CONGRATULATIONS!</b> 🎉🎉🎉</h1>
<p align="center">You just downloaded and installed Oracle VirtualBox VM! 🥳</p>
</pre>
<br/>
<br/>
<br/>


<!----------------         ***DEBIAN GNU/LINUX***        ------------------>


<a id="gif3"></a>
## Debian GNU/Linux ISO Aquisition & Installation

<p align="center">
Launch your browser and head over to the <a href="https://www.debian.org/">official Debian website</a>: 
<br/>
<br/>
<img src="./gifs/2-Oracle-DebianISODownload.gif" height="60%" width="60%" alt="Debian ISO Aquisition"/>
<br/>
<br/><a id="gif4"></a>
<br/>
Create a new VM in the <b>Oracle VirtualBox Manager</b>, and Attach the <b>.iso</b> file we just <a href="https://www.debian.org/download">downloaded</a>
<br/>
<br/>
<img src="./gifs/2.1-Oracle-DebianISOinstall.gif" height="60%" width="60%" alt="Debian in VB"/>
<br/>
<br/>
<br/><a id="gif5"></a>
<p align ="center">
Enable <b>EUFI</b> and start the virtual machine.
<br/>
<br/>
<img src="./gifs/2.2-Oracle-DebianInstallEUFIsetting.gif" height="60%" width="60%" alt="Debian in VB"/>
<br/>
<br/>
<br/><a id="gif6"></a>
<p align ="center">
Follow the <b>installer</b> and configure the system.
<br/>
<br/>
<img src="./gifs/3.1-Oracle-DebianGnomeInstall.gif" height="60%" width="60%" alt="Debian in VB"/>
<br/>
<br/>
<br/>
<a id="gif7"></a>
    
## GNOME Desktop Environment
<p align ="center">
Log in with the credentials we created to enter the <b>GNOME</b> desktop environment.
<br/>
<br/>
<img src="./gifs/3.2-Oracle-Gnomelaunch.gif" height="60%" width="60%" alt="Debian in VB"/>
<pre align="center">
<h1>🎉🎉🎉</h1><b>CONGRATULATIONS!</b> You just installed GNOME, a Linux distro, onto a virtual machine!<h1>🥳</h1>
</pre>
</p>





<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```



<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>



 ### [GIF's](https://)

$${\color{lightblue}Getting \space Started \space with \space Virtualization \space and \space Linux \space Distributions}$$

<h3>Environments Used </h3>

- <b>Windows 11</b>
--!>
