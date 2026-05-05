# FinAI 📈
### AI-powered stock & crypto research assistant for smarter trading decisions.

![Flutter](https://img.shields.io/badge/Flutter-Dart-02569B?style=flat&logo=flutter)
![Gemini](https://img.shields.io/badge/AI-Gemini-4285F4?style=flat&logo=google)
![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat&logo=android)
![Status](https://img.shields.io/badge/Status-Active-success?style=flat)

---

## What is FinAI?

FinAI is a mobile app that brings AI-driven investment research to retail traders. Instead of spending hours reading news and charts, you connect your brokerage account, select assets you're interested in, and let FinAI's analysis engine do the heavy lifting — then you decide what to do with it.

No noise. No hallucinations. Just clear, actionable research.

---

## Features

- **Brokerage & Wallet Integration** — Connect your Zerodha or Groww account, or link your crypto wallet, via secure deep linking
- **Multi-asset Support** — Covers a wide range of Indian stocks and major cryptocurrencies
- **AI Analysis Engine** — Powered by Gemini, generates structured research reports on your selected assets
- **Human-in-the-loop Workflow** — Review every recommendation before anything happens. Accept, edit, or reject.
- **One-tap Trade Execution** — Accepted trades are pre-filled with the exact stock/crypto and quantity, executed via deep link into your broker app
- **Polished UI** — Built with a focus on clarity and aesthetics — because good design builds trust

---

## How It Works

```
Connect Account → Select Assets → AI Runs Analysis → Review Report → Execute Trade
```

1. **Connect** your Zerodha / Groww account or crypto wallet
2. **Select** the stocks or crypto you want researched
3. **Review** the AI-generated analysis — edit figures, accept, or reject entirely
4. **Execute** — if accepted, the exact trade (asset + quantity) is sent to your broker via deep link for final confirmation

You are always in control. FinAI never executes anything without your explicit approval.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Mobile Framework | Flutter (Dart) |
| AI / LLM | Google Gemini API |
| Broker Integration | Zerodha Kite, Groww (deep link) |
| State Management | BLoC |
| Platform | Android |

---

## Screenshots

> *Coming soon*

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/yourusername/finai.git

# Install dependencies
flutter pub get

# Run the app
flutter run
```

> **Note:** You'll need a Gemini API key. Create a `.env` file in the root:
> ```
> GEMINI_API_KEY=your_key_here
> ```

---

## Roadmap

- [ ] iOS support
- [ ] Portfolio tracking dashboard
- [ ] Push notifications for market signals
- [ ] Paper trading mode
- [ ] Historical analysis & backtesting

---

## Disclaimer

FinAI is a research and decision-support tool. It does not provide financial advice. Always do your own due diligence before making investment decisions.

---

Built with Flutter · Powered by Gemini
