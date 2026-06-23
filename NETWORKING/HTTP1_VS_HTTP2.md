# HTTP/1.1 vs HTTP/2

HTTP/2 is a major improvement over HTTP/1.1, designed to improve web performance by reducing latency and improving resource loading efficiency.

---

## 🌐 HTTP/1.1

HTTP/1.1 is a text-based protocol that handles requests sequentially over multiple connections.

### Key Limitations:
- One request per connection (blocking behavior)
- No header compression
- Plain text format
- Head-of-line blocking problem

---

## ⚡ HTTP/2

HTTP/2 is a binary protocol that improves performance by allowing multiple requests and responses over a single connection.

### Key Features:
- Multiplexing (parallel requests over one connection)
- Binary framing for faster processing
- HPACK header compression
- Reduced latency and improved performance

---

## ⚖️ HTTP/1.1 vs HTTP/2

| Feature | HTTP/1.1 | HTTP/2 |
|----------|----------|--------|
| Data Format | Plain text | Binary |
| Request Handling | Sequential | Multiplexed |
| Connections | Multiple | Single |
| Header Compression | No | Yes (HPACK) |
| Performance | Slower | Faster |
| Blocking | Yes | No (mostly eliminated) |

---

## 🚀 Core Advantage

The biggest improvement in HTTP/2 is **multiplexing**, which allows multiple requests to be processed simultaneously over a single connection, eliminating head-of-line blocking.

---

## 🌍 Example

HTTP/1.1 loads resources one by one, while HTTP/2 loads multiple resources (HTML, CSS, images) simultaneously, significantly improving page load speed.

---

## 🧠 Interview Answer (One Line)

HTTP/2 is an improved version of HTTP/1.1 that uses multiplexing and binary framing to send multiple requests over a single connection, reducing latency and improving performance.