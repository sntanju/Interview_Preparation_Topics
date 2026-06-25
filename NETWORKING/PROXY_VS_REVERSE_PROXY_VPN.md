# Proxy vs Reverse Proxy vs VPN

## 🌐 Proxy Server (Forward Proxy)

A proxy server acts as an intermediary between a client and the internet. It sends requests on behalf of the user.

### Key Points:
- Hides user identity (IP masking)
- Controls or filters access to websites
- Works at Application Layer (Layer 7)

### Example:
- School or office internet filtering
- Anonymous browsing

---

## 🔁 Reverse Proxy

A reverse proxy sits in front of servers and handles client requests on behalf of those servers.

### Key Points:
- Protects backend servers
- Performs load balancing
- Improves performance and security
- Works at Application Layer (Layer 7)

### Example:
- Large platforms like YouTube, Netflix

---

## 🔐 VPN (Virtual Private Network)

A VPN creates an encrypted tunnel over the public internet, allowing secure communication between a user and a private network.

### Key Points:
- Encrypts all traffic
- Hides IP address
- Secure remote access
- Works mainly at Network Layer (Layer 3)

### Example:
- Remote work access
- Secure browsing on public WiFi

---

## ⚖️ Comparison

| Feature | Proxy | Reverse Proxy | VPN |
|----------|------|---------------|-----|
| Direction | Client-side | Server-side | User-to-network |
| Purpose | Hide user identity | Protect servers | Secure communication |
| Encryption | Optional | Optional | Strong encryption |
| Scope | App-level traffic | Server traffic | Entire device traffic |

---

## 🧠 Interview Answer (One Line)

A proxy acts on behalf of a client to access the internet, a reverse proxy manages and protects backend servers, and a VPN creates an encrypted tunnel for secure communication over the internet.