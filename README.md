# NMAP-
Scans in Nmap and their role:-

1. Intense scan: This scans top 1000 commonly used ports and then tries to find what exact service and version of that service is running in an open port. This scan also helps in detecting the type of operating system. 

2. Intense scan + UDP: Normal intense scan only scans TCP ports and using this scan, we can also scan UDP ports too.

3. Intense scan all ports: Instead of scanning only the 1000 common ports, this will scan all the possible ports 0-65535 (As it scans all the ports, this scan takes a lot of time to complete).

4. Intense scan no ping: This scan is used where firewalls are placed at the target.

5. Ping scan: This scan only checks if the host is reachable or not. The scan doesn’t scan any port.

6. Quick scan: This scans lesser ports and does no service version detection. It is faster than intense scan but can be a bit unreliable.

7. Quick scan plus:  It scans fewer ports (same as the quick scan) but does version detection. The scan is much more aggressive and hence can put a little stress on the network and be a bit unreliable.

8. Regular scan: Runs Nmap with default options i.e. simple port scanning and no service version detection. 

9. Slow comprehensive scan: It is an extremely slow scan that does deep level scanning with the highest accuracy and least stress on the network.

