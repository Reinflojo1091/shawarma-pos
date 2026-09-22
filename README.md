# Shawarma POS

A VS Code-friendly, dependency-free web POS for a shawarma shop. It supports cash and GCash payments, printable customer receipts, ingredient stock tracking, low-stock alerts, and sales summaries.

## Run locally

1. Open this repository in Visual Studio Code.
2. Open `index.html` directly in a browser, or run a local static server.
3. Example with Node.js: `npx serve .`

The app stores demo data in the browser's `localStorage`, so it works without a backend for demonstrations. Use **Reset demo data** to restore the sample menu.

## Included

- Product menu with shawarma, meals, sides, drinks, and add-ons
- Cash and GCash checkout
- Cash change calculation
- Printable customer receipts
- Ingredient inventory and automatic deduction when a sale is completed
- Low-stock warnings
- Sales history and payment totals
- Responsive layout for desktop and mobile browsers

## Final deliverables

This first working version is a browser-based POS. It can be packaged as a Windows executable with Tauri or Electron and as an Android APK with Capacitor/React Native after selecting a deployment backend and printer hardware.
