# 📶 How WiFi Works

WiFi is a wireless networking technology that uses radio waves to connect devices to a local network and the Internet without physical cables.

---

## Step-by-Step Process

### 1. Internet from ISP

An Internet Service Provider (ISP) delivers internet connectivity to your modem or Optical Network Unit (ONU).

---

### 2. Router Receives Internet

The router receives the internet connection and creates a local wireless network.

Its responsibilities include:

- Broadcasting WiFi
- Assigning IP addresses (DHCP)
- Performing NAT
- Managing connected devices

---

### 3. WiFi Broadcast

The router continuously broadcasts a wireless network (SSID), allowing nearby devices to discover it.

Example:

```
Home_WiFi
```

---

### 4. Device Discovery

Your phone or laptop scans for available WiFi networks and displays nearby SSIDs.

---

### 5. Authentication

The user enters the WiFi password.

The router verifies the credentials using security protocols such as WPA2 or WPA3.

---

### 6. IP Address Assignment

After successful authentication, the router assigns a private IP address using DHCP.

Example:

```
Router: 192.168.0.1
Phone: 192.168.0.105
```

---

### 7. DNS Lookup

When the user enters a website (e.g., google.com), the browser asks a DNS resolver to translate the domain name into an IP address.

---

### 8. TCP & TLS Connection

The browser establishes a TCP connection and performs a TLS handshake to create a secure HTTPS connection.

---

### 9. HTTP Request

The browser sends an HTTP/HTTPS request to the web server.

---

### 10. Data Transmission

The request travels through the OSI layers:

Application → Transport (TCP) → Network (IP) → Data Link (WiFi/MAC) → Physical (Radio Waves)

The router forwards the data through the ISP and the Internet to the destination server.

---

### 11. Server Response

The server returns the requested resources (HTML, CSS, JavaScript, images).

The browser renders the page and displays the website.

---

## Complete Flow

User Device

↓

WiFi (Radio Signal)

↓

Router

↓

Modem / ONU

↓

ISP

↓

Internet

↓

DNS Resolver

↓

Web Server

↓

Response

↓

Browser

---

## OSI Layer Mapping

| OSI Layer | Technology |
|-----------|------------|
| Application | HTTP / HTTPS |
| Presentation | TLS Encryption |
| Session | Session Management |
| Transport | TCP / UDP |
| Network | IP |
| Data Link | WiFi (IEEE 802.11), MAC Address |
| Physical | Radio Waves |

---

## 🧠 Interview Answer (One Line)

WiFi works by using radio waves to wirelessly connect devices to a router, which assigns an IP address, forwards data through the ISP and Internet, and returns responses from remote servers to the user's device.