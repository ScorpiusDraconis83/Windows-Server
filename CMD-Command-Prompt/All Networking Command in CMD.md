**ALL MAC ADDRESS FIND COMMAND**
- **arp -a**
---
**PARTICULAR PC MAC ADDRESS FIND COMMAND**
- **getmac**
---
**IP ADDRESS FIND COMMAND**
- **ipconfig**
- **ipconfig/all**
---
**SYSTEM INFORMATION FIND COMMAND**
- **systeminfo**
---
**DNS Cache Flush**
- **ipconfig /flushdns**
---
**DNS Cache Check**
- **ipconfig/displaydns**
---
**Domain IP Website IP address and Mac address find**
- **nslookup google.com**
---

**GROUP POLICY UPDATE COMMAND IN WINDOWD SERVER **
- **gpupdate /force**
---
**DNS TYPES Recoreds**
- **nslookup -type=a google.com**
- **nslookup -type=aaaa google.com**
- **nslookup -type=ns google.com**
-  **nslookup -type=mx google.com**
-  **nslookup -type=cname google.com**
- **nslookup -type=soa google.com**
-  **nslookup -type=ptr google.com**
- **nslookup -type=rv google.com**

---

---


Here is the list of common networking commands in Windows Command Prompt (CMD) with commands formatted inside \`\`\`bash for easy copy-pasting:

````markdown
# Common Networking Commands in Windows Command Prompt (CMD)

## **Basic Networking Commands**

1. **ipconfig**  
   Displays IP configuration information for all network adapters.  
   ```bash
   ipconfig
````

2. **ipconfig /all**
   Displays detailed IP configuration information for all network adapters, including MAC address.

   ```bash
   ipconfig /all
   ```

3. **ipconfig /release**
   Releases the current DHCP configuration (IP address).

   ```bash
   ipconfig /release
   ```

4. **ipconfig /renew**
   Renews the DHCP configuration and obtains a new IP address.

   ```bash
   ipconfig /renew
   ```

5. **ipconfig /flushdns**
   Clears the DNS resolver cache.

   ```bash
   ipconfig /flushdns
   ```

6. **ipconfig /displaydns**
   Displays the contents of the DNS resolver cache.

   ```bash
   ipconfig /displaydns
   ```

7. **ping \[IP address or hostname]**
   Sends a request to check if the target host is reachable on the network.

   ```bash
   ping [IP address or hostname]
   ```

8. **tracert \[hostname or IP address]**
   Traces the route taken by packets to a destination host.

   ```bash
   tracert [hostname or IP address]
   ```

9. **nslookup \[hostname]**
   Queries the DNS for the IP address of a domain.

   ```bash
   nslookup [hostname]
   ```

10. **nslookup \[IP address]**
    Resolves an IP address to its associated hostname.

    ```bash
    nslookup [IP address]
    ```

---

## **Advanced Networking Commands**

1. **netstat**
   Displays network statistics, including active connections and listening ports.

   ```bash
   netstat
   ```

2. **netstat -an**
   Shows all active connections and listening ports with IP addresses and port numbers.

   ```bash
   netstat -an
   ```

3. **netstat -s**
   Displays protocol statistics for TCP, UDP, and other protocols.

   ```bash
   netstat -s
   ```

4. **netstat -r**
   Displays the current routing table.

   ```bash
   netstat -r
   ```

5. **netstat -b**
   Shows the executable involved in creating each connection or listening port (requires administrative privileges).

   ```bash
   netstat -b
   ```

6. **route print**
   Displays the current routing table.

   ```bash
   route print
   ```

7. **route add \[destination] \[mask] \[gateway]**
   Adds a static route to the routing table.

   ```bash
   route add [destination] [mask] [gateway]
   ```

8. **route delete \[destination]**
   Removes a static route from the routing table.

   ```bash
   route delete [destination]
   ```

9. **tracert -d \[hostname or IP]**
   Traces the route to a target and disables DNS resolution.

   ```bash
   tracert -d [hostname or IP]
   ```

10. **arp -a**
    Displays the ARP table, mapping IP addresses to MAC addresses.

    ```bash
    arp -a
    ```

11. **getmac**
    Displays the MAC address of the local network interfaces.

    ```bash
    getmac
    ```

---

## **Network Interface and Sharing**

1. **netsh interface ip show config**
   Displays IP configuration for all network interfaces.

   ```bash
   netsh interface ip show config
   ```

2. **netsh interface ip set address \[interface] static \[IP address] \[subnet mask] \[default gateway]**
   Configures a static IP address on a network interface.

   ```bash
   netsh interface ip set address [interface] static [IP address] [subnet mask] [default gateway]
   ```

3. **netsh interface ip set address \[interface] dhcp**
   Configures a network interface to obtain an IP address from a DHCP server.

   ```bash
   netsh interface ip set address [interface] dhcp
   ```

4. **netsh wlan show profiles**
   Displays a list of all saved wireless network profiles.

   ```bash
   netsh wlan show profiles
   ```

5. **netsh wlan show profile name=\[profile name] key=clear**
   Displays the Wi-Fi password of a specific saved network profile.

   ```bash
   netsh wlan show profile name=[profile name] key=clear
   ```

6. **net use \[drive letter] \\\[server]\[share]**
   Maps a network share to a drive letter.

   ```bash
   net use [drive letter] \\[server]\[share]
   ```

---

## **Network Services**

1. **net start \[service name]**
   Starts a specific network service (e.g., "net start dhcp" to start the DHCP service).

   ```bash
   net start [service name]
   ```

2. **net stop \[service name]**
   Stops a specific network service.

   ```bash
   net stop [service name]
   ```

3. **net user**
   Displays a list of local user accounts on the system.

   ```bash
   net user
   ```

4. **net user \[username] \[password] /add**
   Creates a new user account on the system.

   ```bash
   net user [username] [password] /add
   ```

---

## **Miscellaneous Networking Commands**

1. **hostname**
   Displays the hostname of the local machine.

   ```bash
   hostname
   ```

2. **nbtstat -n**
   Displays NetBIOS name resolution statistics.

   ```bash
   nbtstat -n
   ```

3. **nbtstat -r**
   Displays the NetBIOS name resolution cache.

   ```bash
   nbtstat -r
   ```

4. **net config workstation**
   Displays the configuration of the workstation.

   ```bash
   net config workstation
   ```

5. **net config server**
   Displays the configuration of the server.

   ```bash
   net config server
   ```

6. **netsh interface ipv4 show interfaces**
   Displays information about IPv4 interfaces.

   ```bash
   netsh interface ipv4 show interfaces
   ```

---

These commands are useful for network configuration, troubleshooting, and monitoring in a Windows environment. Make sure to run certain commands with administrative privileges if required.

---
