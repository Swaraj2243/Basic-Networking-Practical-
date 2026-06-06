# 🌐 Networking Task 01

## 👨‍🎓 Student Information

* **Name:** Swaraj

---

# 📌 Part A: Network Information

| Parameter           | Value                                               |
| :------------------ | :-------------------------------------------------- |
| **Hostname**        | `DESKTOP-6T7SP68`                                   |
| **IPv4 Address**    | `192.168.1.7`                                       |
| **MAC Address**     | `B0-XX-XX-XX-XX-XX` *(Hidden for security reasons)* |
| **Default Gateway** | `192.168.1.1`                                       |

### DNS Servers

* `192.168.1.1`
* `2401:4900:50:9::7ad`
* `2401:4900:50:9::290`

---

# 📚 Part B: Basic Networking Concepts

## 🔹 IP Address

An IP (Internet Protocol) address is a unique numerical identifier assigned to a device connected to a network. It enables communication between devices over the internet or a local network.

## 🔹 MAC Address

A MAC (Media Access Control) address is a unique hardware identifier assigned to a network interface card (NIC) by the manufacturer. For privacy and security, the MAC address has been partially masked.

## 🔹 Default Gateway

A default gateway is a networking device, usually a router, that forwards traffic from a local network to other networks, including the internet.

## 🔹 DNS

The Domain Name System (DNS) translates human-readable domain names (such as `google.com`) into IP addresses that computers use for communication.

---

## 🌍 Public IP vs Private IP

| Public IP                                       | Private IP                                  |
| :---------------------------------------------- | :------------------------------------------ |
| Used on the internet                            | Used within local networks                  |
| Assigned by the Internet Service Provider (ISP) | Assigned by the router                      |
| Globally unique                                 | Can be reused in different private networks |

---

# 🖥️ Part C: Network Diagram

```
           Internet
               │
               ▼
      Router (192.168.1.1)
               │
               ▼
      Device (192.168.1.7)
```

---

# ⚙️ Part D: Network Commands Used

The following Windows networking commands were used during this task:

```bash
ipconfig /all
ping google.com
tracert google.com
```

---

# ❓ Answers

## 1. Was the ping successful?

**Answer:** Yes, the ping was successful.

---

## 2. How many hops were shown in traceroute?

**Answer:** *(Update this value based on your `tracert google.com` output.)*

---

## 3. What is the purpose of traceroute?

**Answer:** Traceroute is a network diagnostic tool that displays the path taken by data packets from the source device to the destination. It helps identify delays and troubleshoot network connectivity issues.

---

# 🎯 Conclusion

This networking practical provided hands-on experience with fundamental networking concepts and tools. It helped in understanding IP addressing, MAC addresses, DNS, default gateways, public and private IPs, and basic network troubleshooting using `ipconfig`, `ping`, and `tracert` commands.

---

## 🛠️ Tools Used

* Windows Command Prompt
* `ipconfig`
* `ping`
* `tracert`

---

**Author:** Swaraj Jadhav 
**Course:** Cyber and Digital Science
