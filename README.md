# Confidence In — Free

The free plugin marketplace from [Confidence In](https://confidence-in.com). Tools for senior tech leaders to find the signal, hold the line, and lead with judgement.

This repo is a Claude Code marketplace. The plugins themselves live in their own repos — this repo just lists them.

---

## What's in the catalog

| Plugin | What it does |
|---|---|
| [Signal Inbox](https://github.com/mrdavemartin/signal-inbox) | Morning brief synthesising the last 24h across Slack, Gmail, and Granola. Find what matters before the noise wins. |

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

Cowork's plugin browser doesn't yet accept GitHub URLs as marketplaces, so the catalog itself can't be added there. **Each plugin must be installed individually as a ZIP upload:**

1. Open the plugin's GitHub repo (e.g. [Signal Inbox](https://github.com/mrdavemartin/signal-inbox)).
2. Click the green **`< > Code`** button → **Download ZIP**.
3. In Cowork, open **Customize** in the left sidebar → **Browse plugins**.
4. Choose the option to **upload a custom plugin** and select the downloaded ZIP.
5. Confirm it appears in your installed plugins list.

To update a plugin later, download a fresh ZIP and re-upload — Cowork will replace the existing copy.

If/when Cowork adds custom marketplace support, the CLI install path above will work in Cowork too.

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

This is the free tier. More plugins land here over time — each focused on a specific problem senior leaders run into. If there's a paid tier in future, it'll live in a separate marketplace; nothing in this catalog will ever move behind a paywall.

---

## Contributing

Issues and suggestions for new plugins are welcome. Open an issue on this repo or on the relevant plugin repo.

---

## Licence

MIT. Each plugin in the catalog has its own licence — see its repo.
