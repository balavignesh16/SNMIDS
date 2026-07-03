# SNMIDS (Simple Network/Node Intrusion Detection System)

A web-based simulation and detection system for network intrusions. This project features a Node.js backend and includes simulated attacker scripts to demonstrate how intrusion detection mechanisms identify and log malicious activities.

## Features
- **Intrusion Simulation**: Includes an `attacker.js` script to simulate network attacks.
- **Detection Dashboard**: A front-end interface (`index.html`, `docs.html`) to visualize logs and detected threats.
- **Backend Logging**: Node.js server that captures and processes incoming requests.

## Tech Stack
- Node.js (Express)
- Vanilla JavaScript / HTML / CSS

## Getting Started
1. Clone the repository.
2. Run `npm install` to download dependencies.
3. Start the detection server using `node server.js`.
4. Run `node attacker.js` to simulate traffic and view the detections on the dashboard.
