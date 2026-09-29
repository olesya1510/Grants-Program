# W3F Grant Application: DeHand Security Shield

- **Project Name:** DeHand Security Shield
- **Team Name:** DeHand Network
- **Payment Address:** 5Da3MXkbGtx8uh8tvdyQDxDKQp87GpqfMMgoi9T3Agcen5L4
- **Level:** 1 (Up to $10,000)

## Project Overview

### Project Description
DeHand Security Shield is a serverless, decentralized peer-to-peer (P2P) infrastructure core designed to protect web resources, decentralized applications (dApps), and EdTech platforms from automated bot-traffic, scraping, and Sybil attacks. 

Unlike traditional centralized solutions (e.g., Cloudflare, WAF) that create a single point of failure, DeHand shifts the traffic filtering and mitigation layer directly to a distributed network of validation nodes. The network utilizes a custom node-reputation graph coupled with a lightweight SHA-256 Proof-of-Work (PoW) mechanism to dynamically throttle malicious automated scripts before they hit target backend databases.

### Ecosystem Fit
The Polkadot ecosystem relies heavily on decentralized infrastructures, cross-chain communication, and node-level resilience. However, RPC nodes, validators, and ecosystem Web3 platforms remain vulnerable to high-intensity scraping and automated bot interactions that exhaust resources. 

DeHand acts as a fundamental cybersecurity layer for Substrate-based projects and Polkadot-native applications, establishing a reputation scoring engine across nodes to automatically isolate malicious traffic.

## Team

### Team members
- **Olesya Dekhand** - Founder, Lead Backend / Software Engineer, Business Analyst.

### Contact
- **Contact Name:** Olesya Dekhand
- **Contact Email:** olesyadekhand@gmail.com

### Legal Structure
- **Individual / Freelancer Profile** (Self-employed status under local registration). 

### Team's Experience
Experienced software engineer specializing in system architecture, network protocols, and distributed database design. Deep practical expertise in Go and Python backend engineering. Developed a standalone peer-to-peer networking core (DeHand) that leverages cryptographic standards for decentralized seed-phrase authorization and node routing. Accomplished extensive technical and business analysis for wholesale enterprise sectors and industrial automation infrastructures.

### Team Code Repos
- https://github.com

## Development Roadmap

### Milestone 1: P2P Network Core and Anti-Bot PoW SDK
- **Estimated Duration:** 4-5 weeks
- **FTE:** 1
- **Costs:** 8,000 USD

| Number | Deliverable | Description |
| -----: | ----------- | ----------- |
| 0a. | License | Apache 2.0 |
| 0b. | Documentation | Complete English documentation explaining the P2P node protocol, architecture, and connection guides. |
| 0c. | Testing Guide | A suite of unit tests for the filtering kernel with instructions on how to execute them. |
| 1. | Core Architecture | Implement the core distributed node-reputation graph engine in Go with local secure storage. |
| 2. | Anti-Bot PoW | Integrating a lightweight SHA-256 Proof-of-Work challenge protocol to deter automated scraping bots at the protocol level. |
| 3. | API Integration | Developing an easy-to-integrate SDK/API wrapper for external decentralized services and educational platforms to route traffic securely. |
