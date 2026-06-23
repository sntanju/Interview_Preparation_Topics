# Socket vs HTTP vs WebSocket

## 🔌 Socket

A Socket is a programming interface used for sending and receiving data over a network. It works at the Transport Layer (TCP/UDP) and provides low-level control over network communication.

### Key Points:
- Not a protocol, but an API
- Works with TCP/UDP
- Handles raw data transmission
- Used in real-time systems like games and chat apps

---

## 🌐 HTTP (HyperText Transfer Protocol)

HTTP is a high-level application protocol used for communication between clients and servers on the web.

### Key Points:
- Works at Application Layer (Layer 7)
- Uses request-response model
- Runs over TCP sockets internally
- Used in websites and REST APIs

---

## ⚡ WebSocket

WebSocket is a protocol that provides full-duplex communication over a single persistent connection.

### Key Points:
- Connection stays open
- Both client and server can send data anytime
- Low latency communication
- Used in real-time applications

---

## ⚖️ Comparison

| Feature | Socket | HTTP | WebSocket |
|----------|--------|------|-----------|
| Type | API | Protocol | Protocol |
| Layer | Transport | Application | Application |
| Connection | Persistent (manual control) | Short-lived | Persistent |
| Data Type | Raw bytes | Structured | Structured |
| Use Case | Low-level networking | Web APIs | Real-time apps |

---

## 🧱 OSI Layer Mapping

- HTTP → Layer 7 (Application)
- WebSocket → Layer 7 (Application)
- Socket → Layer 4 (Transport Interface)
- TCP/UDP → Layer 4 (Transport Protocol)