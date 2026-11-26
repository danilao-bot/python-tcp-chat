# Multi-User TCP Chat Application

**Course:** Data Communication and Networking (400 Level) — Veritas University Abuja  
**Topic:** TCP/IP Transport Layer — Design, Implementation, and Cloud Deployment

## Project Structure

```text
.
├── src/                         # Core TCP chat server, client, and message framing protocol
├── tests/                       # Automated tests (multi-client, framing, malformed input, reconnects)
├── experiments/
│   ├── tcp_udp_comparison/      # Standalone TCP vs. UDP benchmark scripts (100+ messages)
│   └── pcaps/                   # Wireshark packet captures (.pcap / .pcapng)
├── docs/
│   ├── diagrams/                # Application & cloud deployment architecture diagrams
│   ├── screenshots/             # Annotated Wireshark & live chat screenshots
│   └── logs/                    # Saved test logs and benchmark results
├── deploy/                      # Cloud provisioning, service config, and deployment notes
├── .env.example                 # Example environment variables (do not commit .env)
└── .gitignore
```

## Setup & Usage

*(To be completed once the server and client are implemented.)*
