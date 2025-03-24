# Networking Tools Cheat Sheet

## 🖥️ Common Command-Line Tools

- **ping** – Check if a host is reachable
  ```
  ping google.com
  ```

- **traceroute / tracert** – Show path packets take to a host
  ```
  traceroute google.com (Linux)
  tracert google.com (Windows)
  ```

- **ipconfig / ifconfig** – View IP and network interface info
  ```
  ipconfig (Windows)
  ifconfig or ip a (Linux)
  ```

- **nslookup / dig** – DNS queries
  ```
  nslookup google.com
  dig google.com
  ```

- **netstat** – Show open ports and active connections
  ```
  netstat -an
  ```

- **nmap** – Port scanning and host discovery
  ```
  nmap -sS 192.168.1.1
  ```

- **wireshark** – Packet capture and analysis (GUI tool)

## 🔗 Useful References
- [Nmap Cheat Sheet](https://nmap.org/book/inst-windows.html)
- [Wireshark Filters Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Wireshark_Filter_Cheat_Sheet.html)
