# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

XPayLabs Vue 3 integration example, demonstrating how to integrate `@xpaylabs/node-sdk` in a Vue 3 app. Vue 3 + Vue Router + Vite 4.

## Commands

```bash
npm install
npm run dev       # Dev server (localhost:3000)
npm run build     # Production build
npm run preview   # Preview production build
```

## Architecture

### Component Structure
```
src/
├── main.js              # Entry point
├── App.vue              # Root component
├── views/
│   ├── Home.vue         # Login / credential config page
│   └── PaymentDemo.vue  # SDK demo page
├── components/
│   ├── PaymentQRCode.vue  # QR code display component
│   └── WebhookHandler.vue # Webhook verification demo
└── services/
    └── XPayService.js   # @xpaylabs/node-sdk wrapper
```

### Demo Features
- SDK initialization (API Key + Secret)
- Create collection order → display QR code
- Real-time status polling
- Webhook verification demo

## Environment Variables

Configure XPayLabs API credentials in `.env`:
- `VITE_XPAY_API_KEY`
- `VITE_XPAY_API_SECRET`
- `VITE_XPAY_BASE_URL`

## Notes

- Depends on `vite-plugin-node-polyfills` for Node.js browser polyfills
- Functionally identical to the React example, suitable for Vue stack reference
