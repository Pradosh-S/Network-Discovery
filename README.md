# Network-Discovery
Step-by-Step Guide:
1.)Install nmap:
  *Download and install from nmap.org.
2.)Run nmap Scan:
  *Open your terminal or command prompt.
  *Identify your local IP address and subnet (e.g., 192.168.1.9).
  *Run the nmap scan with the following command:
    nmap -sn 192.168.1.9
3.)Analyze the Results:
  *Look through the output for IP addresses and MAC addresses of the discovered devices.

Example Output:
Starting Nmap 7.95 ( https://nmap.org ) at 2024-06-24 08:49 India Standard Time
Note: Host seems down. If it is really up, but blocking our ping probes, try -Pn
Nmap done: 1 IP address (0 hosts up) scanned in 2.26 seconds

Document the Findings:
Below is an example of how to document your findings:

IP Address	-> MAC Address ->	Device Description
192.168.1.1 -> AA:BB:CC:DD:EE -> Home Router (Provides network connectivity)
192.168.1.2	-> 11:22:33:44:55:66	-> Laptop (Personal computer)
192.168.1.3	-> 77:88:99:AA:BB -> Smartphone (Personal mobile device)

Brief Description of Devices:
1.)Home Router: The central device that connects all devices to the internet and manages the network.
2.)Laptop: A personal computer used for work, browsing, and entertainment.
3.)Smartphone: A mobile device used for communication, browsing, and various applications.

Running the Scan and Documenting the Actual Results:
Run the scan on your network and fill in the table with the actual IP addresses, MAC addresses, and device descriptions. Ensure you have the necessary permissions to scan the network and avoid scanning networks you do not own or have explicit permission to scan.
