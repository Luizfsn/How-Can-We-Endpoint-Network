# How-Can-We-Endpoint-Network


**Welcome to the guide-hacking!**

**First of all monitoring has 2 main types:**

- Endpoints
- Networks


**Network

- Do you know which ports are actually in use?
- Which services are actually being used on those ports?
- Do you know which domains are being visited and by who?
- Can you detect malicious encrypted traffic?
- Can you see high-level bandwidth and traffic flow?
- You should be noticed we`re talking about network analyze.

**NSM is for Network Security Monitoring**

- Analyzing network traffic
- Services: DNS, HTTP(S), SMB, RDP, FTP, SSH
- Identifying risky | compromise-like behavior
  - Expolit Delivery
  - Internal recon and pivoting
  - Command & Control (C2) Traffic
  - Data Exfiltration
  - Executable content transfer

**NSM By layer**

**Layer 3 & 4:**

- NetFlow, Firewall LOgs, Statistical Data

**Layer 7:**

- Service Logs
- Packet Capture, IDS alerts


![image](https://user-images.githubusercontent.com/41551654/209858466-80a42dd6-abed-40e9-a7b3-fa6e7c178452.png)



**Endpoints**

Also with Endpoints Monitoring we should put some Questions to answer.

**The Questions Are:**

- Has anyone installed unauthorized program ?
- What Ports are listening and why ?
- What exploits are you vulnerable to ?
- Have any system files been changed ?
- Have any malicious scripts been run. ?
- You should be noticed we’re talking about Computers, Clouds, Servers

**CSM is for Continuous Security Monitoring**

What are the benefits of CSM?

- it is looking at endpoint data – “data at rest” or the data being generated on the endpoint
- Provides real-time visibility into your applications and infrastructure
- Vulnerability scanning
- File/Registry integrity monitoring
- Autoruns
- Services
- Running process
- Classifies devices: to allow you to implement preventive measures

**CSM Event Collection**

Here are the CSM Event Collection Sources:

- OS/Application auth logs
- Sysmon
- Antivirus
- EDR
- Whitelisting
- HIDS/HIPS
- Vulnerability Scanner


![image](https://user-images.githubusercontent.com/41551654/209858494-0de9d5b1-6a4a-4169-a07c-17335d58f869.png)



**Monitoring Data Sources Table:**

**NSM Data**

- Routers & Switches
- Network Firewalls
- IDS & IPS
- Proxy
- WAF
- Service Logs: FTP,SSH,HTTP(S),etc.

**CSM Data**

- Authentication
- Antivirus
- HIDS & HIPS
- Process CommandLine
- Data Loss Prevent (DLP)
- Application access logs
- Executables

**Finally there is a one place to search and alert on events is your SIEM:**

![image](https://user-images.githubusercontent.com/41551654/209858526-8f814de7-c535-4763-a294-bdefd1af8231.png)


**How Data Gets to The SIEM**

**This a small photo shows how (NSM) AND (CSM) are working with SIEM:**

![image](https://user-images.githubusercontent.com/41551654/209858550-a221337d-d508-420b-a5d8-f7b3bed70577.png)


**Resources I Used:**

- SANS
- logrhythm
- NIST
