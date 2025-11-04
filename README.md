# ⚡ Real-Time Notification System (Java)

A modular **Real-Time Notification System** built using **Core Java**, designed to simulate how publishers send notifications to multiple subscribers instantly.  
It supports **topics**, **priorities**, **retries**, **TTL (time-to-live)**, and **dead-letter handling** — all without any external dependencies.

---

## 🧠 Overview

This project demonstrates a simplified **Pub/Sub (Publisher-Subscriber)** model:
- **Publishers** send notifications tagged by topic and priority.
- **Subscribers** receive real-time updates based on their topic subscriptions.
- **Broker** manages queueing, async delivery, retry logic, and failure handling.

---

## 🚀 Features

✅ Topic-based Pub/Sub model  
✅ Asynchronous delivery using thread pools  
✅ Priority-based notification dispatch (HIGH before NORMAL)  
✅ Time-to-Live (TTL) expiration for stale notifications  
✅ Retry with exponential backoff on delivery failure  
✅ Dead-letter queue for undeliverable notifications  
✅ Modular structure — easy to extend or integrate  
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/4db0b8b0-df35-448d-a19b-af5eba106346" />
![Uploading image.png…]()



## 🗂️ Project Structure

