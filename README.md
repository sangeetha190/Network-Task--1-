# Network-Task--1-
1. Get the IP address of guvi.in
    - Command:
       - nslookup guvi.in
         ![image](https://github.com/user-attachments/assets/8c88849e-3466-49a1-95e9-319d05258265)

2.  Check CPU & Memory Usage of Your Server
    - Commands:
       - top      # Live system monitoring
       - free -m  # Check available memory
       ![image](https://github.com/user-attachments/assets/4c88125e-5896-48f3-9c38-77f18fe30253)
       ![image](https://github.com/user-attachments/assets/133cc03f-e3b1-4d2a-a01d-60270b3c067e)

3. Test Connectivity Between Two Nodes (Machines)
    - Commands:
       - ping guvi.in      # Check if the domain is reachable  
       - traceroute guvi.in  # (Optional) Show network path to guvi.in  
       ![image](https://github.com/user-attachments/assets/363f4124-7eef-415c-b9df-5873d7ff1212)
       ![image](https://github.com/user-attachments/assets/453dcd39-1632-4897-925a-4327e1d6445d)


#Task 2 (After So many try the report)
1. Task Report: Port 9000 Check on guvi.com
  - Checked if port 9000 is open using Netcat:
      - Command: nc -zv guvi.com 9000
      - Result: Connection timed out.

  - Verified server reachability with Ping:
      - Command: ping -c 4 guvi.com
      - Result: The server is reachable, meaning the domain resolves correctly.

  - Attempted to connect using Telnet (if applicable):
      - Command: telnet guvi.com 9000
      - Result: (Mention the result, if you tested this.)
      ![image](https://github.com/user-attachments/assets/17768e13-1760-46bb-9605-565d195acae0)

- Conclusion:
 - Port 9000 is not accessible on guvi.com. The connection is timing out.
 - Possible reasons:
  - The application is not running on port 9000.
  - A firewall is blocking access to port 9000.
  - The service may be down or misconfigured.

