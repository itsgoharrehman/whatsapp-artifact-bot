# whatsapp-artifact-bot

An automated WhatsApp bot engine designed for real-time document synthesis, PDF report compilation, and artifact generation with an integrated companion web administration interface.

## Architecture and Stack

* **Engine**: Node.js (v18+), `@whiskeysockets/baileys`
* **Frontend**: Companion web application for live connection status
* **Document Engine**: PDF and text generation pipelines

## Key Features

* **Anti-Ban Compliance**: Respects WhatsApp connection limits and message queuing pacing.
* **Companion Web GUI**: Monitor QR code authentication and connection status from a clean browser dashboard.
* **Document Pipeline**: Synthesizes structured data into portable document formats.

## Getting Started

### Prerequisites
* Node.js v18+

### Installation
```bash
git clone https://github.com/itsgoharrehman/whatsapp-artifact-bot.git
cd whatsapp-artifact-bot
npm install
```

### Running
```bash
npm start
```

## Security Policy

Security reports should be submitted to `goharrehmanfsd260@gmail.com`.

## Maintainer

* **Gohar Rehman**
* GitHub: [@itsgoharrehman](https://github.com/itsgoharrehman)
* Email: `goharrehmanfsd260@gmail.com`
* Website: [itsgoharrehman.netlify.app](https://itsgoharrehman.netlify.app/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
