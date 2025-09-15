# Packet-Tracer-Files
This repository holds my personal packet tracer files containing network topologies created while self practice and learning.


# L5 - Command Line Reference
## 1. Enter configuration Mode
```bash
enable
configure terminal
```
## 2. Assign IP address to an interface
```bash
interface <interface-name>
ip address <ip-address> <subnet-mask>
no shutdown
```
## 3. Configure Static Route
```sh
ip route <destination-network> <subnet-mask> <next-hop-ip>
```
## 4. Save Configuration
```sh
end
write
```
