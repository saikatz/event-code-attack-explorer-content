# Security Policy

## How content is protected

The Event Code Attack Explorer app only installs content that is **digitally signed** (Ed25519) by the author. Every `events.json` in this repository is published together with `events.json.sig`.

- The app verifies the signature with a public key built into the app, before the file is read or installed, and again every time the app starts.
- Changing `events.json` in this repository (or anywhere else) without the author's private signing key produces content the app rejects.
- Downloads are HTTPS only, size-limited, and older versions are never installed.

## Reporting a vulnerability

If you find a security problem in the app or its content, please **do not open a public issue**. Use GitHub's private reporting instead:

**Security tab > Report a vulnerability** on this repository.

Please include what you found, how to reproduce it, and the app version (shown in the app's About window). You will get a reply as soon as possible. This is a volunteer community project, so there is no bug bounty.

## Disclaimer

This is a community educational project provided "as is", without warranty. See the README for the full disclaimer.
