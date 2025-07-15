# MedChain MVP Infosys

## Overview
A blockchain-powered medical supply chain management platform. This project demonstrates secure, transparent, and efficient tracking of medical supplies using Hyperledger and AI forecasting.

## Features
- Blockchain-based supply chain tracking
- AI-powered demand forecasting
- Role-based interfaces (Admin, Manufacturer, Distributor, Hospital)
- Inventory dashboard and analytics
- Patient verification and QR code integration

## Demo Video
[![Demo Video]("public/Screenshot 2025-07-15 at 8.18.49 PM.png")](https://youtu.be/dJR3k6kuW3o?si=c1jcCMIg3V1b5t3M)

## Screenshots
![Login Page]("public/Screenshot 2025-07-15 at 8.18.49 PM.png")
![Manufacturer Dashboard]("public/Screenshot 2025-07-15 at 8.19.30 PM.png")
![Distributer Dashboard]("public/Screenshot 2025-07-15 at 8.19.44 PM.png")
![Hospital/Pharmacy Dashboard]("public/Screenshot 2025-07-15 at 8.19.58 PM.png")
![Patient Verification]("public/Screenshot 2025-07-15 at 8.20.13 PM.png")
![AI Forecasting]("public/Screenshot 2025-07-15 at 8.20.26 PM.png")
![Admin/Regulator]("public/Screenshot 2025-07-15 at 8.21.02 PM.png")

## Getting Started

### Prerequisites
- Node.js
- pnpm
- Python 3 (for AI and blockchain scripts)

### Installation
```bash
pnpm install
```

### Running the App
```bash
pnpm dev
```

### Running Scripts
- AI Model Training: `python scripts/ai_model_training.py`
- Blockchain Simulator: `python scripts/blockchain_simulator.py`
- Database Setup: `python scripts/setup_database.py`

## Project Structure
- `app/` - Next.js app pages and layout
- `components/` - React components
- `hooks/` - Custom React hooks
- `lib/` - Utility functions
- `scripts/` - Python scripts for backend logic
- `public/` - Static assets
- `styles/` - Global styles

## License
[MIT](LICENSE) 