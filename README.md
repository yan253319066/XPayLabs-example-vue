# XPay Labs (xpay) Vue 3 Example — Crypto Payment Gateway Integration Demo

English | [中文](README.zh.md)

A **Vue 3** example application demonstrating how to integrate the [XPay Labs (xpay)](https://www.xpaylabs.com) self-hosted, non-custodial crypto payment gateway SDK into a Vue application. Accept USDT/USDC payments on TRON, EVM chains, and SUI.

## Features

- Initialize the XPay Labs SDK with API credentials
- Create cryptocurrency collection orders
- Display payment QR codes for customers
- Real-time payment status checking
- Webhook verification demo
- Vite-powered development

## Prerequisites

- Node.js 14.x or higher
- npm or yarn

## Installation

```bash
npm install
```

## Configuration

```bash
# Create .env with your credentials
VITE_XPAY_API_KEY=your-api-key
VITE_XPAY_API_SECRET=your-api-secret
VITE_XPAY_BASE_URL=https://api.xpaylabs.com
```

## Running

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

## Project Structure

```
src/
├── views/
│   ├── Home.vue              # Landing page with SDK information
│   └── PaymentDemo.vue       # Main demo with SDK integration
├── components/
│   ├── PaymentQRCode.vue     # QR code display component
│   └── WebhookHandler.vue    # Webhook verification demo
```

## Related Resources

- [XPay Labs Website](https://www.xpaylabs.com)
- [Node.js SDK](https://github.com/yan253319066/XPayLabs-node-sdk)
- [Java SDK](https://github.com/yan253319066/XPayLabs-java-sdk)
- [React Example](https://github.com/yan253319066/XPayLabs-example-react)
- [Vue Demo (E-Commerce)](https://github.com/yan253319066/XPayLabs-demo-vue)
- [Checkout Page](https://github.com/yan253319066/XPayLabs-checkout)

## Repository

**GitHub:** [yan253319066/XPayLabs-example-vue](https://github.com/yan253319066/XPayLabs-example-vue)
**Gitee (mirror):** [XPayLabs/XPayLabs-example-vue](https://gitee.com/XPayLabs/XPayLabs-example-vue)

## License

MIT
