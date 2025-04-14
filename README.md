# rust-node-messenger

A lightweight peer-to-peer command-line messaging app written in Rust. Built to explore TCP networking, thread-safe concurrency, and distributed node communication.

## 🚀 Features
- Spin up a local node to send and receive messages
- Connect to other nodes over TCP
- Handles multiple connections using Rust threads
- Gracefully handles disconnections and errors

## 🔧 Tech Stack
- Language: Rust
- Core Concepts: TCP sockets, multithreading, message broadcasting
- Architecture: Modular with network handling, user input, and message display separated

## 📦 Setup Instructions
```bash
git clone https://github.com/yourusername/rust-node-messenger.git
cd rust-node-messenger
cargo run
