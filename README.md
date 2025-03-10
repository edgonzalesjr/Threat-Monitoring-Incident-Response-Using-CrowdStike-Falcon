## Objective
To build hands-on skills and knowledge that will allow me to effectively analyze and triage cybersecurity detections using various detection and response tools. This will include learning how to prioritize alerts, analyze command line behavior, group detections, and collaborate with the team on incident response efforts.

### Skills Learned
- Detection Analysis
  - Learned to review detection queues to identify and assess new alerts, with an understanding of how to interpret their status to quickly determine their relevance to the organization’s security posture.
- Prioritization of Alerts
  - Developed the ability to prioritize critical alerts, understanding that addressing high-risk alerts first minimizes potential damage and focuses efforts on the most pressing threats.
- Sorting and Filtering Data
  - Gained experience in using various sorting and filtering options, such as filtering by triggering files or severity indicators. Grouping detections by host or technique helped to better organize analysis and triage efforts.
- Command Line Behavior Analysis
  - Understood the importance of analyzing command line arguments. Investigating what’s being executed on compromised hosts provided deeper insights into potential malicious actions that might not be apparent in higher-level alerts.
- Incident Triage and Collaboration
  - Practiced triaging cybersecurity detections, updating their status, and adding comments for better tracking and collaboration, ensuring alignment and more effective incident resolution.

### Tools Used
- CrowdStrike Falcon Eval: a cloud-based cybersecurity platform that provides advanced endpoint protection, threat detection, and response using AI and machine learning.
- VirusTotal: Analyze file details, reputation scores, and community feedback.
- Whois Domain Tools: For querying domain registration information and identifying the legitimacy of the domain.
- CyberChef: For decoding and analyzing data.
- Windows 10 Eval: End-user machine.

## Practical Exercises
- Malware Detection
<p align="center">
<img src="https://imgur.com/BLC8kPL.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Download of malicious file in the victim's machine.</b>
<br/>

<p align="center">
<img src="https://imgur.com/XgAgPhx.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Login to CrowdStrike Falcon website.</b>
<br/>

<p align="center">
<img src="https://imgur.com/qCzxl5d.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/aHmcK9r.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Detected the malicious activity.</b>
<br/>

<p align="center">
<img src="https://imgur.com/1gqMSip.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/cRH8uGu.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/hCFUYXR.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/wn2g9G7.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Malicious file process viewed and file reputation check</b>
<br/>

<p align="center">
<img src="https://imgur.com/eCg6NvW.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/lEdZ8dg.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/sVWACiy.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/5qHf0Hs.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/ehuzXmF.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/LXmyCHE.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Edit the status and start triaging.</b>
<br/>

<p align="center">
<img src="https://imgur.com/3hjwZEP.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/sD76M0J.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Document the case and update the status.</b>
<br/>

- Powershell Detection
<p align="center">
<img src="https://imgur.com/vldzmkn.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Execution of Powershell in the victim's machine.</b>
<br/>

<p align="center">
<img src="https://imgur.com/4AjN1am.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Detected the malicious Powershell activity.</b>
<br/>

<p align="center">
<img src="https://imgur.com/5xwjC5l.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/bCJjgXH.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Malicious PowerShell process viewed.</b>
<br/>

<p align="center">
<img src="https://imgur.com/35rIWJV.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/k9EPLfh.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/0J2hO5M.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Edit the status and start triaging.</b>
<br/>

<p align="center">
<img src="https://imgur.com/lQApGiO.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/9oUHbIc.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Document the case and update the status.</b>
<br/>

- Infected Machine Isolation
<p align="center">
<img src="https://imgur.com/jpk4AnO.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/Kt0UTqq.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/CphnN4n.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/vJqKwVG.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/nO7Ywom.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/pkOKTET.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Isolate the victim's machine to the network to avoid further damage.</b>
<br/>

<p align="center">
<img src="https://imgur.com/RXmXmcE.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/WSL537J.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/cPlOALr.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/HzoIMHN.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Putting back the machine to the network.</b>
<br/>

- Endpoint Detections
<p align="center">
<img src="https://imgur.com/EIk6TYc.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/G3OZ1Xx.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>.</b>
<br/>

- Fusion SOAR
<p align="center">
<img src="https://imgur.com/kl8QDhC.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/X9zYzEo.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Create workflow.</b>
<br/>

<p align="center">
<img src="https://imgur.com/zpd3nPe.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/DtwgvG8.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Create alert.</b>
<br/>

<p align="center">
<img src="https://imgur.com/nbtpIZy.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<img src="https://imgur.com/eS0iEz9.png" height="90%" width="90%" alt="Device Specification"/>
<br/>
<b>Execution Log.</b>
<br/>


## Outcome
- Effective Threat Identification and Prioritization
  - Developed the ability to quickly identify and prioritize cybersecurity threats, focusing on critical alerts first to address the most severe risks immediately.
- Increased Incident Response Efficiency
  - Improved efficiency in triaging and responding to incidents by grouping detections, filtering by triggering files, and analyzing command line arguments, enabling faster and more accurate threat resolution.
- Collaboration and Tracking
  - Enhanced team collaboration by updating detection statuses and adding comments, ensuring continuity and transparency in the investigation process to avoid missing any details.

## Acknowledgements
This project combines ideas and methods from various sources, such as the CrowdStrike Falcon Youtube videos and my IT experience. These resources provided the fundamental information and techniques, which were then modified in light of practical uses. 
 - [CrowdStrike Falcon Eval](https://www.crowdstrike.com/en-us/products/trials/try-falcon-prevent/?utm_campaign=brand&utm_content=crwd-brand-apj-sea-en-psp-x-trl-x-tct-x_x_x_rlsa-x&utm_medium=sem&utm_source=goog&utm_term=crowdstrike%20falcon&cq_cmp=22070106885&cq_plac=&gad_source=1&gclid=Cj0KCQjwm7q-BhDRARIsACD6-fXfpSM1ZTm_7uJx4RKJy-H731QL8srSEPNcKL-ZZA3xf-DtMHbi6JsaApvvEALw_wcB)
 - [CrowdStrike Youtube videos](https://www.youtube.com/@CrowdStrike)
 - [Whois Domain Tools](https://whois.domaintools.com/)
 - [VirusTotal](https://www.virustotal.com/gui/home/url)
 - [CyberChef](https://gchq.github.io/CyberChef/)
 - [Windows 10 Eval](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-10-enterprise)

## Disclaimer
The sole goals of the projects and activities here are for education and ethical cybersecurity research. All work was conducted in controlled environments, such as paid cloud spaces, private labs, and online cybersecurity education platforms. Online learning and cloud tasks adhered closely to all usage guidelines. Never use these projects for improper or unlawful purposes. It is always prohibited to break into any computer system or network. Any misuse of the provided information or code is not the responsibility of the author or authors.
