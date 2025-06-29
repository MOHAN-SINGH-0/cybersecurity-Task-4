# cybersecurity-Task-4

 **Objective:** Configure and test basic firewall rules to allow or block traffic.

 
**Tools:**  
- Windows Firewall
- Windows Telnet

---

**Steps**
1. Opened **Windows Defender Firewall – Advanced Settings**
2. Listed all current **Inbound and Outbound Rules**
3. Created an **Inbound Rule to block TCP port 23 (Telnet)**
   - to create a rule: New rule-> Port->Select TCP and Specific Port 23->Block Connection->Block all profile->Name the rule-> finish 
4. Verified the rule by using the ` telnet 192.168.120.203` command
5. Observed that the connection was **blocked successfully**
7. Removed  test rules to restore original settings

**command used**
- telnet 192.168.120.203

---

**How a Firewall Filters Traffic – Summary**

A firewall is a security system that monitors and controls incoming and outgoing network traffic based on predefined rules.
It acts like a gatekeeper between your device or network and the internet.
Firewalls filter traffic by comparing each network request to a set of security rules. They can allow safe traffic and block unwanted or dangerous connections based on IPs, ports, and protocols.

---

**What I Learned**

- How firewalls manage traffic using port-based rules
- Difference between **inbound vs outbound rules**
- How to block unused services like **Telnet (port 23)** to reduce risk
- That even simple tools like Telnet can be used to validate firewall configurations
