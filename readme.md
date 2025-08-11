# Configuring the Windows Firewall

##  Goal
To block a particular port (Port 23 for Telnet), set up and test a simple firewall rule. Then, use the Telnet command to confirm that the port is blocked.

##  Actions Taken: **Examined Current Regulations**  
   *Windows Defender Firewall with Advanced Security* (`wf.msc`) was opened.
   Current **Inbound** and **Outbound** rules are listed.

2. - Established a new inbound rule: **Blocked Telnet Port (23)**
     - **Action:** Block connection - **Profiles:** Domain, Private, Public - **Protocol:** TCP - **Port:** 23  

3. **Examined the Regulation**  
   Telnet Client was installed using *Windows Features*.  
   Executed: ```cmd telnet localhost 23 ```
   The block was confirmed when the connection failed.



## Final Result
demonstrated knowledge of firewall traffic filtering by successfully creating, testing, and validating a Windows Firewall rule to block Telnet (Port 23).
