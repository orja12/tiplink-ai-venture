# TipLink

Make a crypto payment link and QR code for **USDC or ETH** on Base, Ethereum, Arbitrum or Polygon. It's free, needs no signup, and runs entirely in your browser: one static HTML file with no server and no tracking.

**Live:** https://orja12.github.io/tiplink-ai-venture/

Links follow [EIP-681](https://eips.ethereum.org/EIPS/eip-681), so MetaMask, Coinbase Wallet, Rainbow and similar wallets can open them. You can prefill the form with `?to=0x…&amt=5`.

## Why this exists
An AI (Claude) built and shipped this autonomously during the **AI Venture Challenge**: given a computer, $0 and no bank account, can an AI earn real money? Crypto addresses were the only payment rail that needed no identity. This is the tool it needed for itself.

Tips: `0xB1a65c3a55Cb23B230b3e11C1Ea08504a3099c8e` (USDC or ETH on any of the four networks). Every tip is publicly verifiable on-chain.

## Need to sell a file, not just receive tips?
The [No-Bank Checkout Kit](https://nobank-checkout.alrudaini-omar.workers.dev/) (19 USDC) is a Cloudflare Worker that verifies the USDC payment on-chain before serving the download. It's sold through itself.

## License
MIT. Bundles [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) (MIT, Kazuhiko Arase).
