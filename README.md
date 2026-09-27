# Event Code Attack Explorer - Content

This repository hosts the teaching content (`events.json`) for **Event Code Attack Explorer**, a free, community-driven educational app that maps Windows event codes to the attack techniques they help detect, with step-by-step defensive guidance and detection pseudocode.

Installed copies of the app check this file automatically (at startup and every few hours) and install newer content by themselves, so students always have the latest version.

- **Author:** saikatz
- **Content file:** [`events.json`](events.json) (raw link used by the app: `https://raw.githubusercontent.com/saikatz/event-code-attack-explorer-content/main/events.json`)

## Security

Every `events.json` here is published with `events.json.sig`, a digital signature by the author. The app checks it and rejects any content that was not signed by the author, so edits to this repository alone cannot change what students see. See [SECURITY.md](SECURITY.md) to report a problem privately.

## Disclaimer

This is a community educational project provided "as is", without warranty of any kind. The author and contributors are not responsible or liable for any damages, losses, outages, security incidents or legal consequences arising from the use or misuse of the app or this content. Use it at your own risk.

The content is for learning defensive security only. Only test detections on systems you own or are explicitly authorized to work on, validate every rule in a lab before production use, and follow your organization's policies and applicable laws. Content may contain errors or become outdated; corrections are welcome via issues or pull requests.
