# TakerShield AI

**Execution-risk infrastructure for prediction-market traders.**

![TakerShield Observer](https://raw.githubusercontent.com/takershield/takershield-observer/main/assets/observer_terminal.png)

---

### What We Build

- **Observer** (public, free) — Read-only terminal dashboard. Real-time SAFE / CAUTION / NO_QUOTE signals. No API keys required.
- **Brain** (server) — Polls exchange, computes risk regime, broadcasts via WebSocket. Runs on our infrastructure.
- **Executor** (private, paid) — Automated stand-down. Places/cancels orders locally. Your keys never leave your machine.

---

### Try It
```bash
pip install git+https://github.com/takershield/takershield-observer.git
takershield --token YOUR_TOKEN
```

→ [takershield-observer repo](https://github.com/takershield/takershield-observer)

---

<sub>TakerShield provides risk signals, not trading advice. You are responsible for your own decisions.</sub>
