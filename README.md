# HTTP-SERVER

# High-Performance HTTP Server in C++

A lightweight, high-performance HTTP server built from scratch in **C++**, using **epoll**, **non-blocking I/O**, and a **thread pool**.  
This project demonstrates low-level networking, concurrency, middleware design, and observability concepts used in real backend systems.

---

## 🚀 Features

### Core Architecture

- Non-blocking socket server (Linux)
- `epoll`-based event-driven I/O
- Thread pool for request processing
- Graceful shutdown using signals
- Clean modular architecture

### HTTP & Routing

- Basic HTTP request parsing
- Response builder
- Route-based request handling
- Separate route definition files

### Middleware System

- Middleware pipeline (pre-routing)
- Request logging
- Rate limiting
- Easily extensible middleware design

### Metrics & Observability

- Active connection tracking
- Total request counter
- Average request latency
- `/metrics` endpoint
- Per-request latency logging

### Reliability

- Thread-safe queues
- Atomic counters
- Clean resource cleanup
- Safe shutdown on SIGINT / SIGTERM

---

## 🧠 High-Level Architecture
