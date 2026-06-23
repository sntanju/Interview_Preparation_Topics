# TCP vs UDP (Transport Layer Protocols)

TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are two core protocols used for data transmission over the internet. They operate at the **Transport Layer (Layer 4)** of the OSI Model.

---

## 🚀 TCP (Transmission Control Protocol)

TCP is a connection-oriented protocol that ensures reliable and ordered delivery of data.

### Key Features:
- Establishes a connection before data transfer
- Guarantees delivery of data packets
- Retransmits lost packets
- Maintains data order

### Use Cases:
- Web browsing (HTTP/HTTPS)
- File transfer (FTP)
- Email (SMTP)
- Online banking

---

## ⚡ UDP (User Datagram Protocol)

UDP is a connectionless protocol that focuses on speed rather than reliability.

### Key Features:
- No connection setup required
- No guarantee of delivery
- No retransmission of lost packets
- Faster than TCP

### Use Cases:
- Online gaming
- Video streaming
- Voice/video calls (VoIP)
- DNS queries

---

## ⚖️ TCP vs UDP Comparison

| Feature | TCP | UDP |
|----------|-----|-----|
| Connection | Connection-oriented | Connectionless |
| Speed | Slower | Faster |
| Reliability | High | Low |
| Ordering | Guaranteed | Not guaranteed |
| Error Handling | Yes | Minimal |

---

## 🧱 OSI Model Relation

TCP and UDP operate at the **Transport Layer (Layer 4)** of the OSI Model, which is responsible for end-to-end communication, reliability, and flow control.