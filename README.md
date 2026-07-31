# WhatsApp CRM Server

Backend and deployment files for a WhatsApp CRM and automation platform.

## Stack

- Node.js and Express
- MySQL and MongoDB integrations
- Socket.IO real-time messaging
- WhatsApp, Telegram, and Instagram integrations
- Optional AI and voice-call automation

## Setup

1. Install dependencies:

   ```bash
   npm install
   ```

2. Copy `.env.example` to `.env` and provide local database, JWT, and service credentials.

3. Start the server:

   ```bash
   npm start
   ```

The server entry point is `server.js`. API routes are organized under `routes/`, integrations and reusable services under `helper/`, and scheduled automation under `loops/` and `automation/`.

## Public repository notes

Uploaded media, runtime sessions, generated assets, local secrets, and operating-system metadata are intentionally excluded from this repository. Create required upload and session directories at deployment time as needed by the enabled integrations.
