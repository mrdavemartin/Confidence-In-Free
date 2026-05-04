# Confidence In — Free

The free plugin marketplace from [Confidence In](https://confidence-in.com). Tools for senior leaders in tech companies to find the signal, influence with clarity, and lead with judgement.

This repo is a Claude Code marketplace. The plugins themselves live in their own repos — this repo just lists them.

---

## What's in the catalog

| Plugin | What it does |
|---|---|
| [Signal Inbox](https://github.com/mrdavemartin/signal-inbox) | Brief synthesising the last 24h across Slack, Gmail, and Granola. Find what matters before the noise wins. |

More plugins land here over time. See **What's coming** at the bottom.

---

## Install on Claude Code (CLI)

Add the marketplace once, then install whatever you want from it:

```
/plugin marketplace add mrdavemartin/Confidence-In-Free
/plugin install signal-inbox@confidence-in-free
```

You only need to `marketplace add` once. Future plugins in this catalog install with one command.

To pin to a specific marketplace version:

```
/plugin marketplace add mrdavemartin/Confidence-In-Free@v0.1.0
```

---

## Install on Cowork (desktop app)

This route makes future updates one click.
1. In the desktop Claude app, click “Cowork”.
2. From the left-hand menu, click “Customize”.
3. Click the “+” next to “Personal plugins”. Hover over “Create plugin”, then click “Add Marketplace”.
4. Paste in the GitHub URL: https://github.com/mrdavemartin/Confidence-In-Free and click Sync.
5. The marketplace browser opens, filtered to “Anthropic & Partners”. Click “Personal” instead. You’ll see the Confidence In marketplace.
6. Click into it, find “Signal Inbox”, and click Add.
7. Choose auto-sync if you want updates handled for you, or leave it manual.

---

## Plugins

### Signal Inbox

A morning brief that synthesises the last 24 hours of Slack, Gmail, and (optionally) Granola into one decision-ready summary, written in your voice.

**CLI install:**
```
/plugin install signal-inbox@confidence-in-free
```

**Cowork install:** download the ZIP from the [Signal Inbox repo](https://github.com/mrdavemartin/signal-inbox) and upload it in Cowork.

Full documentation: [mrdavemartin/signal-inbox](https://github.com/mrdavemartin/signal-inbox)

---

## What's coming

The plugins in this marketplace will always be free. More plugins land here over time — each focused on a specific problem senior leaders run into. If there's a paid tier in future, it'll live in a separate marketplace; nothing in this catalog will ever move behind a paywall.

---

## Contributing

Issues and suggestions for new plugins are welcome. Open an issue on this repo or on the relevant plugin repo.

---

## Licence

MIT. Each plugin in the catalog has its own licence — see its repo.
